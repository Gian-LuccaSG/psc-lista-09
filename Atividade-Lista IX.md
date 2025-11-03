##### &nbsp; Atividade-Lista IX

&nbsp; 

// 1. Pessoa

&nbsp;   static class Pessoa {

&nbsp;       private String nome;

&nbsp;       private int idade;

&nbsp;       private String cpf;

&nbsp;       private String email;



&nbsp;       public Pessoa(String nome, int idade, String cpf, String email) {

&nbsp;           this.nome = nome;

&nbsp;           this.idade = idade;

&nbsp;           this.cpf = cpf;

&nbsp;           this.email = email;

&nbsp;       }



&nbsp;       public void andar() {

&nbsp;           System.out.println(nome + " está andando.");

&nbsp;       }



&nbsp;       public void comer() {

&nbsp;           System.out.println(nome + " está comendo.");

&nbsp;       }



&nbsp;       public void dormir() {

&nbsp;           System.out.println(nome + " está dormindo.");

&nbsp;       }



&nbsp;       public void falar() {

&nbsp;           System.out.println(nome + " está falando.");

&nbsp;       }

&nbsp;   }



-----------------------------------------------------------------------------------------------------------------------------------------



// 2. Animal

&nbsp;   static class Animal {

&nbsp;       private String especie;

&nbsp;       private int idade;

&nbsp;       private String cor;

&nbsp;       private double peso; // kg



&nbsp;       public Animal(String especie, int idade, String cor, double peso) {

&nbsp;           this.especie = especie;

&nbsp;           this.idade = idade;

&nbsp;           this.cor = cor;

&nbsp;           this.peso = peso;

&nbsp;       }



&nbsp;       public void comer() {

&nbsp;           System.out.println(especie + " está comendo.");

&nbsp;       }



&nbsp;       public void dormir() {

&nbsp;           System.out.println(especie + " está dormindo.");

&nbsp;       }



&nbsp;       public void correr() {

&nbsp;           System.out.println(especie + " está correndo.");

&nbsp;       }



&nbsp;       public void emitirSom() {

&nbsp;           System.out.println(especie + " está emitindo som.");

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



// 3. Carro

&nbsp;   static class Carro {

&nbsp;       private String marca;

&nbsp;       private String modelo;

&nbsp;       private String cor;

&nbsp;       private String placa;



&nbsp;       public Carro(String marca, String modelo, String cor, String placa) {

&nbsp;           this.marca = marca;

&nbsp;           this.modelo = modelo;

&nbsp;           this.cor = cor;

&nbsp;           this.placa = placa;

&nbsp;       }



&nbsp;       public void ligar() {

&nbsp;           System.out.println(marca + " " + modelo + " ligado.");

&nbsp;       }



&nbsp;       public void desligar() {

&nbsp;           System.out.println(marca + " " + modelo + " desligado.");

&nbsp;       }



&nbsp;       public void acelerar() {

&nbsp;           System.out.println(marca + " " + modelo + " acelerando.");

&nbsp;       }



&nbsp;       public void frear() {

&nbsp;           System.out.println(marca + " " + modelo + " freando.");

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------ 



&nbsp;   // 4. Celular

&nbsp;   static class Celular {

&nbsp;       private String marca;

&nbsp;       private String modelo;

&nbsp;       private String tamanhoTela;

&nbsp;       private String cor;



&nbsp;       public Celular(String marca, String modelo, String tamanhoTela, String cor) {

&nbsp;           this.marca = marca;

&nbsp;           this.modelo = modelo;

&nbsp;           this.tamanhoTela = tamanhoTela;

&nbsp;           this.cor = cor;

&nbsp;       }



&nbsp;       public void ligar() {

&nbsp;           System.out.println("Celular " + marca + " ligado.");

&nbsp;       }



&nbsp;       public void tirarFoto() {

&nbsp;           System.out.println("Celular " + marca + " tirou uma foto.");

&nbsp;       }



&nbsp;       public void enviarMensagem(String texto) {

&nbsp;           System.out.println("Enviando mensagem: " + texto);

&nbsp;       }



&nbsp;       public void fazerLigacao(String numero) {

&nbsp;           System.out.println("Chamando " + numero + "...");

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



&nbsp;   // 5. Computador

&nbsp;   static class Computador {

&nbsp;       private String processador;

&nbsp;       private int memoriaRAM; // GB

&nbsp;       private int armazenamento; // GB

&nbsp;       private String sistemaOperacional;



&nbsp;       public Computador(String processador, int memoriaRAM, int armazenamento, String sistemaOperacional) {

&nbsp;           this.processador = processador;

&nbsp;           this.memoriaRAM = memoriaRAM;

&nbsp;           this.armazenamento = armazenamento;

&nbsp;           this.sistemaOperacional = sistemaOperacional;

&nbsp;       }



&nbsp;       public void ligar() {

&nbsp;           System.out.println("Computador com " + processador + " ligado.");

&nbsp;       }



&nbsp;       public void desligar() {

&nbsp;           System.out.println("Computador desligado.");

&nbsp;       }



&nbsp;       public void rodarPrograma(String nomePrograma) {

&nbsp;           System.out.println("Rodando o programa: " + nomePrograma);

&nbsp;       }



&nbsp;       public void atualizar() {

&nbsp;           System.out.println("Atualizando " + sistemaOperacional);

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------

&nbsp;   // 6. Livro

&nbsp;   static class Livro {

&nbsp;       private String titulo;

&nbsp;       private String autor;

&nbsp;       private String genero;

&nbsp;       private int numeroDePaginas;



&nbsp;       public Livro(String titulo, String autor, String genero, int numeroDePaginas) {

&nbsp;           this.titulo = titulo;

&nbsp;           this.autor = autor;

&nbsp;           this.genero = genero;

&nbsp;           this.numeroDePaginas = numeroDePaginas;

&nbsp;       }



&nbsp;       public void abrir() {

&nbsp;           System.out.println("Abrindo o livro: " + titulo);

&nbsp;       }



&nbsp;       public void lerPagina(int pagina) {

&nbsp;           System.out.println("Lendo a página " + pagina + " de " + titulo);

&nbsp;       }



&nbsp;       public void fechar() {

&nbsp;           System.out.println("Fechando o livro: " + titulo);

&nbsp;       }



&nbsp;       public void marcarPagina(int pagina) {

&nbsp;           System.out.println("Marcando a página " + pagina + " no livro: " + titulo);

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



&nbsp;   // 7. Escola

&nbsp;   static class Escola {

&nbsp;       private String nome;

&nbsp;       private String endereco;

&nbsp;       private int numeroDeSalas;

&nbsp;       private String diretora;



&nbsp;       public Escola(String nome, String endereco, int numeroDeSalas, String diretora) {

&nbsp;           this.nome = nome;

&nbsp;           this.endereco = endereco;

&nbsp;           this.numeroDeSalas = numeroDeSalas;

&nbsp;           this.diretora = diretora;

&nbsp;       }



&nbsp;       public void ensinar() {

&nbsp;           System.out.println(nome + " está ensinando os alunos.");

&nbsp;       }



&nbsp;       public void realizarProvas() {

&nbsp;           System.out.println(nome + " está realizando provas.");

&nbsp;       }



&nbsp;       public void organizarEventos() {

&nbsp;           System.out.println(nome + " está organizando um evento.");

&nbsp;       }



&nbsp;       public void receberAlunos() {

&nbsp;           System.out.println(nome + " está recebendo alunos.");

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



&nbsp;   // 8. Televisão

&nbsp;   static class Televisao {

&nbsp;       private String marca;

&nbsp;       private String tamanho;

&nbsp;       private String resolucao;

&nbsp;       private String cor;



&nbsp;       public Televisao(String marca, String tamanho, String resolucao, String cor) {

&nbsp;           this.marca = marca;

&nbsp;           this.tamanho = tamanho;

&nbsp;           this.resolucao = resolucao;

&nbsp;           this.cor = cor;

&nbsp;       }



&nbsp;       public void ligar() {

&nbsp;           System.out.println("Televisão " + marca + " ligada.");

&nbsp;       }



&nbsp;       public void desligar() {

&nbsp;           System.out.println("Televisão " + marca + " desligada.");

&nbsp;       }



&nbsp;       public void trocarCanal(int canal) {

&nbsp;           System.out.println("Trocando para o canal " + canal);

&nbsp;       }



&nbsp;       public void aumentarVolume() {

&nbsp;           System.out.println("Aumentando volume da TV " + marca);

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



&nbsp;   // 9. Relógio

&nbsp;   static class Relogio {

&nbsp;       private String marca;

&nbsp;       private String tipo; // analógico ou digital

&nbsp;       private String cor;

&nbsp;       private String materialPulseira;



&nbsp;       public Relogio(String marca, String tipo, String cor, String materialPulseira) {

&nbsp;           this.marca = marca;

&nbsp;           this.tipo = tipo;

&nbsp;           this.cor = cor;

&nbsp;           this.materialPulseira = materialPulseira;

&nbsp;       }



&nbsp;       public void mostrarHora() {

&nbsp;           System.out.println("Mostrando a hora no relógio " + marca);

&nbsp;       }



&nbsp;       public void despertar() {

&nbsp;           System.out.println("O relógio " + marca + " está despertando.");

&nbsp;       }



&nbsp;       public void cronometrar() {

&nbsp;           System.out.println("Cronômetro iniciado no relógio " + marca);

&nbsp;       }



&nbsp;       public void ajustarHora(int hora, int minuto) {

&nbsp;           System.out.println("Hora ajustada para " + hora + ":" + String.format("%02d", minuto));

&nbsp;       }

&nbsp;   }



------------------------------------------------------------------------------------------------------------------------------------------



&nbsp;   // 10. Bicicleta

&nbsp;   static class Bicicleta {

&nbsp;       private String marca;

&nbsp;       private String cor;

&nbsp;       private int numeroDeMarchas;

&nbsp;       private String tipo; // MTB, Speed etc.



&nbsp;       public Bicicleta(String marca, String cor, int numeroDeMarchas, String tipo) {

&nbsp;           this.marca = marca;

&nbsp;           this.cor = cor;

&nbsp;           this.numeroDeMarchas = numeroDeMarchas;

&nbsp;           this.tipo = tipo;

&nbsp;       }



&nbsp;       public void pedalar() {

&nbsp;           System.out.println("Pedalando a bicicleta " + marca);

&nbsp;       }



&nbsp;       public void frear() {

&nbsp;           System.out.println("Freando a bicicleta " + marca);

&nbsp;       }



&nbsp;       public void virar(String direcao) {

&nbsp;           System.out.println("Virando para a " + direcao);

&nbsp;       }



&nbsp;       public void estacionar() {

&nbsp;           System.out.println("Bicicleta " + marca + " estacionada.");

&nbsp;       }

&nbsp;   }

}


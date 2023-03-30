# trying-to-help-with-classes
idk i just made it to help some friends

Eu estou estudando sobre classes e decidi fazer um repositório sobre algo que eu me interessasse

Antes é importante que você se sinta confortável para estudar, então eu fiz uma playlist [spotify playlist](https://open.spotify.com/playlist/02ixNQf3bohvyds3j0GvEV?si=9b30dc88b95a4c55)

# Introdução

  Basicamente o java é uma linguagem orientada a objeto, existem outras linguagens que também seguem a mesma linha de raciocínio como o Python, Ruby, etc... 
  
  Esse termo Progamação Orientada a Objetos é um modelo que tenta transformar tudo em objetos, assim os objetos passam mensagens de uns para os outros, logo cada objeto decide o que fazer com a mensagem recebida.
   O java é baseado em classes, usando objetos que podem ser manipulados, criado a partir de uma classe através do instaciamento.
   
   `NomeDaClasse nomeDoObjeto = new NomeDaClasse();`
  
> É importante saber que o new ele pede pro seu S.O um lugar na sua mémoria RAM para armazenar esse objeto

# Classe

  Uma classe é o elemento do código que utilizamos para representar objetos do mundo real. Dentro dela é comum declarar atributos e métodos.
  > Eu tenho uma forma mais simples de explicar isso
  
  Uma televisão seria uma classe, a televisão tem características como: a marca, o volume, canal, polegadas; isso seria os atributos e ligar, desligar, mudar de canal, aumentar o volume seriam os comandos, procedimentos certo?

Porém aí que ta... não existe essas palavras em java. Procedimentos, comandos, ações são todas consideradas como **métodos** 
  >Eu sei que isso é meio confuso, você não está sozinho nessa... mas com tempo você pega.

  Um objeto é algo que pode ser manipulado e é criado por aquela coisa de instaciamento que eu citei lá em cima.
  >Os objetos são separados com o conceito de `this` ou `self` mas eu não sei muito bem ainda... desculpem

  Cada clase determina o comportamento (ou você pode dizer as ações) que são definidos nos métodos e os atributos de seus objetos.

> Esse assunto é meio confuso para quem nunca viu essas coisas, então é algumas videoaulas também ajudam o processo de aprendizagem [^1][^2]

[^1]: [Progrmação orientada a objetos](https://www.youtube.com/watch?v=XlgCv5zE-L0)
[^2]: [wikipedia falando sobre OOP](https://pt.wikipedia.org/wiki/Orienta%C3%A7%C3%A3o_a_objetos)

# Objetos

Em java, um objeto é criado a partir de uma classe. 

public class Main {

  public static void main(String[] args) {
    Main myObj = new Main();
  }
}

  Por exemplo, aqui você está criando um objeto chamado myObj
  
 Você também pode criar vários objetos
 
 public class Main {


  public static void main(String[] args) {
    Main myObj1 = new Main();  // Objeto 1
    Main myObj2 = new Main();  // Objeto 2
  }
}
  Nesses casos você está criando objetos na sua classe Main o que em um software pequeno não faz tanta diferença, porém quanto mais o desenvolvimento acontece se tem a necessidade de criar novas classes para que fique mais organizado, e que não fique confuso.
  
 # Objetos em múltiplas classes
 
  Nesse caso não muda muito, se você entendeu como cria um objeto não terá muitas dificuldades para criar em outras classes.
  
  > O único problema maior é saber como "linkar" essas classes para que fazer com que todas se comuniquem

 Assim vamos fingir que criamos duas classes
  - Main.java
  - Second.java
  
  Main.java

`public class Main {
  int x = 5;
}`

  Second.java

`class Second {
  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}`


  
# Atribuição a Classes

  Atribuir valores não deveria ser algo que você deve ter dúvidas nessa etapa do campeonato, mas eu posso te relembrar o que é
    
    public class Main {
      int x = 5;
      int y = 3;
    }
 Basicamente assim você está definindo atributos ou seja valores a variáveis
> Mas se mesmo assim você não domina esse processo ou tem alguma dúvida, significa que você está se adiantando demais

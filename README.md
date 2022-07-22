


<h1>INFORMAÇÕES GERAIS SOBRE JAVA</h1>

<h4>JAVA - CARACTERÍSTICAS</h4>
1 - TIPAGEM ESTÁTICA,<br> 2- BYTECODE,<br> 3- INDEPENDENTE DE PLATAFORMA,<br> 4- BIBLIOTECA DE ROTINAS e APIs,<br> 5 - Orientada a Objetos (OPP)<br>

Linguagem de programação com orientação a objetos, fortemente tipada.Nela, existe a compilação para um código intermediário,
o bytecode, que é interpretado e executado pela Máquina Virtual Java (JVM).


<h4>JAVA -  UTILIZAÇÃO</h4>
É usado para criar jogos, programas de computador, sistema operacionais,
sistemas automotivos, automação de residências, máquinas industriais e muito mais.


<h4>JAVA -  PONTOS POSITIVOS</h4>
Portabiliade - podem ser executados em todo tipo de hardware e sistema operacioal;
Segurança - privacidade dos dados;
Comunidade - vasta quantidade de desenvolvedores, o que pode ajudar iniciantes ou interessados na linguagem a resolver problemas;
Simplicidade - regras de uso bem definidas. 


<h4>EXEMPLO -  COM CONDIÇÃO</h4> 

public class TestaCondicional {
	
    public static void main(String[] args) {
        System.out.println("testando condicionais");
        int idade = 22;
        int quantidadePessoas = 3;

        if (idade >= 18) {
            System.out.println("você tem mais de 18 anos");
            System.out.println("seja bem vindo");
        } else {
            if(quantidadePessoas >= 2) {
                System.out.println("você não tem 18, mas " + "pode entrar, pois está acompanhado");
            } else {
            System.out.println("infelizmente você não pode entrar");
            }
        }
    }
}

#DIO - dominando IDES - JAVA#


INFORMAÇÕES GERAIS SOBRE JAVA 

JAVA - CARACTERÍSTICAS.
1 - TIPAGEM ESTÁTICA, 2- BYTECODE, 3- INDEPENDENTE DE PLATAFORMA, 4- BIBLIOTECA DE ROTINAS e APIs, 5 - Orientada a Objetos (OPP)

Linguagem de programação com orientação a objetos, fortemente tipada.Nela, existe a compilação para um código intermediário,
o bytecode, que é interpretado e executado pela Máquina Virtual Java (JVM).


JAVA -  UTILIZAÇÃO.
É usado para criar jogos, programas de computador, sistema operacionais,
sistemas automotivos, automação de residências, máquinas industriais e muito mais.


JAVA -  PONTOS POSITIVOS 
Portabiliade - podem ser executados em todo tipo de hardware e sistema operacioal;
Segurança - privacidade dos dados;
Comunidade - vasta quantidade de desenvolvedores, o que pode ajudar iniciantes ou interessados na linguagem a resolver problemas;
Simplicidade - regras de uso bem definidas. 


EXEMPLO -  COM CONDIÇÃO 

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

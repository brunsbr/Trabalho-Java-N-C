# Trabalho-Java N/C
Trabalho em Java 3° Semestre

Segue instruções para realização do seu trabalho personalizado da disciplina Linguagem de Programação Orientada a Objetos.

Informo que as instruções devem ser seguidas rigorosamente, e que o código entregue deve compilar para que o trabalho seja considerado.

Uma dica é compilar o código a cada item concluído, e só partir para o próximo item após a correção dos problemas do item atual.

É necessário aplicar a correta convenção de nomes para os identificadores, conforme exemplos:

Classe, ClasseComNomeComposto
atributo, atributoComNomeComposto
metodo, metodoComNomeComposto
CONSTANTE, CONSTANTE_COM_NOME_COMPOSTO

\Implemente na sequência definida para facilitar a conclusão do trabalho/
1. Criar a classe Pessoa com os seguintes atributos: primeiroNome do tipo String e ultimoNome do tipo String.
2. Encapsular fortemente os atributos, ou seja, tornar primeiroNome, ultimoNome privados e implementar os métodos de acesso (get e set).
3. Criar uma nova classe Cartao com o seguinte atributo encapsulado: codigo do tipo int.
4. Criar um construtor na classe Cartao que receba e inicialize o seguinte atributo: codigo.
5. Na Cartao, criar um método público para imprimir, na saída padrão (System.out.println()), todos os atributos da classe Cartao com a seguinte assinatura: imprime() além do tipo de retorno void.
6. Voltar a classe Pessoa e incluir um atributo cartao do tipo Cartao e o encapsular fortemente.
7. Criar um método público para imprimir, na saída padrão (System.out.println()), todos os atributos da classe Pessoa com a seguinte assinatura: imprime() além do tipo de retorno void.
8. Ainda na classe Pessoa, criar um construtor que receba os três atributos (primeiroNome, ultimoNome, cartao) e os e inicialize.
9. Realize uma sobrecarga (overload) do construtor da Pessoa, que receba os dois atributos (primeiroNome, ultimoNome) e os inicialize. Lembre que o construtor pode chamar um construtor da própria classe (this(lista de parâmetros correta), altere o construtor definido no item anterior).
10. Criar uma nova classe Funcionario que estenda (extends) a Pessoa com o seguinte atributo: ctps o tipo String e o encapsular fortemente.
11. Criar na classe Funcionario, um construtor que receba os atributos de instânica da classe Pessoa (primeiroNome, ultimoNome, cartao) e o atributo ctps e faça a inicialização de todos atributos. Lembre que pelo menos um construtor da classe deve chamar o construtor da super classe (super(lista de parâmetros correta)).
12. Na classe Funcionario, faça a sobreposição/sobreescrita (override) do método imprime() definido na classe Pessoa, para que além dos atributos definidos em Pessoa, também seja impresso o atributo definido em Funcionario.
13. Finalizando crie uma classe Teste que deverá ser executada, ou seja, possuir o método main (public static void main(String[] args)). No método main deve ser realizado o seguinte código:
Cartao cartao = null;// Criar um objeto com o construtor definido no item 4

//Utilizar o método imprime() definido na Cartao para imprimir os atributos do objeto cartao

Pessoa pessoa1 = null;// Criar um objeto com o construtor definido no item 8

//Utilizar o método imprime() definido na Pessoa para imprimir os atributos do objeto pessoa1

Pessoa pessoa2 = null;// Criar um objeto com o construtor definido no item 9

//Utilizar o método imprime() definido na Pessoa para imprimir os atributos do objeto pessoa2

Funcionario funcionario = null;// Criar um objeto com o construtor definido no item 11

//Utilizar o método imprime() definido na Funcionario para imprimir os atributos do objeto funcionario

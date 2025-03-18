# ATVDS01

## Classe Produto
### Atributos
Em minha classe de objeto, achei válido inserir em meus atributos 5 caracteristicas amplas para meu projeto ser usado em diferente setores. Nesse caso, adicionei as 5 caracteristicas obrigatórias como: **código**, para poder identificar aquele produto em especifico, **preço**, para mostrar quanto valhe aquele produto, **nome** do produto para saber o que está sendo catalogado, **cor** do produto para possíveis categorizações por cores e por fim **quantidade** para saber quantas unidades daquele produto ainda restam nos estoques.

-------------------------------------------------------------------------------- || ---------------------------------------------------------------------------
### Métodos Construtores
Em meus 3 métodos construtores obrigatórios, achei necessário separar os tipos de parâmetros que seriam inseridos, como os tipos de variáveis (int, String e float)

-------------------------------------------------------------------------------- || ---------------------------------------------------------------------------
### Métodos funcionais
A única funcionalidade que achei necessária foi para a organização da listagem de atributos, o que torna o código principal visualmente mais limpo, sem a necessidade de 5 *System.out.println* toda vez que eu precisasse listar as caracteristicas do produto.

-------------------------------------------------------------------------------- || ---------------------------------------------------------------------------
## Classe Driver (Main)
Para tornar o código limpo na parte main, abaixo dele inseri funções que seriam chamadas ali na função principal (public static void main) para não poluir tanto com códigos funcionais.

### Função Cadastrar
uma função simples que serve para cadastrar os atributos que o usuário for inserir do produto, que será criado logo após a inserção dos atributos pelo usuário. Para armazenar os produtos, achei preciso criar um array no formato de list, pois ele é bem dinâmico quando se trata de quantidade de elementos disponíveis, o que o torna bem flexível, além de ser fácil de manipular.

### Função Alterar produto
função que apresenta os produtos criados pelo usuário em formato de menu, onde irá alterar um atributo do produto escolhido no prompt. Nesse caso, eu apenas percorro o array buscando, primeiro, todos os produtos disponíveis lá dentro e, após a escolha do produto pelo usuário, utilizo do método funcional do produto para listar seus atributos, e no atributo indicado, eu apenas substituo a caracteristica antiga pela nova através do get, set e uma variável que armazena a nova escolha do usuário.

### Função remover produto
Ele segue a mesma lógica da função citada anteriormente, porém ao invés de adentrar em mais um conceito (que no caso seria a escolha do atributo para sua alteração), é utilizado a função nativa do java *.remove()* que remove um elemento de determinado array

### Função lista de produtos
Essa função foi feita mais para otimizar a função main que poupa algumas linhas de código que servem somente para listar todos os produtos já catalogados pelo usuário, mas eu decidi adicionar um outro ponto que é mostrar os atributos/características do determinado produto, para permitir o usuário verificar se está de acordo as informações contidas ali. 

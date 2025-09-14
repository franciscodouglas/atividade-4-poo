# Atividade 4 - Aplicação de Orientação a Objetos

## Sumário 
- [Como Utilizar Esse Projteto](#como-utilizar-esse-projeto-)
- [Escopo da Atividade](#escopo-da-atividade-%EF%B8%8F) 
- [No Microsoft Teams](#no-microsoft-teams--)
- [Regras](#regras-)
- [Feedback](#feedback-)

## Como Utilizar Esse Projeto 📁

- Nesse projeto há duas pastas:
    - FazerNetBeans:Exclusiva para realizar no VisualStudio Code. 

- Na sua máquina tem que ter instalado o <a href="https://www.oracle.com/br/java/technologies/downloads/" target="_blank">Java Development Kit (JDK) </a> 
- Caso utilize o VisualStudio Code é necessário que instale a <a href="https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack" target="_blank">Extension Pack for Java</a>


- <b>Atenção!</b> Escolhe apenas <b>UMA</b> das pastas para realizar a atividade! 

## Escopo da Atividade 🛠️
Implemente um sistema simples de gestão de Produtos com base no seguinte cenário:

- Crie uma classe chamada Produto com os seguintes atributos privados:
    - String nome
    - double preco
    - int quantidadeEstoque
- Implemente:
    - a) Construtores
        -   Construtor padrão (sem parâmetros).
        -   Construtor com 2 parâmetros (nome, preco).
        -   Construtor com 3 parâmetros (nome, preco, quantidadeEstoque).
    -   b) Métodos de acesso (getters e setters) para todos os atributos.
        -   No setPreco, não permita valores negativos.
        -   No setQuantidadeEstoque, não permita valores abaixo de 0.
    -   c) Métodos adicionais:
        -   adicionarEstoque(int qtd) → soma a quantidade informada ao estoque.
        -   removerEstoque(int qtd) → reduz a quantidade (validar para não ficar negativa).
        -   calcularValorTotal() → retorna o valor total em estoque (preco * quantidadeEstoque).
    -  Crie uma classe Main que:
        - Instancie 3 objetos Produto utilizando diferentes construtores.
        - Utilize os métodos get/set para alterar atributos.
        - Aplique operadores aritméticos e lógicos (ex.: verificar se o estoque é suficiente antes de remover).
        - Exiba as informações dos produtos no console.

## No Microsoft Teams  👥

- Não há necessidade fazer o upload do projeto 

## Regras 📄

- Utilize as boas práticas de programação que são sempre mencionadas em aula e nos materiais; 
- Observe sempre os modificadores de acesso em atributos e métodos;
- Observe os nomes de classes e atributos;
- Utilze comentários para elucidar o cenário elaborado;

## Feedback 📨
-  Sua atividade receberá uma pontuação de 0 a 10, que compõe a Nota da ATV1;
-  A nota será atribuída no Microsoft Teams


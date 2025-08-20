# Conteúdo Aula 2 - Variáveis e funções 
Link base: https://inteli.bitdocs.ai/share/d/xcxNIYYyFSc2ve1t

---

## Uma Introdução a programação com Foco em Marketing
&emsp; Para entender como a tecnologia pode otimizar processos em áreas como o marketing, é essencial começar pela base da programação: o algoritmo. Um algoritmo nada mais é do que uma sequência de passos lógicos para executar uma tarefa ou resolver um problema. A partir desse conceito, podemos mergulhar nos blocos de construção fundamentais de qualquer código.

### O que são Variáveis?
&emsp; Em programação, uma variável é um espaço nomeado na memória do computador que armazena um valor que pode ser alterado durante a execução do programa.
&emsp; Para simplificar, imagine uma variável como uma caixa. Você dá um nome a essa caixa para identificá-la facilmente, como "Ingredientes do Bolo". Dentro dela, você pode adicionar, trocar ou remover objetos (os dados). Toda vez que precisar de algo que está lá dentro, basta pedir pela caixa usando o nome que você deu. Essa capacidade de armazenar e manipular informações é a base de toda a programação.

### Organizando a Informação: Tipos de Dados
&emsp; Continuando com a analogia, para manter a organização, você não guardaria ferramentas e alimentos na mesma caixa. Você definiria que uma caixa é só para "Objetos de Limpeza", outra para "Equipamentos de Gravação", e assim por diante. Em programação, essa organização é feita através dos tipos de dados, que são categorias que definem a natureza dos valores que uma variável pode armazenar.

&emsp; Aqui estão os tipos de dados mais comuns:
- **Inteiro (Integer ou int):** Representa números inteiros, sem casas decimais.
Exemplos: 1, 10, -5, 999

- **Ponto Flutuante (Float):** Representa números com casas decimais.
Exemplos: 0.1, 10.8, 3.14, -2.5

- **Texto (String):** Representa sequências de caracteres, como palavras ou frases. O valor é geralmente colocado entre aspas.
Exemplos: "marketing", "dinheiro", "Lançamento incrível!", "2" (note que o número 2 entre aspas é tratado como texto).

- **Booleano (Boolean ou bool):** Representa um valor lógico, que só pode ser verdadeiro ou falso.
Exemplos: true (verdadeiro), false (falso).

- **Lista (List ou Array):** É uma coleção ordenada de múltiplos valores, que podem ser de tipos diferentes.
Exemplos: [1, 2, 3, 4], ["escola", "divertida", "Butantã"], [1, "cidade", 10.2]

### O que são Funções?
&emsp; Agora que sabemos como guardar informações, precisamos de uma forma de realizar ações com elas. Uma função é um bloco de código organizado e reutilizável que executa uma tarefa específica.
&emsp; Voltando à nossa caixa, imagine que toda segunda-feira você tem a rotina de gravar o pôr do sol. Para isso, você precisa pegar o objeto "câmera" da sua caixa de "Equipamentos de Gravação". Essa rotina, que conta com ações organizadas (ir até a caixa, abri-la, pegar a câmera, fechá-la), pode ser expressa como uma função no mundo da programação. Você cria a rotina uma vez e pode "chamá-la" toda vez que precisar executá-la.

#### Aplicação Prática no Marketing: Publicando no Instagram
&emsp; Vamos unir todos esses conceitos em um exemplo prático. Imagine que queremos automatizar a publicação de um post no Instagram.
&emsp; Primeiro, precisamos organizar as informações que vamos usar. Em programação, guardamos essas informações em variáveis:

- `imagem_do_post: "foto_produto_novo.jpg"` (O arquivo da nossa imagem)
- `texto_do_post: "Lançamento incrível! Conheça nosso novo produto X que vai revolucionar seu dia a dia."` (O texto da descrição)
- `hashtags: "#marketingdigital #lançamento #produtoX"` (As hashtags para aumentar o alcance)
- `plataforma_para_enviar: "Instagram"` (Onde vamos publicar)

&emsp; Com as informações prontas, criamos nossa função, nossa ferramenta de ação, que podemos chamar de `publicarPost`. Abaixo está um exemplo de como essa lógica seria escrita em pseudo-código (um rascunho do código):

```
// 1. Guardar as informações nas variáveis
var imagem_do_post = "foto_produto_novo.jpg"
var texto_do_post = "Lançamento incrível! Conheça nosso novo produto X..."
var hashtags = "#marketingdigital #lançamento #produtoX"
var plataforma_alvo = "Instagram"

// 2. Criar nossa ferramenta - a função
// Ela precisa saber o que postar e onde postar.
função publicarPost(imagem, texto, tags, rede_social) {
    // Ações que a função executa:
    CONECTAR na 'rede_social'
    FAZER_UPLOAD da 'imagem'
    ESCREVER o 'texto' na descrição
    ADICIONAR as 'tags'
    CLICAR no botão "Publicar"
    MOSTRAR "Post publicado com sucesso em " + rede_social + "!"
}

// 3. Usar nossa função com as variáveis que criamos
publicarPost(imagem_do_post, texto_do_post, hashtags, plataforma_alvo)
```

&emsp; Ao entender esses pilares — variáveis para guardar dados, tipos para organizá-los e funções para agir sobre eles — começamos a enxergar como a programação pode automatizar e otimizar tarefas rotineiras, abrindo um leque de possibilidades para criar ferramentas e estratégias mais eficientes no marketing.

---
# Conteúdo para os slides

**Slide 1** - *Resumo breve sobre o que é algoritmo* 

**Slide 2**- *O que são variáveis* - explicação sobre variáveis
O que são variáveis?
Em programação, uma variável é um espaço nomeado na memória do computador que armazena um valor que pode ser alterado durante a execução do programa.

**Slide 3** - *Exemplo de como funciona os variáveis* - explicação de variável com um exemplo

- Como isso funciona?
    - Imagine uma **caixa** onde **você guarda algum objeto**,
    - Você **nomeia** essa **caixa**,
    - Nessa caixa, você **pode adicionar, trocar ou tirar objetos**,
    - Toda vez que você **quiser ver esse objeto**, você pede para **alguém pegar a caixa com o nome que você deu**.

**Slide 4** - *O que são os tipos de dados?* - explicação sobre os tipos de dados
- Em programação, tipos de dados são categorias que definem a natureza dos dados que podem ser armazenados e manipulados em um programa.

**Slide 5** - *Exemplo de como funciona os tipos de dados* - explicação de tipos de dados
- Voltando para a **caixa**
- Por questão de **organização**, você define que **em uma caixa você só vai colocar objetos** de **limpeza**, outra para **equipamentos de gravação** e assim por diante.

**Slide 6** - *Tipos de dados* - Listamento com os tipos de dados
- *(Fazer uma tabela com as seguintes informações)*
    - **Inteiro (Int)** - 1; 2; 3 …
    - **Float** - 0.1; 10.8 …
    - **String** - “marketing”; “dinheiro”; “felicidade”; “2” …
    - **Char** - m; d; f …
    - **Lista** - coleção de valores. Ex: [1, 2, 3, 4]; [escola, divertida, Butantã]; [1, cidade, 10.2, técnico] …
    - **Bool** - true, false
    - **Funções** - Bloco de código que pode ser chamado

**Slide 7** - *Hora de treinar* - Pequeno exercício para incentivar a galera a participar da aula
- Identifique os tipos dos seguintes dados:
    - 10 - int
    - 1000000000.1 - float
    - “Um” - string
    - “8” - string ou char
    - “true” - string
    - false - bool
    - “[1, 2, 3, 4]” - string

**Slide 8** - *O que são funções?* - Explicação sobre função
- O que é uma função?
    - Função é um bloco de código organizado e reutilizável que executa uma tarefa específica.

**Slide 9** - *O que isso significa?* - Explicação sobre função com um exemplo
- Voltando a velha **caixa**,
- Todas as **segundas** eu **faço uma gravação do pôr do sol**, para isso eu **vou querer tirar** o **objeto câmera** da **caixa de equipamento de gravação**
- Essa rotina, conta com **ações organizadas para realizar uma atividade específica**.
- Isso pode ser expresso como uma função no mundo da programação

**Slide 10** - *Como isso pode ser aplicado no marketing?* - Explicação com um exemplo na área de marketing
- Vamos planejar uma publicação no Instagram?
    - Nossas Informações (Variáveis):
        - `imagem_do_post: "foto_produto_novo.jpg"` (O arquivo da nossa imagem)
        - `texto_do_post: "Lançamento incrível! Conheça nosso novo produto X que vai revolucionar seu dia a dia."` (O texto que vai na descrição)
        - `hashtags: "#marketingdigital #lançamento #produtoX"` (As hashtags para aumentar o alcance)
        - `plataforma_para_enviar: "Instagram"` (Onde vamos publicar)
    - Nossa Ação Principal (Função):
        - `publicarPost` (A ação de pegar essas informações e efetivamente postar)


**Slide 11** - *Como isso pode ser aplicado no marketing?* - Explicação com um exemplo na área de marketing
- Vamos aplicar o que vimos em marketing
    - Pseudo-código
```
//Guardar as informações nas variáveis
var imagem_do_post = "foto_produto_novo.jpg" 
var texto_do_post = "Lançamento incrível! Conheça nosso novo produto X..." 
var hashtags = "#marketingdigital #lançamento #produtoX" var plataforma_alvo = "Instagram"

//Criar nossa ferramenta - a função
//Ela precisa saber o que, e onde postar
função publicarPost(imagem, texto, tags, rede_social) {
	//Ações da função
	CONECTAR na 'rede_social' 
FAZER_UPLOAD da 'imagem' 
ESCREVER o 'texto' na descrição 
ADICIONAR as 'tags' 
CLICAR no botão "Publicar" 
MOSTRAR "Post publicado com sucesso em " + rede_social + "!"
}

//Usar nossa função com as variáveis
publicarPost(imagem_do_post, texto_do_post, hashtags, plataforma_alvo)
```

**Slide 12** - *Vamos exercitar* - Um kahoot para consolidar o que foi passado na aula
	Hora do kahoot!


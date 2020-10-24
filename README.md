# Trabalho Final - Construção de Compiladores #

### Equipe ###

* Manuel Edvar Bento Filho - 384368
* Mozart Breno da Silva Vieira - 384374
* Vitoria Verçosa de Oliveira - 384386

### Etapas ###

* Etapa 01: Analisador Léxico e Sintático
* Etapa 02: Árvore Sintática Abstrata, Tabela de Símbolos e Verificação de Tipos
* Etapa 03: Registros de Ativação e Tradução para o Código Intermediário
* Etapa 04: Blocos Básicos e Traços e Seleção de Instruções
* Etapa 05: Análise de Longevidade e Alocação de Registradores

### Relatório ###

* Trabalho Final: Este trabalho tem como objetivo, a implementação de um compilador para a linguagem MiniJava, sendo esta um subconjunto da linguagem Java que conhecemos, este compilador, foi construído em módulos (pacotes), seguindo as instruções do livro texto Modern Compiler Implemntation in Java, que instrui todo o processo da criação do mesmo

* Etapa 01: Esta primeira etapa, sendo a mais fácil do compilador, é caracterizado pelo uso da gramática que formula o MiniJava e o uso do JavaCC como auxiliador nessa etapa e que gera o analisador léxico e sintático, a partir das definições dos tokens e das produções da gramática. Nesta etapa tudo o que foi proposto foi implementado.

* Etapa 02: Nesta etapa do compilador, temos a geração da árvore sintática abstrata, tabela de símbolos e é realizada 
a verificação de tipos para a análise semântica do código a ser compilado, por meio de visitors esse três processos são executados. Nesta etapa, tudo o que foi proposto foi implementado.

* Etapa 03: Esta consiste no uso de registros de ativação e na tradução para código intermediário, também por meio de visitors e o uso de nós da estrutura da árvore, há um método para cada ação possível do MiniJava, sendo que alguns destes não foram possíveis de serem implementados, sendo eles a definição de variável e identifiador e o Call.

* Etapa 04: Nesta parte do compilador é realizado a criação de blocos básicos e a seleção de instruções, por meio de uma estrutura de árvore canônica, desta etapa fizemos por completo a parte responsável pela árvore canônica, e do assembly, só não foi possível o término do CodeGen, devido alguns empecilhos em relação ao código.

* Etapa 05: Da etapa final temos que realizar a análise de longevidade e alocar os registradores. Por questões de tempo de fim de semestre só foi possível ser feita a implementação da estrutura da análise de longevidade, com o grafo de fluxo de controle e da etapa de alocação de registradores, somente a estrutura foi realizada.

### Reuniões ###

* Etapa 01: 29/04 às 11:30
* Etapa 02: 22/04 às 11:00
* Etapa 03: 10/05 às 10:30
* Etapa 04: 29/05 às 10:00
* Etapa 05: 19/06 às 10:00
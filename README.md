# Relatório Final - Construção de Compiladores - 2020 UFC#

### Participantes da Equipoe ###

* Breno Araújo de Lima
* Everson Magalhães Cavalcante
* Belchior Dameão de Araújo Neto

### Etapas ###

* 1 - Análise Léxica e Análise Sitática
* 2 - Árvore Sintática Abstrata (AST), Tabela de Símbolos e Verificação de Tipos
* 3 - Registros de Ativação, Tradução para Representação Intermediária e Código Intermediário Canônico
* 4 - Seleção de Instruções
* 5 - Análise de Longevidade e Alocação de Registradores

### Relatório ###

* Trabalho Final: Tem como objetivo contruir um compilador para a liguagem "minijava" que é uma versão minimizada do JAVA, para isso foi usado como fonte principal as video-aulas do professor e o livro-texto indicado para a disciplina, "Modern Compiler Implementation in Java" de Jens Palsberg e Andrew Appel

* primeira etapa - Na primeira Etapa implementamos os módulos de "Análize Léxica" e "Análize Sintática", tivemos certa dificuldade por ser uma etapa muito teórica, e além disso foi necessário aprender a sintaxe da linguagem JavaCC, necessária para a implementação do código nesta primeira etapa.

* segunta etapa - Nesta etapa tivemos a primeira visão mais detalhada e consequentemente o melhor entendimento do framework, entendendo melhor os padrões de projetos usados para melhor organização do projeto final, a implementação dos códigos necessários foi relativamente tranquilas na etapa da AST e um pouco mais complicada na etapa da verificação de tipos.

* terceira etapa - Tivemos certa dificuldade na integração das classes fornecidas pelo framework ao projeto quando consideramos todo o processo envoldido nesta etapa, onde foi necessário resolver alguns conflitos entre as classes existentes no framework e as nossas implementações, estas dificuldades porém nos forçaram a entender melhor o projeto como um todo.

* quarta etapa - Aqui implementamos a tradução da IRTree para código de máquina, especificamente para arquitetura MIPS, foi utilizado o algorítimo Maximal Munch, onde precisamos usar boa parte do tempo no estudo e entendimento da teoria por tras do algorítimo.

* quinta etapa - Nesta fase trabalhamos na implementação das classes reponsáveis por fazer a coloração do grafo responsável por fazer a alocação de registradores, também nesta fase foi onde fizemos a integração de todos os módulos e os testes finais e nos reunimos para avaliação do projeto como um todo.

# Pascal e Objective Pascal com `fpc`

~~~bash
sudo apt install fpc
touch nymph.pas
nano nymph.pas
~~~

## Começe a programar agora!  
Inicie no mundo da programção com pascal, linguagem poderosa e que fornece uma base solida e divertida para aprendizagem da programação de computadores.    
> Esta linguagem pode ser considerada `old school`, mas recomendo fortemente sua aprendizagem. [^author]

~~~pascal
PROGRAM Pascal(Nymph);
BEGIN   
        Writeln('Hello,World!');
END.    
~~~

~~~bash
# compilar e executar o programa
fpc nymph.pas
./nymph
~~~

> * _Digite o codigo no terminal `fpc nymph.pas` para criar o programa_ 
> * Execute o codigo no teminal `./nymph` para ver o resultado

# Desfrute de todo o conteudo do guia
| Pratique o _**Guia**_              |  
|:---|
| Consulte os exemplos de _**Codigos**_   |  
| Resolva os _**Desafios**_          |
| Construa os _**Projetos**_         |

# :card_index: Pascal, Guia do Programador

## [Guia Basico](1-guia-basico/README.md)
Construindo um programa basico de dados simples.
## ~~[Guia Intermediario](2-guia-intermediario/README.md)~~
Controle e manipulacão de dados simples e compostos
## ~~[Guia Avançado](3-guia-avancado/README.md)~~
Constuindo programas completos e com facilidade.
## ~~[Guia Mestre](4-guia-mestre/README.md)~~
Construindo e manipulando tipos de dados complexos.   

## Arvore de Pasta do Projeto
~~~
    PASTAS DO PROJETO
    └─ pascal
        ├─ guia-basico
        |   └─ codigos-em-pascal
        ├─ guia-intermediario
        │   └─ codigos-em-pascal
        └─ guia-avancado
            └─ codigos-em-pascal
~~~

# Requisitos
Linux ou macOS
> * Instale o Compilador `fpc`. 

### Nota de Rodapé
[^author]: Samuel Oliveira, [@juniobash](https://github.com/juniobash)

___

> ### Basic Guide

|#   | |Capitulo |Link|
|:---|:---|:---|:---|
|1   |`int` `float` `caracter` `boolean` | Tipos de Dados Simples|[Link]()|
|1.1 | `<-` | Atribuição de Dados|[Link]()|
|1.2 | `ReadLn` | Entrada de Dados|[Link]()|
|1.3 | `WriteLn` | Saída de Dados|[Link]()|
|1.4 | `+` `-` `*` `/` `\` `%` `ˆ` | Operando Com numeros|[Link]()|
|1.5 | `+` | Operando Com Textos|[Link]()|
|1.6 | `==` `<>` `<` `<=` `>` `>=` | Operando Com Relações|[Link]()|
|1.7 | `\|\|` `!` `&&`  `XOR` | Operando Com Logica Booleana|[Link]()|

> ### Intermediate Guide

|#   || Capitulo |Link|
|:---|:---|:---|:---|
|2   | `*ponteiro`| Variável de Endereço de Memória|[Link]()|
|2.1 | `fila[1..10]`| Variável de Vetor de Dados|[Link]()|
|2.2 | `ingressos[1..3][1..10]`| Variável de Matriz de Dados|[Link]()|
|2.3 | `if else` `swicth`| Fluxo de Dados de Seleção|[Link]()|
|2.4 | `for` `do while` `loop`| Fluxo de Dados de Repetição|[Link]()|
|2.5 | `procedure`| Blocos de Códigos de Procedimentos|[Link]()|

> ### Advanced Guide

|#   || Capitulo |Link|
|:---|:---|:---|:---|
|3   | `struct` `record` `class` `objeto` `type`| Tipos de Dados Abstratos e Complexos |[Link]()|
|3.1 | `func`| Bloco de Códigos de Funções|[Link]()|
|3.2 | `subprogramas` `package` `subrotinas`| Criando Programas Auxiliares|[Link]()|
|3.3 | `arquivo.txt`| Percisitencia de dados em txt|[Link]()|

#  Special Programming Guide
> ### Estrutura e Ordenação de Dados

|#   | |Capitulo |Link|
|:---|:---|:---|:---|
|4 | `crescente` `decresente`| Pesquisa e Ordenação de dados|[Link]()|
|4.1 | `pilha[1..10]`| Pilha de Dados|[Link]()|
|4.2 | `fila[1..10]`| Fila de Dados|[Link]()|
|4.3 | `lista[1..10]`| Lista de Dados|[Link]()|
|4.4 | `arvore`| Arvore de Dados|[Link]()|

# A1 - Técnicas de Desenvolvimento de Algoritmos

Este repositório contém as atividades práticas desenvolvidas para a Avaliação A1 da disciplina Técnicas de Desenvolvimento de Algoritmos, conforme o plano de avaliação, cobrindo os tópicos obrigatórios: Estruturas Condicionais, Estruturas de Repetição, Listas e Dicionários.

Critério de Entrega: Repositório público no GitHub, com pastas organizadas e este README explicativo.

##  Estrutura do Repositório (Organização - 1,0 pt)

O projeto está organizado em quatro pastas, cada uma contendo o código Python do exercício correspondente:

- `Estruturas_Condicionais`
- `Estruturas_de_Repeticao`
- `Listas`
- `Dicionarios`


##  Atividades Práticas e Critérios de Avaliação

### 1.  Estruturas Condicionais (`verificacao_idade.py`) - 1,0 pt

**Breve Explicação:**
O programa simula um sistema de verificação de idade para entrada em eventos. Ele solicita a idade do usuário e utiliza a estrutura **`if`**, **`elif`** e **`else`** para determinar o status de entrada com base em regras de maioridade (menor que 16, 16+, 18+).

**Critérios Atendidos:**
- Uso correto de `if`, `elif`, `else`
- Entrada e saída de dados
- Clareza no código e comentários

**Exemplo de Entrada/Saída:**
| Entrada | Saída Esperada |
| :--- | :--- |
| `15` | ` Entrada Proibida. Evento apenas para maiores de 16 anos.` |
| `17` | ` Entrada Permitida (16+). Você pode entrar, mas não tem acesso a áreas 18+.` |
| `25` | ` Entrada Permitida (18+). Seja bem-vindo(a)!` |

---

### 2.  Estruturas de Repetição (`contadores_pares.py`) - 1,0 pt

**Breve Explicação:**
O programa demonstra a implementação de dois contadores de 1 a 100, exibindo apenas os números **pares**. O primeiro contador utiliza o laço **`for`**, e o segundo utiliza o laço **`while`**, aplicando o operador lógico (módulo `%`) para a filtragem dos números pares.

**Critérios Atendidos:**
- Implementação correta dos laços (`for` e `while`)
- Uso de operadores lógicos (módulo %)
- Organização do código

**Exemplo de Entrada/Saída:** 
| Execução | Saída no Console | 
| :--- | :--- | 
| `python contadores_pares.py` 
|`--- Contagem de Pares (1 a 100) usando FOR ---` | `2 4 6 8 10 12 ... 100` |


`--- Fim da contagem FOR ---`


| `--- Contagem de Pares (1 a 100) usando WHILE ---` | `2 4 6 8 10 12 ... 100` |


`--- Fim da contagem WHILE --- `|

---

### 3.  Listas (`cadastro_alunos.py`) - 1,0 pt

**Breve Explicação:**
O programa implementa um sistema de cadastro que recebe nomes de alunos de forma dinâmica (em loop) e armazena cada nome em uma **Lista** (usando `append`). Ao digitar "sair", o loop é encerrado e a **impressão correta** de todos os nomes armazenados na lista é realizada.

**Critérios Atendidos:**
- Uso adequado de listas
- Entrada dinâmica de dados (usando `while`)
- Impressão correta dos elementos

**Exemplo de Entrada/Saída:** 
| Sequência de Comandos |
| :--- | 
| ` Nome do aluno: Ana` |

| `'Ana' cadastrado. Total: 1 alunos.` |


| `Nome do aluno: Pedro` |

| `'Pedro' cadastrado. Total: 2 alunos.` |


| `Nome do aluno: sair` | 


---  Lista Final de Alunos ---


`1. Ana`


`2. Pedro` 

---

### 4.  Dicionários (`cadastro_produtos.py`) - 1,0 pt

**Breve Explicação:**
O programa desenvolve um sistema simples de cadastro de produtos. Os dados são armazenados em um **Dicionário**, onde o **Nome do Produto** atua como a **chave** e o **Preço** atua como o **valor**. O código demonstra a inserção, manipulação e a recuperação dos dados do dicionário.

**Critérios Atendidos:**
- Uso correto de `dict()`
- Inserção e recuperação de dados
- Estrutura clara e funcional

**Exemplo de Entrada/Saída:** 
| Sequência de Comandos | 
| :--- |
| `Nome do Produto: Camiseta` |


| `Preço de Camiseta: R$ 50.00` |

| `Produto 'Camiseta' (R$ 50.00) cadastrado com sucesso.` |


| `Nome do Produto: Bermuda` |


| `Preço de Bermuda: R$ 80.00` |

| `Produto 'Bermuda' (R$ 80.00) cadastrado com sucesso.` |


| `Nome do Produto: sair` |


---  Produtos Cadastrados ---


`Produto: Camiseta | Preço: R$ 50.00` 


`Produto: Bermuda | Preço: R$ 80.00 |`

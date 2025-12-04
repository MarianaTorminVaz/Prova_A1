# A1 - Técnicas de Desenvolvimento de Algoritmos

Este repositório contém as atividades práticas desenvolvidas para a Avaliação A1 da disciplina Técnicas de Desenvolvimento de Algoritmos, conforme o plano de avaliação, cobrindo os tópicos obrigatórios: Estruturas Condicionais, Estruturas de Repetição, Listas e Dicionários.

Critério de Entrega: Repositório público no GitHub, com pastas organizadas e este README explicativo.

##  Estrutura do Repositório (Organização - 1,0 pt)

O projeto está organizado em quatro pastas, cada uma contendo o código Python do exercício correspondente:

- `Estruturas_Condicionais`
- `Estruturas_de_Repeticao`
- `Listas`
- `Dicionarios`

##  O Problema e a Solução Proposta

Cenário: Imagine que estamos desenvolvendo um Sistema de Gestão de Eventos e Produtos simplificado, focado em operações essenciais de verificação de acesso, monitoramento, cadastro de participantes e registro de itens.

A Solução: O projeto é estruturado em quatro módulos Python independentes, cada um resolvendo uma parte desse cenário, aplicando uma estrutura de dados ou controle de fluxo específica.

**Conteúdo / Tarefa Implementada / Pontuação**

`Estruturas Condicionais / Verificação de Idade para Entrada em Eventos / "1,0 pt "`

`Estruturas de Repetição / Contador de 1 a 100, exibindo apenas Pares (com for e while) / "1,0 pt "`

`Listas / Cadastro de Nomes de Inscritos/Participantes / "1,0 pt "`

`Dicionários / Cadastro Simples de Produtos (Nome e Preço) / "1,0 pt "`

##  Atividades Práticas e Critérios de Avaliação

### 1.  Estruturas Condicionais - 1,0 pt

**História do Projeto: O Porteiro Digital**

Problema: A casa de eventos "Python Club" precisa de um sistema automatizado e infalível para verificar a idade dos clientes na entrada. Eles querem garantir que menores de 18 anos sejam barrados e que clientes idosos (65+) recebam uma saudação especial de acesso prioritário.

Solução: Criamos um "Porteiro Digital" que utiliza a lógica de Estruturas Condicionais (if, elif, else ) para tomar a decisão correta.
O programa simula um sistema de verificação de idade para entrada em eventos. Ele solicita a idade do usuário e utiliza a estrutura **`if`**, **`elif`** e **`else`** para determinar o status de entrada com base em regras de maioridade (menor que 18, 18+, 65+).

**Critérios Atendidos:**
- Uso correto de `if`, `elif`, `else`
- Entrada e saída de dados
- Clareza no código e comentários

**Exemplo de Entrada/Saída:**
| Entrada | Saída Esperada |
| :--- | :--- |
| `15` | ` Entrada Proibida. Evento apenas para maiores de 18 anos.` |
| `18` | ` Entrada Permitida. Bem-vindo(a) ao evento!` |
| `65` | ` Entrada Permitida. Acesso prioritário para idosos.` |

---

### 2.  Estruturas de Repetição - 1,0 pt

**História do Projeto: O Monitor de Qualidade**

Problema: Uma linha de produção industrial precisa de um mecanismo simples para monitorar a contagem de itens de 1 a 100. Por uma regra de inspeção, apenas os itens em posições pares (2º, 4º, 6º, etc.) devem ser registrados para um controle de qualidade automatizado.

Solução: Desenvolvemos um "Monitor de Qualidade" que usa Estruturas de Repetição (for e while) para simular a passagem dos 100 itens. Utilizando o operador de módulo (%), ele identifica e registra apenas os números pares. O programa demonstra a implementação de dois contadores de 1 a 100, exibindo apenas os números **pares**. O primeiro contador utiliza o laço **`for`**, e o segundo utiliza o laço **`while`**, aplicando o operador lógico (módulo `%`) para a filtragem dos números pares.

**Critérios Atendidos:**
- Implementação correta dos laços (`for` e `while`)
- Uso de operadores lógicos (módulo %)
- Organização do código

**Exemplo de Entrada/Saída:** 

|`--- Contagem de Pares (1 a 100) usando FOR ---` | `2 4 6 8 10 12 ... 100` |


`--- Fim da contagem FOR ---`


| `--- Contagem de Pares (1 a 100) usando WHILE ---` | `2 4 6 8 10 12 ... 100` |


`--- Fim da contagem WHILE --- `

---

### 3.  Listas - 1,0 pt

**História do Projeto: O Gerenciador de Participantes**

Problema: O setor de RH está organizando um grande treinamento e precisa de uma ferramenta rápida para registrar o nome de cada participante conforme ele se inscreve. O sistema deve ser flexível, aceitando um número indeterminado de nomes, e capaz de exibir a lista final de todos os inscritos.

Solução: O "Gerenciador de Participantes" utiliza uma Lista como seu principal mecanismo de armazenamento. O programa implementa um sistema de cadastro que recebe nomes de alunos de forma dinâmica (em loop) e armazena cada nome em uma **Lista** (usando `append`). Ao digitar "sair", o loop é encerrado e a **impressão correta** de todos os nomes armazenados na lista é realizada.

**Critérios Atendidos:**
- Uso adequado de listas
- Entrada dinâmica de dados (usando `while`)
- Impressão correta dos elementos

**Exemplo de Entrada/Saída:** 

| ` Nome do participante: Ana Souza` |

| `'Ana Souza' cadastrado. Total: 1 inscritos.` |


| `Nome do participante: Beto Lima` |

| `'Beto Lima' cadastrado. Total: 2 inscritos.` |


| `Nome do participante: sair` | 


---  Lista Final de Inscritos ---


`1. Ana Souza`


`2. Beto Lima` 

---

### 4.  Dicionários - 1,0 pt

**História do Projeto: O Catálogo Inteligente**

Problema: Um pequeno e-commerce precisa de um sistema de inventário onde cada produto possa ser rapidamente identificado pelo seu nome e associado a um único valor, que é o seu preço.

Solução: O "Catálogo Inteligente" resolve isso utilizando um Dicionário (dict()). O **Nome do Produto** atua como a **chave** e o **Preço** atua como o **valor**. O código demonstra a inserção, manipulação e a recuperação dos dados do dicionário.

**Critérios Atendidos:**
- Uso correto de `dict()`
- Inserção e recuperação de dados
- Estrutura clara e funcional

**Exemplo de Entrada/Saída:** 

| `Nome do Produto: Mouse Pad`|


| `Preço de Mouse Pad: R$ 35.00` |

| `Produto 'Mouse Pad' (R$ 35.00) cadastrado com sucesso.` |


| `Nome do Produto: Webcam HD` |


| `Preço de Webcam HD: R$ 150.00` |

| `Produto 'Webcam HD' (R$ 150.00) cadastrado com sucesso.` |


| `Nome do Produto: sair` |


---  Produtos Cadastrados ---


`Produto: Mouse Pad | Preço: R$ 35.00` 


`Produto: Webcam HD | Preço: R$ 150.00 |`

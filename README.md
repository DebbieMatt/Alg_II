# Exercícios de Algoritmo e estrutura de Dados II em C 

## Descrição

![C](https://img.shields.io/static/v1?label=Linguagem&message=C&color=00599C&style=for-the-badge&logo=c)
![Status](https://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=green&style=for-the-badge)
![License](https://img.shields.io/static/v1?label=LICENÇA&message=MIT&color=blueviolet&style=for-the-badge)

> Resolução em **C** dos exercícios e listas da disciplina de **Algoritmos e Estrutura de Dados I**.  
> Os programas cobrem desde fundamentos de ponteiros e alocação de memória até estruturas de dados clássicas como pilhas, filas e listas encadeadas.

### Conteúdo

Arquivos com seus respectivos desafios:

1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Conteúdos Abordados](#-conteúdos-abordados)
3. [Estrutura do Repositório](#-estrutura-do-repositório)
4. [Saiba Antes de Executar](#-saiba-antes-de-executar)
5. [Como Compilar e Executar](#-como-compilar-e-executar)
6. [Enunciados](#enunciados)
7. [Contribuindo](#-contribuindo)
8. [Licença](#-licença)
  
---
 
## 🎯 Sobre o Projeto
 
Este repositório reúne a resolução dos exercícios desenvolvidos ao longo da disciplina de **Algoritmos e Estrutura de Dados I**. O foco está nos fundamentos da programação em C, abordando desde manipulação de ponteiros e alocação de memória até estruturas de dados lineares e algoritmos de ordenação.
 
> ⚠️ **Nota:** Como os exercícios fazem parte de um curso introdutório, algumas boas práticas avançadas de engenharia de software foram omitidas intencionalmente, priorizando a clareza dos conceitos fundamentais.
 
## 🧠 Conteúdos Abordados
 
| Unidade | Tema |
|---|---|
| 🔵 Unidade 1 | Passagem de Parâmetros, Alocação de Memória e Ponteiros |
| 🟢 Unidade 1 | Aritmética de Ponteiros, Vetores e Matrizes |
| 🟡 Unidade 1 | Manipulação de Ponteiros (void, malloc, calloc) |
| 🟠 Unidade 2 | Typedef, Struct, Union e Enumerador |
| 🔴 Unidade 3 | Manipulação de Arquivos (texto e binário) |
| 🟣 Unidade 4 | Pilha, Fila e Lista (estática e dinâmica) |
| ⚫ Unidade 5 | Algoritmos de Ordenação |
 
## 📁 Estrutura do Repositório
 
```
ALG_ESTRUT_DADOS_I/
│
├── PONTEIROS/                              # Unidade 1 — Ponteiros, Vetores e Matrizes
│   ├── UNID.01_ATV_00.c                    # Aposentadoria com ponteiros
│   ├── UNID.01_ATV_01.c                    # Comparação de endereços de memória
│   ├── UNID.01_ATV_02.c                    # CuiaBank — controle de saques
│   ├── UNID.01_ATV_03.c                    # Reajuste salarial por departamento
│   ├── UNID.01_ATV_04.c                    # Troca de vetores com aritmética de ponteiros
│   ├── UNID.01_ATV_05.c                    # Vetor C com maior valor entre A e B
│   ├── UNID.01_ATV_06.c                    # Vetor → Matriz de multiplicação
│   ├── UNID.01_ATV_07.c                    # Produto das diagonais de matriz NxN
│   └── UNID.01_ATV_08.c                    # Ponteiros genéricos (void**)
│
├── UNID. 1 - MEMÓRIA/                      # Alocação Dinâmica
│   ├── UNID.01_ATV_10.c                    # Interruptor com ponteiros de função
│   └── UNID.01_ATV_12.c                    # Vetor dinâmico com malloc/realloc
│
├── UNID. 2 - TIPOS ABSTRATOS DE DADOS/     # Struct, Union, Enum
│   ├── UNID.02_ATV_01.c                    # Sistema de inventário de produtos
│   ├── UNID.02_ATV_02.c                    # Gerenciamento de estacionamento
│   ├── UNID.02_ATV_03.c                    # Sistema de funcionários e departamentos
│   └── UNID.02_ATV_04.c                    # Sensores de automação residencial (union)
│
├── UNID. 3 - MANIPULAÇÃO DE ARQUIVOS/      # Leitura e escrita em arquivos
│   ├── UNID.03_ATV_01.c                    # Memória de estado da lâmpada
│   ├── UNID.03_ATV_02.c                    # Criptografia de mensagens em arquivo
│   └── UNID.03_ATV_03.c                    # Concessionária — registros em arquivo
│
├── UNID.4 - PILHA, FILA E LISTA/           # Estruturas de dados lineares
│   ├── UNID.04_ATV_v01.c                   # Garagem com pilha estática
│   ├── UNID.04_ATV_02.c                    # Playlist com desfazer/refazer (pilha dinâmica)
│   └── UNID.04_ATV_03.c                    # Fila de atendimento — clínica médica
│
└── UNID.5 - ALGORITMO DE ORDENAÇÃO/        # Algoritmos de ordenação
    ├── UNID.05_ATV_01.c                    # Ordenação de strings
    ├── UNID.05_ATV_02.c                    # Cadastro com ordenação múltipla
    ├── UNID.05_ATV_03.c                    # Desempilhamento recursivo com soma
    └── UNID.05_ATV_04.c                    # Quick Sort em ordem decrescente
```

## ⚠️ Saiba Antes de Executar
 
- Os programas são escritos em **C padrão (C99/C11)** e compilados com **GCC**
- Cada arquivo `.c` é independente — compile e execute individualmente
- Alguns exercícios utilizam **alocação dinâmica de memória** (`malloc`, `calloc`, `realloc`, `free`)
- Exercícios marcados como `(POR FAZER)` ainda estão em desenvolvimento
 
## ▶️ Como Compilar e Executar
 
### Pré-requisitos
 
Certifique-se de ter o GCC instalado:
 
```bash
gcc --version
```
 
### Clonando o repositório
 
```bash
git clone https://github.com/DebbieMatt/ALG_ESTRUT_DADOS_I.git
cd ALG_ESTRUT_DADOS_I
```
 
### Compilando um arquivo
 
```bash
# Sintaxe básica
gcc -o saida nome_do_arquivo.c
 
# Com flags recomendadas (exibe avisos e erros detalhados)
gcc -Wall -Wextra -o saida nome_do_arquivo.c
```
 
### Executando
 
```bash
./saida
```
 
### Exemplo completo
 
```bash
gcc -o garagem "UNID.4 - PILHA, FILA E LISTA/UNID.04_ATV_v01.c"
./garagem
```

## Enunciados

### Passagem de Parâmetros, Alocação de Memória e Ponteiros

> Tópicos abordados: Passagem de parâmetros para funções, princípios da alocação de memória, conceito de ponteiros, utilização de ponteiros na passagem de parâmetro para funções e manipulação de ponteiros.

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_00.c)

Escreva, usando ponteiros, uma função que recebe duas variáveis do tipo inteiro: uma representa a idade de uma pessoa, enquanto a outra representa o sexo. A função deve atualizar o valor da variável que representa a idade para o tempo que falta para a pessoa se aposentar, considerando as seguintes regras hipotéticas: 

* Mulheres podem se aposentar aos 60 anos; 
* Homens podem se aposentar aos 65 anos.

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_01.c)

Implemente, na linguagem de programação C, um programa que contenha duas variáveis: uma do tipo inteiro e outra com ponto flutuante. Compare os endereços dessas variáveis e exiba, de uma só vez, o maior endereço de memória, junto ao valor que ele armazena. 

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/45bd30dbb30efb010adcd75ca5cd8e896f055c2d/PONTEIROS/UNID.01_ATV_02.c)

O CuiaBank é um banco digital criado por estudantes da UFMT, incluindo você, que ficou responsável por implementar uma função para controle de saques. O CuiaBank oferece para seus clientes um valor de saldo especial, que pode ser emprestado a juros.

A cada tentativa de saque, deve ser verificado se o valor a ser sacado é inferior ou igual à soma do saldo da conta com o saldo especial. Se a operação for efetivada, a função deve alterar os seguintes valores: saldo em conta, saldo especial utilizado (ambos armazenados na função principal). Ao final das operações, escreva na tela o extrato bancário. 

#### [Exercicio 04](https://github.com/DebbieMatt/Alg_II/blob/ec932aefd31a65b0ba1d8d8175260461f53ebbe8/PONTEIROS/UNID.01_ATV_03.c)

Maria Gláucia trabalha no departamento de recursos humanos de uma empresa que aumentará o salário dos seus funcionários. O programa lida com as seguintes informações:

* código do departamento, representado por um número inteiro de 1 a 5;
* salário do funcionário, representado por um número real;

Para funcionários dos departamentos 1 e 2, o aumento será de 22%. Para os funcionários do departamento 3, o aumento será de 17%. Para os funcionários do departamento 4 e 5, o aumento de salário será de 10%.

Considerando as informações anteriores, implemente um programa com uma função que altera o novo salário dos funcionários, considerando o salário atual, o reajuste e o departamento de atuação. 

Ao final, imprima os valores de salário reajustados.

### Aritmética de Ponteiros, Vetores e Matrizes

> Aritmética de ponteiros (operações de adição e subtração com endereços de memória), acessar valores em vetores e matrizes com ponteiros.

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/2b809813961e2f9929de2947287335964f5f299c/PONTEIROS/UNID.01_ATV_04.c)

Crie um programa contendo dois vetores (A e B), de tamanho igual, cujos valores foram lidos do teclado. Em seguida, implemente uma função que recebe esses vetores e troque os valores do vetor A com os valores do vetor B. Use aritmética de ponteiros para efetuar essas operações.

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/4aa95ef573439409a5ef5688460644b4e3c27708/PONTEIROS/UNID.01_ATV_05.c)

Crie um programa contendo três vetores (A, B e C), de tamanho igual. Para os vetores A e B, os valores devem ser lidos do teclado. 

Em seguida, implemente uma função que recebe os três vetores. Cada posição do vetor C deve ser preenchido com o maior valor do vetor A ou B naquela mesma posição.

Use aritmética de ponteiros para efetuar essas operações. 

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/312395a5ed3b3fcca30d546a12d83213342a58d2/PONTEIROS/UNID.01_ATV_06.c)

Escreva um programa com um vetor de tamanho N (informado pelo usuário via teclado), com dados de tipo inteiro ou ponto flutuante (a seu critério), também informados pelo usuário final via teclado. 

Em seguida, implemente uma função que receba esse vetor e crie uma matriz de tamanho N por N. A primeira coluna da matriz deve conter os valores originais do vetor. As colunas restantes devem conter o resultado da multiplicação por 2, 3… n-1.

Exemplo:

Considere o seguinte vetor de entrada:

> 1 2 3 4 5

Considere a matriz de saída:

``````
1 	2	3	4	5
2	4	6	8	10
3	6	9	12	15
4	8	12	16	20
5	10	15	20	25
``````

Elabore as operações usando exclusivamente aritmética de ponteiros para percorrer o vetor e a matriz.

#### [Exercicio 04](https://github.com/DebbieMatt/Alg_II/blob/312395a5ed3b3fcca30d546a12d83213342a58d2/PONTEIROS/UNID.01_ATV_07.c)

Escreva um programa em C que contém uma matriz N por N. O tamanho pode ser escolhido por você. Usando exclusivamente a aritmética de ponteiros, o programa deve percorrer e calcular o produto da diagonal principal, bem como produto da diagonal secundária.

### Manipulação de Ponteiros

> Ponteiros Genéricos (void) e Múltiplos, Malloc e Calloc, Alocação Dinâmica de Memória: Vetores e Matrizes.

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/662120258cea1293fead3882e9d2abb8b5e89c20/PONTEIROS/UNID.01_ATV_08.c)

Analise o fragmento de código a seguir:

```
int a = 17;
int *ptr1 = &a;
void **ptr2 = (void **) &ptr1;
```

Qual operação pode ser feita para, a partir de ptr2, se chegar ao valor da variável a?

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/74a9def4a464562218ce6d26168ac7c18d6c84d7/UNID.%201%20-%20MEM%C3%93RIA/UNID.01_ATV_10.c)

Roberval é um estudante de Controle e Automação que deseja criar um sistema controle de luzes de uma casa. Para começar, ele pretende criar procedimentos para ligar e desligar as luzes.

Um terceiro procedimento, que simula um interruptor, recebe os endereços de memória dos procedimentos ligar e desligar. Se a lâmpada estava desligada, o procedimento deve ligá-la quando acionada. Da mesma forma, se ela estivesse desligada, o procedimento deveria desligar a luz.

O procedimento interruptor deve acionar os anteriores usando ponteiros.

#### [Exercicio 03 (POR FAZER)]()

João implementou dois procedimentos em seu programa, um para verificar se um número é divisível por 3, outro para multiplicar o valor recebido por 10. Ambos os procedimentos recebem um número inteiro com parâmetro e não retornam valores, apenas exibem o resultado na tela.

João deseja criar um vetor com ponteiros para esses procedimentos para, em seguida, passar o vetor como parâmetro para um procedimento especial. Este último procedimento acionará os procedimentos recebidos como parâmetro para um conjunto de números inteiros determinados localmente.

#### [Exercicio 04](https://github.com/DebbieMatt/Alg_II/blob/74a9def4a464562218ce6d26168ac7c18d6c84d7/UNID.%201%20-%20MEM%C3%93RIA/UNID.01_ATV_12.c)

Uma estudante de Algoritmos e Estrutura de Dados II deseja implementar com conjunto de funções/procedimentos para facilitar a criação de vetores alocados dinamicamente na memória, oferecendo recursos que possibilitem:

* a criação de um novo vetor;

* a inserção de valores no vetor, lidos do teclado;

* a impressão do vetor;

* a mudança da capacidade de armazenamento do vetor, para mais ou para menos;

* a liberação do espaço de memória ocupado pelo vetor;

### Typedef Struct, Union e Enumerador 

> Os tipos `enumerados` são classificados como um dos tipos básicos;

> O `struct` e `union` são tipos derivados, o que significa que você pode ter um `struct` ou `union`, e conter outros objetos;

> A `struct` é um tipo agregado (assim como um `array`), mas `union` é um tipo próprio. E `enum` como tipo escalar - não contém instâncias de outros objetos.


#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/9d4779da431f9945831471dc56cc3ce42ec98b64/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_01.c)

Crie um programa em C que utilize uma struct para armazenar informações sobre um produto em um sistema de inventário. 

A struct deve conter o nome do produto, preço e quantidade em estoque. 

O programa deve permitir ao usuário adicionar novos produtos ao sistema, atualizar a quantidade em estoque e o preço, listar todos os produtos com suas informações ou excluir um produto a partir do índice. 

Além disso, implemente uma função para calcular o valor total em estoque de um produto, multiplicando o preço pela quantidade disponível.

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/9d4779da431f9945831471dc56cc3ce42ec98b64/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_02.c)

Elabore um programa em C que utilize uma struct para gerenciar informações de veículos em um estacionamento. 

A struct deve conter detalhes como placa do veículo, marca, modelo, cor e número de horas estacionado. 

O programa deve permitir ao usuário registrar a entrada de veículos, calcular o custo do estacionamento com base nas horas estacionadas (defina uma tarifa por hora), e registrar a saída dos veículos. 

Além disso, inclua uma funcionalidade para listar todos os veículos atualmente presentes no estacionamento, exibindo suas informações.

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/a2a3745139ee4955b9b6ebbe5a83bfa0a6dd39cf/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_03.c)

Imagine que você foi contratado(a) para desenvolver um sistema que irá gerenciar informações de funcionários e departamentos de uma empresa, onde um funcionário está associado a um departamento específico. Quando o departamento é atualizado, a mudança deve refletir em todos os funcionários associados a ele.

Para o departamento, devem ser armazenados o nome e o código. Para o funcionário, deve-se armazenar nome, código e o departamento ao qual está vinculado. 

O usuário deve ter a possibilidade cadastrar, listar e atualizar tanto os departamentos quanto os dados dos funcionários.

#### [Exercicio 04](https://github.com/DebbieMatt/Alg_II/blob/f8cf03975c4472bcebb5563213f9adeda54399ed/UNID.%202%20-%20TIPOS%20ABSTRATOS%20DE%20DADOS/UNID.02_ATV_04.c)

Estudantes da Faculdade de Engenharia estão desenvolvendo um programa em C para um sistema de automação residencial que integra diferentes tipos de sensores: temperatura (float), luminosidade (float) e movimento (int ou bool), cada um medindo um aspecto específico do ambiente. Implemente uma estrutura de dados eficiente em termos de memória para armazenar as informações desses sensores.

O programa deve permitir o cadastro de novos sensores, dando ao usuário a opção de escolher o tipo de sensor e inserir os dados correspondentes. Além disso, o programa deve ser capaz de exibir informações de todos os sensores cadastrados, com descrições apropriadas, como "Temperatura: 23.5°C", "Luminosidade: 75.0%", ou "Movimento detectado: Sim/Não".


### Manipulação de Arquivos em C

> Funções / Procedimentos de leitura e escrita de aquivos de texto e binários.

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/12c720607987006863e6b682e26b65af966aa0fc/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_01.c)

Roberval, aquele um estudante de Controle e Automação que queria criar um sistema controle de luzes de uma casa, está de volta. Agora, ele pretende melhorar o sistema desenvolvido, colocando uma “memória”, que considera o estado da lâmpada após a execução anterior do programa. 
Por exemplo: se o programa anterior terminou com a lâmpada ligada, em uma nova execução, essa informação deve ser considerada.

`Para relembrar: Roberval criou procedimentos para ligar e desligar as luzes. Um terceiro procedimento, que simula um interruptor, recebia os endereços de memória dos procedimentos ligar e desligar. Se a lâmpada estava desligada, o procedimento a ligava quando acionado. Da mesma forma, se ela estivesse desligada, o procedimento desligava a luz. O procedimento interruptor acionava os anteriores usando ponteiros. [Clique aqui para visualizar o exercício anterior]().`

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/6b412798a3000ba8894a07b6892b81b0144046cf/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_02.c)

João está desenvolvendo um programa para trocar mensagens com seus amigos usando arquivos de texto. A intenção dele é fazer com que as outras pessoas não entendam o conteúdo dos arquivos, mesmo tendo acesso a eles. 
Para isso, ele resolveu fazer a seguinte brincadeira: ao iniciar o programa, o usuário deve selecionar uma das seguintes opções em um menu: escrever ou ler mensagem. Optando por escrever uma mensagem, o usuário deve informar uma frase de até 100 caracteres e um número inteiro Não entre 1 e 5. 
Lidas as opções, o programa deve armazenar a frase digitada em um arquivo, pulando n casas a cada caractere. Da mesma forma, quando a opção de leitura for selecionada, o programa deve solicitar: um inteiro negativo, entre 1 e 5, imprimindo a mensagem decodificada. 

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/8d341680576407f0b03f6fc2f68f6df699aee818/UNID.%203%20-%20MANIPULA%C3%87%C3%83O%20DE%20ARQUIVOS/UNID.03_ATV_03.c)

Elabore um programa em C para gerenciar o registro de veículos de uma concessionária. Use uma struct chamada Veiculo contendo variáveis para modelo, marca, ano de fabricação, cor e preço. Guarde vários registros de veículos em um vetor dessa struct. Implemente funções para salvar os registros em um arquivo e carregá-los quando o programa for iniciado. Desenvolva uma interface de usuário simples para adicionar novos veículos, exibir todos os registros e atualizar os dados salvos.

### Pilha, Fila e Lista

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/d4f73dd38d74ead50e76821cc1035421e1368847/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_v01.c)

Em um prédio de Cuiabá, há uma garagem estreita, porém comprida. Sua largura contém espaço suficiente para um único veículo, além da passagem para o motorista. Assim, os carros são estacionados um atrás do outro, sem exceção. Para remover um carro, é preciso que todos os demais sejam removidos também. Como o prédio não tem manobrista, em todas as manhãs o cenário é de correria e confusão. Para tentar agilizar o processo, o porteiro Ribamar implementou um sistema de informação que registra, para cada carro, a placa e o número do apartamento do proprietário. Quando um morador chega para retirar seu carro, ele informa a placa do seu veículo e o programa retorna: a quantidade de veículos a serem retirados primeiro, bem como o números dos apartamentos dos proprietários dos veículos envolvidos. Implemente esse programa em C, usando uma estrutura de dados adequada para essa finalidade.

Atenção: Considere a implementação ESTÁTICA da estrutura.

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/806a2ae29af77d145c83aef6f3234715554b8e22/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_02.c)

Uma estudante de "Algoritmos e Estruturas de Dados II", fascinada com o conteúdo da disciplina, está criando um módulo de playlists para um aplicativo de música como o Spotify. Uma playlist, evidentemente, pode conter diversas músicas. Como no Spotify, músicas mais recentes são as primeiras a serem exibidas na lista. Para facilitar a vida dos usuários, ela deseja implementar o seguinte recurso em seu programa: uma opção de desfazer e refazer a inserção de músicas na playlist, que funciona da seguinte forma:

* Se o usuário selecionar a opção desfazer, a última música inserida na playlist será removida;
* Se o usuário selecionar a opção refazer, a último música excluída voltará para a playlist;

Considere a implementação DINÂMICA da estrutura.

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/5aa9185a7790105b8db40095f04649caa0be24a1/UNID.4%20-%20PILHA%2C%20FILA%20E%20LISTA/UNID.04_ATV_03.c)

Você foi designado para desenvolver um sistema de atendimento para uma clínica médica. A clínica deseja organizar a fila de pacientes de forma eficiente, usando uma estrutura de dados adequada. Considere as seguintes informações:

- Cada paciente é representado por um número de registro único e possui informações como nome, idade e motivo da consulta.
- O sistema deve permitir a inserção de novos pacientes na fila de espera.
- Quando um médico está disponível, o próximo paciente na fila é chamado para a consulta.
- Durante a consulta, o médico registra o atendimento e libera o paciente, removendo-o da fila.
- O sistema também deve permitir a consulta do próximo paciente na fila sem removê-lo, caso o médico queira antecipar a chamada.
- O usuário deve ter a opção de encerrar o programa a qualquer momento.

Sua tarefa é implementar esse sistema de atendimento utilizando uma fila dinâmica em C. Considere a necessidade de criar funções para realizar as seguintes operações:

1. Inserir um novo paciente na fila.
2. Chamar o próximo paciente para a consulta.
3. Consultar as informações do próximo paciente sem removê-lo.
4. Encerrar o programa.

Lembre-se de gerenciar corretamente a alocação e liberação de memória. Além disso, crie um menu simples para que o usuário possa interagir com o sistema de atendimento. Considere a implementação estática, em que a fila armazena no máximo 10 pacientes. 

### Algoritmos de Ordenação

> Bubble SortURL, Insertion sortURL, Selection sortURL, Quick SortURL, Merge SortURL.

- **Pilha**: É uma estrutura de dados que segue o princípio LIFO (Last In, First Out), ou seja, o último elemento a ser inserido é o primeiro a ser removido. As operações principais são `push` (inserir um elemento no topo da pilha) e `pop` (remover o elemento do topo da pilha).

- **Fila**: É uma estrutura de dados que segue o princípio FIFO (First In, First Out), ou seja, o primeiro elemento a ser inserido é o primeiro a ser removido. As operações principais são `enqueue` (inserir um elemento no final da fila) e `dequeue` (remover o elemento do início da fila).

- **Lista**: É uma estrutura de dados que pode conter zero ou mais elementos, que estão ligados em uma sequência. As listas podem ser implementadas de várias maneiras, como listas ligadas, listas duplamente ligadas, listas circulares, etc. As operações principais são `inserir` (inserir um elemento em uma posição específica), `remover` (remover um elemento de uma posição específica) e `buscar` (encontrar um elemento na lista).

#### [Exercicio 01](https://github.com/DebbieMatt/Alg_II/blob/d67cfb45845688e287ed0a09ed284cc204799d49/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_01.c)

Os algoritmos de ordenação utilizam uma variável chave para ordenar um vetor. Em geral, para fins didáticos, trabalha-se com uma variável do tipo int como este atributo. Escolha, dentre os algoritmos de ordenação apresentados na aula anterior, um para adaptar. O algoritmo, após o seu ajuste, deve ser capaz de ordenar strings.

Entrada	            Saída
RONDONOPOLIS	AMORINOPOLIS
CUIABA	        CUIABA
AMORINOPOLIS	DIORAMA
DIORAMA	        RONDONOPOLIS

#### [Exercicio 02](https://github.com/DebbieMatt/Alg_II/blob/d67cfb45845688e287ed0a09ed284cc204799d49/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_02.c)

Considere um programa de cadastro (de produtos, clientes, veículos, etc) que contém, no mínimo, 10 registros alocados de forma estática na memória. Cada registro deve conter, no mínimo, três variáveis. O programa deve exibir um menu de opções ao usuário, com as seguintes funcionalidades:

* Cadastrar um novo item;
* Listar por nome em ordem crescente;
* Listar por valor ou quantidade em ordem crescente;
* Listar por valor ou quantidade em ordem decrescente;
* Excluir um item.

#### [Exercicio 03](https://github.com/DebbieMatt/Alg_II/blob/3669c8926270cbc26ff73da9d8dd3189d681c671/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_03.c)

Implemente um algoritmo recursivo que desempilha todos os itens de uma pilha (com, no mínimo, 10 itens) e retorna a soma da chave dos registros. O programa deve imprimir o valor retornado. 

#### [Exercicio 04](https://github.com/DebbieMatt/Alg_II/blob/3669c8926270cbc26ff73da9d8dd3189d681c671/UNID.5-ALGORITMO%20DE%20ORDENA%C3%87%C3%83O/UNID.05_ATV_04.c)

Adapte o algoritmo Quick Sort para que a ordenação seja feita em ordem decrescente, não em ordem crescente.

## 📫 Contribuindo para a manutenção

Para contribuir com projeto final e nos auxiliar a continuar desenvolvendo melhor, aprimorando e torna-lo mais eficientes, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
 
## 📝 Licença
 
Este projeto está sob licença. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
 
<div align="center">
  Feito com 💙 e muito <code>malloc</code>
</div>

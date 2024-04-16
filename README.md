# Sistema de Controle de Atendimento

Este sistema implementa uma fila circular em JavaScript, utilizando a classe `FilaCircular`, e um sistema básico de controle de atendimento com a classe `Atendimento`.

## Funcionalidades da Fila Circular

- `constructor(tamanho)`: Inicializa a fila circular com um tamanho específico.
- `isFull()`: Verifica se a fila está cheia.
- `enqueue(elemento)`: Adiciona um elemento à fila.
- `dequeue()`: Remove e retorna o primeiro elemento da fila.
- `isEmpty()`: Verifica se a fila está vazia.
- `first()`: Retorna o primeiro elemento da fila.
- `last()`: Retorna o último elemento da fila.
- `toString()`: Retorna uma representação em string da fila.

## Funcionalidades do Controle de Atendimento

A classe `Atendimento` representa um atendimento na fila, e possui os seguintes atributos e métodos:

- Atributos: `nome`, `cpf`, `data` e `hora`.
- Métodos: `equals(outroAtendimento)`, `toString()`.

## Funcionalidades Adicionais

Além das classes principais, o sistema possui as seguintes funcionalidades adicionais:

- Adicionar elemento à fila.
- Remover elemento da fila.
- Buscar por CPF na fila.
- Atualizar a exibição da fila.
- Limpar os campos de entrada.
- Obter a data atual.
- Obter a hora atual.
- Calcular a diferença de horas.

## Como usar

O sistema é composto por um arquivo HTML (`index.html`), um arquivo CSS (`style.css`), um arquivo JavaScript para a classe `FilaCircular` (`FilaCircular.js`), um arquivo JavaScript para a classe `Atendimento` (`Atendimento.js`), e um arquivo JavaScript principal (`index.js`).

Para utilizar o sistema, basta abrir o arquivo `index.html` em um navegador web compatível com JavaScript.

## Autor

- Maycon Luis Franco Carpes.
- Caua Fortes Vieria.

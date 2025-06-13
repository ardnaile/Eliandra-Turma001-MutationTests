# Mutation Tests
O projeto consiste na aplicação de Mutation Tests com a ferramenta [Stryker](https://stryker-mutator.io/), com base no código de [Unit Tests](https://github.com/ardnaile/Eliandra-Turma001-UnitTest) desenvolvido na primeira avaliação. 

## Começando

Para executar este projeto siga os passos abaixo:

1. Instalar o [Node JS](https://nodejs.org/) (versão >= 20.x)

2. Instalar todas as dependências do projeto:
```
npm install
```

3. Comando para executar todos os testes:
```
npm run test
```

 4. Comando para executar todos os testes com coverage:
```
npm run coverage
```

5. Comando para executar os mutation tests:
```
npx stryker run
```

Todos os artefatos de execução podem ser encontrados em ./coverage. Se você quiser remover esses arquivos, execute `npm run clean`.

## Estrutura do projeto
* src: source code</li>
* test: unit test files

[![Code coverage badge](https://img.shields.io/badge/coverage-100%25-brightgreen)](https://stryker-mutator.io/robo-coasters-example/reports/coverage/lcov-report/index.html)
[![Mutation testing badge](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fbadge-api.stryker-mutator.io%2Fgithub.com%2Fstryker-mutator%2Frobo-coasters-example%2Fmaster)](https://dashboard.stryker-mutator.io/reports/github.com/stryker-mutator/robo-coasters-example/master)

# PGATS - Projeto Base - CI

## Pré-requisitos

1. Instale o [git](https://git-scm.com)

2. Instale o [nodejs](https://nodejs.org/)

3. Instale o Yarn -
   `npm install -g yarn`

```sh {"id":"01J9EGBBE2MVKHJG2R5YQDYV18"}
npm install -g yarn
```

4. Faça um _Fork_ do projeto

5. Clone o repositório para sua máquina (seu fork)

6. Instale as dependências

```sh {"id":"01J9EFXBHFTSTDK4ET11PQCZJQ"}
cd pgats-ci-projeto-base
```

```sh {"id":"01J9EG9T1DK4JZKRQBPMX5AYTH"}
yarn
```

7. Execute os testes de unidade - isso vai gerar um relatório

```sh {"id":"01J9EFXBHFTSTDK4ET155840J8"}
yarn run test
```

8. Abra o relatório de cobertura de código em `reports/coverage/lcov-report`

9. Execute os testes de mutação com o Stryker

```sh {"id":"01J9EFXBHFTSTDK4ET15E8MR6Z"}
yarn run test:mutation
```

10. Abra o relatório de mutação em `reports/mutation`

11. Execute os testes end-to-end com o Playwright

```sh {"id":"01J9EGP5MM4SVZFV866QB8605K"}
 yarn playwright install
```

```sh {"id":"01J9EFXBHFTSTDK4ET18EBEM3Z"}
yarn run e2e
```

```sh {"id":"01J9EGWHWBD4V8HDS6VCMHFQ5Q"}
 yarn playwright show-report
```

```sh {"id":"01J9EHC6K61G0EMA9AY98P6G4B"}

```

12. Execute a aplicação com `yarn start`

```sh {"id":"01J9EGCN9MK1WTMJ56JV8EQKHR"}
yarn start
```

13. Acesse a aplicação publicada [neste link](https://pgats-ci-example.netlify.app)

---

💜⚡️

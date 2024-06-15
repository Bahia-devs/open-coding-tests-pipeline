![Branches](./badges/coverage-branches.svg)
![Functions](./badges/coverage-functions.svg)
![Lines](./badges/coverage-lines.svg)
![Statements](./badges/coverage-statements.svg)
![Jest coverage](./badges/coverage-jest%20coverage.svg)

# Open-Coding Tests Pipeline com GitHub Actions

Neste open-coding nós exploramos o básico sobre criação de Pipeline com GitHub Actions. Este repositório é um fork do [open-coding de testes com jest](https://github.com/Bahia-devs/open-coding-tests-with-jest).

Em `.github/workflows` você pode encontrar vários exemplos de diferentes workflows que podem ser utilizados em seus projetos, basta modificá-los para as configurações específicas de seu projeto.

## Configurações

- Para que o workflow de Coverage Badges funcione, certifique de que seu repositório aceita criação de branches pelo workflow, vá em `Settings->Actions->General` encontre `Workflow permissions` e ative o `Read and write permissions`.

## Links

- [Docs do GitHub Workflows](https://docs.github.com/en/actions/using-workflows/about-workflows)
- [GitHub Actions jest-badges-generation](https://github.com/marketplace/actions/jest-badges-generation-action)
# Contribuindo com o projeto

Obrigado por contribuir com o projeto Pizzaria API.

Este documento define os padrões utilizados no desenvolvimento.

---

# Fluxo de branches

O projeto utiliza o seguinte fluxo:

main
→ código estável

develop
→ integração das funcionalidades

feature/*
→ desenvolvimento de novas funcionalidades


## Padrão de nomes

Novas funcionalidades:

feature/nome-da-funcionalidade

Exemplo:

feature/cadastrar-sabor


Correções:

fix/nome-da-correcao

Exemplo:

fix/calculo-total


Refatorações:

refactor/nome-da-refatoracao

---

# Commits

Utilizamos Conventional Commits.

Formato:

tipo: descrição


## Tipos utilizados

feat:
Nova funcionalidade.

Exemplo:

feat: add flavor registration


fix:
Correção de problema.

Exemplo:

fix: prevent duplicated flavors


test:
Criação ou alteração de testes.

Exemplo:

test: add flavor validation tests


docs:
Alterações de documentação.

Exemplo:

docs: update readme


refactor:
Melhoria estrutural sem alterar comportamento.

Exemplo:

refactor: improve flavor entity


chore:
Configurações e manutenção.

Exemplo:

chore: configure project structure

---

# Pull Requests

Todo código deve seguir o fluxo:

feature/*
        ↓
     develop
        ↓
       main


Antes de abrir um Pull Request:

- Verificar se o projeto compila;
- Executar testes;
- Revisar alterações;
- Garantir que não existem arquivos desnecessários.
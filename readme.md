## Congfig

Instalamos Husky:

```shell
npx husky-init && npm install
```

Añadimos Hooks:

- commit-msg: necesita un commit con 10 y 42 caracteres.
- pre-push: Branch name: feature/_ - hotfix/_ - bugfix/\*

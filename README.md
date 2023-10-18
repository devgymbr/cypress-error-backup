# cypress-error-backup

GitHub action that uploads cypress error screenshots to another github repository and make them available as an artifact for debugging purposes. 

```yaml
uses: devgymbr/cypress-error-backup@v1.0.0
with:
  gh-repo: account/repo
  gh-token: token_with_permissions_to_commit_and_push
```

On the pipeline summary you can see the link to screenshots: 

![](./example.png)

## Próximo Passo

Que tal estudar com desafios técnicos com solução em vídeo? Acesse [devgym.com.br](https://app.devgym.com.br?utm_campaign=cypresserrrepo&utm_medium=social&utm_source=github). 

[![](https://raw.githubusercontent.com/devgymbr/files/main/devgymblack.png)](https://app.devgym.com.br?utm_campaign=cypresserrrepo&utm_medium=social&utm_source=github)

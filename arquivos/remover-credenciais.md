Removendo credenciais
---
Se usar o prompt de comando, o Windows salvará sua senha automaticamente. Para apagar, vá até:

> Acessar `Painel de Controle > Contas de Usuário > Gerenciador de Credenciais`

> Clicar em `Credenciais do Windows` e na lista de Credenciais Genéricas, clicar em `git:https://github.com` e depois em `Remover`

Se usar o WSL Terminal:

> Para salvar a senha por 1 hora, usar o comando: 
`git config credential.helper "cache --timeout 3600"`

> Para remover: 
`git credential-cache exit && rm -rf ~/.git-credential-cache`

> Para remover todas as configurações globais:
`git config --global --unset-all`
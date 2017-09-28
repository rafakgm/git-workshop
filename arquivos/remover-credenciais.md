Removendo credenciais
---
Se usar o prompt de comando, o Windows salvará sua senha automaticamente. Para apagar, vá até:

> Acessar `Painel de Controle > Contas de Usuário e Segurança Familiar > Contas de Usuário`

> No menu à esquerda, clicar em `Gerenciar suas credenciais`

> Na lista de Credenciais Genéricas, clicar em `git:https://github.com` e depois em `Remover do Cofre`

Em seguida, remova as configurações globais do git:

> `git config --global --remove-section user`

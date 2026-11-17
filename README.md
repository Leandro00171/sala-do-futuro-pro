# Sala do Futuro PRO

Versão inicial de um painel independente para organizar atividades escolares e preparar pedidos de ajuda ao ChatGPT.

## Como usar
1. Abra `index.html` no navegador ou publique o repositório com GitHub Pages.
2. Cadastre manualmente as atividades e prazos que aparecem na Sala do Futuro oficial.
3. Use o painel para filtrar tarefas e marcar atividades concluídas.
4. No Assistente IA, cole uma questão, prepare o pedido e abra o ChatGPT para receber uma explicação.

## Publicar pelo GitHub Pages
1. Entre no seu repositório GitHub.
2. Envie `index.html` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois salve.
6. Aguarde a publicação e abra o endereço que o GitHub Pages mostrar.

## Limitações importantes
- Este projeto não é oficial da Secretaria da Educação de São Paulo.
- Não pede nem armazena RA, RG, CPF ou senha da SED.
- Não acessa automaticamente tarefas, notas ou dados da SED. O estudante cadastra manualmente as atividades.
- O assistente nesta versão prepara um prompt e abre o ChatGPT; ainda não existe uma API de IA integrada ao site.
- As tarefas ficam salvas no `localStorage` do navegador/dispositivo. Limpar os dados do navegador pode apagá-las.
- A integração direta com a SED só deve ser feita com documentação e autorização oficial, sem contornar autenticação ou controles de acesso.

Portal oficial do estudante: https://saladofuturo.educacao.sp.gov.br/login-alunos

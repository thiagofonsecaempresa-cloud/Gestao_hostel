# Gestão do Hostel · Thiago Fonseca

Aplicativo web estático em HTML, CSS e JavaScript, preparado para publicação no GitHub Pages.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `gestao-hostel`.
2. Envie os arquivos desta pasta para a raiz do repositório: `index.html`, `manifest.json`, `icon.svg` e `README.md`.
3. No repositório, acesse **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
6. Aguarde o GitHub Pages publicar e abra a URL exibida nessa tela.

## Recursos

- Custos fixos e variáveis, com despesas sugeridas e personalizadas.
- Estimativa de custo mensal, custo por quarto disponível e custo por quarto ocupado.
- Salvamento local no navegador.
- Backup/importação JSON e exportação CSV.
- Layout responsivo para celular.

## Observação sobre os dados

O aplicativo não possui servidor nem banco de dados remoto. Os dados ficam no armazenamento local do navegador e não são sincronizados automaticamente entre dispositivos. Use o backup JSON para transferir os dados.


Versão 2.0: identidade visual azul e despesas personalizadas guardadas também na lista de opções, neste navegador e nos backups JSON.


Versão 2.1: categorias fixas e variáveis organizadas conforme a lista do hostel, com migração dos nomes equivalentes para evitar duplicatas.

# Portfólio · Marcos Vinícius Pessoa

Meu portfólio de desenvolvedor Full Stack em formação. É um site estático feito só com HTML e CSS, em um único arquivo (`index.html`), sem dependências e sem etapa de build.

## O que tem na página

- Apresentação e resumo
- Projetos: VaiDeBike, FocusFlow, gerador de senhas e carta de namoro
- Habilidades
- Trajetória de trabalho e estudos
- Contato
- Tema claro e escuro automático, de acordo com o aparelho
- Layout adaptado para celular

## Como ver no computador

Baixe o repositório e abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub. Para o endereço ficar `https://archvini.github.io`, chame o repositório de `archvini.github.io`. Com outro nome, o endereço fica `https://archvini.github.io/nome-do-repositorio`.
2. Envie os arquivos para a branch `main`:

   ```bash
   git init
   git add .
   git commit -m "Primeira versão do portfólio"
   git branch -M main
   git remote add origin https://github.com/archvini/NOME-DO-REPOSITORIO.git
   git push -u origin main
   ```

3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
5. Depois de alguns minutos o site fica no ar no endereço que o GitHub mostrar nessa mesma tela.

## Como editar

Tudo está em `index.html`:

- **Cores:** estão no começo do bloco `<style>`, nas variáveis `--accent` (roxo), `--pink` (rosa) e `--grad` (degradê). Há um conjunto para o tema claro e outro para o escuro.
- **Textos e projetos:** estão no corpo da página, separados por seção (`#sobre`, `#projetos`, `#habilidades`, `#trajetoria`, `#contato`).
- **Novo projeto:** copie um bloco `<article class="mini">` dentro de `<div class="minis">` e troque o título, a descrição e os links.

## Tecnologias

HTML5, CSS3 e fontes do Google Fonts (Familjen Grotesk, Public Sans e IBM Plex Mono).

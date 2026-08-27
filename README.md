# projeto-github

Projeto desenvolvido durante o Workshop de GitHub na COTI Informática.

Este repositório contém um projeto simples de front-end criado com HTML, CSS e JavaScript como parte das atividades do workshop. O objetivo foi aprender a usar Git/GitHub e praticar a construção de páginas web estáticas.

## Tecnologias usadas

- HTML: estrutura das páginas.
- CSS: estilização e layout responsivo básico.
- JavaScript: interatividade e manipulação do DOM.

Todos os arquivos do projeto estão na raiz do repositório (ou em pastas como `css/`, `js/`, `assets/` conforme a organização adotada).

## Como abrir e rodar o projeto no Visual Studio Code (VS Code)

Siga os passos abaixo para abrir e executar o projeto localmente usando o VS Code:

1. Pré-requisitos
   - Git instalado na sua máquina (https://git-scm.com/).
   - Visual Studio Code instalado (https://code.visualstudio.com/).
   - Recomenda-se instalar a extensão "Live Server" no VS Code para facilitar o desenvolvimento (extensão: Ritwick Dey).

2. Clonar o repositório

```bash
# clone o repositório para sua máquina
git clone https://github.com/marocomichael/projeto-github.git

# entre na pasta do projeto
cd projeto-github
```

3. Abrir o projeto no VS Code

- Abra o VS Code e escolha "File > Open Folder..." (ou "Arquivo > Abrir Pasta...") e selecione a pasta `projeto-github` que você clonou.
- Alternativamente, no terminal você pode executar:

```bash
code .
```

4. Rodar o projeto

Opção A — Usando a extensão Live Server (recomendado):

- Instale a extensão Live Server no VS Code (se ainda não tiver).
- Abra o arquivo `index.html` no editor, clique com o botão direito e escolha "Open with Live Server".
- O Live Server abrirá automaticamente o projeto no navegador e fará reload automático quando você salvar mudanças.

Opção B — Abrir o arquivo diretamente no navegador:

- Abra `index.html` na pasta do projeto usando o navegador (arrastar o arquivo para o navegador ou usar "Abrir com").
- Observação: algumas funcionalidades que usam requisições AJAX/Fetch podem exigir um servidor local, então preferir a opção Live Server.

Opção C — Usar um servidor HTTP simples (sem VS Code):

- Com Python 3 instalado, execute no terminal dentro da pasta do projeto:

```bash
# para Python 3.x
python -m http.server 8000
```

- Abra http://localhost:8000 no navegador.

## Estrutura sugerida de pastas

- index.html
- css/
  - styles.css
- js/
  - script.js
- assets/
  - imagens, fontes, etc.

(Adapte conforme a estrutura real do seu projeto.)

## Contribuições

Contribuições e melhorias são bem-vindas. Para contribuir, crie um fork, abra uma branch com sua alteração e envie um pull request.

## Licença

Coloque aqui a licença do projeto (por exemplo, MIT) ou remova esta seção se não for aplicável.

---

Se quiser, eu posso também adicionar um badge de status, instruções para execução de testes (se houver) ou adaptar o README para a estrutura exata do repositório — me diga o que prefere.
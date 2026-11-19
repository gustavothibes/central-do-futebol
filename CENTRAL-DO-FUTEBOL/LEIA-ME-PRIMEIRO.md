# CENTRAL DO FUTEBOL — Projeto final Front-End para Web

**Integrantes:** Gustavo Thibes da Silveira e João Henrique Kasburg Tom  
**Disciplina:** Desenvolvimento Front-End para Web — DFEW.08  
**Instituição:** Universidade Positivo  

## O que está incluído
- 10 páginas HTML conectadas por uma navegação comum.
- CSS responsivo, Grid Layout, Flexbox, seletores por tag/classe/ID, estados `:hover`, `:focus` e `:invalid`.
- Bootstrap 5.3.6 local nas páginas que demonstram componentes e utilitários do framework.
- Duas páginas sem Bootstrap: `classificacao.html` e `jogadores.html`, usando HTML, CSS e JavaScript puros.
- JavaScript com filtros, busca, ordenação, menu responsivo, favoritos e formulários.
- `localStorage` para guardar favoritos, mensagens e inscrições neste navegador.
- Vídeo e áudio locais com controles HTML5 nativos.
- Documentação acadêmica editável em Word, guia passo a passo do VS Code e roteiro de defesa na pasta `doc`.

## COMO ABRIR NO VS CODE (passo a passo)
1. Baixe `Central_do_Futebol_Projeto.zip` e salve em uma pasta fácil de encontrar, como a Área de Trabalho.
2. Clique com o botão direito no ZIP e escolha **Extrair Tudo...**. Não abra o `index.html` ainda dentro do ZIP.
3. Abra o Visual Studio Code.
4. Clique em **Arquivo > Abrir Pasta...** e selecione a pasta extraída `CENTRAL-DO-FUTEBOL`.
5. Na coluna esquerda do VS Code, confirme que aparecem `index.html`, `noticias.html`, `css`, `js`, `img`, `video`, `audio` e `doc`.
6. Abra `index.html` com duplo clique no VS Code.
7. Para testar, clique com o botão direito em `index.html` e escolha **Open with Live Server** (caso a extensão Live Server esteja instalada). Se não tiver, abra a pasta no Explorador de Arquivos e dê duplo clique em `index.html`.
8. Use o menu do site para abrir as outras nove páginas. O projeto também funciona sem internet: Bootstrap, imagens, vídeo e áudio usados pelo site estão dentro da pasta.
9. Teste a busca em Notícias e Jogadores, os filtros, os botões de favoritos, a ordenação da Classificação, o formulário Contato e a inscrição da página inicial.
10. Para conferir o `localStorage`, abra o site no Chrome, pressione `F12`, entre em **Application > Local Storage** e selecione o endereço local. Procure `cf_favorites`, `cf_messages` e `cf_subscribers`.

## IMPORTANTE SOBRE OS DADOS
As transferências hipotéticas (como Messi no Barcelona e De Bruyne no Atlético de Madrid), boletins de lesões, placares, agenda e estatísticas são **conteúdos fictícios/demonstrativos**, identificados no site. Não os apresentem como notícias verdadeiras. O portal não consulta API nem atualiza resultados em tempo real.

## COMO EDITAR CONTEÚDO
- Notícias, partidas, agenda, transferências e jogadores estão no arquivo `js/script.js`, nas listas `newsItems`, `transferItems`, `matches`, `schedules` e `players`.
- Estilos e cores estão em `css/style.css`.
- Cada página é um arquivo HTML na raiz.
- Imagens SVG estão em `img`; o vídeo fica em `video`; o áudio fica em `audio`.
- Documentação completa: `doc/Documentacao_Central_do_Futebol.docx`.
- Guia de instalação, execução e testes: `doc/Guia_Passo_a_Passo_VS_Code.docx`.
- Roteiro de apresentação e perguntas para a defesa: `doc/Roteiro_de_Defesa.docx`.

## ANTES DE ENTREGAR
- Os dois integrantes devem abrir o site e testar todos os links e formulários.
- Personalizem a divisão de tarefas na documentação para refletir o trabalho realmente realizado por cada integrante.
- Leiam o roteiro de defesa e pratiquem explicar o JavaScript, o localStorage, o CSS responsivo, a tabela e os formulários.
- Fechem o navegador, abram novamente o `index.html` e confirmem que a navegação local continua funcionando.
- Compactem a pasta inteira `CENTRAL-DO-FUTEBOL` em ZIP, preservando todas as subpastas.

## Estrutura da pasta
```text
CENTRAL-DO-FUTEBOL/
├── index.html
├── noticias.html
├── transferencias.html
├── jogos.html
├── campeonatos.html
├── classificacao.html
├── jogadores.html
├── lesoes.html
├── videos.html
├── contato.html
├── css/  (Bootstrap local e CSS do projeto)
├── js/   (JavaScript)
├── img/  (imagens locais SVG e poster)
├── video/ (vinheta MP4)
├── audio/ (vinheta WAV)
└── doc/  (documentação Word, guia passo a passo e roteiro de defesa)
```

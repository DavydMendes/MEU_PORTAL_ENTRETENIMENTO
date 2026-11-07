🎬 Meu Portal de Entretenimento Digital — Agenda 13

Projeto desenvolvido para a disciplina de Desenho de Sistemas I (Agenda 13 — CSS), focado na construção de um portal web responsivo utilizando HTML5, CSS3 (Reset, Inline, Interno, Externo) e layout flexível com Flexbox.

🎯 Objetivo da Atividade

Desenvolver uma página web temática dividida em três seções principais:

🍿 Filmes e Séries

🎵 Música e Podcasts

🎮 Games e Tecnologia

A atividade exercita a aplicação prática dos conceitos de estilização CSS, boas práticas de estruturação semântica em HTML e o uso da Inteligência Artificial como mentora técnica durante o desenvolvimento.

🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica (<header>, <main>, <section>, <footer>).

CSS3:

Reset CSS: Baseado no modelo de Eric Meyer para padronização em diferentes navegadores.

CSS Inline: Aplicado diretamente em atributos de elementos para estilizações pontuais.

CSS Interno: Localizado na tag <style> dentro do <head>.

CSS Externo: Arquivo estilo.css estruturado com classes, IDs e comentários.

Flexbox: Organização do layout em 3 colunas ajustáveis e responsivas.

📂 Estrutura de Arquivos

MEU_PORTAL_ENTRETENIMENTO/
│
├── reset.css     # Folha de estilo de reset (Eric Meyer)
├── estilo.css    # Folha de estilo principal (CSS Externo + Flexbox)
├── portal.html   # Estrutura principal da página HTML
└── README.md     # Documentação do projeto


🚀 Como Executar o Projeto

Faça o download ou clone este repositório:

git clone https://github.com/seu-usuario/meu-portal-entretenimento.git


Certifique-se de que todos os arquivos (portal.html, estilo.css e reset.css) estão na mesma pasta.

Abra o arquivo portal.html em qualquer navegador web (Google Chrome, Firefox, Edge, Safari).

📋 Requisitos Atendidos

[x] Três seções temáticas: Filmes e Séries, Música e Podcasts, Games e Tecnologia.

[x] Conteúdo por seção: Título (<h2>), 2 imagens ilustrativas (<img>) e parágrafos explicativos (<p>).

[x] 3 tipos de CSS: Inline, Interno (<style>) e Externo (estilo.css).

[x] Seletores CSS: Uso coerente de Classes (.secao-card, .titulo-secao) e IDs (#cabecalho-principal).

[x] Layout Flexbox: Três colunas dispostas lado a lado e ajustáveis (display: flex).

[x] Comentários no código: Explicações das regras de estilo no arquivo CSS.

[x] CSS Reset: Arquivo reset.css vinculado antes da folha de estilo principal.

🤖 Registro de Interações com a IA (Mentoria Técnica)

Etapa 1 – Estrutura HTML

Pergunta: "IA, revise minha estrutura HTML. Estou usando corretamente as tags <div>, <h1> e <img>?"

Resultado: A IA recomendou a substituição de divs genéricas por tags semânticas (<header>, <main>, <section>), garantindo acessibilidade e melhor SEO.

Etapa 2 – CSS Interno e Externo

Pergunta: "IA, como posso definir estilos diferentes para cada seção usando classes e IDs?"

Resultado: Definido o ID #cabecalho-principal para o topo da página e a classe reutilizável .secao-card para padronizar os três blocos de conteúdo no CSS externo.

Etapa 3 – Flexbox

Pergunta: "IA, me ajude a configurar o layout flexível com três colunas ajustáveis."

Resultado: Aplicado display: flex no conteiner pai (main) e flex: 1 nas seções filhas, com gap: 20px e flex-wrap: wrap para responsividade em telas menores.

📝 Autor & Disciplina

Componente Curricular: Desenho de Sistemas I — Agenda 13

Arquivo para Entrega: seuNome_Ag13_DS_I
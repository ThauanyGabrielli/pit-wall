# 🏎️ PIT WALL · GP de São Paulo

Landing page temática de automobilismo inspirada no Grande Prêmio de São Paulo de Fórmula 1 (Autódromo de Interlagos — Temporada 2026). Desenvolvida como projeto de estudo de **HTML5** e **CSS3**, com foco em tipografia esportiva, identidade visual de equipes e layout responsivo.

## ✨ Funcionalidades e Seções

* **Navegação Fixa (`topbar`):** Menu de acesso rápido às seções da página (`Pilotos`, `Classificação`, `Ingressos`) e botão de chamada para ação (*CTA*).
* **Hero Banner & Dados da Pista:** Apresentação do evento com métricas técnicas do circuito de Interlagos (71 voltas, 4.309 km por volta e 15 curvas) e acabamento gráfico estilo zebra (*kerb*).
* **01 · Grid de Pilotos:** Cards estilizados com as cores oficiais das equipes (`Ferrari`, `McLaren`, `Mercedes` e `Audi`), destacando números dos carros e pilotos (incluindo o brasileiro Gabriel Bortoleto).
* **02 · Classificação:** Tabela completa de pontuação do campeonato com destaque para o líder, indicadores visuais de equipe e interface de filtros por nome e escuderia.
* **03 · Reserva de Ingressos:** Informações de setores e valores (*Arquibancada A*, *Setor da Reta* e *Box VIP*), alerta de disponibilidade e formulário completo com campos para dados pessoais, data, quantidade, upload de foto para o telão e recado aos pilotos.

## 🎨 Identidade Visual e CSS

O arquivo `styles.css` utiliza variáveis CSS (`:root`) e recursos modernos de layout:

* **Paleta Dark Mode:** Fundo em preto profundo (`#0b0b0f`) e painéis em cinza grafite (`#16161d`), contrastando com o vermelho racing (`#e10600`) e cores temáticas por equipe (`--ferrari`, `--mclaren`, `--mercedes`, `--audi`).
* **Tipografia:** Fonte **Titillium Web** (Google Fonts) com pesos variados e itálico em títulos para transmitir velocidade e dinamismo.
* **Layout & Responsividade:** Uso combinado de **CSS Grid** e **Flexbox**, com *media queries* (`@media (max-width: 768px)`) adaptando o grid de pilotos, formulários e tabelas com rolagem horizontal para dispositivos móveis.

## 📁 Estrutura de Arquivos

```text
pit-wall/
├── index.html      # Estrutura semântica e conteúdo da landing page
├── styles.css      # Estilização, variáveis de cores, animações e responsividade
└── img/
    └── piloto.jpg  # Imagem de destaque utilizada no plano de fundo do Hero
```

## 🚀 Como Visualizar

1. Baixe ou clone os arquivos do projeto mantendo a estrutura de pastas (`index.html`, `styles.css` e a pasta `img/`).
2. Abra o arquivo `index.html` diretamente no navegador de sua preferência (Chrome, Firefox, Edge, Safari) ou utilize a extensão **Live Server** no VS Code.

## 👩‍💻 Autoria

Projeto desenvolvido para fins de estudo em HTML e CSS por **Thauany Gabrielli**.

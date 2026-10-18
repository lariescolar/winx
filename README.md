# Olimpíadas da Advocacia — Site institucional

Projeto de encerramento do **Módulo 3** da disciplina de **Design Web** (IFRN).
Site institucional completo do evento esportivo *Olimpíadas da Advocacia*, com seis páginas conectadas, construído em grupo a partir de um layout de referência no Figma.

## Páginas

| Página | Arquivo | Descrição |
|---|---|---|
| Home | `index.html` | Apresenta a olimpíada e direciona para as demais páginas |
| Notícias (lista) | `noticias.html` | Lista de todas as notícias publicadas, em cards |
| Notícia (post) | `noticia.html` | Leitura completa de uma notícia |
| Modalidades (lista) | `modalidades.html` | Catálogo das modalidades por ordem alfabética, com busca e filtro (coletiva/individual) |
| Modalidade (detalhe) | `modalidade.html` | Formato de disputa, regras, local e programação de uma modalidade |
| Cronograma do evento | `cronograma.html` | Calendário semanal dos jogos e cronograma por modalidade (acordeão) |

## Tecnologias

- **HTML5**
- **[DaisyUI](https://daisyui.com/) 4** — componentes da estrutura (`navbar`, `menu`, `footer`, `input`, `select`, `breadcrumbs`, `btn`)
- **[Tailwind CSS](https://tailwindcss.com/)** (via CDN) — identidade visual e ajustes finos
- **JavaScript** puro — busca e filtro de modalidades, calendário semanal e acordeão do cronograma
- **Google Fonts** — Poppins (títulos) e Open Sans (textos)

Não há arquivos CSS próprios: toda a estilização vem de classes do DaisyUI e do Tailwind.

## Identidade visual

| Item | Valor |
|---|---|
| Cor principal | `#009fe3` (azul) |
| Cor do texto | `#383838` |
| Títulos | Poppins (negrito) |
| Textos e menu | Open Sans |

## Estrutura de pastas

```
/
├── index.html
├── noticias.html
├── noticia.html
├── modalidades.html
├── modalidade.html
├── cronograma.html
├── README.md
└── assets/
    └── img/
```

## Como executar

Não é necessário instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone <link-do-repositorio>
cd <pasta-do-projeto>
```

Para um servidor local (opcional), use a extensão **Live Server** do VS Code.
É preciso ter conexão com a internet, pois DaisyUI, Tailwind e as fontes são carregados por CDN.

## Organização do trabalho

- Uma **issue** por página, cada uma com um responsável e uma branch própria (`feat/...`)
- Alterações entram na `dev` por merge, e a `main` recebe apenas a versão final
- Commits no padrão `feat`, `fix`, `chore` e `docs`, referenciando a issue (`refs #N`)
- Layout de referência: arquivo do Figma fornecido pelo professor

## Equipe

| Integrante | Responsabilidade |
|---|---|
| _Larissa Beatriz_ | _Layout base (header, footer e paleta)_ |
| _Larissa Beatriz_ | _Home_ |
| _Anne Julie_ | _Notícias (lista)_ |
| _Esther Carvalho_ | _Notícia (post)_ |
| _Kauany Costa_ | _Modalidades (lista)_ |
| _Camyla Ruth_ | _Modalidade (detalhe)_ |
| _Vitória Vale_ | _Cronograma_ |

## Créditos

Disciplina de Design Web — IFRN, Módulo 3.

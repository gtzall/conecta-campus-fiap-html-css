# Conecta Campus FIAP

**Checkpoint 2 · Turma 1TDSPB · 2026**

- Repositório: [gtzall/conecta-campus-fiap-html-css](https://github.com/gtzall/conecta-campus-fiap-html-css)
- Unidade: **FIAP Paulista — Av. Paulista, 1106, São Paulo/SP**
- O site não está publicado. Para visualizar, abra `index.html` no navegador.

## Sobre o projeto

O Conecta Campus é um guia estudantil da unidade FIAP Paulista, com informações sobre espaços, acessibilidade e integrantes. O site é estático e feito somente com **HTML e CSS**: não usa Python, JavaScript, frameworks, backend ou banco de dados.

A página inicial usa a imagem panorâmica composta enviada pelo grupo como fundo: ambiente de estudo à esquerda e edifício envidraçado à direita. A navegação se integra à faixa superior; título, texto e CTA ficam à esquerda, com sobreposição graduada para preservar a legibilidade, sem androide. O androide enviado pelo grupo aparece somente em `detalhes.html`, em grandes dimensões à direita da introdução, sem cartão e sem chatbot. A imagem “A FIAP está onde você está” permanece no topo de Locais, como banner de largura total sob a navegação.

## Páginas

- `index.html` — apresentação e destaques do campus.
- `locais.html` — diretório com categoria, localização, informação útil, imagem e link.
- `detalhes.html` — informações sobre os espaços, acessibilidade e fontes, com atalhos internos.
- `integrantes.html` — fotos, RMs, turma, áreas informadas e perfis sociais.

## Capturas

| Início | Locais |
| --- | --- |
| ![Página inicial do Conecta Campus](docs/prints/inicio.png) | ![Lista de locais da FIAP Paulista](docs/prints/locais.png) |

| Detalhes | Integrantes |
| --- | --- |
| ![Detalhes dos espaços](docs/prints/detalhes.png) | ![Página dos integrantes](docs/prints/integrantes.png) |

## Estrutura

```text
conecta-campus-fiap-html-css/
├── index.html
├── locais.html
├── detalhes.html
├── integrantes.html
├── cp2.txt
├── README.md
├── css/
│   └── style.css
├── img/                 # Imagens e fotos locais do site
├── fonts/               # Roboto e licença
└── docs/
    ├── equipe/          # Miniaturas usadas na tabela abaixo
    └── prints/          # Capturas usadas neste README
```

## Integrantes

| Foto | Nome | RM | Turma | Área informada | Perfis |
| --- | --- | --- | --- | --- | --- |
| ![Asaffe Gabriel](docs/equipe/asaffe-gabriel.png) | Asaffe Gabriel | 574554 | 1TDSPB | Front-End e design | [GitHub](https://github.com/Asaffeggmsmfj) · [LinkedIn](https://www.linkedin.com/in/asaffe-gabriel-bb4288302) |
| ![Gustavo Almeida](docs/equipe/gustavo-almeida.png) | Gustavo Almeida | 576939 | 1TDSPB | Back-end Java e DDD | [GitHub](https://github.com/gtzall) · [LinkedIn](https://www.linkedin.com/in/gustavo-almeida-rodrigues) |
| ![Moises Alciati](docs/equipe/moises-alciati.png) | Moises Alciati | 575893 | 1TDSPB | Banco de dados | [GitHub](https://github.com/moisesalciati) · [LinkedIn](https://www.linkedin.com/in/moises-de-oliveira-alciati-08a944441) |
| ![Claudio Augusto Silva de Assis](docs/equipe/claudio-augusto-silva-de-assis.png) | Claudio Augusto Silva de Assis | 576661 | 1TDSPB | Python, IA e chatbot | [GitHub](https://github.com/claudiosilva06) · [LinkedIn](https://www.linkedin.com/in/claudio-augusto-b7660a433) |

As áreas foram informadas pela equipe e não indicam as tecnologias usadas pelo site. As fotos foram fornecidas pelo grupo. A Roboto local inclui sua licença em `fonts/roboto-ofl.txt`.

## Fontes

- [FIAP — Contato da graduação](https://www.fiap.com.br/graduacao/contato/): endereço e horário de atendimento.
- [FIAP — Campus Paulista, 7 ago. 2012](https://www.fiap.com.br/2012/08/07/campus-fiap-paulista/): informações históricas sobre espaços.
- [FIAP — Ampliação do campus, 28 jun. 2012](https://www.fiap.com.br/imprensa/fiap-inaugura-novo-campus-na-avenida-paulista/): informações históricas sobre laboratórios, auditório e convivência.
- [Plano de Garantia de Acessibilidade da FIAP](https://www.fiap.com.br/wp-content/themes/fiap2016/documents/fiap/informacoes-academicas/politicas-institucionais/PLANO%20DE%20GARANTIA%20DE%20ACESSIBILIDADE.pdf): diretrizes institucionais de 2020.

## Entrega

`cp2.txt` contém uma linha por integrante e o link do repositório. Conforme o enunciado, o líder envia o arquivo no Teams. A atividade também exige pelo menos 20 commits reais e dois commits por integrante, feitos pela própria conta de cada estudante. Não reatribua commits nem fragmente mudanças artificialmente. A permissão do professor indicada no enunciado continua pendente de autorização.

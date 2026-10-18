# 💻 Conecta Procópio

Website de uma ONG (fictícia) de **inclusão digital** em Cornélio Procópio – PR, desenvolvido para o **Projeto 1 – HTML e CSS** da disciplina **Programação Web Front-End (UTFPR – 2026/2)**, ministrada pela Profa. Rosangela Marquesone.

🔗 **Acesse o site:** https://hugo-pessoni.github.io/conecta-procopio/

🎬 **Vídeo de apresentação:** https://youtu.be/QDiKWu-luj4

## 📌 Sobre o projeto

Muitas famílias e escolas da região ainda não têm computador em casa ou não sabem usar a tecnologia no dia a dia. Ao mesmo tempo, empresas e pessoas descartam equipamentos que ainda funcionam. A **Conecta Procópio** une as duas pontas:

1. recebe computadores doados;
2. recondiciona os equipamentos com voluntários;
3. entrega para famílias e escolas cadastradas;
4. oferece cursos gratuitos de informática.

O site permite conhecer a ONG e os cursos, fazer o cadastro e acessar a conta.

**Público-alvo:** famílias de baixa renda, estudantes, escolas públicas e pessoas que querem aprender informática, além de doadores e voluntários.

## 🎯 ODS atendido

**ODS 9 – Indústria, Inovação e Infraestrutura**, em especial a meta 9.c: *aumentar significativamente o acesso às tecnologias de informação e comunicação*. O projeto amplia o acesso a computadores e internet, reaproveita equipamentos que seriam descartados e capacita pessoas para a inovação e o mercado de trabalho em tecnologia.

## 🗂️ Estrutura do projeto

```
conecta-procopio/
├── index.html       → página principal (como funciona, cursos, ODS 9)
├── cadastro.html    → página de cadastro (formulário com 7 campos)
├── login.html       → página de login (e-mail e senha)
├── css/
│   └── style.css    → folha de estilo externa usada pelas três páginas
├── figs/            → imagens do site (ilustrações em SVG)
├── prints/          → prints da validação no W3C (HTML e CSS)
└── README.md
```

**Fluxo de navegação:** cadastro → login → página principal.

## 🛠️ Tecnologias e conceitos utilizados

- **HTML5** com tags semânticas: `header`, `nav`, `main`, `section`, `article`, `aside`, `figure`, `figcaption`, `footer`
- Listas ordenada, não ordenada e de descrição (`ol`, `ul`, `dl`)
- Formulários com `label`, `input` (text, email, tel, date, password, submit), `select` e `textarea`
- **CSS3** em arquivo externo: seletores de elemento, classe e pseudo-classe (`:hover`), modelo de caixa, `border-radius`, **Flexbox** e **Grid Layout**
- Fontes: **Poppins** (Google Fonts, externa) e **Georgia**
- Ícones: **Google Material Icons**
- Sem frameworks

## ✅ Validação

O código foi validado nos validadores oficiais do W3C:

- HTML: https://validator.w3.org/
- CSS: https://jigsaw.w3.org/css-validator/

Os prints estão na pasta [`prints/`](prints/).

## 👤 Integrante

- **Hugo Rafael Pessoni Batista** – [Currículo](https://hugo-pessoni.github.io/cv-css-hugo/)

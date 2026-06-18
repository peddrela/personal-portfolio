<div align="center">

# 🧑‍💻 Pedro Guzzo — Portfolio Pessoal

**Meu espaço na web. Projetos, habilidades e um pouco sobre mim.**

[![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://pages.github.com/)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

🌐 **[peddrela.github.io/personal-portfolio](https://peddrela.github.io/personal-portfolio)**

</div>

---

## 🚀 Sobre o projeto

Portfolio pessoal desenvolvido com **Astro** e hospedado gratuitamente no **GitHub Pages**, com deploy automático a cada push na branch `main` via **GitHub Actions**.

O site reúne minha apresentação, habilidades técnicas e projetos desenvolvidos ao longo da minha jornada como estudante de Ciência da Computação.

---

## 🛠️ Tecnologias

| Tecnologia     | Uso                                            |
| -------------- | ---------------------------------------------- |
| Astro          | Framework principal — geração de site estático |
| CSS            | Estilização e layout                           |
| GitHub Actions | CI/CD — deploy automático                      |
| GitHub Pages   | Hospedagem gratuita                            |

---

## 📁 Estrutura do projeto

```
personal-portfolio/
├── .github/
│   └── workflows/       # Pipeline de deploy automático
├── public/              # Arquivos estáticos (imagens, favicon)
├── src/
│   ├── components/      # Componentes reutilizáveis .astro
│   └── pages/
│       └── index.astro  # Página principal
├── astro.config.mjs     # Configuração do Astro + GitHub Pages
└── package.json
```

---

## ⚙️ Como rodar localmente

```bash
# 1. Clone o repositório
git clone https://github.com/peddrela/personal-portfolio.git
cd personal-portfolio

# 2. Instale as dependências
npm install

# 3. Inicie o servidor de desenvolvimento
npm run dev
```

O site estará disponível em `http://localhost:4321`.

### Outros comandos úteis

| Comando           | Ação                              |
| ----------------- | --------------------------------- |
| `npm run build`   | Gera o site estático em `./dist/` |
| `npm run preview` | Pré-visualiza o build localmente  |

---

## 🔄 Deploy

O deploy é feito automaticamente via **GitHub Actions** toda vez que há um push na branch `main`. O site é publicado no GitHub Pages em:

> **https://peddrela.github.io/personal-portfolio**

Nenhuma configuração manual é necessária.

---

<div align="center">

Feito por [Pedro Guzzo](https://github.com/peddrela)

</div>

# 📚 Playlite - Documentação Oficial

Bem-vindo ao repositório oficial de documentação do **Playlite**, um Game Manager focado em performance e organização, construído com Tauri, Rust e React.

Este site é construído utilizando [VitePress](https://vitepress.dev/) e está hospedado automaticamente no [Vercel](https://vercel.com).

🔗 **Acesse a documentação online:** [Docs](https://playlite.vercel.app/en/)

---

## 🏗️ Arquitetura da Documentação

A documentação do Playlite é dividida em duas partes principais:

1. **Guias Manuais (Markdown):** Tutoriais, arquitetura, explicações do sistema de recomendação e guias de uso. Estes arquivos são deste repositório e estão divididos por idioma (`pt-BR/` e `en/`).

2. **API Reference (Gerada Automaticamente):** A documentação do código-fonte (Rustdocs para o backend e TypeDoc para o frontend).

### 🤖 Automação da API Reference

Os arquivos da documentação de API (`rustdocs` e `jsdocs`) **não são gerados neste repositório**.

Eles são gerados no repositório principal do código e enviados automaticamente para a pasta `public/api/` através de uma pipeline do GitHub Actions sempre que a branch `main` do repositório principal é atualizada.

---

## 📁 Estrutura do Repositório

```plaintext
.
├── .vitepress/          # Configurações globais do VitePress, rotas e tema (config.ts)
├── en/                  # Guias e tutoriais em Inglês
├── pt-BR/               # Guias e tutoriais em Português (Brasil)
├── public/              # Arquivos estáticos (imagens, ícones)
│   └── api/             # ⚠️ GERADO AUTOMATICAMENTE: TypeDocs e RustDocs injetados via Actions
├── API_README.md        # Readme base para a home da documentação do TypeDoc
├── package.json         # Dependências do VitePress e scripts
└── README.md            # Este arquivo
```

---

## 🔗 Links Úteis

* Repositório Principal (Código-fonte): [Playlite](https://github.com/playlite-app/playlite)
* Releases do Playlite: [Baixar versões](https://github.com/playlite-app/playlite/releases)

---

Playlite - Desenvolvido para organizar e potencializar a sua biblioteca de jogos. 🎮

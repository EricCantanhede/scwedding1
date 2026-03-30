# SC Weddings — Landing Page

Produtora de Filmes & Fotos para Casamentos.

## 📁 Estrutura do Projeto

```
scweddings/
└── index.html   ← arquivo único, sem dependências externas
```

> Não há pasta `node_modules`, `package.json` ou build necessário.  
> Basta abrir o `index.html` no navegador — ou subir no GitHub Pages.

---

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório público no GitHub (ex: `scweddings`)
2. Suba o arquivo `index.html` para a raiz do repositório
3. Vá em **Settings → Pages → Source: main branch / root**
4. Seu site estará em `https://seuuser.github.io/scweddings/`

---

## ⚙️ Configuração do Admin (uma vez só)

O site usa dois serviços gratuitos para salvar dados na nuvem e torná-los visíveis para todos os visitantes.

### 1️⃣ JSONbin.io — Textos e Configurações

1. Acesse [jsonbin.io](https://jsonbin.io) e crie uma conta gratuita
2. Vá em **perfil → API Keys** e copie a **Master Key**
3. No site, clique em **Admin** (canto superior direito)
4. Faça login com `admin` / `admin123`
5. Vá na aba **Configuração** → cole a Master Key → clique **Criar Armazenamento**
6. Copie o link gerado (com `?bin=ID`) e **use esse link como o endereço oficial do site**

### 2️⃣ ImgBB — Fotos

1. Acesse [imgbb.com](https://imgbb.com) e crie uma conta gratuita
2. Acesse [api.imgbb.com](https://api.imgbb.com) → clique em **Get API key**
3. No admin → aba **Configuração** → cole a API Key → clique **Salvar Chave ImgBB**

---

## 🔐 Credenciais Padrão do Admin

| Campo   | Valor     |
|---------|-----------|
| Usuário | `admin`   |
| Senha   | `admin123`|

> Troque a senha na aba **🔒 Senha** após o primeiro acesso.

---

## 🐛 Bugs Corrigidos nesta Versão

- **Imagens nunca mais são salvas como base64** — apenas URLs reais (ImgBB ou Unsplash)
- **`deepMerge` garante que nenhum campo some** após uma edição parcial
- **Defaults completos** — a página nunca fica em branco, mesmo sem conexão
- **`localStorage` não corrompe** — base64 é filtrada antes de qualquer gravação
- **Fotos aparecem imediatamente** em DOM (preview local) sem depender de uploads

---

## 📦 Dependências

- **Nenhuma** — apenas o arquivo `index.html`
- Google Fonts carrega do CDN (necessita internet)
- JSONbin.io e ImgBB são serviços gratuitos externos

---

## 📞 Suporte

Site desenvolvido para SC Weddings Production — Fortaleza, CE.

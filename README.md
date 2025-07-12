# Beta Reader Go

Plataforma gamificada onde você ganha dinheiro escrevendo críticas de livros. Leia, avalie e seja recompensado!

## 📖 Sobre o Projeto

Este é um site estático que foi baixado usando HTTrack do site original [betareader.space](https://betareader.space/). A plataforma permite que usuários ganhem dinheiro avaliando livros através de críticas e resenhas.

## 🚀 Como Executar Localmente

### Pré-requisitos
- Node.js (versão 18 ou superior)

### Instalação e Execução

1. **Instale as dependências:**
   ```bash
   npm install
   ```

2. **Execute o servidor local:**
   ```bash
   npm run dev
   ```

3. **Acesse o projeto:**
   - Abra seu navegador e vá para: `http://localhost:8000`
   - O site será aberto automaticamente

## 🌐 Deploy na Vercel

### Deploy Automático via GitHub

1. **Faça push do código para o GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Conecte com a Vercel:**
   - Acesse [vercel.com](https://vercel.com)
   - Faça login com sua conta GitHub
   - Clique em "New Project"
   - Selecione o repositório `beta-reader-go`
   - Clique em "Deploy"

### Deploy Manual via Vercel CLI

1. **Instale o Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Faça login na Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy:**
   ```bash
   vercel
   ```

## 📁 Estrutura do Projeto

```
beta-reader-go/
├── index.html                 # Página principal do HTTrack
├── betareader.space/         # Site baixado
│   ├── index.html            # Página principal do Beta Reader Go
│   ├── _next/               # Arquivos estáticos do Next.js
│   ├── favicon.ico          # Ícone do site
│   └── apple-touch-icon.html # Ícone para iOS
├── package.json             # Configuração do Node.js
├── vercel.json             # Configuração do Vercel
└── README.md               # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **HTTrack**: Ferramenta para baixar sites completos
- **Next.js**: Framework React original do site
- **Node.js**: Runtime JavaScript
- **Vercel**: Plataforma de deploy

## 📝 Funcionalidades

- ✅ Interface responsiva
- ✅ Design moderno e gamificado
- ✅ Sistema de avaliação de livros
- ✅ Plataforma de ganhos por críticas
- ✅ Otimizado para SEO

## 🔧 Configurações

### Vercel
- **Framework Preset**: Other
- **Build Command**: `npm run build`
- **Output Directory**: `.`
- **Install Command**: `npm install`

### Variáveis de Ambiente
Nenhuma variável de ambiente necessária para este projeto estático.

## 📞 Suporte

Para dúvidas ou problemas:
- Abra uma issue no GitHub
- Entre em contato através do site original

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Desenvolvido com ❤️ para a comunidade de leitores e escritores** 
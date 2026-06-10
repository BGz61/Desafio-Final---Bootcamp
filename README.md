Portfólio - Gabriel Borges

Um portfólio moderno e responsivo para desenvolvedor Front-End, construído com React 19, Tailwind CSS 4 e Framer Motion.

🎨 Características

•
✨ Design Minimalista Moderno - Interface elegante com tema escuro e acentos ciano

•
🎬 Animações Suaves - Transições fluidas com Framer Motion

•
📱 Totalmente Responsivo - Funciona perfeitamente em desktop, tablet e mobile

•
⚡ Performance Otimizada - Carregamento rápido e otimizado

•
🌐 Pronto para GitHub Pages - Deploy fácil e direto

•
🇧🇷 100% em Português Brasil - Interface completamente em português

📋 Seções

•
Hero - Apresentação principal com chamada para ação

•
Sobre Mim - Informações pessoais e profissionais

•
Habilidades - Grid visual de competências técnicas

•
Projetos - Showcase de projetos com cards interativos

•
Contato - Links diretos para email, WhatsApp e LinkedIn

🛠️ Stack Tecnológico

•
React 19 - Framework JavaScript

•
TypeScript - Tipagem estática

•
Tailwind CSS 4 - Estilização utilitária

•
Framer Motion - Animações e transições

•
Lucide React - Ícones de alta qualidade

•
Vite - Build tool rápido

•
Wouter - Roteamento leve

🚀 Como Usar

1. Clonar o Repositório

Bash


git clone https://github.com/seu-usuario/seu-usuario.github.io.git
cd seu-usuario.github.io



2. Instalar Dependências

Bash


npm install
# ou
pnpm install



3. Rodar Localmente

Bash


npm run dev
# ou
pnpm dev



Acesse http://localhost:5173 no seu navegador.

4. Fazer Build

Bash


npm run build
# ou
pnpm build



5. Deploy no GitHub Pages

Bash


git add .
git commit -m "Atualização do portfólio"
git push



O site será automaticamente publicado em https://seu-usuario.github.io

📝 Personalização

Editar Informações Pessoais

Abra client/src/pages/Home.tsx e atualize:

•
Nome e descrição na seção Hero

•
Texto da seção "Sobre Mim"

•
Links do LinkedIn, GitHub e Email

•
Projetos (título, descrição, tags e links )

Mudar Cores

Edite client/src/index.css e altere as variáveis CSS:

CSS


--primary: #00d9ff;        /* Cor principal (ciano) */
--background: #0f172a;     /* Fundo (preto) */
--foreground: #f1f5f9;     /* Texto (branco) */



Adicionar Projetos

No arquivo Home.tsx, adicione novos objetos ao array projects:

JavaScript


{
  id: 4,
  title: "Seu Projeto",
  description: "Descrição do projeto",
  tags: ["React", "Tailwind"],
  link: "https://seu-projeto.com",
  github: "https://github.com/seu-usuario/seu-projeto",
  image: "url-da-imagem"
}



📦 Estrutura do Projeto

Plain Text


client/
├── src/
│   ├── pages/
│   │   ├── Home.tsx          # Página principal
│   │   └── NotFound.tsx      # Página 404
│   ├── components/
│   │   └── ui/               # Componentes shadcn/ui
│   ├── App.tsx               # Configuração de rotas
│   ├── main.tsx              # Entrada da aplicação
│   └── index.css             # Estilos globais
├── public/
│   └── favicon.ico           # Ícone do site
└── index.html                # HTML principal



🎯 Próximos Passos Sugeridos

1.
Adicionar seus projetos reais - Substitua os projetos de exemplo com seus trabalhos pessoais

2.
Colocar uma foto sua - Na seção "Sobre Mim" para humanizar o portfólio

3.
Implementar formulário de contato - Integre com EmailJS ou Formspree

4.
Adicionar seção de Blog - Compartilhe artigos sobre desenvolvimento

5.
Otimizar SEO - Adicione meta tags e schema markup

🔗 Links Úteis

•
React Documentação

•
Tailwind CSS

•
Framer Motion

•
GitHub Pages

•
Lucide Icons

📄 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

👤 Autor

Gabriel Borges - Desenvolvedor Front-End

•
LinkedIn: gabriel-borges

•
Email: gabrielllborgesss146@gmail.com

•
WhatsApp: (61) 99219-2765


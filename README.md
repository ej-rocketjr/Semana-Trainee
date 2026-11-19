# 🐝 Beescuit — Artes em Biscuit Feitas à Mão

Landing Page institucional e vitrine digital desenvolvida durante a **Semana Imersão Trainee da Diretoria de Projetos – RocketJR (2026)**.

## 📌 Sobre o Projeto
Este projeto consiste no desenvolvimento de uma Landing Page responsiva de página única (*Single Page*) e alta conversão para a **Beescuit**, empreendimento de Penedo/AL especializado na confecção de artefatos artesanais em biscuit (peças decorativas, chaveiros, acessórios, lembrancinhas e artigos personalizados).

A solução atua como vitrine digital e ponto de venda direto, eliminando intermediários e distrações no atendimento. Por meio dela, o público-alvo pode visualizar o portfólio artesanal, conferir depoimentos reais, tirar dúvidas no FAQ e solicitar orçamentos ou encomendas sob medida diretamente pelo WhatsApp.

## 👥 Equipe
- **Josué Filipe (Felipe)** – Gerente de Projeto (GP): contato com a cliente, acompanhamento de prazos, gestão do quadro Kanban no Trello, controle de atas e gestão de escopo.
- **João Barbosa** – Designer UI/UX: criação do guia visual, wireframe, protótipo interativo no Figma (desktop e mobile), vitrine de produtos e ajustes de identidade visual.
- **Ravi Brocco** – Desenvolvedor Principal: arquitetura de código front-end, implementação da responsividade, gerenciamento do fork/commits no GitHub e apoio ao deploy.
- **João Neto** – Responsável por Documentação e Hospedagem: levantamento de requisitos, redação da documentação, manual do cliente e hospedagem em domínio.
- **Tainá Lopes** – Responsável por QA: aplicação do checklist de qualidade, testes de responsividade em múltiplos dispositivos, auditoria de links, validação de performance (PageSpeed) e registro de atas.

## 🎯 Cliente
- **Cliente:** Aysha – Beescuit (Artesanato em biscuit – Penedo/AL).
- **Objetivo do projeto:** Estruturar um canal profissional de vendas e vitrine digital para apresentar peças artesanais, orientar pedidos personalizados e converter visitantes em compradores recorrentes com atendimento ágil via WhatsApp.

## 📋 Levantamento de Requisitos

### Requisitos Funcionais
- **RF01 – Atendimento rápido via WhatsApp:** Botão no cabeçalho e botão flutuante direcionando diretamente para o WhatsApp comercial da Beescuit com mensagem pré-preenchida.
- **RF02 – Canal de pedidos personalizados:** Seção dedicada para solicitação de peças sob medida com redirecionamento direto para atendimento personalizado no WhatsApp.
- **RF03 – Vitrine responsiva de produtos:** Galeria organizada com fotos reais das peças artesanais produzidas pela marca.
- **RF04 – Prova social e FAQ:** Seção de feedbacks reais de clientes e acordeão interativo com perguntas frequentes sobre prazos, entrega em Penedo/AL e formas de pagamento.
- **RF05 – Redes sociais:** Integração e redirecionamento para os perfis oficiais da marca (Instagram e Pinterest).

### Requisitos Não Funcionais
- **RNF01 – Responsividade:** Layout 100% responsivo (desenvolvido com abordagem *Mobile First*, otimizado para Desktop, Tablet e Mobile, sem quebra de elementos ou overflow horizontal).
- **RNF02 – Performance:** Carregamento rápido e leve utilizando HTML5 e CSS3 puros, com imagens otimizadas e meta de pontuação $\ge 90$ no PageSpeed Insights Desktop.
- **RNF03 – Identidade visual:** Fidelidade à paleta de cores (`--sand`, `--brown`, `--honey`, `--orange`, `--teal`), tipografia (`Fredoka` e `DM Sans`) e logomarca oficial da Beescuit.
- **RNF04 – Acessibilidade e código limpo:** Uso de HTML5 semântico, atributos `alt` descritivos nas imagens, `aria-label` nos controles e ausência de erros críticos de console.

## 🎨 Prototipação
A prototipação foi desenvolvida utilizando a abordagem *Mobile First* (contemplando versões desktop e mobile). Após a criação do wireframe e do protótipo de alta fidelidade, foi realizada reunião de alinhamento com a cliente para validar ajustes visuais no cabeçalho, tipografia, esquema de cores e atualização da logomarca.
- **Ferramenta utilizada:** Figma
- **Link do protótipo:** [Acessar Protótipo no Figma](https://www.figma.com/design/Bf1JX3IMPw562TkuhbL38z/Beescuit---Landing-Page?node-id=0-1&t=FEZ8iWGTZwoeI4LU-1)
- **Status:** Aprovado pelo cliente

## 🛠️ Tecnologias Utilizadas
- **HTML5 e CSS3** (CSS Grid, Flexbox, variáveis CSS, máscaras SVG e Media Queries)
- **Figma** (prototipação UI/UX)
- **Git & GitHub** (versionamento de código, branches e Pull Requests)
- **Trello** (gestão ágil de tarefas via quadro Kanban)

## 💻 Como Rodar o Projeto Localmente
1. Clone este repositório:
   ```bash
   git clone [https://github.com/soaresravi/Beescuit.git](https://github.com/soaresravi/Beescuit.git)
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd Beescuit
   ```
3. Abra o arquivo `index.html` diretamente no navegador de sua preferência (ou utilize a extensão **Live Server** no VS Code).

## 🔧 Organização e Versionamento
Este projeto seguiu as diretrizes da Diretoria de Projetos da RocketJR:
- Repositório criado a partir de fork do repositório base (`ej-rocketjr/Semana-Trainee`);
- Desenvolvimento centralizado na branch `dev` por meio de branches de funcionalidades e Pull Requests internos revisados antes da integração final na `main`;
- Uso de commits semânticos e bem descritos por todos os membros da equipe;
- Pull Request final aberto para o repositório oficial ao término da atividade.

## 🌐 Deploy e Como Publicar
- **Plataforma / Hospedagem:** Hospedagem web com domínio personalizado
- **Link do deploy:** https://Buykaito.com.br/Beescuit-dev
- **Como publicar:** Por ser uma aplicação front-end estática (HTML/CSS/Assets), basta enviar os arquivos da branch `main` (`index.html`, pasta `css/` e pasta `assets/`) para o diretório público (`public_html`) do servidor de hospedagem ou conectar a branch `main` diretamente em plataformas como Vercel, Netlify ou GitHub Pages.

## 🤖 Uso de IA no Desenvolvimento
Ferramentas de Inteligência Artificial foram utilizadas de forma auxiliar durante o desenvolvimento para:
- Revisão de boas práticas de HTML5 semântico e atributos de acessibilidade (`alt` e `aria-label`);
- Apoio em ajustes finos de responsividade em CSS (reordenação de elementos via Flexbox no mobile e breakpoints);
- Revisão de código em Pull Requests e estruturação da documentação técnica.

## 📂 Estrutura do Projeto
```text
/
├── assets/
│   └── img/          # Logos, fotos dos produtos e feedbacks de clientes
├── css/
│   └── style.css     # Estilização global, variáveis e regras responsivas
├── index.html        # Estrutura principal da Landing Page
└── README.md         # Documentação do projeto
```

## 📎 Referências e Materiais de Apoio
- Guia de Projetos RocketJR
- Padrões de Commits (Conventional Commits)
- Material sobre Métodos Ágeis
- Documentação oficial HTML5 e CSS3 (MDN Web Docs)

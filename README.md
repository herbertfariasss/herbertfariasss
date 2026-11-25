<h1 align="center">Olá, eu sou Herbert Farias 👋</h1>

<p align="center">
  <strong>Analista Jr. de Automações</strong> na Eazytech · Estudante de Análise e Desenvolvimento de Sistemas na UNISUAM<br>
  Rio de Janeiro, Brasil 🇧🇷
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/herbert-farias-185a87378/">
    <img src="https://img.shields.io/badge/LinkedIn-Conecte--se-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn de Herbert Farias">
  </a>
  <a href="https://github.com/herbertfariasss?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositórios-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositórios de Herbert Farias">
  </a>
</p>

## 👨‍💻 O que faço

- Atuo na manutenção e evolução de sistemas **CRM e ERP**, além de desenvolver automações de processos de negócio.
- Crio fluxos em **n8n** e integro plataformas por **APIs REST** e **webhooks**. Já desenvolvi integrações com **Google Sheets** e **Google Drive**.
- Desenvolvo soluções com **Python** e **JavaScript**, aplicando orientação a objetos, validação de regras e testes automatizados.
- Construo agentes com a **API da OpenAI** e já trabalhei com as APIs da **Groq** e do **Gemini**.
- Uso **Claude**, **Claude Code**, **Codex** e a IDE **Antigravity** em projetos, incluindo orquestração de agentes por playbooks. Também já usei **GitHub Copilot**.
- Trabalho com consultas, modelagem e integrações de dados em **PostgreSQL/Supabase**.

Atuo na Eazytech desde **maio de 2026**. Estou concluindo o **2º período de Análise e Desenvolvimento de Sistemas na UNISUAM**, com início do 3º período previsto para 2027 e formação estimada para 2028.

## 🚨 Projeto de backend em destaque

**[Integration Incident Monitor](https://github.com/herbertfariasss/integration-incident-monitor)** — API desenvolvida em Python para receber eventos fictícios por webhook, identificar falhas repetidas em integrações e acompanhar incidentes.

- A classe `IncidentService` concentra as regras de abertura, atualização e encerramento de incidentes.
- Três falhas únicas da mesma integração e do mesmo código de erro, dentro de 30 minutos, abrem um incidente.
- Eventos duplicados são ignorados e novas falhas atualizam o incidente aberto.
- Persistência em **SQLite**, contratos com **Pydantic** e rotas documentadas automaticamente pelo **FastAPI**.
- **12 testes automatizados** para regras e rotas, com **87% de cobertura local** e execução contínua pelo **GitHub Actions**.
- Extensão opcional de IA para resumir o incidente e sugerir verificações, sempre com aviso de conferência humana.

**Tecnologias:** Python · FastAPI · SQLite · Pydantic · pytest · HTTPX · GitHub Actions

## 🔄 Projeto profissional em uso

**[Reconexão de instâncias de WhatsApp](https://github.com/herbertfariasss/whatsapp-reconexao-n8n-demo)** — automação desenvolvida para uso no trabalho, integrada a uma API não oficial de WhatsApp. O repositório apresenta uma versão demonstrativa do fluxo, com dados fictícios.

O fluxo em **n8n** recebe eventos por webhook, identifica quando uma instância desconecta ou volta a conectar e envia avisos ao grupo responsável. Quando é preciso reconectar, uma ação interativa solicita um novo **QR Code**; o fluxo consulta a API, envia o código ao grupo e oferece a opção de gerar outro caso necessário. Também trata falhas na identificação da instância ou na geração do QR Code.

**Tecnologias:** n8n · Webhooks · APIs REST · JavaScript · Zaptos

## 🛠️ Tecnologias e ferramentas

**Linguagens e web**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)

**Backend e testes**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Dados, automação e IA**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Groq API](https://img.shields.io/badge/Groq_API-B83D23?style=for-the-badge)
![Gemini API](https://img.shields.io/badge/Gemini_API-345FBF?style=for-the-badge&logo=googlegemini&logoColor=white)

**Integrações com Google Workspace**

![Google Sheets](https://img.shields.io/badge/Google_Sheets-137333?style=for-the-badge&logo=googlesheets&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-1666CB?style=for-the-badge&logo=googledrive&logoColor=white)

**Ferramentas de IA no desenvolvimento**

![Claude](https://img.shields.io/badge/Claude-9E4D2D?style=for-the-badge&logo=claude&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-7D3621?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-292D32?style=for-the-badge)
![Antigravity IDE](https://img.shields.io/badge/Antigravity_IDE-345FBF?style=for-the-badge)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-181717?style=for-the-badge&logo=githubcopilot&logoColor=white)

**Versionamento**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## 📚 O que estou aprendendo

Estou estudando **MongoDB** por meio do curso oferecido pela MongoDB para estudantes.

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

## 🎯 Foco profissional

Quero evoluir como desenvolvedor **backend e full stack**, fortalecendo minha base em arquitetura de sistemas, APIs, bancos de dados, automação de processos e inteligência artificial aplicada a soluções empresariais.

## 📂 Projetos em destaque

| Projeto | Descrição |
| --- | --- |
| [Integration Incident Monitor](https://github.com/herbertfariasss/integration-incident-monitor) | API em Python/FastAPI com SQLite, orientação a objetos, detecção de falhas repetidas, testes unitários e de rotas, integração contínua e extensão opcional de IA. |
| [Próximo Passo](https://github.com/herbertfariasss/proximo-passo-sanitizado) | Sistema web acadêmico da UNISUAM para organizar tarefas e objetivos pessoais e analisar decisões financeiras com IA. Utiliza PHP, MySQL, JavaScript e a API da Groq. |
| [Landing page de estofados — demo](https://site-limpeza-de-estofados-demo.vercel.app/) | Versão demonstrativa de uma landing page para higienização de estofados, com apresentação de serviços, comparação visual e jornada de solicitação de orçamento. [Abrir o site](https://site-limpeza-de-estofados-demo.vercel.app/). |
| [Projeto Faculdade](https://github.com/herbertfariasss/Projeto-Faculdade) | Plataforma acadêmica de cursos com HTML, CSS e JavaScript, catálogo, páginas responsivas e fluxo demonstrativo de cadastro e login. [Abrir o site](https://herbertfariasss.github.io/Projeto-Faculdade/). |
| [Prontuário Farmacêutico](https://github.com/herbertfariasss/prontuario-farmaceutico) | Protótipo em Python e Streamlit com autenticação, persistência local e documentação da arquitetura. Em desenvolvimento. |
| [Cadastro de Usuário](https://github.com/herbertfariasss/cadastro-de-usuario) | Formulário responsivo com validação de senha no navegador. [Abrir a demo](https://herbertfariasss.github.io/cadastro-de-usuario/). |

Também estou desenvolvendo um **escritório virtual de agentes de IA** em pixel art, associado a uma experiência de orquestração por playbooks.

## 📊 GitHub em números

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=herbertfariasss&show_icons=true&theme=tokyonight&hide_border=true" alt="Estatísticas públicas do GitHub de Herbert Farias">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=herbertfariasss&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens dos repositórios públicos de Herbert Farias">
</p>

<sub>Os cartões são gerados automaticamente a partir da atividade e dos repositórios públicos no GitHub.</sub>

## 📫 Contato

Quer conversar sobre desenvolvimento, automações ou integrações? [Conecte-se comigo no LinkedIn](https://www.linkedin.com/in/herbert-farias-185a87378/).

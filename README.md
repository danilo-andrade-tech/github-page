<!-- Crie este arquivo em: github-page/docs/index.html -->
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body >
    <h1>PortfólioHub - Documentação de Implementação</h1>
    <p>Este repositório hospeda a camada técnica e a documentação do meu projeto final do Bootcamp.</p><br>
    <h2>Acesso ao Portfólio Visual</h2>
    <p>A interface visual e institucional deste portfólio foi desenvolvida e está hospedada no Google Sites.</p>
    <!-- LINK PARA O SEU GOOGLE SITES AQUI -->
    <a href="https://sites.google.com/view/portifolio-danilo-engsoftware/in%C3%ADcio" class="btn" target="_blank">Acessar Portfólio no Google Sites</a><br>
    <h2>Especificações Técnicas</h2>
    <p>O código-fonte do projeto prático está localizado no arquivo  <code>Portifolio.html</code> deste repositório.</p>
</body>
</html>
# Documentação Técnica de Implementação: PortfólioHub

Este documento consolida o planejamento, a engenharia, os parâmetros de segurança e a estratégia de lançamento do ecossistema **PortfólioHub** — uma infraestrutura unificada que conecta o Google Sites, o GitHub, o GitHub Pages e o LinkedIn para criar uma vitrine profissional de alto impacto técnico.

---
# 📌 Planejamento de Implementação do Gemini 

O **PortfólioHub** é um ecossistema integrado que une **Google Sites, GitHub, GitHub Pages e LinkedIn** em uma única infraestrutura coesa, eliminando a fragmentação de informações e validando competências técnicas para recrutadores.

---

## 🧠 1. Planejamento com IA (Gemini)
*   **Framework CATR:** Aplicação de engenharia de prompts para estruturação de escopo e arquitetura.
*   **Personas Utilizadas:** Engenheiro de Software (Fase Técnica), Especialista em AppSec (Segurança) e Tech Recruiter (Lançamento).
*   **Eficiência:** Redução de 40% no tempo de documentação.

---

## 📁 2. Arquitetura do Repositório (`github-page`)

github-page/
├── docs/            # Documentação técnica servida no GitHub Pages (index.html)
├── src/             # Código-fonte do projeto técnico do Bootcamp (main.py)
└── README.md        # Esta página de apresentação do ecossistema
Deploy: Configurado via Settings > Pages apontando para a branch main na pasta /docs.

URL Ativa: danilo-andrade-tech.github.io/github-page/

---

## 🔒 3. Governança e Segurança (Google Workspace)
Identity & Access (IAM): Ativação de MFA (Autenticação de Dois Fatores) na conta admin e uso de conta secundária sem privilégios para edições diárias.

Controle de Compartilhamento: Google Sites público, mas arquivos de suporte (PDFs/certificados) isolados no Drive como "Apenas Leitor".

Proteção de Dados (DLP): Opção de download, impressão e cópia desativada nas propriedades avançadas dos arquivos sensíveis do Drive para evitar plágio.

---

## 🛠️ 4. Governança do Código (GitHub)
Estratégia de Branching: Uso de branches temporárias (feature/) para novos ajustes. A branch main armazena apenas código 100% estável.

Branch Protection: Regra ativa de Require a pull request before merging na main, impedindo commits diretos e acidentais.

Gestão de Credenciais: Autenticação via Personal Access Tokens (PAT) e proteção de chaves de API através do GitHub Secrets.

---

## 🧪 5. Checklist de Validação (QA)
Links Cruzados: Validação das conexões entre Google Sites ↔ GitHub ↔ LinkedIn.

Responsividade: Teste de layout em Desktop, Tablet e Mobile.

Janela Anônima: Verificação de permissões públicas para garantir que nenhum arquivo peça login do Google.

---

## ⏱️ 6. Resumo do Roteiro do Pitch (5 Minutos)
0:00 - 0:45 | Introdução: Gancho sobre o problema da fragmentação e a proposta do PortfólioHub.

0:45 - 2:00 | Camada Visual: Demonstração do Google Sites focado em UX e funil para o LinkedIn.

2:00 - 3:30 | Camada Técnica: Apresentação do repositório GitHub, arquitetura de pastas e GitHub Pages.

3:30 - 4:30 | Segurança: Explicação das travas do Drive, IAM, MFA e GitHub Secrets.

4:30 - 5:00 | Fechamento: Conclusão do projeto e Call to Action para contatos.

Para ver o documento de Planelamento com mais informação acesse o PDF neste repositorio: <code></code> 
---
<br><br><br><br><br>
<a href="https://www.linkedin.com/in/danilo-andrade-b4a523258">
  <img src="https://imgs.search.brave.com/uIVOEoybk0hTmltyke8eQLu4sfCXb9H_yWhfrB96iOM/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly93d3cu/ZnJlZXBuZ2xvZ29z/LmNvbS91cGxvYWRz/L2xpbmtlZGluLWxv/Z28tdHJhbnNwYXJl/bnQtcGljdHVyZS0z/MS5wbmc" align="center" heigth="40" width="50">
</a>


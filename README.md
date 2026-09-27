# Computação em Nuvem I — Atividade de Pesquisa e Prática

Repositório acadêmico contendo o relatório completo, respostas teóricas fundamentadas e artefatos práticos da disciplina de **Computação em Nuvem I**.

---

## 📄 Conteúdo do Repositório

| Arquivo | Descrição |
| :--- | :--- |
| **[`Relatorio_Computacao_em_Nuvem_I.pdf`](./Relatorio_Computacao_em_Nuvem_I.pdf)** | **Relatório final formatado em PDF (Pronto para entrega)**, incluindo cabeçalho acadêmico, tabelas comparativas, diagramas e referências ABNT. |
| **[`Relatorio_Computacao_em_Nuvem_I.docx`](./Relatorio_Computacao_em_Nuvem_I.docx)** | **Relatório em formato Microsoft Word (.docx)** para eventuais edições de nome, turma e personalizações. |
| **[`index.html`](./index.html)** | **Página web desenvolvida para a Prática 2**, cobrindo os conceitos centrais de computação em nuvem e pronta para hospedagem no GitHub Pages ou Vercel. |
| **[`RELATORIO_COMPLETO.md`](./RELATORIO_COMPLETO.md)** | Versão integral em Markdown com todas as respostas, tabelas e diagramas Mermaid. |

---

## 🌐 Publicação Prática no GitHub Pages (Hands-On)

A página `index.html` deste repositório foi projetada para ser servida diretamente pelo **GitHub Pages**:

1. Acesse a aba **Settings** deste repositório no GitHub.
2. Na barra lateral esquerda, clique em **Pages**.
3. Em **Branch**, selecione `main` e a pasta `/(root)`.
4. Clique em **Save**.
5. Em poucos instantes, a aplicação estará publicada e acessível em:
   > **`https://tuzzooz.github.io/computacao-em-nuvem-atividade/`**

---

## 📚 Tópicos Abordados no Relatório

### Parte 1 — Atividade Teórica (Pesquisa Dirigida)
* **Bloco 1 — Contextualização e Modelos de Implantação:**
  * Diferenças entre computação em nuvem e TI tradicional on-premise (CapEx vs OpEx, elasticidade, manutenção).
  * Definições e casos reais de Nuvem Pública, Nuvem Privada e Nuvem Híbrida.
  * Análise do setor financeiro (Resolução CMN nº 4.893/2020 do BACEN).
  * Nuvem Comunitária no padrão NIST SP 800-145 e diferenciação da Nuvem Privada.
* **Bloco 2 — As Cinco Características Essenciais (NIST):**
  * Autoatendimento sob demanda, amplo acesso à rede, pool de recursos, elasticidade rápida e serviço mensurável.
  * Passo a passo técnico para configuração de Auto Scaling de instâncias EC2 com Application Load Balancer na AWS.
* **Bloco 3 — Desafios da Computação em Nuvem:**
  * Segurança: 3 principais ameaças atuais (CSA Top Threats) e controles de mitigação (MFA, CSPM, WAF, Zero Trust).
  * Privacidade: Obrigações legais sob a LGPD (Lei nº 13.709/2018, Artigos 46 e 48).
  * Sistemas Legados: Análise aprofundada dos "6 Rs" da migração (Rehost, Replatform, Refactor).
  * Cultura Organizacional: Estudo de caso real da resistência à nuvem no banco Capital One e superação com CCoE e DevSecOps.
* **Bloco 4 — Modelos de Serviço (IaaS, PaaS, SaaS):**
  * Matriz comparativa de responsabilidade compartilhada e controle.
  * Exemplos reais de provedores alternativos do mercado.
  * Enquadramento técnico de Function as a Service (FaaS) / Serverless no modelo PaaS.

### Parte 2 — Atividade Prática
* **Prática 1:** Matriz comparativa entre AWS, Microsoft Azure e Google Cloud Platform (modelos, serviços, free tier e data centers no Brasil).
* **Prática 2:** Desenvolvimento e publicação de página web com análise técnica do modelo PaaS/Static Hosting.
* **Prática 3:** Estudo de caso de arquitetura híbrida para um hospital de médio porte (divisão de componentes clínicos sensíveis e serviços elásticos de telemedicina/agendamento, segurança mTLS/VPN e diagrama arquitetural).

---

## 📖 Referências Bibliográficas

* MELL, Peter; GRANCE, Timothy. *The NIST Definition of Cloud Computing*. NIST Special Publication 800-145, 2011.
* BRASIL. *Lei nº 13.709, de 14 de agosto de 2018 (Lei Geral de Proteção de Dados Pessoais - LGPD)*.
* BANCO CENTRAL DO BRASIL (BACEN). *Resolução CMN nº 4.893/2020*.
* Documentações oficiais: Amazon Web Services (AWS), Microsoft Azure, Google Cloud Platform (GCP).
* CLOUD SECURITY ALLIANCE (CSA). *Top Threats to Cloud Computing*.

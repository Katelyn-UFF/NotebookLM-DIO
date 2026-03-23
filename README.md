# NotebookLM-DIO
Miniguia de Estudos: Inteligência Artificial no Suporte Nível II Repositório dedicado à estruturação de conhecimento técnico e otimização de troubleshooting utilizando o NotebookLM. Foco em redução de MTTR, curadoria de fontes técnicas e engenharia de prompts aplicada ao dia a dia de um Analista de Suporte.

# 🚀 Suporte Inteligente: Miniguia de Troubleshooting com NotebookLM

## 📌 Contexto e Objetivos
Como **Analista de Suporte II**, lido diariamente com incidentes que exigem consultas rápidas a manuais extensos e logs complexos. Este repositório documenta a criação de um ecossistema de estudo e consulta semântica utilizando o **NotebookLM** para otimizar o suporte técnico.

**Objetivos do Projeto:**
* **Redução de MTTR (Mean Time To Repair):** Localizar soluções em segundos, não minutos.
* **Centralização de Conhecimento:** Unificar manuais de fabricantes e wikis internas.
* **Treinamento Técnico:** Facilitar o onboarding de novos membros da equipe através de resumos estruturados.

---

##  Link do Projeto
Você pode interagir com a base de conhecimento construída através do link abaixo:
* **NotebookLM - Guia de Estudos:** [Visualizar Notebook](https://notebooklm.google.com/notebook/ed36dec7-3dca-426f-901b-f5c9f6b5d1fc)

---

##  Curadoria de Fontes
Para alimentar o NotebookLM, selecionei fontes que representam o ecossistema real de um suporte de Nível II:

1.  **Manual Técnico Oficial (PDF):** A fonte da verdade do fabricante.
2.  **Wiki de Erros Conhecidos (Texto):** Notas de campo e "pulos do gato" da equipe de suporte.
3.  **Log de Erro Padrão (TXT):** Exemplos reais de logs de falha para treinamento de reconhecimento de padrões.
4.  **Best Practices Guide (PDF):** Guia de configuração recomendada para evitar incidentes.

---

##  Engenharia de Prompts e "Cicatrizes"
O diferencial de um profissional Nível II é o seu raciocínio. Abaixo, documento a evolução das minhas consultas para obter o melhor da IA:

### Evolução do Raciocínio (Prompting)
* **Prompt 1 (Nível I - Genérico):** *"Como resolvo erro de conexão no banco?"*
    * **Resultado:** Resposta muito ampla, sem contexto de rede.
* **Prompt 2 (Nível II - Técnico):** *"Com base no Manual de Administração, qual a porta padrão para o serviço X e quais as 3 causas mais comuns para o erro 'Connection Refused' em ambientes Linux?"*
    * **Resultado:** Resposta precisa, citando as páginas do manual e comandos de `netstat` e `iptables`.

### Troubleshooting da IA (Cicatrizes)
* **Dificuldade Encontrada:** A IA às vezes misturava versões do software.
* **Solução:** Ajustei o prompt para: *"Responda utilizando exclusivamente as informações da Fonte 1 (Versão 2.0). Ignore referências a versões anteriores."* ---

##  Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto
* **Arquitetura do Sistema:** Compreensão dos fluxos de dados e dependências.
* **Pontos Críticos de Falha:** Onde o sistema costuma "gargalar" sob carga.
* **Comandos de Diagnóstico:** Lista de comandos essenciais para validação rápida.

### 2. Glossário para o Suporte II
* **Latência:** Tempo de resposta entre a requisição e o processamento.
* **Idempotência:** Garantia de que repetir uma ação de correção não causará danos extras.
* **Provisionamento:** Capacidade de alocar recursos conforme a demanda.

### 3. Biblioteca de Prompts Reutilizáveis
> `Analise o log anexado e identifique se a causa raiz é falta de memória (OOM) ou timeout de aplicação.`
> `Crie um resumo de 'passos iniciais' para um Analista Nível I seguir ao receber um ticket sobre este tema.`

---

##  A Importância do NotebookLM no meu Dia a Dia
Inovar no suporte significa parar de "caçar palavras-chave" em PDFs de 500 páginas. O **NotebookLM** se tornou meu braço direito porque:
* **Evita Alucinações:** Ele fundamenta todas as respostas nas fontes que eu forneci.
* **Contexto de Negócio:** Posso subir a Wiki da minha empresa e ele entende as particularidades do nosso ambiente.
* **Agilidade:** Transforma horas de pesquisa em segundos de tomada de decisão técnica.

---
*Este material foi desenvolvido para o desafio de NotebookLM da plataforma DIO no bootcamp, Riachuelo - Cibersegurança e reflete meu compromisso com a melhoria contínua e inovação no suporte técnico.*

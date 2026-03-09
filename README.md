# Curso Básico de Agente de IA e Automações

## Ferramentas:
 - n8n
 - Gmail
 - Google Sheets

[Arquivo passo a passo do desenvolvimento](https://github.com/gracieleo/ai-and-automation-agent/blob/master/passos_criacao_projeto.pdf)


 ---


## Aula 1 - O que são agentes de IA?
- **Simples** \
Age conforme a sequencia de passos pré definidas por humanos.
- **Autonomos** \
Planeja e executa as próprias tarefas, recebe o objetivo final e executa.
  * Raciocinar - planejar a estratégia que tem que fazer para chegar ao objetivo final;
  * Agir - executa as ações com as ferramentas conectadas.

### RAG
É uma técnica que permite que as IAs (LLMs) consultem base de conhecimento externa.
- **R**etrival (Recuperar) - recupera informações de documentos que tem acesso;
- **A**ugmented (Aumentada) - recebe o prompt inicial e adiciona informação recuperada de documentos que tem acesso;
- **G**eneration (Geração) - LLM recebe o prompt incrementado com o novo contexto, modelo gera uma resposta mais precisa.

---


## Aula 2 - Criação de automação para envio de e-mail
Agente de IA Simples \
**Contexto:** uma agencia de marketing que trabalha com consultoria e cada consultor recebe um feedback de avaliação através de um formulário google forms que é preenchido pelo cliente e os dados encaminhados a uma planilha. \
**Objetivo:** Dispar um e-mail para o consultor todos os dias as 9:00h da noite sempre que sua nota média de avaliação for menor que 7. 

![fluxo automocao envio email](https://github.com/gracieleo/ai-and-automation-agent/blob/master/automacao_envio_email.jpg)

---

## Aula 3 - Criação de um Agente de IA

Transformar uma automação comum em um agente de inteligência artificial completo.\
Integrar uma IA ao seu fluxo automatizado para que ela leia feedbacks, gere análises e escreva e-mails automáticos com sugestões personalizadas.

![fluxo automocao agente ia](https://github.com/gracieleo/ai-and-automation-agent/blob/master/agente_ia.jpg)

---

## Aula 4 - Melhoramento do Agente de IA

Fazer o agente olhar para os dados de todos os consultores cadastrados na planilha, no passo anterior ainda estava pegando dados de apenas um consultor.

![fluxo automocao agente ia_melhoria](https://github.com/gracieleo/ai-and-automation-agent/blob/master/agente_ia_melhoria.jpg)


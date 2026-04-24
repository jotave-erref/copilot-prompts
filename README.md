# 🤖 Copilot Prompts — Biblioteca de Copilotos de IA

Coleção de prompts otimizados para transformar LLMs (ChatGPT, Claude, etc.)
em copilotos especializados de desenvolvimento.

## 🎯 O que é isso?

São 4 agentes com personalidades e regras distintas, prontos para usar
como System Prompts em qualquer chat de IA:

| Agente | Arquivo | Função |
|--------|---------|--------|
| 🛠️ **CODE** | [`code-agent.md`](Prompts/code-agent.md) | Implementa código pronto para o projeto |
| ❓ **ASK**  | [`ask-agent.md`](Prompts/ask-agent.md)   | Responde dúvidas sem alterar código |
| 📋 **PLAN** | [`plan-agent.md`](Prompts/plan-agent.md) | Planeja antes de codar |
| 📖 **STUDY**| [`study-agent.md`](Prompts/study-agent.md)| Tutor de aprendizado ativo |

## 🛠️ Stack atual

Os prompts estão adaptados para:
- **Backend:** Java 17 + Spring Boot 3 + Maven + Flyway + MySQL
- **Frontend:** React 18 + JavaScript
- **Testes:** JUnit 5 + Mockito

## 🚀 Como usar

1. Escolha o agente que precisa (CODE, ASK, PLAN ou STUDY)
2. Copie o conteúdo do arquivo `.md` correspondente
3. Cole como **System Prompt** ou **Custom Instructions** no seu chat de IA
4. Comece a conversar!

## 🔄 Como adaptar para outra stack

Os prompts têm uma seção `STACK (EDITÁVEL)` no topo.
Basta trocar as tecnologias para a sua realidade.

## 📄 Licença

MIT — use, modifique e compartilhe à vontade.



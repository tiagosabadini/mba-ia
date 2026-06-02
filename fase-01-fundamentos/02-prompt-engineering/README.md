# 02 - Prompt Engineering

> Meses 1–2 · Chain-of-Thought, few-shot, ReAct, estruturação de contexto.

Este módulo me surpreendeu bastante. Em vez de testar tudo no ChatGPT ou no Claude que já têm arquiteturas mais avançadas e "corrigem" prompts ruins automaticamente, rodei os experimentos em modelos locais via Ollama (LLaVA 7B, Mistral) para ver os efeitos das técnicas de forma mais "pura". A diferença de resultado entre um prompt mal estruturado e um bem estruturado fica muito mais evidente quando o modelo não tem rede de segurança.

---

## Cursos e conteúdos estruturados

| Recurso | Tipo | Idioma |
|---|---|---|
| [Asimov Academy - Módulo de Prompt Engineering](https://asimov.academy) | Curso | PT-BR |
| [DeepLearning.AI - ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) | Curso | EN |
| [Anthropic - Guia oficial de Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview) | Documentação | EN |
| [Learnprompting.org](https://learnprompting.org) | Guia | EN |

---

## Artigos e leituras técnicas

- [Zapier - Chain-of-thought (CoT) prompting: What it is and how to use it](https://zapier.com/blog/chain-of-thought-prompting/)
- [arXiv - ReAct: Synergizing Reasoning and Acting in LLMs](https://arxiv.org/abs/2210.03629)
- [Cursor - Agents Window (documentação)](https://cursor.com/pt-BR/docs/agent/agents-window) - como o Cursor estrutura contexto e instruções para o agente
- [Anthropic Blog - Improving frontend design through skills](https://claude.com/blog/improving-frontend-design-through-skills)
- [Skills for Claude Code: The Ultimate Guide from an Anthropic Engineer](https://medium.com/@tort_mario/skills-for-claude-code-the-ultimate-guide-from-an-anthropic-engineer-bcd66faaa2d6)
- [LinkedIn - Skills no Claude Code: guia definitivo](https://www.linkedin.com/pulse/skills-claude-code-o-guia-definitivo-para-quem-quer-parar-eric-luque-kosuf/)

---

## Conteúdo produzido

Posts e série de anotações escritos a partir do que aprendi neste módulo:

- [Engenharia de prompt: o nome chique pra se comunicar direito](https://tiagosabadini.substack.com/p/engenharia-de-prompt-o-nome-chique?utm_source=github)
- [Post 1: 3 prompts pra descobrir se sua ideia de negócio tem futuro](https://tiagosabadini.substack.com/p/3-prompts-pra-descobrir-se-sua-ideia?utm_source=github)
- [Post 2: Defina ICP, Persona e Jornada de Compra. Com 3 prompts prontos pra usar](https://tiagosabadini.substack.com/p/defina-icp-persona-e-jornada-de-compra?utm_source=github)
- [Sabe o seu histórico de bugs e decisões ruins? Isso pode virar vantagem agora.](https://tiagosabadini.substack.com/p/sabe-o-seu-historico-de-bugs-e-decisoes?utm_source=github)

---

## O que ficou de verdade

- Testar em modelos locais menores (LLaVA 7B, Mistral) foi a melhor decisão deste módulo. 
  Modelos pequenos conseguem simular raciocínio com CoT, seguem o processo, mas entregam 
  resultado errado quando o conhecimento simplesmente não está no modelo. Isso deixa muito 
  claro o que é técnica de prompt e o que é capacidade do modelo. Nos modelos grandes essa 
  distinção fica mascarada.

- ReAct foi o experimento mais revelador. Ver um modelo pequeno expandir sua capacidade 
  real através de raciocínio + ação deixou claro por que isso importa em aplicações. 
  Não é só uma técnica acadêmica.

- Prompt engineering não é só para usar Claude ou ChatGPT no dia a dia. É a base de 
  qualquer aplicação que chama uma LLM. A qualidade do prompt é a qualidade do output, 
  isso vale tanto para uma interface quanto para um sistema em produção.

- Construir bem um prompt é estender sua capacidade de produção. Não é atalho, 
  é alavanca e tem limite onde começa o fine-tuning.

---

## Possíveis projetos

- Construção do modelo de negócios a partir de uma ideia, com ajuda de prompts. Escrevi a série **Empreendendo com o poder da Inteligência Artificial**. Os artigos estão na listagem mais acima.


---

*Módulo concluído: maio–junho 2026*

# Mine-Guia engenharia de prompt e otimiza o de tokens

**Fontes:** 
- [6 Técnicas pra Gastar Menos Tokens com IA 2026](https://www.youtube.com/watch?v=aGEPDVA38SM)
- [Design de Prompt: Introdução a Engenharia de Prompt - @CursoemVideo Inteligência Artificial](https://www.youtube.com/watch?v=ATp4Q4UD-c8)
- [Engenharia de Prompt: O Guia Definitivo](https://www.youtube.com/watch?v=1VDcke66TRE)
- [O que é engenharia de prompts? - IBM](https://www.ibm.com/br-pt/think/topics/prompt-engineering)

**Prompt usado:**
```bash
Sou estudante do 2o semestre de ciência da computação. Baseado nas  fontes passadas, crie um mine-guia de estudos de engenharia de prompt e otimização de tokens. O guia deve conter um pequeno dicionário de termos técnicos aplicado durante o guia
```

# 📘 Dicionário de Engenharia de Prompt

## Engenharia de Prompt
É a ciência de **planejar, criar e testar instruções (prompts)** para obter as melhores respostas das IAs.  
Pode ser comparada ao ato de **ensinar uma tarefa específica a um amigo muito inteligente**, fornecendo as orientações corretas.

---

## Prompt
É a **pergunta ou instrução** que você envia para a inteligência artificial.  
Pode ser **simples**, como uma frase, ou **complexo**, com vários parágrafos de instruções.

---

## Tokens
São a **“moeda” das IAs**.  
Em vez de ler palavras inteiras, a IA processa **pedaços de palavras**, como se fossem sílabas ou identificadores numéricos.

- Em português, **aproximadamente 3 caracteres ≈ 1 token**.

---

## Input e Output
- **Input:** sua pergunta ou instrução enviada para a IA (entrada de dados).
- **Output:** a resposta gerada pela IA (saída).

💡 **Curiosidade:** o *output* costuma ser **até 5 vezes mais caro** que o *input* em termos de processamento.

---

## Janela de Contexto (Context Window)
É o **limite máximo de tokens** que a IA consegue processar de uma vez.

Funciona como a **memória de curto prazo** do modelo.  
Se a conversa ficar longa demais, a IA pode **começar a esquecer informações do início**.

---

## Stateless (Sem Estado)
Significa que a IA **não possui memória própria entre mensagens**.

Cada nova pergunta exige que o modelo **releia todo o histórico da conversa** para entender o contexto.

---

## Persona
Técnica onde você define um **papel ou personagem** para a IA atuar.

Exemplos:

- "Aja como um especialista em marketing."
- "Você é um programador experiente."

Isso ajuda a **direcionar o tom, estilo e precisão da resposta**.

---

## Zero-shot vs Few-shot

### Zero-shot
Você faz uma pergunta **sem fornecer exemplos anteriores**.

### Few-shot
Você fornece **alguns exemplos ("shots")** antes da pergunta para que a IA **entenda o padrão desejado**.

---

## Cadeia de Pensamento (Chain of Thought – CoT)
Consiste em **instruir a IA a pensar passo a passo**.

Essa técnica melhora significativamente o desempenho em tarefas que exigem **lógica, cálculo ou raciocínio complexo**, como:

- Matemática
- Problemas lógicos
- Análise jurídica

---

## Alucinação (Hallucination)
Ocorre quando a IA **inventa informações incorretas**, mas as apresenta de forma convincente.

Pode ser reduzido ao:

- Pedir respostas **baseadas em fatos**
- Permitir que a IA diga **"não sei"**
- Fornecer **fontes ou contexto confiável**

---

## Roteamento Inteligente (Smart Routing)
Estratégia de **escolher o modelo de IA adequado para cada tarefa**.

Exemplos:

- **Tarefas simples:** resumo de e-mails → modelos mais baratos  
- **Tarefas complexas:** arquitetura de software → modelos premium

Isso ajuda a **reduzir custos e aumentar eficiência**.

---

## Markdown
Formato de texto estruturado que usa **símbolos para organizar conteúdo**.

Exemplos:

- `#` para títulos
- `**texto**` para negrito
- listas e seções

Organizar prompts em **Markdown melhora a interpretação da IA**.

---

## RAG (Retrieval-Augmented Generation)
Técnica em que a IA **consulta uma base de dados externa** antes de responder.

Exemplos de fontes:

- PDFs
- Bancos de dados
- Documentação interna
- Sites

Assim, a IA responde **com base em dados atualizados**, e não apenas no treinamento original.

---

## Temperatura
Parâmetro técnico que controla **o nível de criatividade da IA**.

- **Temperatura baixa:** respostas mais **precisas e factuais**
- **Temperatura alta:** respostas mais **criativas e variadas**

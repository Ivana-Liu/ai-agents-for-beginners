## What are AI Agents?
AI Agents are **systems** that enable Large Language Models(LLMs) to perform actions by extending their capabilities by giving LLMs access to tools and knowledge.

```
LLM (for reasoning)
  ├──> Memory (short or long)
  └──> Tools
          ↓
      perform tasks
```

```mermaid
graph TD
  LLM[LLM (for reasoning)] --> Memory[Memory (short or long)]
  LLM --> Tools
  Memory --> Tasks[perform tasks]
  Tools --> Tasks


### system
- environment
- sensors: environments' info
- actuators: action
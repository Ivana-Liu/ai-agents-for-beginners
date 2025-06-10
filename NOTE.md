### What are AI Agents?
AI Agents are **systems** that enable Large Language Models(LLMs) to perform actions by extending their capabilities by giving LLMs access to tools and knowledge.

```
LLM (for reasoning)
  ├──> Memory (short or long)
  └──> Tools
          ↓
      perform tasks
```

#### system
- environment
- sensors: environments' info
- actuators: action

development:
Jan. operator
Feb. deep research 
Mar. manus
5.6 windsurf

scrapybara   

cursor/windsurf: priority: context engine, deep understanding of env.    

展望：    
- 大厂占据主要pipe, 门槛降低但是只能占据小pipe; prediction: 大厂ai-agent building **platform**, others create agents on it; 类似内容创作     
- 看好coding ai: Through MCP, realize manus-like    
- Evaluation is more important than training(human/code-base/LM-base);continuely iteration
  - structured evaluation frame/refer to general reward to parallel

manus example: create websites/slides;   
shallow research to new areas-->demonstrate by websites    
对齐度很好：可以随时跟进度+记住history指令   

局限性：数据壁垒    
- e.g. personal social media    
- 隐形数据: e.g. coffee chat人的微表情

根本原因：coding capability: sonnet


mino os; secondme: build agents

from interacting with ppl -> interact w/ env(coding&reasoning model appears)

### learning example: semantic kernel
- kernel  
Def: manages all of the services and plugins necessary to run your AI application.   
  - Services: AI services (e.g., chat completion) and other services (e.g., logging and HTTP clients) that are necessary to run your application.  
  - Plugins/functions/tools: AI services, for example, can use plugins to retrieve data from a database or call an external API to perform actions.  
  e.g.  
  ``` python
  #kernel
  from semantic_kernel import Kernel
  #service
  from semantic_kernel.connectors.ai.open_ai 
  import AzureChatCompletion
  #plugins
  from semantic_kernel.core_plugins.time_plugin import TimePlugin
  ```  
- Thread and messages.  
  - keep track of the history of messages from a particular conversation.  
  - It represents a conversation or interaction between an agent and a user. Threads can be used to track the progress of a conversation, store context information, and manage the state of the interaction.   

### tool use design
def.: 
- Tools are interesting because they allow AI agents to have a broader range of capabilities.   
- Tools are code that can be executed by an agent to perform actions.  



## What are AI Agents?
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

mino os; secondme: build agents

from interacting with ppl -> interact w/ env(coding&reasoning model appears)

### learning example: semantic kernel
- kernel
Def: manages all of the services and plugins necessary to run your AI application. 
  - Services: AI services (e.g., chat completion) and other services (e.g., logging and HTTP clients) that are necessary to run your application.  
  - Plugins: AI services, for example, can use plugins to retrieve data from a database or call an external API to perform actions.  
  e.g.  
  ```
from semantic_kernel import Kernel
from semantic_kernel.connectors.ai.open_ai import AzureChatCompletion
from semantic_kernel.core_plugins.time_plugin import TimePlugin
```  

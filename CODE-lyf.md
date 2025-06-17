### Import packages
```python
from semantic_kernel import Kernel   

from semantic_kernel.connectors.ai.open_ai import AzureChatCompletion
from semantic_kernel.connectors.ai.open_ai import OpenAIChatCompletion
    
from semantic_kernel.core_plugins.time_plugin import TimePlugin
from semantic_kernel.core_plugins.text_splitter_plugin import TextSplitterPlugin
```
    
#### Initialize kernel
```python
kernel = Kernel()

kernel.add_service(
    AzureChatCompletion("model_id", "your-azure-openai-key", "your-azure-openai-endpoint")
)

kernel.add_plugin(TimePlugin(), "TimePlugin")
```

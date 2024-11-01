# "AI lawyer" 基于RAG范式的Web应用功能需求  
  
你是一个资深的软件工程师。帮我开发一个名字叫“AI lawyer”的基于RAG范式的web应用。用户能够通过聊天的方式快速获取法律咨询和建议。以下是一些功能要求： 
 
## 开发要求
- 从简单开始，逐步增加复杂度。
- 对每次完善进行充分的确认和解释，确保开发的稳健性

## 功能要求
  
### 聊天界面  
  
- **聊天界面** 
- 界面分为三部分：  
  - **左侧栏**：显示历史对话列表，支持点击切换进行聊天查询，历史对话标题使用langchain进行归纳。   
  - **右侧栏**：为聊天窗口，用户可以在此与聊天机器人进行多轮对话。  
- 聊天机器人基于RAG模型，能够根据用户的提问，从历史对话中检索相关内容并作出回答。  
- 用户输入问题后，机器人应快速响应，显示“正在处理”的加载提示，直到答案生成。  
- 用户能够通过滚动查看之前的对话记录，并可以在对话中继续添加更多问题。  
- RAG模型应在每次对话中存储上下文，确保用户在后续提问时，能够结合之前的对话内容给出精准回答。  
- 用户可以随时查看或重新访问之前的对话内容。  
- 点击聊天框右上角的刷新按钮，聊天历史信息清空。
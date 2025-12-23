# ai-app-examples

《人工智能基础》应用开发案例库。



# 目录说明

每个目录单独存放一个完整的可运行项目，请阅读每个目录下的 `README.md` 文件，了解项目介绍和运行方法。

> 建议按照顺序学习，内容是按照后一个继承前一个的模式由浅入深安排的。

- [01-chatbot-cli](./01-chatbot-cli)：一个基于命令行界面的最简聊天机器人。
- [02-chatbot-cli-stream](./02-chatbot-cli-stream)：流式输出改进版本。
- [03-chatbot-cli-langchain](./03-chatbot-cli-langchain)：引入 LangChain 框架的重构版本。
- [04-chatbot-ui](./04-chatbot-ui)：带 Web UI 界面的版本，含服务端（Express）和前端（React/Vite）的 SSE GET/POST 实现。
- [05-chatbot-ui-websearch](./05-chatbot-ui-websearch)：添加联网搜索功能（Workflow 范式）。
- [06-chatbot-ui-agent](./06-chatbot-ui-agent)：联网搜索的 Agent 版本（Agentic 范式）。
- [07-chatbot-ui-langgraph](./07-chatbot-ui-langgraph)：引入 LangGraph 框架的重构版本。

<!--
- [08-coding-agent](./08-coding-agent)：自动写简单前端项目（HTML/CSS/JS）的编程工具（LangGraph + ReAct）（WIP）。 -->

# 环境准备

此代码库包含前后端案例，为了避免引入复杂的环境配置，统一采用前端技术栈。

你需要准备好以下环境：

- Node.js >= v22.x
- 建议使用 Linux/macOS 系统，使用 Windows 的同学如果遇到问题请提交 issue。

然后，在根目录下执行以下命令，安装公共依赖包：

```bash
npm install
```


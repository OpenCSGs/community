# 贡献者指南

欢迎来到 CSGHub，感谢您对本项目的关注与支持！  

CSGHub 是一个开源、可信的大模型资产管理平台，旨在帮助用户管理 LLM 及其应用生命周期中涉及到的资产（数据集、模型文件、代码等）。CSGHub 提供可私有化部署的类 Hugging Face 平台功能，以类似 GitLab 管理源代码、OpenStack Glance 管理虚拟机镜像、Harbor 管理容器镜像以及 Sonatype Nexus 管理制品的方式，实现对 LLM 资产的管理。  

## 贡献流程

如需为本项目贡献内容，请遵循`“Fork & Pull request”`流程。除非您是维护者，请勿直接向主仓库推送代码。  

1. 从 GitHub 上 Fork 此仓库（<https://github.com/OpenCSGs/csghub>）到您的 GitHub 账号。  
2. 在 Fork 的仓库中进行所需的更改。  
3. 在 Fork 仓库中创建一个新分支来保存您的修改。建议以 `main` 分支为基础创建。  
4. 在新分支中进行必要的更新。  
5. 完成更改后，向原始仓库的 `main` 分支提交一个 Pull Request（PR）。  
6. 维护者将审查您的 PR，提供反馈并与您讨论。  
7. 完成必要的修改和讨论后，您的 PR 将被合并到 `main` 分支中。  

请确保您的贡献符合以下要求：  

- 保持代码风格一致。  
- 新功能或改进应进行相应的测试。  
- 添加或修改的文档应清晰易读，以便其他开发者理解和使用。  

## 报告问题和提出建议

如果您遇到任何问题、想要提出改进建议或请求新功能，请在我们的 [Issues](https://github.com/OpenCSGs/csghub/issues) 页面上提交。我们会定期查看并回应您的反馈。  

在报告问题或提出建议时，请遵循以下准则：  

- 提供尽可能详细的信息。明确描述问题、故障情况以及错误信息。`“XY 不工作”`这样的描述不利于问题排查。请务必包含您运行的代码，并尽可能提取相关部分而非整个脚本，以帮助我们复现问题。  
- 如果需要包含较长的代码块、日志或回溯信息，请使用 `<details>` 和 `</details>` 标签将内容折叠，以便于阅读和跟踪。更多关于内容折叠的信息，请参考[此链接](https://developer.mozilla.org/en/docs/Web/HTML/Element/details)。  

## 问题标签

关于用于标记问题和 Pull Requests 的标签系统概述，请参考[此页面](https://github.com/OpenCSGs/csghub/labels)。  

## 本地开发

您可以使用 [Docker Compose](https://github.com/OpenCSGs/csghub-installer/blob/main/docs/cn/docker_compose_installation.md) 或 [本地环境](https://github.com/OpenCSGs/csghub/blob/main/docs/setup.md) 来进行 CSGHub 的开发。  

感谢您对 CSGHub 项目的贡献！我们期待您的参与和宝贵建议。  

# jittor_reproduction_of_Responsibility-Attribution-for-Poisoned-Knowledge-in-RAG

本项目是对论文《Who Taught the Lie? Responsibility Attribution for Poisoned Knowledge in Retrieval-Augmented Generation》的复现分别使用pytorch，jittor框架进行复现
## 论文简介
论文提出了 RAGOrigin，这是一种黑盒归因框架 。这意味着它不需要访问 LLM 的内部参数或梯度，仅通过观察系统的输入和输出来识别中毒文档
核心机制：黑盒归因：利用相似度得分（similarity score）等指标来评估文档与生成内容之间的关联；动态环境适应性：RAGOrigin 被设计为可以在动态变化的知识库中有效工作;清理与防御：一旦识别出中毒文档，系统可以将其移除，从而修复 RAG 系统的知识库并防止未来的错误生成
## 环境配置


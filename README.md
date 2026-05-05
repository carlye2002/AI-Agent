# AI-Agent
我构建了一个 AI 简历优化与面试模拟 Agent Demo，主要解决求职者在简历修改、岗位匹配和面试准备中的低效率问题。用户可以上传简历或粘贴简历文本，并输入目标岗位 JD。系统会自动分析简历与岗位的匹配度，识别关键词缺口、项目表达问题和能力短板，并基于 STAR 法则生成简历优化建议。同时，Agent 会根据用户简历和岗位要求生成针对性面试问题，用户回答后，系统会从内容完整度、逻辑结构、岗位相关性、项目细节可信度和表达清晰度五个维度进行评分，并给出改进建议和参考回答。

该 Demo 采用简化版多 Agent 工作流，包括简历解析 Agent、岗位匹配 Agent、简历优化 Agent、模拟面试 Agent 和评分反馈 Agent。虽然部署为单文件应用，但内部通过不同提示词完成多阶段任务编排，能够展示完整的 AI 驱动求职辅导流程。该系统适合用于求职辅导、简历诊断、岗位投递前自检和面试训练场景。


如何运行demo？ 运行步骤：

打开终端，进入项目目录： 
Copy code to clipboard cd d:\project\giveme

安装依赖： 
Copy code to clipboard python -m pip install -r requirements.txt

启动 Demo： 
Copy code to clipboard python -m streamlit run app.py

浏览器会打开类似这样的地址： Copy code to clipboard http://localhost:8501 如果没有自动打开，就手动复制终端里显示的本地地址到浏览器。 使用方式： • 如果没有 OpenAI API Key，可以打开侧边栏的“演示模式”，跑通页面流程。 • 如果要真实调用 AI，需要在侧边栏输入你的个人 OpenAI API Key。 • 点击“填入示例数据”，再依次进入“简历分析”“模拟面试”“报告与日志”即可演示完整流程。

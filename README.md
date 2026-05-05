# AI-Agent
单文件简化版 Demo：简历诊断 + 岗位匹配 + 简历优化 + 模拟面试 + 回答评分
如何运行demo？
运行步骤：
1. 打开终端，进入项目目录：
Copy code to clipboard
cd d:\project\giveme
2. 安装依赖：
Copy code to clipboard
python -m pip install -r requirements.txt
3. 启动 Demo：
Copy code to clipboard
python -m streamlit run app.py
4. 浏览器会打开类似这样的地址：
Copy code to clipboard
http://localhost:8501
如果没有自动打开，就手动复制终端里显示的本地地址到浏览器。
使用方式：
• 如果没有 OpenAI API Key，可以打开侧边栏的“演示模式”，跑通页面流程。
• 如果要真实调用 AI，需要在侧边栏输入你的个人 OpenAI API Key。
• 点击“填入示例数据”，再依次进入“简历分析”“模拟面试”“报告与日志”即可演示完整流程。

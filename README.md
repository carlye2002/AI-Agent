# AI-Agent
我构建了一个 AI 简历优化与面试模拟 Agent Demo，主要解决求职者在简历修改、岗位匹配和面试准备中的低效率问题。用户可以上传简历或粘贴简历文本。

该 Demo 采用简化版多 Agent 工作流，包括简历解析 Agent、岗位匹配 Agent、简历优化 Agent、模拟面试 Agent 和评分反馈 Agent。虽然部署为单文件应用，但内部逻辑完整清晰。


## 如何运行demo？

### 运行步骤：

**1. 打开终端，进入项目目录：**

```bash
cd d:\project\giveme
```

**2. 安装依赖：**

```bash
python -m pip install -r requirements.txt
```

**3. 启动 Demo：**

```bash
python -m streamlit run app.py
```

**4. 访问应用：**

浏览器会自动打开应用地址，如果没有自动打开，请手动复制终端中显示的本地地址到浏览器：

```
http://localhost:8501
```

### 使用方式：

• 上传或粘贴简历文本
• 输入目标岗位信息
• 获取简历优化建议
• 进行模拟面试练习
• 查看面试反馈和评分

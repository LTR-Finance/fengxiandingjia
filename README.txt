X-Bank RiskQuote HTML Demo 使用说明

文件：
- index.html：可直接打开的静态 HTML Demo，无需后端、无需安装依赖。

本地演示：
1. 双击 index.html。
2. 浏览器打开后，按 F11 进入全屏。
3. 现场点击“生成治理报价单”，并调整滑块或控制包。

部署到 GitHub Pages：
1. 新建或打开你的 GitHub 仓库。
2. 上传 index.html 到仓库根目录。
3. 进入 Settings → Pages。
4. Source 选择 Deploy from a branch。
5. Branch 选择 main / root，点击 Save。
6. 等待 1-3 分钟，GitHub 会生成访问链接，通常格式为：
   https://你的用户名.github.io/仓库名/
7. 把这个链接粘贴到 PPT 的“在线交互 Demo”按钮上。

PPT 中添加超链接：
1. 在 PPT 上选中“▶ 在线交互 Demo”按钮或形状。
2. 按 Ctrl + K / Command + K。
3. 粘贴 GitHub Pages 链接。
4. 进入放映模式测试点击是否能打开浏览器。

建议演示默认参数：
- 事件影响金额：4000 万
- 年发生概率：20%
- 风险偏好阈值：300 万/年
- 审计证据完整度：40%
- 四个治理控制包全部勾选

一句话讲法：
RiskQuote 不是问 AI 治理值不值得投，而是回答：这个风险现在值多少钱，最低花多少钱治，治完还剩多少风险。

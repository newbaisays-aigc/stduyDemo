# V2.2 Open Source Edition

这是从 `V2.2-stable` 拆出的开源演示版，保留界面、结构化编辑、后端保存与导入导出流程，但不包含真实真题校对数据。

## 特点
- 保留题库结构、试卷结构、编辑与保存逻辑
- 保留本地后端接口与静态服务方式
- 仅附带少量演示数据，便于 GitHub 用户直接运行
- 不包含你已校对过的真题正文、答案库和图片资源

## 目录说明
- `people-knowledge-graph-V2.2-open.html`：公开版入口
- `server.py`：公开版服务入口
- `README-open-source.md`：公开版说明

## 运行方式
- 先启动 `server.py`
- 浏览器打开 `http://127.0.0.1:8000/people-knowledge-graph-V2.2-open.html`

## 开源边界
- 真实试卷、手工校对答案、上传图片和私有资料请不要放入公开仓库
- 如需二开，可在演示数据基础上自行替换为合规内容

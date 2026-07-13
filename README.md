# 🏪 二房东门面租赁账期催缴系统（演示版）

> ⚠️ **本仓库为演示版本，所有数据均为虚构实验数据，不包含真实信息。**

## 功能
- 门面管理（增删改查）
- 房东合同管理
- 租户合同管理
- 租期提醒（租户付款提前3天提醒，房东付款提前5天提醒）
- 微信推送通知（Server酱）

## 部署

### PythonAnywhere
1. 上传文件到 PythonAnywhere
2. 配置 WSGI 文件
3. 安装依赖：`pip install flask requests`

### 本地运行
```bash
pip install flask requests
python app.py
```

## 技术栈
- Python 3 + Flask
- SQLite
- Server酱 / PushDeer 微信推送

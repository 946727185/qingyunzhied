# 批量格式化节点名称

>使用 CF worker 部署

## 环境变量

- LINK_RENAME = 自定义名称后缀，如`Yutian81专用`
- BG_IMG = 前端页面背景图直链，如：`https://raw.githubusercontent.com/yutian81/abcabc/main/picbed/vpscheck_beijing.jpg`

## 使用方法
- 在上方输入框填入节点或订阅，支持批量格式化多条
- 点击格式化按钮，下方输入框将显示base64编码后的节点内容
- 复制输入框内容导入 v2rayN 客户端即可
- 默认显示国旗、国家代码、自定义后缀，即时取消所有勾选，也会显示国家代码

![image](https://github.com/user-attachments/assets/c64e8445-fbd3-47fb-899d-26b13b891119)

**注意**：不支持clash类订阅；不支持直接输入base64编码的节点

## 支持的协议
vless、vmess、hysteria2、tuic、ss、trojan

## 支持API
- 可以直接使用浏览器访问 `https://项目域名/sub/vless节点链接` 格式化单个节点的名称
- 或者访问 `https://项目域名/sub/https订阅链接` 批量格式化整个订阅的节点名称

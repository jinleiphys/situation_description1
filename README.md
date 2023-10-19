## Openai的账户免费额度到期，目前充值困难，暂停服务



# 部署ChatGPT网页版教程

## 基本要求

该教程将向您说明如何部署： chatgpt 的网页版。首先，您需要获取 chatgpt 的 API Key。

## 步骤一：获取 API Key

1. 前往 OpenAI 官网 (https://openai.com) 并创建一个账号，如果已经有账号，可以忽略此步骤并直接登录。

2. 需要登录进入此页面："https://platform.openai.com/account/api-keys"。

3. 点击“创建新密钥(Create new secret key)”以生成新的 API Key。

4. 点击复制图标来复制您的 API Key，稍后会用到。

*注意：此处的 API Key 具有安全隐患，请妥善处理，切勿外泄。*

## 步骤二：下载并部署 Project

有两个GitHub项目可以选择：

1. https://github.com/Yidadaa/ChatGPT-Next-Web
2. https://github.com/binary-husky/gpt_academic

只需要选择一个即可。下面以第一个项目为例进行说明：

1. 将项目fork到您的GitHub帐号。

2. 访问Railway官网(https://railway.app)，选择使用 GitHub 账号登录。

3. 在 Railway 用户界面上，点击新建工程。

4. 搜索刚刚fork过来的仓库并选择。

5. 在部署设置中，将刚获取的 API Key 填入。

6. 完成设置后，点击部署。

部署完毕后，Railway 将会自动为您生成一个访问 URL，这意味着您的 chatgpt 网页版已成功部署。

## 步骤三：自定义域名

1. 如果您希望使用自定义域名访问您的网页版 ChatGPT，您需要在域名提供商网站（如 Godaddy）购买。

2. 如已经购买，记得将域名 DNS A 记录指向 Railway 提供的 IP 地址，只有这样用户才能通过您的自定义域名来访问您的 chatgpt 网页版。

3. 对于如何配置 DNS，您可以联系提供商的在线支持，他们会很乐意为您提供帮助。

完成上述步骤后，即可通过自定义域名访问您的 ChatGPT 网页版。
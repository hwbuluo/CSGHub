#### OIDC 配置
你所需要的 OIDC 相关的配置项如下：
1. 用于建立 OIDC connection
  - identifier: 客户端ID
  - secret：客户端密钥
  - authorization_endpoint: 授权接口
  - token_endpoint: 获取 access token 接口
  - userinfo_endpoint: 获取用户信息接口
  - redirect_uri: callback url
2. 用于登录注册
  - login_url: OIDC 登录入口
  - signup_url: OIDC 注册入口

可以通过两种方式提供 OIDC 配置项
1. 通过环境变量
- OIDC_IDENTIFIER
- OIDC_SECRET
- OIDC_REDIRECT_URI
- OIDC_AUTHORIZATION_ENDPOINT
- OIDC_TOKEN_ENDPOINT
- OIDC_USERINFO_ENDPOINT
- LOGIN_URL
- SIGNUP_URL
2. 通过管理员后台进行系统设置


# vscode-yapi-接口文档高效工具

[掘金 vscode-yapi 文章](https://juejin.im/post/5e9b07adf265da47d4057e26)

[插件设置，b站视频观看](https://www.bilibili.com/video/BV1AK411573W/)

[功能操作，b站视频观看](https://www.bilibili.com/video/BV1Je411s7mA/)

## 功能

### vscode-yapi（插件截图）

<img src="https://user-gold-cdn.xitu.io/2020/4/19/1719084dbb00436c?w=2878&h=1798&f=jpeg&s=491486"  width="800"/>

### 操作演示设置：GIF

<img src="https://user-gold-cdn.xitu.io/2020/4/19/171904d3b96f7634?w=1280&h=800&f=gif&s=4461251"  width="800"/>


## 版本说明

### 1.1.0

1: 插件设置，简化新增项目的操作（团队vscode-yapi里的操作会同步到yapi接口），去掉编辑操作，如下图：

<img src="https://user-gold-cdn.xitu.io/2020/4/23/171a59e53742ff18?imageView2/0/w/1280/h/960/format/webp/ignore-error/1" width="800"/>

2: 模板设置，打通openapi更新接口（团队vscode-yapi里的操作会同步到yapi接口）

<img src="https://user-gold-cdn.xitu.io/2020/4/23/171a59f16ba80a30?imageView2/0/w/1280/h/960/format/webp/ignore-error/1" width="800"/>

### 1.0.9

1: 插件设置，给项目列表增加（删除、添加、编辑）的操作，打通openapi更新接口

<img src="https://user-gold-cdn.xitu.io/2020/4/22/171a18570a625e37?w=2170&h=1538&f=png&s=364082" width="800"/>

### 1.0.8

1: api模版，增加复制模板的重复验证校验

2: 管理中心，增加根据输入yapi接口地址，点击 “查看接口文档” 按钮操作。

### 1.0.7

1: api模版，增加字段 yapi_url、yapi_domain

2: 接口文档页面，增加 “进入管理中心” 入口

3: 管理中心，增加了yapi地址快速查询接口操作。

### 1.0.6

1: 调整模板webview页面演示

2: api模板增加 api_method_camel 字段

案例： // cat_name: ${api.cat_name}, method: ${api.method}, create_time: ${api.current_date_time} \n export const ${api.api_method_camel} = (params, opts) => request(CONFIG.URL + ${api.path},params${(api.method==='POST')? ', { ...opts, method: "POST",emulateJSON: true }':''});

### 1.0.4

1: 更新文档

### 1.0.3

1: API模板增加 cat_name 【分类】 字段

### 1.0.2

1: 增加对（js、tsx、ts、jsx）文件格式的接口文档查看

2: 增加插件设置、功能操作的视频演示

### 1.0.1

1: 增加对（js、tsx、ts）文件格式的接口文档查看

### 1.0.0

1: 插件设置（包含了个性化的主题设置，以及包含yapi的入口配置：domain、token、id）

2: 模板设置（包含2个类型的模板：参数模板、api模板【亮点】）

3: 查看接口文档 (一键跳转到接口文档 【亮点】)

3: 管理中心（跨项目的选择导出不同的api模版【亮点】）
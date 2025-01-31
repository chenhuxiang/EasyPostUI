# EasyPostUI
WebApi接口测试工具 EasyPostUI.exe，是一个临时替代PostMan的WebApi调试小工具，绿色免安装单文件，支持Post和Get两种请求方式。

## 功能说明：
1. Post请求，自定义Header请求头信息，美化body-raw请求报文及响应报文。
2. Get请求，不限数量的参数
3. 保存记录，点击发送按钮后，会将请求报文和响应报文记录在本地，方便下次打开工具时查看。
4. 定时调用，支持指定间隔时长、多个并发次数的测试接口。

## 更新说明
### V1.6
1. 接口列表增加【克隆】功能。
2. 变量特征值界面增加 变量值的显示与修改。
3. 修复token特征值有时会失效的BUG

### V1.5
1. 自动提取响应报文中的特征值，存入常见变量列表中：token,cookie,session,account
2. 请求报文支持常见变量绑定{{token}},{{cookie}},{{session}},{{account}}, 自动关联上一接口响应报文中特征值
3. 支持转换curl格式地址

### V1.4
1. 增加导出Api文档的功能
2. 状态栏增加关于对话框，显示历史更新记录
3. 状态栏增加 临时缓存处，用于临时记录cookie、token信息

### V1.3
1. 修复接口调用报错：未能创建 SSL/TLS 安全通道
2. 优化界面，所有区域大小均可手动调整。
3. 保存历史接口调用的数据，并支持拖拽调整上下顺序。
4. 快速复制请求报文和响应报文。

### V1.2
1. 修复不显示500的内部错误
2. 增加定时调用功能

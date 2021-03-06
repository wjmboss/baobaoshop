## 更新日志

### v2.1.3.170316
- [优化]兼容php7
- [优化]部分服务层代码
- [优化]插件变量读取方式
- [优化]会员登陆、退出、注册的扩展性
- [优化]商品编辑后，我的咨询无商品信息的问题
- [优化]收货地址超过10个不显示
- [优化]后台订单详情显示问题
- [修复]发货导致下单时间显示错误的问题
- [修复]商品详情页分类名称显示错误的问题
- [修复]文章列表所属分类不显示的问题
- [修复]部分链接伪静态失效的问题
- [修复]付款后减库存未减库存的问题
- [修复]php7环境下安装字符集为空
- [其它]修复其它已知问题

### v2.1.2.170120
- [修复]前台注入漏洞
- [修复]商品列表页修改货号会改变商品名称的问题
- [修复]远程图片本地化没有正确返回地址的问题
- [修复]发货单货号显示不正常的问题
- [修复]发货短信中物流方式显示不正确的问题
- [优化]安装时增加数据库严格模式的检测
- [优化]手机号作为用户名时的登陆验证
- [优化]商品编辑里支持sku的重量、体积编辑
- [优化]编辑器支持图片空间
- [优化]商品属性被删除后，商品详情页显示错误的问题
- [优化]购买记录接口返回数据格式
- [其它]修复其它已知问题

### v2.1.1.161230
- [新增]运费模板
- [新增]全局设置增加付款后减库存设置
- [修复]微信手机支付充值后跳转到错误的页面
- [修复]微店diy导航链接被遮挡的问题
- [修复]文章标签分页失效的问题
- [修复]小能客服配置读取错误问题
- [修复]部分情况导致商品类型无法选择的问题
- [修复]后台确认付款时提示错误的问题
- [优化]用户订单显示问题
- [优化]插件列表现在支持显示插件扩展版本
- [优化]商品模块扩展机制
- [优化]wap端微信支付配置错误时的提示
- [优化]云平台绑定用户体验
- [其它]修复其它已知问题


### v2.1.0.161202
- [新增]附件管理
- [新增]后台订单详情页增加收货地址编辑
- [修复]商品编辑页颜色拾取器被遮挡的问题
- [修复]设计插件时插件详情有时保存错误的问题
- [修复]安装时mysql严格模式的兼容问题
- [修复]后台商品列表页上下架有时点击无效的问题
- [修复]移动端商品详情页在微信浏览器无法正常上拉的问题
- [修复]商品编辑页面规格过多时规格会被保存按钮遮挡的问题
- [修复]插件设计时排序无效的问题
- [修复]修改后台DIY微店导航出现多个二级导航后前台显示出错问题
- [优化]全站控制器和服务层和标签的调用及部分代码优化
- [优化]全站缓存机制
- [其它]修复其它已知问题

### v2.0.4.161028
- [新增]小能客服内置模块
- [修复]部分浏览器无法生成商品规格的问题
- [优化]后台diy公共模块新增“全部分类页”和“购物车页”链接
- [优化]商品详情页判断收藏的加载机制
- [优化]修改移动端公共底部版权信息
- [优化]部分页面logo没有限制大小的问题
- [其它]修复其它已知问题

### v2.0.3.161021
- [新增]后台站点设置中增加地区级数设置功能
- [修复]wap端商品详情图片因某些特殊样式无法正常显示的问题
- [修复]微点设置中的导航在前台显示错位的问题
- [修复]商品编辑流程中出现的部分问题
- [修复]商品详情页设置规格为颜色输出时显示错误的问题
- [优化]商品编辑流程重构
- [优化]增强后台表格的拓展性
- [优化]移动端商品列表页样式并新增橱窗样式，在后台可以选择使用哪一种样式
- [优化]修复商品分类描述里有特殊符号，导致后台移动端diy出问题
- [优化]增强站点下的表格拓展性
- [其它]修复其它已知问题

### v2.0.2.160926
- [新增]插件设计助手
- [新增]移动端diy首页图片导航、公告
- [新增]移动端微店导航设置
- [修复]移动端订单上拉有时会显示重复数据的问题
- [修复]收货地址添加编辑时的xss漏洞
- [修复]部分用户插件更新无效的问题
- [修复]部分余额支付时，取消订单后冻结金额未返还的问题
- [优化]现在支持通过支付流水号查询订单
- [优化]安装系统时，地区sql导入导致部分数据库链接超市的问题
- [优化]会员中心为您推荐连续切换时造成样式错乱的问题
- [其它]修复其它已知问题

### v2.0.1.160901
- [修复]立即购买结算订单时，选择收货地址导致价格出错的问题
- [修复]订单结算页选择发票后无法正常下单的问题
- [修复]微信手机充值不能正常进行的问题
- [修复]关闭商城后wap打开首页报错
- [修复]收藏商品跳转到错误链接的问题
- [其它]修复其它已知问题
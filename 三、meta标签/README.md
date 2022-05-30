三、meta 基础知识
h5 页面窗口自动调整到设备宽度，并禁止用户缩放页面

<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=no" />
# 忽略将页面中的数字识别为电话号码
<meta name="format-detection" content="telephone=no" />
# 忽略Android平台中对邮箱地址的识别
<meta name="format-detection" content="email=no" />
# 当网站添加到主屏幕快速启动方式，可隐藏地址栏，仅针对ios的safari
<meta name="apple-moblie-web-app-capable" content="yes" />

tips：
1、在不添加任何 meta 标签时，页面渲染宽度默认是 980px！layout viewport（布局视口）
2、加上 meta 标签，就可以适配手机端，并且网页同样适用。

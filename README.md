<h1>qq-xml-ip</h1>
通过QQ的xml卡片进行ip探测

- ~~因为现版本qq安全性更新导致伪造分享卡片的软件不能用了，所以用此方法需要配合xml代码转卡片的模块或者机器人使用~~（1.0版本改进）

- 启发：来自qq机器人的"谁在窥屏"功能
- 原理：利用qq加载xml卡片消息会自动访问xml卡片中的图片地址
- 注意：此方法获取的ip可能多达数个，注意区分腾讯服务器ip和真实目标ip

<h2>版本：</h2>

**0.1** 通过qq机器人或者转xml卡片插件发送ip探测卡片

**1.0 Beta** 不需要再使用转卡片模块，可通过iptest.html页面，在qq内打开，直接分享给对方xml卡片。此方法需要在iptest.php后跟一堆随机无效参数才行，不然会被qq直接转换，暂时还未清楚原因(注意:IOS端无法通过此方法发送卡片)

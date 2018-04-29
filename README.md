# export hj words
从网页版一键导出沪江生词本的单词，目前只支持单页导出 :disappointed:

# 安装
## 轻量级
将下面代码保存为书签
![添加书签](https://ecator.github.io/export-hj-words/img/tutorial-js-1.jpg)
```
javascript:(function(){var tm_s=document.createElement("script");tm_s.src="https://ecator.github.io/export-hj-words/index.user.js";document.body.appendChild(tm_s)})();
```
只需要在沪江词本页面点击这个书签即可出现**导出**按钮
![点击书签出现导出按钮](https://ecator.github.io/export-hj-words/img/tutorial-js-2.jpg)

## 猴油脚本安装
从[Greasy Fork](https://greasyfork.org/zh-CN/scripts/44563-export-hj-words)即可一键安装。

# 使用
脚本安装成功后会在沪江生词本的页面会有一个**导出**按钮
> 如果通过书签注入方式需要手动点击书签才会出现按钮

![导出按钮](https://ecator.github.io/export-hj-words/img/tutorial-tm-1.jpg)

点击导出按钮后耐心等待一段时间即可出现下载链接

![导出结果](https://ecator.github.io/export-hj-words/img/tutorial-js-2.jpg)

# 导出格式
一共导出以下三个字段，以制表符分隔，每条记录以换行符分隔
1. 单词本身
2. 音标
3. 简单释义
	- 释义字段包括html标签，所以如果需要将导出结果用于其他软件的导入需要支持html标签，比如Anki
	![anki import](https://ecator.github.io/export-hj-words/img/tutorial-anki-1.jpg)

# bug反馈
直接发issue或者在[Greasy Fork][https://greasyfork.org/zh-CN/scripts/44563-export-hj-words/feedback]进行反馈:smile:
# nhentai-download-as-zip
为 nhentai 本子页增加 zip 打包下载

![](https://i.loli.net/2018/12/26/5c23a39505d14.png)

如果你觉得下载速度太慢，可以尝试适当提高线程数

```javascript
(async function () {
	'use strict';
	const THREAD = 5; // 修改这个
```
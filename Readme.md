Modal for mobile

Get Start : https://hwgq2005.github.io/m-modal

<p align="left">
<a href="https://www.npmjs.com/package/m-modal"><img src="https://img.shields.io/npm/dt/m-modal.svg" alt="Downloads"> </a><a href="https://www.npmjs.com/package/m-modal"><img src="https://img.shields.io/npm/v/m-modal.svg" alt="Version"></a> <a href="https://www.npmjs.com/package/m-modal"><img src="https://img.shields.io/npm/l/m-modal.svg" alt="License"></a>
</p>

###Introduce
Modal for mobile

###Install
```
npm install m-modal  
```

###Usage
```
var Model = require('m-modal');
Modal({
	id:'modal',
	title:'提示',
	content:'确认执行此操作?',
	complete:function(){
		// do something ...				
	},
	confirm:function(){
		// do something ...
	},
	cancel:function(){
		// do something ...
	}
})
```
###CDN

- https://unpkg.com/m-modal/dist/css/modal.min.css
- https://unpkg.com/m-modal/dist/js/modal.min.js

###Contact

- Weibo：[@hwgq2005](http://www.weibo.com/hwgq2005) 
- Email：hbook@bookcss.com

###License
MIT
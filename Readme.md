Modal for mobile

Get Start : https://hwgq2005.github.io/modal-mobile

<p align="left">
<a href="https://www.npmjs.com/package/modal-mobile"><img src="https://img.shields.io/npm/dt/modal-mobile.svg" alt="Downloads"> </a><a href="https://www.npmjs.com/package/modal-mobile"><img src="https://img.shields.io/npm/v/modal-mobile.svg" alt="Version"></a> <a href="https://www.npmjs.com/package/modal-mobile"><img src="https://img.shields.io/npm/l/modal-mobile.svg" alt="License"></a>
</p>

###Introduce
Modal for mobile

###Install
```
npm install modal-mobile  
```

###Usage
```
var Model = require('modal-mobile');
new Modal({
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

- https://unpkg.com/modal-mobile/dist/css/modal.min.css
- https://unpkg.com/modal-mobile/dist/js/modal.min.js

###Contact

- Weibo：[@hwgq2005](http://www.weibo.com/hwgq2005) 
- Email：hbook@bookcss.com

###License
MIT
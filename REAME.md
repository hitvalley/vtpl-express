# vtpl-express

当前版本：1.0.2

ValleyTpl 应用于 Express 的插件

## 版本要求

* NodeJS > 8.0
* ValleyTpl > 1.1.2
* Express > 4.0

## 使用

安装

	npm i --save vtpl-express

使用

	app.set('view engine', 'vtpl');
	app.set('views', './views');
	app.set('view encoding', 'utf-8'); // 设定文件编码格式
	app.set('view cache', true); // 设定是否使用cache

	app.get('/', function(req, res){
	  res.render(tpl, data, filters);
	});


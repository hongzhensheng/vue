新建vue项目
	vue init webpack projectName
	
项目安装 npm 库
	在项目跟目录 npm install
	
启动项目
	npm run dev
	
安装vue-router 
	npm install --save vue-router
	官方文档 https://router.vuejs.org/zh/
	
	1.引用
	import VueRouter from 'vue-router'	
	Vue.use(VueRouter);
	
	2.配置路由
		var router = new VueRouter({
			routes:[
				{
					path:'/hello',
					name:'hello', //用于传参数使用
					component:HelloWorld,
				}
			],
		});
		
		new Vue({
		  /*注册*/
		  router
		})
		
	3.试图加载位置
		<router-view></router-view>


其他第三方组件
	element-ui
		https://element.eleme.cn/#/zh-CN/component/installation
	awesome-swiper
		https://github.com/surmon-china/vue-awesome-swiper
	vue-lazyload--懒加载
		https://github.com/hilongjw/vue-lazyload
	axios--网络请求
		http://www.axios-js.com/docs/
	mockjs--数据模拟
		https://github.com/nuysoft/Mock/wiki/Getting-Started

<script>
	export default {
		// 当uni-app 初始化完成时触发（全局只触发一次）
		onLaunch: function () {
			console.log('App Launch')
		},
		// 当 uni-app 启动，或从后台进入前台显示
		onShow: function () {
			console.log('App Show')
		},
		// 当 uni-app 从前台进入后台
		onHide: function () {
			console.log('App Hide')
		},
		// 对 nvue 页面发送的数据进行监听，
		onUniNViewMessage:function(){}
	}
</script>

<style>
	/*每个页面公共css */
</style>

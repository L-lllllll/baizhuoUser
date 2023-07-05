<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
button {
	background: none !important;
	border: 1px solid #fe402a !important;
}
button[type=primary] {
  background: #fe402a !important;
	border: none !important;
}
</style>

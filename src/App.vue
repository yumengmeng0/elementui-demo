<template>
	<div id="app">
		<div id="nav">
			<!-- <router-link to="/">Home</router-link> | -->
			<!-- <router-link to="/about">About</router-link> | -->
			<h1>element ui 组件的使用示例</h1>

			<table align="center" border="1" cellspacing="0" cellpadding="10">
				<tr>
					<th>组件</th>
					<th>示例</th>
					<th>官方地址</th>
				</tr>
				<tr>
					<td>时间选择组件</td>
					<td>
						<router-link to="/datetimepicker">DateTimePicker</router-link>
					</td>
					<td>
						<a href="https://element.eleme.cn/#/zh-CN/component/datetime-picker"
							>datetime-picker</a
						>
					</td>
				</tr>
			</table>
		</div>
		<!-- Home -->
		<router-view />
	</div>
</template>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}

#nav {
	padding: 30px;
}

#nav a {
	font-weight: bold;
	color: #2c3e50;
}

#nav a.router-link-exact-active {
	color: #42b983;
}
</style>

<template>

         <!-- value-format="yyyy-MM-dd HH:mm:ss" 能改变输出的时间格式 -->
	<div class="datetimepicker">
		<el-date-picker
			v-model="startTime"
			type="datetime"
            value-format="yyyy-MM-dd HH:mm:ss"
			placeholder="选择日期时间"
			@change="changeTime()"
		>
		</el-date-picker>
	</div>
</template>

<script>
export default {
	data() {
		return {
			startTime: null,
		};
	},
	methods: {
        changeTime(){
            console.log(this.startTime);
        }
    },
};
</script>

<template>
    <div class="fillcontain">
        <head-top></head-top>
        <p class="explain_text">INSUREMO REPORT 練習</p>
        <p class="explain_text">測試取得最新旅遊資訊</p>
        <p class="explain_text">增加兩個查詢條件</p>
        <p class="explain_text">顯示結果後並印出報表</p>
    </div>
</template>

<script>
	import headTop from '../components/headTop'
    export default {
    	components: {
    		headTop,
    	},
    }
</script>

<style lang="less">
	@import '../style/mixin';
	.explain_text{
		margin-top: 20px;
		text-align: center;
		font-size: 20px;
		color: #333;
	}
</style>

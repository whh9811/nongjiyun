<template>
	<view>
	<view class="content">
		<text style="color: #FFFFFF;text-align: center;">知识库</text>
	</view>
	<view class="knowledge">
		<view class="one">
			<view class="aa"><navigator url="../../pages/nine/zyhz">
				<image src="../../static/icon_zuwu.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">作物品种库</text>
			</navigator></view>
			<view class="aa"><navigator url="../../pages/nine/ysns">
				<image src="../../static/icon_zhibao.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">植保库</text>
			</navigator></view>		
		</view>
		<view class="one">
			<view class="aa"><navigator url="../../pages/nine/zyhz">
				<image src="../../static/icon_chuqin.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">畜禽品种库</text>
			</navigator></view>
			<view class="aa"><navigator url="../../pages/nine/ysns">
				<image src="../../static/icon_tufei.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">土肥库</text>
			</navigator></view>		
		</view>
		<view class="one">
			<view class="aa"><navigator url="../../pages/nine/zyhz">
				<image src="../../static/icon_zjtx.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">产业技术体系专家</text>
			</navigator></view>
			<view class="aa"><navigator url="../../pages/nine/ysns">
				<image src="../../static/icon_zhutui.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
				<text class="a" style="text-align: center;">主推技术库</text>
			</navigator></view>		
		</view>
	</view>
	</view>
</template>

<script>
</script>

<style>
	.content {
		display: flex;
		align-items: flex-end;
		justify-content: center;
		background: #32CD32;
		height: 150upx;
		border: 1px solid #32CD32;
	}
	.one{
		display: flex;
		align-items: center;
		justify-content: center;
		
	}
	.aa{
		width: 50%;
		height: 200upx;
		display: flex;
		flex-direction: column;
		align-content: center;
		text-align: center;
		justify-content: center;
		margin: 0 auto;
		border: 1px solid #ebebeb;
		border-right: none;
		border-top: none;
	}
	.aa image{
		/* padding-left: 70upx; */
		display: flex;
		padding-left: 70px;
		flex-direction: column;
		align-content: center;
		text-align: center;
		justify-content: center;
	}
	.a{
		display: flex;
		flex-direction: column;
		align-content: center;
		justify-content: center;
		/* margin-left: 40upx; */
		
	}
</style>

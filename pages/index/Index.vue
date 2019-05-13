<template>
	<view class="all">
		<view class="content">
			<view class="searchbar">
				<text style="color: #FFFFFF;">省版</text>
				<image src="../../static/abc_spinner_mtrl_am_alpha.png" style="width: 50upx;height: 50upx;"></image>
				<view class="q" style="display: flex;border: 1px solid #ebebeb;background: #FFFFFF;border-radius: 10upx;">
					<image src="../../static/icon_search_black.png" style="width: 40upx;height: 40upx;align-items: center;justify-content: center;"></image>
					<input type="search" placeholder="请输入搜索内容"></input>
				</view>
				<view class="img">
					<image src="../../static/btn_notice.png" style="width: 40upx;height: 50upx;"></image>
				</view>
				<image src="../../static/btn_speak_normal.png" style="width: 60upx;height: 50upx;"></image>
			</view>
		</view>
		<view class="advertising">
			<swiper catchtap="onSwiperTap" vertical="{{false}}" indicator-dots="true" autoplay="true" interval="5000">
				<swiper-item>
					<image src="../../static/guanggao1.JPG" data-postId="1" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao2.JPG" data-postId="2" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao3.jpg" data-postId="3" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao4.jpg" data-postId="4" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao5.jpg" data-postId="5" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao6.jpg" data-postId="6" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao7.jpg" data-postId="7" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
				<swiper-item>
					<image src="../../static/guanggao8.jpg" data-postId="8" style="width: 100%;height: 100%;margin: 0 auto;"></image>
				</swiper-item>
			</swiper>
		</view>
		<view class="data">
			
		</view>
		<view class="nine">
			<view class="one">
				<view class="aa">
					<navigator url="../../pages/nine/zyhz">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">专业合作</text>
					</navigator>
				</view>
				<view class="aa">
					<navigator url="../../pages/nine/ysns">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">应时农事</text>
					</navigator>
				</view>
				<view class="aa">
					<navigator url="../../pages/nine/nykj">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">农业科技</text>
					</navigator>
				</view>
			</view>
			<view class="one">
				<view class="aa">
					<navigator url="../../pages/nine/nyzj">
						<image src="../../static/icon_zjtx.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">农业专家</text>
					</navigator>
				</view>
				<view class="aa">
					<navigator url="../../pages/nine/nyzc">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">农业政策</text>
					</navigator>
				</view>
				<view class="aa">
					<navigator url="../../pages/nine/kjzx">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">科技专项</text>
					</navigator>
				</view>
			</view>
			<view class="one">
				<view class="aa">
					<navigator url="../../pages/nine/schq">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">市场行情</text>
					</navigator>
				</view>
				<view class="aa">
					<navigator url="../../pages/nine/xcly">
						<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
						<text class="a" style="text-align: center;">乡村旅游</text>
					</navigator>
				</view>
				<view class="aa">
					<image src="../../static/icon_more_11.png" style="width: 90upx;height: 90upx;text-align: center;"></image>
					<text class="a" style="text-align: center;">更多</text>
				</view>
			</view>
		</view>
		<view class="top">
			<view class="bb">
				<image src="../../static/icon_file.png" style="width: 50upx;height: 50upx;"></image>
				<text style="color: #DF7401;">头条</text>
				<text class="b" style="text-align: right;">更多>></text>
			</view>
		</view>
		<view class="dong">
			<view class="bb">
				<image src="../../static/icon_dynamic.png" style="width: 50upx;height: 50upx;"></image>
				<text style="color: #04B404;">动态</text>
				<text class="b" style="text-align: right;">更多>></text>
			</view>
		</view>
		<view class="video">
			<view class="bb">
				<image src="../../static/icon_play.png" style="width: 50upx;height: 50upx;"></image>
				<text style="color: #0174DF;">视频</text>
				<text class="b" style="text-align: right;">更多>></text>
			</view>
		</view>
</template>

<script>

</script>

<style>
	.content {
		display: flex;
		align-items: flex-end;
		justify-content: left;
		background: #32CD32;
		height: 150upx;
		border: 1px solid #32CD32;
	}

	.searchbar {
		display: flex;
	}

	.img {
		margin-left: 40upx;
		margin-right: 50upx;
	}

	.advertising {}

	.nine {
		/* display: flex;
		flex-direction: column; */
		border: 1px solid #EBEBEB;
	}

	.one {
		display: flex;
		align-items: center;
		justify-content: center;

	}

	.aa {
		width: 33%;
		height: 160upx;
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

	.aa image {
		/* padding-left: 70upx; */
		display: flex;
		padding-left: 43px;
		flex-direction: column;
		align-content: center;
		text-align: center;
		justify-content: center;
	}

	.a {
		display: flex;
		flex-direction: column;
		align-content: center;
		justify-content: center;
		/* margin-left: 40upx; */

	}

	.bb {
		display: flex;
		border: 1px solid #EBEBEB;
	}

	.b {
		text-align: right;
	}
</style>

<template>
	<view>
		<view class="title">
		  <!-- 箭头图标 -->
		
		  <view>
		    <image class="title-ime" src="http://www.lvketang.com/images/upload/websiteLogo/20190423/1555987578965.png"> </image>
		  </view>
		  <!-- 输入框 -->
		  <view style="margin-left: 170px;margin-right: 40px;padding:1px 25px;">
		    <viwe url="/pages/search/search" class="SearchInput">
		      <input style="float: left;" placeholder="请输入试卷名称"></input>
		      <view>
		        <icon type="search" size="20" class="home-sear" />
		      </view>
		    </viwe>
		  </view>
		
		  <!-- 图标 -->
		  <view class="mw">
		    <view class="mw-nav-btn">
		      <view class="mw-nav-icon"></view>
		    </view>
		  </view>
		</view>
		
		
		<view class='list'>
		
		  <view class="list-li-1">
		    <view class="pro-l-b-li-info-1">
		
		      <view class="in-art">
		        <view class="fsize18 c-333">
		          中国首款学习习近平重要讲话APP上线
		        </view>
		        <view class="bj-op">
		          <!-- <view class="bj">
		            <image class="icon-time-arct" src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1585802481888&di=58ffaff2349cfda4d43dfa831afa7d1f&imgtype=0&src=http%3A%2F%2Fpic.51yuansu.com%2Fpic2%2Fcover%2F00%2F35%2F34%2F58119ba6c87ec_610.jpg"></image>
		            编辑时间： 2018/01/09 07:52
		          </view> -->
		        </view>
		
		        <view class="xt"></view>
				<p style="border: 0px; margin: 0px; padding: 0px; font-size: 19px;margin-top: 22px;margin-left: 5px;margin-bottom: 7px; font-weight: bold;">
				法国总理证实失事客机无人生还</p>
		        <image class="xt-img" src="http://www.lvketang.com/images/upload/article/20150910/1441853275555.jpg"></image>
		
		      </view>
		
		      <view class="so">
		
				
				<span class="span-time" style="font-size: 15px;">
								  <div 
				style="margin-bottom: 10px;text-indent: 32px;line-height: 200%;font-family: 宋体">
									
					【环球网综合报道】德国汉莎航空公司旗下的德国之翼(Germanwings)一架A320客机，3月24日从巴塞罗那飞往杜塞尔多夫途中，在法国南部阿尔卑斯山脉坠机。			　　
								</div>
				        </span>
				<span class="span-time" style="font-size: 15px;">
								  <div 
				style=" margin-bottom: 30px;text-indent: 32px;line-height: 200%;font-family: 宋体">
							据美国《华盛顿邮报》3月24日报道，法国总理瓦尔斯称，一架直升机已尝试降落在坠毁地点附近，并未发现失事客机上有生还者。(实习编译：苏俏英 审稿：谭利娅)		
								
								</div>
								<div
											style="margin-bottom20px 32px;line-height: 200%;font-family: 宋体">
																
									
															</div>
				<p style="margin-top: 20px;">
						<div class=""></div>
						<div></div>
						<div></div>
						</span>
		      </view>
		
		    </view>
		  </view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		methods: {
			
		}
	}
</script>

<style scoped>
/* pages/MorES/MorES.wxss */
.list{
      background: #f5f5f5;
  width: 100%;
  height: 800px;
}
.list-li-1 {
  padding-top: 12px;
    width: 100%;
    margin-bottom: 14px;
}

.list-WO {
  padding-top: 12px;
    width: 100%;
    margin-bottom: 14px;
}
.pro-l-b-li-info-1 {
    margin-left: 4px;
   
    border: 1px solid #e9e9e9;
    position: relative; 
    margin-right: 4px;
    border-top: 0;
    height: 710px;
    padding-top: 3px;
    background: #fff;
}
.pro-l-b-WO {
    margin-left: 4px;
   
    border: 1px solid #e9e9e9;
    position: relative; 
    margin-right: 4px;
    border-top: 0;
    height: 145px;
    padding-top: 3px;
    background: #fff;
}
.pro-l-b {
    margin-left: 4px;
    border: 1px solid #e9e9e9;
    position: relative; 
    margin-right: 4px;
    border-top: 0;
    height: 200px;
    padding-top: 3px;
    background: #fff;
}
.title{
 
  background-color: #1e2432;
  height: 50px;
}
.SearchInput {
  display: flex;
  box-sizing: border-box;
 
  font: inherit;
  font-size: 13px;
  line-height: 24px;
  padding: 6px 16px;
  background: rgb(242, 242, 242);
  border: none;
  border-radius: 999px;
  outline: none;
  margin-top: -36px;
  
}
.home-sear {
  height: 10px;
 right: 1px;
  float: right
  
}

.mw-nav-btn {
    display: block;
    position: absolute;
    width: 30px;
    height: 30px;
    top: 9px;
    right: 8px;
}
.mw-nav-icon {
    width: 25px;
    height: 2px;
    background: #fff;
    margin-top: 5px;
}
.mw-nav-icon:before {
    content: '';
    width: 25px;
    height: 2px;
    background: #fff;
    position: absolute;
    top: 13px;
} 
.mw-nav-icon:after {
    content: '';
    width: 25px;
    height: 2px;
    background: #fff;
    position: absolute;
    top: 21px;
}
.title-ime{
  width: 90px;  
  height: 33.75px;
  margin-left: 9px;
  margin-top: 6px;
}
.fsize18 {
    font-size: 1rem;
}

.c-333 {
    color: #333;
}
.in-art{  
  margin: 10px;
  
}
.js{
    font-size: 0.7rem;
    color: #666;
    margin-right: 20px;
    margin-top: 7px;
    margin-left: 5px;
}
.bj{

  margin-top: 5px;
  color: #666;
  font-size: 0.7rem;
}
.icon-time-arct {
    display: inline-block;
    width: 17px;
    height: 17px;
	margin-right: 5px;
    vertical-align: middle;
    background-position: -380px -3px;
}
.bj-op{
  display: flex;
  
}
.xt{
  margin-top: 14px;
  border-bottom: 1px solid #e6ebf1;
}
.xt-img{
  margin-top: 16px;
   width: 100%;
   height: 232.36px;
} 
.so{
  line-height: 28px;
}

.span-time{
  margin-left: 18px;
 
}

.title-name{
  flex-direction: column;
}
.pro-info-b-title {
    height: 40px;
    border-bottom: 1px solid #e6ebf1;
}
.clearfix {
    display: block;
}
.o-img{
  width: 90px;
  height: 59.75px;
  float: left;
  margin-top: 13px;
  margin-left: 10px;
    margin-right: 10px;
}
.pro-info-b-title .title-name {
    font-size: 1rem;
    margin: 13px 0 0 10px;
        padding-left: 10px;
    border-left: 3px solid #ff662f;
    
    height: 18px;
    line-height: 16px;
    display: inline-block;
}
.c-333 {
    color: #333;
}
.name-imng{
   padding-top: 20px;
   font-size: 14px;
}
</style>

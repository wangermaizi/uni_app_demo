<template>
	<view>
		<view class="title">
		  <!-- 箭头图标 -->
		  
		  <!-- 输入框 -->
		  <view style="margin-left: 40px;margin-right: 40px;padding:1px 25px;">
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
		
		
		<view class="body-aa">
		
		  <!-- 分类 -->
		  <view class="view-ss">
		    <view class="clearfix">
		      <view class="mo">
		        <navigator class="la" href="javascript:void (0)">
		          <p class="tt-a">
		            地方导游基础知识</p>
		        </navigator>
		      </view>
		
		      <view class="mo">
		        <navigator class="la" href="javascript:void (0)">
		          <p class="tt-a">
		            最新</p>
		        </navigator>
		      </view>
		      <view class="mo">
		        <navigator class="la" href="javascript:void (0)">
		          <p class="tt-a">
		            筛选条件</p>
		        </navigator>
		      </view>
		    </view>
		  </view>
		
		  <!-- 导游 -->
		  <view class="list-ss-1">
		
		    <!-- 地方导游基础知识练习题 -->
		    <view class="list-li-1">
		      <view class="pro-l-b-li-info-1">
		        <image class="info-image" src="http://www.lvketang.com/static/exam/new_img/pro-li-top-bg.gif"></image>
		        <view class="li-info-top-1">
		            <h5 class="f-fM-1 fsize16-1 c-333-1 title-1">地方导游基础知识规练习题</h5>
		            <view class="nr-fl-warp-1">
		              <span class="f-fM-1 c-666-1 n-fl-boy-1 fsize12-1">题库</span>
		              <span class="f-fM-1 c-666-1 n-fl-boy-1 fsize12-1">可做次数： 无限次</span>
		              <span class="f-fM-1 c-666-1 n-fl-boy-1 fsize12-1">总题数：228题</span>
		            </view>
		        </view>
		        <view class="li-info-bottom-1">
		          <span class="c-master-1 fsize18-1 fl-1 jg-li-1">
		            免费
		          </span>
		          <navigator url="/pages/ops/ops" target="_blank" title="查看详情" class="details-btn-1">查看详情</navigator>
		        </view>
		      </view>
		    </view>
		
		     
		
		
		  </view>
		
		
		  <!-- 整体背景 -->
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
.title{
 
  background-color: #1e2432;
  height: 50px;
}
.SearchInput {
  display: flex;
  box-sizing: border-box;
 
  font: inherit;
  font-size: 16px;
  line-height: 24px;
  padding: 6px 16px;
  background: rgb(242, 242, 242);
  border: none;
  border-radius: 999px;
  outline: none;
  margin-top: 10px;
  
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
.body-aa{
  background: #f5f5f5;
  width: 100%;
  height: 735px;
}
.clearfix {
    display: block;
    background: #fff;
    width: 100%;
    height: 43px;
}
.mo {
    float: left;
    width: 33.33%;
    text-align: center;
    height: 40px;
}
.o{
  width: 40px;
}
.la {
    display: block;
    line-height: 40px;
    font-size: 0.8rem;
    color: #666;
}
.tt-a {
    line-height: 40px;
    font-size: 0.8rem;
    color: #666;
    display: inline-block;
}
.m-o-t-fl-ico {
    background-position: -426px -204px;
}
.icon16 {
    display: inline-block;
    height: 16px;
    width: 16px;
    vertical-align: middle;
}
.view-ss{
   display: flex;
   margin-top: 4px;
   
}

.list-ss-1{
  display: flex;
   margin-left: -7px;
}
.list-li-1 {
  margin-top: 5px;
    width: 50%;
    margin-bottom: 15px;
}
.list-li-mf {
  margin-top: -8px;
    width: 50%;
    margin-bottom: 15px;
}
.pro-l-b-li-info-1 {
    margin-left: 10px;
    border: 1px solid #e9e9e9;
    position: relative;
    
    border-top: 0;
    
    padding-top: 3px;
    background: #fff;
}
.info-image{
   width: 100%;
   height: 3px;
   margin-top: -10px;
    
}
.li-info-top-1 {
    margin: 5px 5px 0;
        position: relative;
}
.title-1 {
    line-height: 20px;
    height: 40px;

    font-weight: bold;
    font-size: 0.8rem;
    color: #333;
}
.nr-fl-warp-1 {
    margin-top: 10px;
}
.n-fl-boy-1 {
    display: block;
    min-width: 90%;
    margin: 0 auto 10px;
    height: 22px;
    line-height: 22px;
    padding: 0 5px;
    border-radius: 6px;
    text-align: center;
    border: 1px solid #dddddd;
}
.fsize12-1 {
    font-size: 0.7rem;
}

.c-666-1 {
    color: #666;
}
.li-info-bottom-1 {
    height: 40px;
    border-top: 1px solid #ddd;
}
.jg-li-1 {
    line-height: 40px;
    margin-left: 5px;
}
.fsize18-1 {
    font-size: 1rem;
}
.fl-1 {
    float: left;
}
.c-master-1{
color: #ff662f;
}
.details-btn-1 {
    margin: 8px 5px 0 0;
    height: 22px;
    line-height: 22px;
    font-size: 0.6rem;
    border-radius: 5px;
    padding: 0 10px;

    display: block;
    float: right;
   
    color: #ff662f;
    border: 1px solid #ff662f;
    
}
</style>

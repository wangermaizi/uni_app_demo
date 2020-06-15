<template>
	
	<view>
<!-- 标题 -->
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
<!-- 内容 -->
<view class="body-aa">
  <!-- 分类 -->
  <view class="view-ss">
    <view class="clearfix">
      <view class="mo">
        <navigator class="la" href="javascript:void (0)">
          <p class="tt-a">
            专业分类</p>
        </navigator>
      </view>
    </view>

    <view class="content">
      <view class="TI">
        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515514161603.jpg"> </image>
        <view class="img-name">提防平行志愿三大误区 </view>
        <view class="ji">地方导游基础知识</view>
        <view class="time-Data">2017/11/16 01:50</view>
        <view class="V">兰劲华在高招咨询中发现，考生和家长对</view>
      </view>
    </view>
        <view class="paging">
            <navigator class="padding-a">首</navigator>   
           <navigator url="/pages/seeMore/seeMore"  class="padding-a" >1</navigator>
           <navigator url="pages/Morss/Morss" class="padding-a current undisable">2</navigator>
           
           <navigator   class="padding-a"   href="javascript:goPage(2);" title="">末</navigator>
            <view class="clear"></view>
        </view>
  </view>



  <!-- 背影颜色 -->
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

.content {
   padding: 5px;
   background-color: #fff;
   margin-top: 12px;
   height: 103px;
   width: 100%;
}
.content-A {
   padding: 5px;
   background-color: #fff;
   margin-top: 12px;
   margin-bottom: 16px;
   height: 80px;
   width: 100%;
}

.content-img{
   width: 120px;
   height: 79.67px;
   float: left;
   margin-right: 10px;
}
.img-name{
    height: 20px;
    line-height: 20px;
    font-size: 0.8rem;
        color: #333;
    display: block;
    /* 文字变 ... */
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;

}
.ji{

    height: 22px;
    line-height: 22px;
  
    padding: 0 10px;
    font-size: 0.7rem;
   
  

}
.time-Data{
  display: inline-block;
    margin-right: 20px;
    font-size: 0.7rem;
    color: #666;
}
.V{
      line-height: 20px;
      font-size: 0.7rem;
          color: #999;
}
.TI{
   margin-top:6px;
}

.paging {
    padding: 25px 0;
    text-align: center;
}
 .padding-a{
  width: 20px;
    height: 20px;
    line-height: 20px;
        border: 1px solid #ccc;
    border-radius: 40%;
    color: #666;
    display: inline-block;
        margin: 0 5px;
}


 .undisable {
        cursor: text;
}
.current {
  border-color: #ff662f;
    color: #ff662f;
    text-decoration: none;
    border-radius: 50%;
}
.clear {
    clear: both;
    font-size: 0;
    content: " ";
    line-height: 1px;
    height: 1px;
    _height: 1%;
    margin-top: -1px;
}

</style>

<template>
	<div>
	<!-- 标题 -->
	<div class="title">
	  <!-- 箭头图标 -->
	  <!-- 输入框 -->
	  <div style="margin-left: 40px;margin-right: 40px;padding:1px 25px;">
	    <div url="/pages/search/search" class="SearchInput">
	      <input style="float: left;" placeholder="请输入试卷名称"></input>
	      <div>
	        <icon type="search" size="20" class="home-sear" />
	      </div>
	    </div>
	  </div>
	  <!-- 图标 -->
	  <div class="mw">
	    <div class="mw-nav-btn">
	      <div class="mw-nav-icon"></div>
	    </div>
	  </div>
	</div>
	
	<div class="body-aa">
		  <!-- 分类 -->
		  <div class="div-ss">
			  
			<div class="clearfix">
			  <div class="mo">
				<navigator class="la" href="javascript:void (0)">
				  <p class="tt-a">
					专业分类</p>
				</navigator>
			  </div>
			</div>
			
			 <div class="content">
			      <div class="TI">
			
			      <navigator  url="/pages/MoreDetails/MoreDetails">
			        <image  class="content-img" src="http://www.lvketang.com/images/upload/article/20180109/1515513154061.jpg"> </image>
			        </navigator>
			        <div class="img-name">2015年9月全国计算机等级考试（NCRE）网上报名考生须知 </div>
			        <div class="ji">计算机等级</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">2015年9月第43次全国计算机等级考</div>
			      </div>
			    </div>
			
			    <div class="content">
			      <div class="TI">
			        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515513733269.jpg"> </image>
			        <div class="img-name">2017年下半年物流证书过渡阶段报考和办证通知 </div>
			        <div class="ji">导游业务</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">经中国交通运输协会与英国物流与供</div>
			      </div>
			    </div>
			
			
			    <div class="content">
			      <div class="TI">
			        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515513787056.jpg"> </image>
			        <div class="img-name">高考志愿网上填报操作流程发布 本人须当场签字确认 </div>
			        <div class="ji">计算机等级</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">日前，安徽省2015年普通高校招生考</div>
			      </div>
			    </div>
			
			    <div class="content">
			      <div class="TI">
			        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515514337176.jpg"> </image>
			        <div class="img-name">省高考录取率约为83.5% </div>
			        <div class="ji">政法与法律法规</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">2015年，辽宁省高考招生计划减生规</div>
			      </div>
			    </div>
			
			    <div class="content">
			      <div class="TI">
			        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515513882884.jpg"> </image>
			        <div class="img-name">高考加分考生今年减少2952人 </div>
			        <div class="ji">计算机等级</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">昨日，市教育考试院公布了《2015</div>
			      </div>
			    </div>
			
			    <div class="content-A">
			      <div class="TI">
			        <image class="content-img" src="http://www.lvketang.com/images/upload/article/20180110/1515513953623.jpg"> </image>
			        <div class="img-name">高考志愿填报怎么填？四大法则为您指 </div>
			        <div class="ji">计算机等级</div>
			        <div class="time-Data">2017/11/16 01:50</div>
			        <div class="V">　每年最受高考考生家长期待的下面市</div>
			      </div>
			    </div>
				
			
				<div class="paging">
					<navigator class="padding-a">首</navigator>
					 <navigator url="/pages/seeMore/seeMore" class="padding-a current undisable">1</navigator>
					<navigator url="/pages/Morss/Morss"  class="padding-a" >2</navigator>
			 <navigator   class="padding-a"   href="javascript:goPage(2);" title="">末</navigator>
					<div class="clear"></div>
				</div>

				
				
				
				
			
			
			
		</div>
	</div>
	
	
	
	
	
	
	
	
	
	

	</div>
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
   height: 100px;
   width: 99%;
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

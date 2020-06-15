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
		  <!-- <view class="mw">
		    <view class="mw-nav-btn">
		      <view class="mw-nav-icon"></view>
		      
		    </view>
		  </view> -->
		</view>
		
	  <view style="background-color: #fafafa;height: 788px;">
		 <view>
			  <view style="display: flex;">
				<navigator url="../education/education">
					  <image  class="img-tp" src="http://www.lvketang.com/images/upload/article/20161223/1482459616819.jpeg"></image>
				</navigator>  
			    <navigator url="../jinpingInformation/jinpingInformation">
					  <image class="img-tp" src="http://www.lvketang.com/images/upload/article/20150910/1441853023802.jpg"></image> 
				</navigator>
			  </view>
			  <view style="display: flex;">
			  	<navigator url="../returnQie/returnQie">
					 <image class="img-tp" src="http://www.lvketang.com/images/upload/article/20150910/1441853211287.jpg"></image>
				</navigator> 
				<navigator url="../BlackGround/BlackGround">
					<image class="img-tp" src="http://www.lvketang.com/images/upload/article/20150910/1441853275555.jpg"></image> 			  
				</navigator>
			  </view>
			 
		 </view>
		 
		<view style="background-color: #FF662F; 
		              width: 40px;border-radius: 4px;
					  margin-top: 19px;margin-left: 15px;">
			 <view style="font-size: 0.8rem;">全部</view>
		 </view>
		 
		 
		 <view style="margin-top: 8px;">
						 	 <view class="xian"></view>
			 <navigator url="../leiju/leiju" style="display: flex;">
							 <image  style="width: 190px; 
				height: 66.39px; margin-top: 1px;margin-left: 10px;margin-right: 10px;"
								src="http://www.lvketang.com/images/upload/article/20150928/1443424285823.jpg"></image>
						  <view style="flex-direction: column;margin-top: -13px;">  
							<h3 class="hLh30 txtOf unFw">
								<a target="_blank" title="哈佛商学院院长：21世纪人人都需要创业精神" class="i-art-title">雅思阅读能力提高有方法 文章精</a>
							</h3>
							<p style="margin-top: 8px; color: #999;font-size: 12px;">
					
						关于雅思(课程)精读，首先，认真选择精读文章，只需10篇剑
						我一直认...
													
					...	
			 ...</p>
						 </view>
				 </navigator>
				 <view class="xian"></view>
					<div class="paging">
							<navigator class="padding-a">首</navigator>
							 <navigator url="/pages/InformationModule/InformationModule" class="padding-a">1</navigator>
							<navigator url="/pages/InformationModuleTwo/InformationModuleTwo"  class="padding-a current undisable" >2</navigator>
		  <navigator   class="padding-a"   href="javascript:goPage(2);" title="">末</navigator>
							<div class="clear"></div>
					</div>
							 							 
							 			 
							 
			 
			 
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
	.paging {
	    padding: 25px 0;
	    text-align: center;
		margin-top: -10px;
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
	.xian{
		border-bottom: 1px solid #C0C0C0;
		margin-top: 18px;
		margin-bottom: 18px;
		}
	.hLh30 {
	   
		margin-top: 6px;
	}
	.i-art-title {
	    font-size: 16px;
		color: #333;
	}
	.img-tp{
		width: 177.5px;
		height: 117.86px;
		margin-top: 10px;
		margin-right: 7px;
		margin-left: 3px;
		margin-bottom: -1px;
	}
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
</style>

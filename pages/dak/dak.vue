<template>
	<view>
		<!--pages/dak/dak.wxml-->
		<!-- <text>pages/dak/dak.wxml</text> -->
		<!-- 标题 -->
		<view class="view-oo">
		  <view class="title">
		    <!-- 箭头图标 -->
		    <view>
		      <image class="title-ime" src="http://www.lvketang.com/images/upload/websiteLogo/20190423/1555987578965.png">
		      </image>
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
		
		
		</view>
		
		
		
		
		<view class="body-css">
		
		  
		
		
		
		<view class="w60pre fl">
		  <view class="mr15">
		    <view class="Result-top-l bg-fff Result-top">
		      <view class="Result">
		        <span class="name f-fM fsize18 c-333">
		          答题卡
		        </span>
		        <ul class="clearfix top-r-w-li">
		          <li>
		            <navigator url="../question/question" href="javascript:void(0)" onclick="datikaAnchor(1)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              1</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(2)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              2</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(3)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              3</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(4)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              4</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(5)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              5</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(6)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              6</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(7)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              7</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(8)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              8</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(9)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              9</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(10)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              10</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(11)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              11</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(12)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              12</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(13)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              13</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(14)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              14</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(15)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              15</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(16)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              16</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(17)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              17</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(18)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              18</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(19)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              19</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(20)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              20</a>
		          </li>
		          <li>
		            <navigator url="../shijiuQuestion/shijiuQuestion" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              21</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(22)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              22</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(23)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              23</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(24)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              24</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(25)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              25</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(26)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              26</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(27)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              27</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(28)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              28</a>
		          </li>
		          <li>
		            <navigator url="../Twenty-nine/Twenty-nine" href="javascript:void(0)" onclick="datikaAnchor(29)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              29</navigator>
		          </li>
		          <li>
		            <navigator url="../sQuestion/sQuestion"  href="javascript:void(0)" onclick="datikaAnchor(30)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              30</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(31)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              31</a>
		          </li>
		          <li>
		            <navigator url="../eight/eight" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              32</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(33)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              33</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(34)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              34</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(35)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              35</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(36)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              36</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(37)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              37</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(38)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              38</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(39)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              39</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(40)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              40</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(41)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              41</a>
		          </li>
		          <li>
		            <navigator url="../FortyTwo/FortyTwo"  href="javascript:void(0)" onclick="datikaAnchor(42)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              42</navigator>
		          </li>
		          <li>
		            <navigator url="../FortyTwo/Forty-six/Forty-six" href="javascript:void(0)" onclick="datikaAnchor(43)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              43</navigator>
		          </li>
		          <li>
		            <navigator url="../FortyTwo/Answer-four/Answer-four" href="javascript:void(0)" onclick="datikaAnchor(44)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              44</navigator>
		          </li>
		          <li>
		            <navigator url="../FortyTwo/Answer-wu/Answer-wu" href="javascript:void(0)" onclick="datikaAnchor(45)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              45</navigator>
		          </li>
					 <li>
		            <navigator url="../FortyTwo/Answer-liu/Answer-liu" href="javascript:void(0)" onclick="datikaAnchor(46)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              46</navigator>
		          </li>
		          <li>
		            <navigator url="../FortyTwo/Answer-qi/Answer-qi" href="javascript:void(0)" onclick="datikaAnchor(47)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              47</navigator>
		          </li>
		          <li>
		            <navigator href="javascript:void(0)" onclick="datikaAnchor(48)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              48</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(49)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              49</a>
		          </li>
		          <li>
		            <navigator href="javascript:void(0)" onclick="datikaAnchor(50)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              50</navigator>
		          </li>
		          <li>
		            <navigator href="javascript:void(0)" onclick="datikaAnchor(51)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              51</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(52)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              52</a>
		          </li>
		          <li>
		            <navigator href="javascript:void(0)" onclick="datikaAnchor(53)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              53</navigator>
		          </li>
		          <li>
		            <navigator url="../sixtFor/sixtFor" href="javascript:void(0)" onclick="datikaAnchor(54)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              54</navigator>	
		          </li>
		          <li>
		            <navigator url="../sixtYeven/sixtYeven" href="javascript:void(0)" onclick="datikaAnchor(55)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              55</navigator>
		          </li>
		          <li>
		            <navigator url="../FiftySix/FiftySix" href="javascript:void(0)" onclick="datikaAnchor(56)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              56</navigator>
		          </li>
		          <li>
		            <navigator url="../fiftySeven/fiftySeven" href="javascript:void(0)" onclick="datikaAnchor(57)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              57</navigator>
		          </li>
		          <li>
		            <navigator url="../fiftyBA/fiftyBA" href="javascript:void(0)" onclick="datikaAnchor(58)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              58</navigator>
		          </li>
		          <li>
		            <navigator url="../fiftyJiu/fiftyJiu" href="javascript:void(0)" onclick="datikaAnchor(59)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              59</navigator>
		          </li>
		          <li>
		            <navigator url="../LiuShi/LiuShi" href="javascript:void(0)" onclick="datikaAnchor(60)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              60</navigator>
		          </li>
		          <li>
		            <navigator url="../LiuYi/LiuYi" href="javascript:void(0)" onclick="datikaAnchor(61)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              61</navigator>
		          </li>
		          <li>
		            <navigator url="../sixtyTwo/sixtyTwo" href="javascript:void(0)" onclick="datikaAnchor(62)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              62</navigator>
		          </li>
		          <li>
		            <navigator url="../three/three" href="javascript:void(0)" onclick="datikaAnchor(63)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              63</navigator>
		          </li>
		          <li>
		            <navigator url="../four/four" href="javascript:void(0)" onclick="datikaAnchor(64)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              64</navigator>
		          </li>
		          <li>
		            <navigator url="../ShouldFive/ShouldFive" href="javascript:void(0)" onclick="datikaAnchor(65)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              65</navigator>
		          </li>
		          <li>
		            <navigator url="../SixtySix/SixtySix" href="javascript:void(0)" onclick="datikaAnchor(66)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              66</navigator>
		          </li>
		          <li>
		            <navigator url="../lshiQie/lshiQie" href="javascript:void(0)" onclick="datikaAnchor(67)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              67</navigator>
		          </li>	
		          <li>
		            <navigator url="../SixtyEight/SixtyEight" href="javascript:void(0)" onclick="datikaAnchor(68)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              68</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(69)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              69</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(70)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              70</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(71)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              71</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(72)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              72</a>
		          </li>
		          <li>
		            <navigator url="../seventyThree/seventyThree" href="javascript:void(0)" onclick="datikaAnchor(73)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              73</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/seventyFour" href="javascript:void(0)" onclick="datikaAnchor(74)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              74</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/sixteen/sixteen" href="javascript:void(0)" onclick="datikaAnchor(75)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              75</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/qshiWu/qshiWu" href="javascript:void(0)" onclick="datikaAnchor(76)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              76</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/PageQshiq/PageQshiq" href="javascript:void(0)" onclick="datikaAnchor(77)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              77</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(78)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              78</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(79)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              79</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(80)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              80</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(81)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              81</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(82)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              82</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(83)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              83</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(84)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              84</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(85)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              85</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(86)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              86</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(87)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              87</a>	
		          </li>
		          <li>
		            <navigator url="../seventyFour/pageEight/pageEight" href="javascript:void(0)" onclick="datikaAnchor(88)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              88</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/pageNine/pageNine" href="javascript:void(0)" onclick="datikaAnchor(89)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              89</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/ninety/ninety" href="javascript:void(0)" onclick="datikaAnchor(90)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              90</navigator>
		          </li>
		          <li>
		            <navigator url="../seventyFour/naviga/naviga" href="javascript:void(0)" onclick="datikaAnchor(91)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              91</navigator>
		          </li>	
		          <li>	
		            <a href="javascript:void(0)" onclick="<datika></datika>Anchor(92)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              92</a>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(93)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              93</a>
		          </li>
		          <li>
		            <navigator url="../Twenty-nine/hundred/hundred" href="javascript:void(0)" onclick="datikaAnchor(94)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              94</navigator>
		          </li>
		          <li>
		            <navigator url="../Twenty-nine/ninetyFive/ninetyFive" href="javascript:void(0)" onclick="datikaAnchor(95)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              95</navigator>
		          </li>
		          <li>
		            <navigator url="../NinetySix/NinetySix" href="javascript:void(0)" onclick="datikaAnchor(96)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              96</navigator>
		          </li>
		          <li>
		            <navigator url="../NineHundredSeven/NineHundredSeven" href="javascript:void(0)" onclick="datikaAnchor(97)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              97</navigator>
		          </li>
		          <li>
		            <a href="javascript:void(0)" onclick="datikaAnchor(98)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              98</a>
		          </li>
		          <li>
		            <navigator href="javascript:void(0)" onclick="datikaAnchor(99)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              99</navigator>
		          </li>
		          <li>
		            <navigator url="../NineHundredSeven/yName/yName" href="javascript:void(0)" onclick="datikaAnchor(100)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
		              100</navigator>
		          </li>	
				  <li>
				    <navigator url="../NineHundredSeven/OneHundred/OneHundred" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      101</navigator>
				  </li>
				  <li>
				    <navigator url="../NineHundredSeven/hundredAndTwo/hundredAndTwo" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      102</navigator>
				  </li>
				  <li>
				    <navigator url="../two-name/two-name" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      103</navigator>
				  </li>
				  <li>
				    <navigator url="../two-name/four-name/four-name" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      104</navigator>
				  </li>
				  <li>
				    <navigator url="../two-name/two-wu/two-wu" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      105</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      106</navigator>
				  </li>	
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      107</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      108</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      109</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      110</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      111</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      112</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      113</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      114</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      115</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      116</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      117</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      118</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      119</navigator>
				  </li>
				  <li>
				    <navigator url="../two-name/twenty-name/twenty-name" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      120</navigator>
				  </li>
				  <li>
				    <navigator url="../two-name/twenty-one/twenty-one" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      121</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/twenty-two-name" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      122</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/twenty-three/twenty-three" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      123</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/twty-view-four/twty-view-four" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      124</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/view-name/view-name" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      125</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      126</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      127</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      128</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      129</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/thirty-view/thirty-view" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      130</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/thirty-one/thirty-one" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      131</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/thirty-two/thirty-two" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      132</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/thirty-trheeRE/thirty-trheeRE" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      133</navigator>
				  </li>
				  <li>
				    <navigator url="../twenty-two-name/thirty-trh/thirty-trh" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      134</navigator>
				  </li>
				  <li>
				    <navigator href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      135</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      136</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      137</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      138</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      139</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      140</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      141</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      142</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      143</navigator>
				  </li>
				  <li>
				    <navigator url="../user/deno-wu/deno-wu" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      144</navigator>
				  </li>
				  <li>
				    <navigator  url="../user/use-for/use-for" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      145</navigator>
				  </li>
				  <li>
				    <navigator  url="../user/deno-liu/deno-liu" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      146</navigator>
				  </li>
				  <li>
				    <navigator url="../user/demk-qi/demk-qi" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      147</navigator>
				  </li>
				  <li>
				    <navigator url="../user/demo-ba/demo-ba" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      148</navigator>
				  </li>
				  <li>
				    <navigator url="../user/demo-jiu/demo-jiu"  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      149</navigator>
				  </li>
				  <li>
				    <navigator url="../user/demk-shi/demk-shi"  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      150</navigator>
				  </li>
				  <li>
				    <navigator url="../user/test-one/test-one" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      151</navigator>
				  </li>
				  <li>
				    <navigator url="../user/test-two/test-two" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      152</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      153</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      154</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      155</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      156</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      157</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      158</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      159</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      160</navigator>
				  </li>
				  <li>
				    <navigator url="../three/demo-test-one/demo-test-one" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      161</navigator>
				  </li>
				  <li>
				    <navigator  url="../three/demo-test-two/demo-test-two" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      162</navigator>
				  </li>
				  <li>
				    <navigator  url="../three/demo-test-three/demo-test-three" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      163</navigator>
				  </li>
				  <li>
				    <navigator url="../three/demo-test-si/demo-test-si"  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      164</navigator>
				  </li>
				  <li>
				    <navigator  url="../three/demo-test-wu/demo-test-wu" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      165</navigator>
				  </li>
				  <li>
				    <navigator url="../three/demo-test-qi/demo-test-qi" href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      166</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      167</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      168</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      169</navigator>
				  </li>
				  <li>
				    <navigator  href="javascript:void(0)" onclick="datikaAnchor(21)" title="" class="em-k-big f-fM fsize12 tac em-k-red c-red">
				      170</navigator>
				  </li>
		        </ul>
		      </view>
		
		
		
		      <view class="Result-top-jg">
		
		        <view>
		          <p class="fsize16 disFw c-333 f-fM"></p>
		
		        </view>
		
		
		
		
		
		
		
		
		
		
		
		
		
		      </view>
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
   /* pages/dak/dak.wxss */.disFw {
		font-weight: 600;
	}

	.clearfix {
		display: block;
		margin-left: -7px;
	}

	li {
		float: left;
		margin-right: 6px;
	}

	ul {
		list-style: none;
	}

	li .em-k-big {
		display: block;
		width: 23px;
		height: 18px;
		line-height: 18px;
		border-style: solid;	
		border-width: 1px;
		border-radius: 4px;
		margin: 5px;
	}

	.tac {
		text-align: center;
	}

	.em-k-red {
		border-color: #569aff;
	}

	.c-red {
		color: red;
	}

	.fsize12 {
		font-size: 0.7rem;
	}

	.con {
		position: relative;
		display: inline-block;
		height: 200px;
		width: 200px;
		margin-left: 74px;
	  }

	.percent-circle {
		position: absolute;
		height: 100%;
		background: #FFFF00;
		overflow: hidden;
	}

	.percent-circle-right {
		right: 0;
		width: 100px;
		border-radius: 0 100px 100px 0/0 100px 100px 0;
	}

	.percent-circle-right .right-content {
		position: absolute;
		content: '';
		width: 100%;
		height: 100%;
		transform-origin: left center;
		transform: rotate(0deg);
		border-radius: 0 100px 100px 0/0 100px 100px 0;
		background: #D8D8D8;	
	}

	.percent-circle-left {
		width: 100px;
		border-radius: 100px 0 0 100px/100px 0 0 100px;
	}

	.percent-circle-left .left-content {
		position: absolute;
		content: '';
		width: 100%;
		height: 100%;
		transform-origin: right center;
		transform: rotate(0deg);
		border-radius: 100px 0 0 100px/100px 0 0 100px;
	}

	.text-circle {
		position: absolute;
		display: -webkit-box;
		display: -webkit-flex;
		display: flex;
		-webkit-box-align: center;
		-webkit-align-items: center;
		align-items: center;
		-webkit-box-pack: center;
		-webkit-justify-content: center;
		justify-content: center;
		height: 80%;
		width: 80%;
		left: 10%;
		top: 10%;
		border-radius: 100%;
		/* background: #000; */
		background: #fff;
		color: #000;
	}

	.body-css{
		width: 100%;
		/* height: 680px; */
		background: #f5f5f5;
	}

	.title-ime {
		width: 90px;
		height: 33.75px;
		margin-left: 9px;
		margin-top: 6px;
	}
	
	.title {
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
	.w50pre {
		width: 100%;
		float: inherit;
		margin-bottom: 20px;

	}
  .w60pre {
    
		width: 100%;
		float: inherit;
		margin-bottom: 20px;

	}

	.Result-top {
		padding: 1px 5px;
	}

	.bg-fff {
		background-color: #fff;
	}

	.Result-top-title {
		height: 48px;
		border-bottom: 1px solid #efefef;
		text-align: center;
	}

	.Result {
		height: 650px;
		border-bottom: 1px solid #efefef;
		text-align: center;
	}

	.name {
		line-height: 46px;
		display: inline-block;
		padding: 0 15px;
		margin-bottom: 12px;
		border-bottom: 2px solid #C0C0C0;
		/* line-height: 68px; */
		font-weight: bold;
	}

	.fsize18 {
		font-size: 1rem;
	}

	.c-333 {
		color: #333;
	}

	.Result-top-jg {
		margin: 10px 5px 0;
	}

	.fsize16 {
		font-size: 0.8rem;
	}

	.Result-top-jg-warp {
		padding-right: 0;
		position: inherit;
		min-height: 213px;
	}

	.Result-top-jg-tu {
		position: inherit;
		width: 220px;
		top: 20px;
		right: 0;
		height: 220px;
		margin: 15px auto;
	}

	.mt20 {
		margin-top: 10px;
	}

	.mb30 {
		margin-bottom: 30px;
	}

	.fsize14 {
		font-size: 0.9rem;
		font-weight: 500;
	}

	.c-333 {
		color: #333;
	}

	.mt10 {
		margin-top: 10px;
	}
</style>

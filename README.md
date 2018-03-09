# 2018.3.6

![image](https://github.com/Lmao-Pt/2018.3.6/blob/master/images/ok.png)<br /> 
  一共两个布局：1、悬浮侧栏 固定在屏幕的右侧  分上下两个部分实现<br /> 
上半部分的实现： 二维码可以用background-image实现与下方文字放置在同一个父级盒子 可以方便定位。<br />  
下半部分的实现：1、 布局为<!--ul>li*3--> 给定li宽高后可 腾讯小图标可以用background-image  （left center）固定在li左侧 <br /> 
TOP和箭头小图标可以位于同一标签中 图标设置为背景 并给上（center top）<br /> 
素材给了 <b>横线</b> 的图片来给定 li 下边框，可以将<b>横线</b> 绝对定位于 li 的底部 <b>防止超出</b> <br />
顶部的小 <b>X<b /> 图标 从语义上来分析应将其与下面悬浮栏同级 可以通过绝对定位于父级盒子 确定其位置。<br />
由于背景的素材图片宽度高不一致 在调整上下两部分时 下方最高的 li 可能会无法存在背景 可以通过background-color<br />
提取原有背景颜色 再设置背景。





这种进度条的动画是最容易实现的，根据具体进度百分比设置默认的width百分比和动画里100%处的width百分比就行了，比如说，我想实现70%的进度条动画效果，那么我只需要修改一下两处地方：

#progress span{
    width: 70%;
}
@-webkit-keyframes load{
      0%{
        width: 0%;
      }
    100%{
        width:70%;
      }
}
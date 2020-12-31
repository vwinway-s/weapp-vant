# weapp-vant
vant原生小程序代码

``` wxml
// 事件未触发
<van-uploader file-list="{{files}}" bindafterread="afterRead"/>

// 事件触发
<van-uploader file-list="{{files}}" bind:after-read="afterRead"/>
```

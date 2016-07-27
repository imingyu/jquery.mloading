# jquery.mloading
为jquery element增加loading遮罩效果，jquery.watercolor.js简易版

[![NPM](https://nodei.co/npm/jquery.mloading.js.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/jquery.mloading.js/) 

![image](https://segmentfault.com/img/bVyRN0)

使用方法
------
将jquery.mloading.js和jquery.mloading.css引入到页面，调用：
```
$(element).mLoading({
    text:"",//加载文字，默认值：加载中...
    icon:"",//加载图标，默认值：一个小型的base64的gif图片
    html:false,//设置加载内容是否是html格式，默认值是false
    content:"",//忽略icon和text的值，直接在加载框中显示此值
    mask:true//是否显示遮罩效果，默认显示
});
```

方法：
- ```$(element).mLoading("show");//显示loading组件 ```
- ```$(element).mLoading("hide");//隐藏loading组件 ```
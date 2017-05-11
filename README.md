## Angular2.0仿今日头条应用

### 前言
看到好多人用微信小程序、vue、swift等开发今日头条，我想着既然vue被人抢先，那么我就用最麻烦的angular，并且不使用具有污染性的jquery与任何插件来做一个仿今日头条，一切都为了代码的纯洁性。

### 项目准备

- 使用angular CLI创建新项目，将app替换
- 项目使用者需掌握ES6和Typescript

### 项目截图

![](http://i4.buimg.com/591295/8c0baca7a55f2a1c.png)
![](http://i4.buimg.com/591295/c563e95230e005a9.png)
![](http://i2.muimg.com/591295/3870d2709777127c.png)
![](http://i2.muimg.com/591295/1f3eff5955439781.png)

### 项目相关

- 1、该仿作应用是基于web页面，浏览时调制手机页面大小
- 2、由于没有使用任何插件，没有使用jquery等类库，体验效果和数据刷新效果比较差
- 3、大量使用angular2中的Jsonp服务跨域调取今日头条数据
- 4、现项目刚完成1/3,还有大量工作，后续将不定期优化和更新
- 5、github地址：https://github.com/jingegebuguai/Angular2 ，谢谢您的star与关注

### 更新日志

- 5.4~8 实现Api接口数据获取(新闻、评论和段子)
- 5.9 实现频道选择功能 ,同步到导航栏
- 5.10 实现搜索框功能
- 5.11 优化API接口,合并导航频道组件（除段子）

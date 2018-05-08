# 微信学习记录

  # git相关

    Git中的upstream和downstream概述（即把本地分支设为相应远程分支的downstream）
    https://blog.csdn.net/taiyangdao/article/details/52766483

    Git - Your branch and 'origin/xxx' have diverged
    https://blog.csdn.net/d6619309/article/details/52711035

    使用git往github上提交代码时出现[packet_write_wait connection to xx.xx.xx.xx Broken pipe]错误的解决办法
    https://blog.csdn.net/hsx1612727380/article/details/51984251

    git 从master分支拉到其它分支
    ./img/gitbranch.jpg

    git创建远程本地分支      寻找ssh   打开相应文件夹
    ./img/gitssh1.jpg
    ./img/gitssh2.jpg

  # vue相关
    
    计算属性和观察者
    https://cn.vuejs.org/v2/guide/computed.html

    关于Vue实例的生命周期created和mounted的区别
    https://segmentfault.com/a/1190000008570622
    
    vue 遮罩层阻止默认滚动事件
    https://blog.csdn.net/panyang01/article/details/75663677

    vue2组件实现懒加载浅析
    http://www.jb51.net/article/109865.htm

    vue.js之获取当前点击对象(其实是套着vue的原生javascript吧，笑)
    https://www.cnblogs.com/meng1314-shuai/p/7455575.html

    最详细的Vuex教程
    https://blog.csdn.net/h5_queenstyle12/article/details/75386359

    vue组件间传值的几种方式
    https://mp.weixin.qq.com/s/J8Khg5Ru_PNpnSUdOmk-3g

    Vue2.0 新手完全填坑攻略——从环境搭建到发布
    https://www.jianshu.com/p/5ba253651c3b

    Vue2.0 新手入门 — 从环境搭建到发布
    http://www.runoob.com/w3cnote/vue2-start-coding.html

    Vue js 的生命周期（看了就懂）
    https://blog.csdn.net/qq_24073885/article/details/60143856

    npm run build 打包后，如何运行在本地查看效果（vue-cli）
    https://www.cnblogs.com/qiu-Ann/p/7477593.html

    vue中的$event 和$的含义，简单来说$没有啥特殊含义
    https://segmentfault.com/q/1010000008491642?_ea=1662743
    https://segmentfault.com/q/1010000010054474/a-1020000010055018

    vue自定义指令
    https://cn.vuejs.org/v2/guide/custom-directive.html

    vm.$emit( event, […args] ) ： 触发当前实例上的事件。附加参数都会传给监听器回调

    vue.js组件中的v-on绑定自定义事件理解
    https://blog.csdn.net/hayre/article/details/60572435

    vue.js之路(4)——vue2.0s中eventBus实现兄弟组件通信
    https://blog.csdn.net/u013034014/article/details/54574989?locationNum=2&fps=1

    最详细的Vuex教程
    https://blog.csdn.net/h5_queenstyle12/article/details/75386359

  # 微信小程序相关

    微信小程序 + mock.js 实现后台模拟及调试
    https://www.cnblogs.com/xzma/p/7591090.html

    微信小程序-navigator 跳转url传递参数
    https://blog.csdn.net/u013778905/article/details/59141486

    快速掌握小程序组件事件自定义参数的方法
    https://blog.csdn.net/beilinyu/article/details/53945438

    微信小程序 全局变量
    https://blog.csdn.net/u010095372/article/details/53421670

    微信小程序：合法域名校验出错，解决方法
    https://blog.csdn.net/userhr/article/details/53227876

    微信小程序组件化开发框架WePY官方文档
    https://tencent.github.io/wepy/document.html#/

    wepy编译
    ./img/wepybuild.jpg

    W3Cschool微信小程序开发文档
    https://www.w3cschool.cn/weixinapp/9wou1q8j.html

    微信小程序 退出小程序亲测可行
    https://blog.csdn.net/wu_shuxuan/article/details/79089838
    微信小程序 退出小程序亲测不可行
    https://blog.csdn.net/sinat_33881413/article/details/78061290

    全局变量
    App({
      globalData: {
        quit: false
      }
    })
    重新赋值
    getApp().globalData.quit = true
    获取
    getApp().globalData.quit

  # es6相关

    箭头函数和普通函数的区别
    https://www.jianshu.com/p/73cbeb6782a0

    ECMAScript 6 入门
    http://es6.ruanyifeng.com/#docs/promise

    promise源码分析
    https://segmentfault.com/a/1190000006103601

    ES6系列文章 异步神器async-await
    https://segmentfault.com/a/1190000011526612


  # 原生js相关

    理解JS的浅拷贝与深拷贝
    http://yuanhehe.cn/2016/11/03/%E7%90%86%E8%A7%A3JS%E7%9A%84%E6%B5%85%E6%8B%B7%E8%B4%9D%E4%B8%8E%E6%B7%B1%E6%8B%B7%E8%B4%9D/

    根据对象的某一属性进行排序的js代码
    http://www.jb51.net/article/24536.htm

    彻底弄懂JS的事件冒泡和事件捕获
    https://www.cnblogs.com/qq9694526/p/5653728.html
    
    addEventListener和on的区别
    https://www.cnblogs.com/pssp/p/5196716.html

    break跳出整个循环，continue跳出当层循环

    上下文（context）->this->挂载着变量与函数的对象(object-base)
    作用域->函数定义时决定->作用于函数(function-base)

    简单粗暴地理解js原型链–js面向对象编程
    https://blog.csdn.net/H5_QueenStyle12/article/details/75434701

    JS - 控制小数位数的方法（保留小数点后N位、以及小数取整）
    http://www.hangge.com/blog/cache/detail_1791.html

    js动态添加、修改、删除对象的属性与方法
    http://www.jquerycn.cn/a_11222

    JavaScript 判断一个对象{}是否为空对象的简单方法
    http://www.jb51.net/article/94318.htm

    e.target与e.currentTarget的区别
    https://www.jianshu.com/p/1dd668ccc97a

    获取浏览器型号与浏览器版本信息代码（原生）
    ./img/browser.jpg

    js原生操作HTML对象的属性区别
    http://www.zhangyunling.com/28.html
	
	自执行匿名函数：!function () { /* code */ } ();
	http://www.cnblogs.com/beijingstruggle/p/5970824.html

  # 基础知识相关

    什么是IP地址和域名
    https://zhidao.baidu.com/question/237404184.html

    谈谈HTTP协议中的短轮询、长轮询、长连接和短连接
    http://web.jobbole.com/85541/

    页面图片都加载出来的时候，我们才把主页面给显示出来
    https://blog.csdn.net/hh279768876/article/details/68925041

    网站部署发布到互联网等整套流程
    https://blog.csdn.net/shuai7boy/article/details/53203339

    二维数组处理可以将最外层写成对象形式 就会比较规范

    命名一定要严谨，标准，专业！

    跨域资源共享 CORS 详解
    http://www.ruanyifeng.com/blog/2016/04/cors

    浅谈session,cookie,sessionStorage,localStorage的区别及应用场景
    https://www.cnblogs.com/cencenyue/p/7604651.html

    三次握手四次挥手的原理
    https://www.cnblogs.com/shihaochangeworld/p/5770294.html

    HTTP请求行、请求头、请求体、响应行、响应头、响应体详解
    https://blog.csdn.net/u010256388/article/details/68491509

    同步(Synchronous)和异步(Asynchronous)
    https://www.cnblogs.com/anny0404/p/5691379.html

    线程和进程的区别是什么？
    https://www.zhihu.com/question/25532384

  # 移动端适配相关

    js判断移动端浏览器版本和手机类型
    https://zhidao.baidu.com/question/712639685420775565.html?fr=iks&word=js%C5%D0%B6%CF%CA%D6%BB%FA%C0%E0%D0%CD&ie=gbk
      
    移动端触发touch事件同时触发click事件的相关解决方法
    https://blog.csdn.net/feniuben/article/details/21159271

    移动端的touch click事件的理解+点透
    https://www.jianshu.com/p/dc3bceb10dbb

    移动端web开发，click touch tap区别
    https://www.cnblogs.com/wangkongming/p/6254358.html

    ios对fixed定位支持不好
    不能用fixed定位
    可以用flex布局来替代

    ios对点击事件不友好，可以用watch属性值监听来实现类点击事件效果

    混合app开发--js和webview之间的交互总结
    https://www.cnblogs.com/shiyou00/p/6874006.html

    Android WebView中客户端与JavaScript的基本交互
    https://blog.csdn.net/qq_25867141/article/details/50751354

    浅谈Hybrid技术的设计与实现
    https://www.cnblogs.com/yexiaochai/p/4921635.html

  # css相关

    css 放在最前面 js抽出单独文件 否则会出现无样式闪烁的问题

    关于无样式闪烁
    https://www.jianshu.com/p/db82a546267a

    逐步解决动态添加样式导致的元素闪烁
    https://segmentfault.com/a/1190000006216880

  # node相关

    Node.js 教程 | 菜鸟教程
    http://www.runoob.com/nodejs/nodejs-npm.html

    Node.js 在命令行下执行Console.log()命令时，第二行会打印undefined的原因
    https://blog.csdn.net/chy555chy/article/details/52332752

    module.exports require 相对目录（廖雪峰：小程序一点补充（node教程的一部分））
    https://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000/001434502419592fd80bbb0613a42118ccab9435af408fd000

    怎样有效地学习 Node.js？ - 知乎用户的回答 - 知乎 
    https://www.zhihu.com/question/19793473/answer/15952853

  # 杂项

    hexo Github部署个人博客之填坑
    http://www.yanxinhua.com/2018/02/06/%E6%9B%B4%E6%96%B0Hexo%E5%8D%9A%E5%AE%A2%E4%B8%AD%E9%81%87%E5%88%B0%E7%9A%84%E4%B8%80%E4%BA%9B%E9%97%AE%E9%A2%98/

    利用Valine给Hexo添加评论系统
    http://www.yanxinhua.com/2018/02/06/Valine-%E2%80%94%E2%80%94-%E4%B8%80%E6%AC%BE%E6%9E%81%E7%AE%80%E7%9A%84%E8%AF%84%E8%AE%BA%E7%B3%BB%E7%BB%9F/

    二坑：要确定有密钥并且公钥有匹配，否则会报错
    项目名必须与用户名相同，否则不能实现

    hexo框架官方文档
    https://hexo.io/zh-cn/docs/

    axios 中文文档 翻译
    https://segmentfault.com/a/1190000008470355

    mock官方文档
    http://mockjs.com/0.1/#%E7%94%A8%E6%B3%95

    windows 10 下无法启动nginx的解决方法
    https://www.jianshu.com/p/7242b0ba324e

    React学习笔记
    https://blog.csdn.net/u010412719/article/details/78384846

    最快的速度搭建Gitlab服务器
    https://blog.csdn.net/u012556150/article/details/53053577

# 简介
利用HTML5的Canvas和CSS3实现手机端页面的图表效果，通过Fullpage.js插件实现页面切换效果。<br>
JS代码以组件的形式进行模块化编写，实现代码的复用，同时便于后期维护。


## JS有以下三个组件模块

- 内容组织类：H5
```sh
新增一个Fullpage页面：通过返回this实现链式调用
新增页面一个组件：通过实例化图表组织类：H5component????
初始化组件：即展现所有页面
```

- 图文组织类：H5componentBase
```sh
初始化一个组件，即生成一个div
```

- 图表组织类：H5component????
```sh
实例化一个图文组织类，然后在此div中动态生成不同图表的结构
```
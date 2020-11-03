# 谔谷

开源の基础页面模板

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>关于谔谷</title>
<meta name="keywords" content="谔谷,简介,介绍">
<meta name="description" content="关于谔谷">
<meta name="author" content="miaohongxuan,谔谷">
<style>
    /* 下拉按钮样式 */
.dropbtn {
    background-color: #2e75b6;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
    cursor: pointer;
}

/* 容器 <div> - 需要定位下拉内容 */
.dropdown {
    position: relative;
    display: inline-block;
}

/* 下拉内容 (默认隐藏) */
.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

/* 下拉菜单的链接 */
.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

/* 鼠标移上去后修改下拉菜单链接颜色 */
.dropdown-content a:hover {background-color: #f1f1f1}

/* 在鼠标移上去后显示下拉菜单 */
.dropdown:hover .dropdown-content {
    display: block;
}

/* 当下拉内容显示后修改下拉按钮的背景颜色 */
.dropdown:hover .dropbtn {
    background-color: #3e8e41;
}
    /* 头部样式 */
.header {
  background-color: #f1f1f1;
  padding: 10px;
  text-align: center;
}
    /* 创建三个不相等的列 */
.column {
  float: left;
  padding: 10px;
}

/* 左右两侧宽度 */
.column.side {
  width: 25%;
}

/* 中间区域宽度 */
.column.middle {
  width: 50%;
    background-color:#EEEEEE;
}

/* 列后面清除浮动 */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* 响应式布局 - 宽度小于600px时设置上下布局 */
@media screen and (max-width: 600px) {
  .column.side, .column.middle {
    width: 100%;
  }
}
/*************导航栏****************/
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #2e75b6;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover {
    background-color: #1f4f7a;
}
</style>
</head>
<body>

<ul>
  <li><a class="active" href="">主页</a></li>
  <li><a href="#news">新闻</a></li>
  <div class="dropdown">
    <a href="#" class="dropbtn">作品</a>
    <div class="dropdown-content">
      <a href="#">谔谷杂志</a>
      <a href="#">谔谷OJ</a>
      <a href="#">谔谷论坛</a>
    </div>
  <li><a href="#about">关于</a></li>
</ul>

</body>
</html>

```

---

# 联系方式

邮箱：<谔谷官方@xxxhi.cc>

<kbd>ps:谔谷工作人员会每周六下午检查邮箱，邮箱设置为24小时清空，请在星期五下午~星期六上午发送邮件</kbd>

---

powered by [©miaohongxuan](https://www.luogu.com.cn/user/280679)&[Aaron-mhx](https://github.com/Aaron-mhx)&[谔谷](https://github.com/Aaron-miao-2020/eg)

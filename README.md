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
    background-color: #333;
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
    background-color: #111;
}
</style>
</head>
<body>

<ul>
  <li><a class="active" href="">主页</a></li>
  <li><a href="#news">新闻</a></li>
  <li><a href="#contact">联系</a></li>
  <li><a href="#about">关于</a></li>
</ul>

</body>
</html>

```

---

# 联系方式

邮箱：<谔谷官方@xxxhi.cc>

<kbd>ps:谔谷工作人员会每周六下午检查邮箱，邮箱设置为24小时清空，请在星期五下午~星期六上午发送邮件</kbd>

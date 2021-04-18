<template>
  <div class="about">
    <h1>关于我的网站</h1>
    <p>这个是我个人每天不想学习瞎搞出来的东西，做的很菜。</p>
    <p>后端前端都是自己一个人搭建的，有些力不从心，这个网站就佛系迭代吧。</p>
    <p>以后计划加入Markdown显示。然后不加其他功能了</p>
    <p>
      主要计划记录自己的iOS学习历程，顺便和大家分享自己搭建网站时踩的这些大大小小的坑。
    </p>
    <p>
      自己的后端API是用Gin写的，前端使用Evan
      You的Vue3(尤大男神!)，现在只写了个注册和登录，可以发放token,如下:
    </p>
    <ul>
      <li>
        <a href="https://www.fengzigeng.com/api/" target="_blank" rel="noopener"
          >https://www.fengzigeng.com/api/</a
        >
      </li>
      <li>
        <a href="https://www.fengzigeng.com/api/register" target="_blank" rel="noopener"
          >https://www.fengzigeng.com/api/register</a
        >
      </li>
      <li>
        <a href="https://www.fengzigeng.com/api/login" target="_blank" rel="noopener"
          >https://www.fengzigeng.com/api/login</a
        >
      </li>
    </ul>
    <h4>Warning:上面两个要用POST请求，所以浏览器直接Get是会404的哦！😯</h4>
  </div>
</template>

<template>
  <div class="dashboard-container">
    <div title="欢迎页面" style="padding: 50px; overflow: hidden; color: #409eff;font: lighter 16px 'Lucida Sans Unicode';"
         data-options="iconCls:'icon-heart',plain:true">
        <b style="font-size: 36px; line-height: 30px; height: 30px;">欢迎使用图书管理系统</b>
        <p>开发人员: 上海华东理工大学 章海斌</p>
        <p>联系方式-Email: haibinzhang09@gmail.com</p>
        <p>联系方式-QQ: 1406912774</p>
        <p>开发周期: 2024/08/1 —— 2021/8/25</p>
        <hr/>
        <b>项目开发环境介绍</b>
        <p>操作系统: Windows 10 home</p>
        <p>开发工具: IntelliJ IDEA 2024.2.0.1 (Ultimate Edition)</p>
        <p>Java版本: 17.0</p>
        <p>服务器: Tomcat 8.5</p>
        <p>数据库: MySQL 8.2</p>
        <p>前端技术: HTML+CSS+JavaScript+Vue+Axios+ElementUI</p>
        <p>后端技术: Java+SpringBoot+MyBatis+MySQL</p>
    </div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'id',
      'name',
      'roles'
    ])
  }
}
</script>

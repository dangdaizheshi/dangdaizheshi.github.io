<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SideBar from '@/views/Home/components/SideBar.vue'
import PostNews from '@/views/Home/components/PostNews.vue';
import Menu from '@/views/Home/components/Menu.vue';
import Test from './components/Test.vue';
import TopBar from './components/TopBar.vue';
import Check from './components/Check.vue';
</script>

<template>
  <TopBar />
  <Check />
  <!-- <div class="common-layout">
    <el-container>
      <el-header>
        <el-row>
          <el-col :span = "4" class = 'logo'>
           <a href=""><el-icon size = "27px"><Grid /></el-icon></a> 
            <h2>Dangdaizheshi</h2>
          </el-col>
          <el-col :span = "17">
            <ul class = "top-nav">
              <li><a href=""><el-icon><Search /></el-icon>主页</a></li>
              <li><a href=""><el-icon><House /></el-icon>主页</a></li>
              <li><a href=""><el-icon><Notebook /></el-icon>主页</a></li>
              <li><a href=""><el-icon><Histogram /></el-icon>主页</a></li>
              <li><a href=""><el-icon><FolderRemove /></el-icon>主页</a></li>
              <li><a href=""><el-icon><FolderRemove /></el-icon>主页</a></li>
              <li><a href=""><el-icon><FolderRemove /></el-icon>主页</a></li>
              <li><a href=""><el-icon><FolderRemove /></el-icon>主页</a></li>
            </ul>
          </el-col>
          <el-col :span = "3">fff</el-col>
        </el-row>
      </el-header>
      <el-container>
        <el-aside width="330px">
          <SideBar />
          <PostNews />
          <Menu />
        </el-aside>
        <el-container>
          <el-main>Main</el-main>
          <el-footer>Footer</el-footer>
        </el-container>
      </el-container>
    </el-container>
  </div> -->
</template>

<style scoped>
.top-nav {
  height: 60px;
  display: flex;
  justify-content: end;
  align-items: center;
  gap: 20px;
  li {
    a {
      font-size: 16px;
      color: rgba(53, 53, 53);
      display: flex;
      align-items: center;
      gap: 5px;
    }
    a:hover {
      border-bottom: 3px solid orange;
    }
   }
}
.logo {
  display: flex;
  height: 60px;
  justify-content: space-evenly;
  align-items: center;
  font-size: 17px;
}
</style>

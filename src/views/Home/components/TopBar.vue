<template>
  <div class="main">
    <header>
    <div class="logo">
      <div class="logo-icon">
        <span></span><span></span><span></span>
        <span></span><span></span><span></span>
        <span></span><span></span><span></span>
      </div>
      <div class="logo-text">Leonus</div>
    </div>

    <div class="title">Leonus - <strong>进一寸有进一寸的欢喜。</strong></div>

    <div class="icons">
      <i class="fa-solid fa-headphones"><el-icon><Headset /></el-icon></i>
      <i class="fa-solid fa-star"><el-icon><StarFilled /></el-icon></i>
      <i class="fa-solid fa-image"><el-icon><PictureFilled /></el-icon></i>
      <i class="fa-solid fa-magnifying-glass"><el-icon><Search /></el-icon></i>
      <i class="fa-solid fa-moon"><el-icon><Opportunity /></el-icon></i>
    </div>
  </header>
  </div>
</template>

<script setup>

</script>

<style scoped lang="scss">
.main {
    header {
        font-family: "Segoe UI", "Microsoft YaHei", sans-serif;
        background: linear-gradient(to right, #f8fafc, #f0f4ff, #fff);
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 60px;
        background: rgba(255, 255, 255, 0.5);
        backdrop-filter: blur(500px);
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 0 40px;
        box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
        z-index: 1000;
        transition: background 0.4s ease, box-shadow 0.4s ease;

        &.scrolled {
            background: #ffffff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
    }

    /* 左侧 Logo 区 */
    .logo {
    display: flex;
    align-items: center;
    gap: 10px;

    .logo-icon {
        font-size: 22px;
        display: grid;
        grid-template-columns: repeat(3, 4px);
        grid-template-rows: repeat(3, 4px);
        gap: 3px;

        span {
        width: 4px;
        height: 4px;
        background: #333;
        border-radius: 1px;
        }
    }

    .logo-text {
        font-size: 20px;
        font-weight: 700;
        color: #333;
    }
    }

    /* 中间标题 */
    .title {
    font-size: 16px;
    color: #444;
    font-weight: 500;

    strong {
        font-weight: 700;
    }
    }

    /* 右侧图标组 */
    .icons {
    display: flex;
    align-items: center;
    gap: 20px;

    i {
        font-size: 20px;
        color: #444;
        cursor: pointer;
        transition: transform 0.2s ease, color 0.2s ease;

        &:hover {
        transform: scale(1.15);
        color: #111;
        }
    }
    }
}

</style>

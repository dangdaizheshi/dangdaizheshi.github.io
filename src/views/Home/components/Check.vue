<template>
  <div class="main">
    <div class="profile-card">
    <div class="cover"></div>

    <div class="avatar">
      <!-- 头像为空白背景 -->
      <div class="status-dot"></div>
    </div>

    <div class="info">
      <div class="name">Leonus</div>
      <div class="desc">进一寸有进一寸的欢喜。</div>
    </div>

    <div class="stats">
      <div class="item">
        <div class="num">10</div>
        <div class="label">分类</div>
      </div>
      <div class="item">
        <div class="num">22</div>
        <div class="label">标签数</div>
      </div>
      <div class="item">
        <div class="num">82</div>
        <div class="label">文章数</div>
      </div>
    </div>
  </div>
  </div>
</template>

<script setup>

</script>

<style scoped lang="scss">
    .profile-card {
        margin-top: 100px;
      width: 300px;
      background: #fff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;

      &:hover {
        transform: translateY(-4px);
        box-shadow: 0 6px 25px rgba(0, 0, 0, 0.12);
      }

      .cover {
        width: 100%;
        height: 120px;
        background: linear-gradient(135deg, #e9f1ff, #f8faff);
      }

      .avatar {
        position: relative;
        width: 90px;
        height: 90px;
        margin: -45px auto 10px;
        border-radius: 50%;
        overflow: hidden;
        border: 4px solid #fff;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        background: #ccc; // 头像空白占位

        .status-dot {
          position: absolute;
          right: 6px;
          bottom: 6px;
          width: 16px;
          height: 16px;
          background: #3de35c;
          border: 2px solid #fff;
          border-radius: 50%;
        }
      }

      .info {
        padding: 10px 0 20px;

        .name {
          font-size: 20px;
          font-weight: 700;
          color: #333;
        }

        .desc {
          font-size: 14px;
          color: #666;
          margin-top: 6px;
        }
      }

      .stats {
        display: flex;
        border-top: 1px solid #eee;

        .item {
          flex: 1;
          padding: 12px 0;
          display: flex;
          flex-direction: column;
          gap: 4px;

          .num {
            font-size: 18px;
            font-weight: 700;
            color: #333;
          }

          .label {
            font-size: 13px;
            color: #666;
          }
        }
      }
    }
</style>

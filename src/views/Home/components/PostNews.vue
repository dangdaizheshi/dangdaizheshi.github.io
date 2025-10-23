<script setup>
</script>

<template>
  <div class="PostNewsContainer">
    <div class="up">
        公告
    </div>
    <p class="text">
        有问题请直接留言或添加QQ和微信。（上班忙可能没时间）
    </p>
  </div>
</template>

<style scoped>
.PostNewsContainer {
    width: calc(375px * 0.8);
    height: calc(190px * 0.8);
    background-color: rgb(252, 253, 255);
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    padding-left: 24px;
    padding-right: 40px;
    transition: all 0.3s;
}
.PostNewsContainer:hover {
    border: 1px solid blue;
}
.PostNewsContainer .text {
    color: rgb(117, 115, 115);
}
.PostNewsContainer .up {
    color: rgb(76, 73, 72);
}
</style>

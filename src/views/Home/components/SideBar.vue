<script setup>
</script>

<template>
    <div class = "SidebarContainer">
        <div class="myImage">
            <img src="@/assets/images/11.PNG" alt="">
        </div>
        <h1 class="myName">
            Dang-dai-zhe-shi
        </h1>
        <p class="myWord">
            幸福，就是猫吃鱼，狗啃骨头，猪睡觉
        </p>
        <ul class="myText">
            <li class = 'uuj'>
                <a href="">
                    <span>10</span>
                    <span>分类</span>
                </a>
            </li>
            <li class = 'uui'></li>
            <li class = 'uuj'>
                <a href="">
                    <span>10</span>
                    <span>标签书</span>
                </a>
            </li>
            <li class = 'uui'></li>
            <li class = 'uuj'>
                <a href="">
                    <span>10</span>
                    <span>文章数</span>
                </a>
            </li>
        </ul>
    </div>
</template>

<style scoped >
.SidebarContainer {
    background-color: rgb(252, 253, 255);
    width: calc(370px * 0.8);
    height: calc(410px * 0.8);
    border-radius: 10px;
}
.SidebarContainer .myImage{
    position: relative;
    width: 100%;
    height: calc(190px * 0.8);
    margin-bottom: calc(25px * 0.8);
}
.SidebarContainer .myImage img {
    position: absolute;
    bottom: 0;
    left: calc(((370px * 0.8) - (125px * 0.8)) / 2);
    width: calc(125px * 0.8);
    height: calc(125px * 0.8);
    border-radius: 50%;
}
.SidebarContainer .myName {
    font-size: 20px;
    color: rgb(76, 73, 72);
    text-align: center;
    font-weight: 600;
    margin-bottom: calc(15px * 0.8);
}
.SidebarContainer .myWord {
    text-align: center;
    font-size: 15px;
    color: rgb(76, 73, 72);
    margin-bottom: calc(25px * 0.8);
}
.SidebarContainer .myText {
    display: flex;
    justify-content: center;
    align-items: center;
    height: calc(60px * 0.8);
}
.SidebarContainer .myText .uuj {
    width: calc(85px * 0.8);
}
.SidebarContainer .myText li a {
    height: calc(60px * 0.8);
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
}
.SidebarContainer .myText .uui {
    border: 1px solid rgb(199, 198, 200);
    height: 40px;
    margin: 0 24px;
}
</style>
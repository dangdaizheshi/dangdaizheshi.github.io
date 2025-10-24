<script setup>

</script>

<template>
    <div class="container">
        <div class="logo">
            <img src="@/assets/images/11.PNG" alt="">
            <div class = "circle"></div>
        </div>
        <h1 class="name">
            xbn
        </h1>
        <div class="word">
            进一寸有进一寸的欢喜。
        </div>
        <ul class="list">
            <li class="box">
                <a href="">
                    <h2>10</h2>
                    <span>分类</span>
                </a>
            </li>
            <li class="line1 line"></li>
            <li class="box">
                <a href="">
                    <h2>23</h2>
                    <span>标签数</span>
                </a>
            </li>
            <li class="line2 line"></li>
            <li class="box">
                <a href="">
                    <h2>22</h2>
                    <span>文章数</span>
                </a>
            </li>
        </ul>
    </div>
</template>

<style scoped lang = "scss">
.container {
    background-color: rgba(252, 253, 255);
    width: 330px;
    height: 390px;
    border-radius: 1rem;
    overflow: hidden;
    .logo {
        position: relative;
        width: 100%;
        height: 200px;
        margin-bottom: 15px;
        background-image: 
        linear-gradient(to top, rgba(255,255,255,1), rgba(255,255,255,0)),
        url('@/assets/images/bg1.png'); 
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        img {
            position: absolute;
            left: calc(50% - 125px / 2);
            bottom: 0;
            width: 125px;
            height: 125px;
            border: 5px solid white;
            border-radius: 50%;
        }
        .circle {
            position: absolute;
            z-index: 2;
            top: 172px;
            left: 216px;
            width: 25px;
            height: 25px;
            border: 4px solid white;
            border-radius: 50%;
            background-color: rgba(107, 223, 143);
        }
    }
    .name {
        text-align: center;
        margin-bottom: 15px;
    }
    .word {
        text-align: center;
        margin-bottom: 15px;
    }
    .list {
        display: flex;
        justify-content: space-evenly;
        position: relative;
        padding: 6px;
        li {
            a {
                display: flex;
                height: 60px;
                flex-direction: column;
                justify-content: space-between;
                align-items: center;
            }
            a:hover {
                color: rgba(91, 131, 246);
            }
        }
        .line {
            height: 56px;
            border: 1px solid rgba(199, 198, 200);
        }
    }
}
</style>
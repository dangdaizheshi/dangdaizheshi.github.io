<script setup>
</script>

<template>
    <div class = "container">
        <div class = "head">
            <h2>目录</h2>
            <span>0</span>
        </div>
        <div class = 'change'>
            <p><a href="">修改源码</a></p>
            <p><a href="">修改配置文件</a></p>
        </div>
    </div>
</template>

<style scoped>
.container {
    width: 330px;
    height: 180px;
    background-color: rgba(252, 253, 255);
    border-radius: 1rem;
    overflow: hidden;
    padding: 30px 25px;
    .head {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 25px;
        margin-bottom: 25px;
        span {
            font-size: 26px;
            font-style: italic;
        }
    }
    .change{
        height: 70px;
        width: 270px;
        p {
            width: 270px;
            height: 40px;
            a {
                display: block;
                width: 270px;
                height: 35px;
                border-radius: 10px;
                line-height: 35px; 
                padding-left: 5px;
                transition: all .3s;
            }
            a:hover {
                background-color: rgba(73, 118, 245);
                color:rgba(252, 253, 255);
            }
        }
    }
}
</style>

<template>
    <article class="col-md-7 header-nav">
        <div class="nav1">
            <img src="../assets/bootstrap1.jpg" alt="">
            <p>Bootstrap</p>
        </div>
        <div class="nav2">
            <ul>
                <li>
                    <a href="">
                        <img src="../assets/React.png" alt="" class="img-fluid">                        
                        <p>React</p>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/React.png" alt="" class="img-fluid">                        
                        <p>React</p>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/React.png" alt="" class="img-fluid">                        
                        <p>React</p>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/logo.svg" alt="" class="img-fluid">                        
                        <p>React</p>
                    </a>
                </li>
            </ul>
        </div>
       
    </article>
</template>
<style scoped>
    .header-nav {
        display: flex;
    }
    .nav1 {
        width: 50%;
        height: 97%;
    }
    .nav1 img {
        width: 100%;
        height: 70%;
    }
    .nav1 p {
        font-size: 20px;
        text-align: center;
        height: 60px;
        padding-top: 5%;
        background-color: black;
        color: #fff;
    }
    .nav2 {
        width: 50%;
        /* height: 97%; */
    }
    ul {
        list-style: none;
        display: flex;
        flex-wrap: wrap;
        padding: 0px;
        margin: 0px;
    }
    ul li {
        flex:50%;
        height: 130px;
        margin-bottom: 10px;
    }
    ul li a {
        display: block;
        width: 90%;
        height: 70%;
        margin: 10px;
        margin-top: 25%;
    }
    ul li a img {
        max-width: 100%;
        margin-top: -10px;
        height: auto;
    }
    ul li p {
        background-color: black;
        text-align: center;
        color: #fff;
    }
    ul li:nth-child(4) a img {
        width: 65%;
        margin: 0px 20%;
        margin-top: -10px;
    }
</style>
<script lang="ts" setup>

</script>
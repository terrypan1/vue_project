<template>
    <header class="col-md-2">
        <div class="log">
            <a href="">
                <img src="../assets/boolstrap.png" alt="">
            </a>
        </div>
        <div class="nav1">
            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/camera-fill.svg" alt="" class="camera">
                        生活館
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/nature.svg" alt="" class="camera">
                        自然匯
                    </a>
                </li>
                <li>
                    <a href="#">
                        <i></i>
                        <img src="../assets/phone.svg" alt="" class="camera">
                        科技潮
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/telephone-plus.svg" alt="" class="camera">
                        奇趣事
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/wifi.svg" alt="" class="camera">
                        美食節
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>
<style scoped>
    .log a {
        display: block;
        width: 100%;
    }
    .log a img {
        width: 100%;
    }
    
    .log {
        padding-left: 0px;
    }
    .nav1 {
        background-color: #ccc;
    }
    .nav1 ul {
        padding: 0px;
        margin: 0px;
    }
    .nav1 ul li {
        list-style: none;
        width: 100%;
    }
    .nav1 ul li:nth-child(4) {
        border-bottom: #555;
    }
    .nav1 a {
        display: block;
        height: 50px;
        font-weight: 700;
        text-decoration: none;
        text-align: center;
        line-height: 50px;
        color: #555;
    }
    .nav1 a:hover {
        background-color: #fff;
        color: #333;
        border: 1px solid #333;
    }
    .camera {
        /* width: 15%; */
        max-width: 15%;
        margin-bottom: 5px;
    }
</style>
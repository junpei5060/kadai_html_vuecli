<template>
    <div>
        <div>
            <h1 id="news">NEWS</h1>
            <P class="news-title">ニュース</P>
        </div>

        <div class="news-content">
            <div class="news1">
                <img class="news-img" src="../../src/assets/news_img.jpg">
                <p class="news-day">2016/11/18</p>
                <p class="news-text">チーズアカデミー卒業生のコスゲさんによる<br>
                チーズだけをふんだんに使用した話題のピザ屋<br>
                「Kosuge Pizza」が渋谷でオープンしました！</p>
            </div>
            <div class="news1">
                <img class="news-img2" src="../../src/assets/news_img.jpg">
                <p class="news-day2">2016/11/18</p>
                <p class="news-text2">チーズアカデミー卒業生のコスゲさんによる<br>
                チーズだけをふんだんに使用した話題のピザ屋<br>
                「Kosuge Pizza」が渋谷でオープンしました！</p>
            </div>
            <div class="news1">
                <img class="news-img3" src="../../src/assets/news_img.jpg">
                <p class="news-day3">2016/11/18</p>
                <p class="news-text3">チーズアカデミー卒業生のコスゲさんによる<br>
                チーズだけをふんだんに使用した話題のピザ屋<br>
                「Kosuge Pizza」が渋谷でオープンしました！</p>
            </div>
        </div>
        <div class="btn-area">
            <button class="btn-more">More</button>
        </div>
    </div>
</template>

<style scoped>
#news{
    color: #ffd61a;
    font-size: 24px;
    font-weight: bold;
    padding-top: 60px;
    text-align: center;
}

.news-title{
    font-size: 16px;
    text-align: center;
    margin-top: 30px;
}

.news-content{
    margin-top: 60px;
    display: flex;
    justify-content: center;
}

.news-content:hover{
    cursor: pointer;
}

.news-day{
    margin-top: 30px;
    font-size: 14px;
}
.news-day2{
    margin-top: 30px;
    margin-left: 30px;
    font-size: 14px;
}
.news-day3{
    margin-top: 30px;
    margin-left: 30px;
    font-size: 14px;
}

.news-text{
    margin-top: 30px;
    font-size: 14px;
}
.news-text2{
    margin-top: 30px;
    font-size: 14px;
    margin-left: 30px;
}
.news-text3{
    margin-top: 30px;
    font-size: 14px;
    margin-left: 30px;
}

.news-img2{
    margin-left: 30px;
}

.news-img3{
    margin-left: 30px;
}

.btn-area{
    text-align: center;
}
.btn-more{
    margin-top: 60px;
    text-align: center;
    font-size: 18px;
    font-weight: bold;
    height: 60px;
    width: 300px;
    background-color: #ffd61a;
    color: #fff;
    cursor: pointer;
    border: none;
    border-radius: 50%;
}



</style>
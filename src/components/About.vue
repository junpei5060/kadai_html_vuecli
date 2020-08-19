<template>
    <div class="about">
        <h1 id="about">ABOUT</h1>
        <div class="about-text"> 
            <P class="about-text1">チーズアカデミーについて</P>
            <P class="about-text2">チーズアカデミーは、チーズ職人養成学校です。</P>
            <P class="about-text3">チーズの素晴らしさを、自給自足を通じて、できるだけ多くの人に知っていただきたい。<br>
            そして、食卓にはいつもチーズがあった、あの頃の当たり前をこの手で取り戻したい。</P>
            <P class="about-text4">そんな思いから、チーズ職人養成学校「チーズアカデミーTOKYO」は歩みを始めています。</P>
            <p class="about-text5">卒業後、チーズ自給自足のバックアップはもちろんのこと、<br>
            チーズ職人への就職・転職もサポートします。</p>
        </div>

        <div class="about-img">
            <div>
                <img  src="../../src/assets/about_04.jpg">
            </div>
            <div>
                <img  src="../../src/assets/about_03.jpg" >
            </div>
            <div>
                <img  src="../../src/assets/about_02.jpg" >
            </div>
            <div>
                <img  src="../../src/assets/about_01.jpg" >
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.about{
    text-align: center;
}

.about h1{
    color: #ffd61a;
    font-size: 24px;
    font-weight: bold;
    padding-top: 30px;
}

.about-text1{
    padding-top: 30px;
    font-size: 14px;
}
.about-text2{
    padding-top: 60px;
    font-size: 14px;
}
.about-text3{
    padding-top: 30px;
    font-size: 14px;
}
.about-text4{
    padding-top: 40px;
    font-size: 14px;
}
.about-text5{
    padding-top: 40px;
    font-size: 14px;
}

.about-img{
    display: flex;
    margin: 80px auto;
}

.about-img img{
    width: 100%;

}
</style>
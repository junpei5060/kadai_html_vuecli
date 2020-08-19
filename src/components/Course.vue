<template>
    <div>
        <div class="course">
            <h1 id="course">COURSE</h1>
            <div class="course-text"> 
            <P class="course-title1">未経験からでもスタートができるよう、カリキュラムは多くの専門家や</P>
            <P class="course-title2">現役チーズ職人のアドバイスのもと、作られました。</P>
            </div>
        </div>

        <div class = "course-introdunction">
            <img class="course-img1" src="../../src/assets/course_01.jpg" alt="画像です" >
            <div class="course-content">
                <p class="course-text1">本格的な農園を使った実地研修<p>
                <p class="course-text2">チーズアカデミーでは、
                本格的な農園を使った実地研修を<br>
                行うことができます。プロとして活躍するチーズ職人も<br>
                使用するような、広大で環境も整った農園を余すところ<br>
                なく使い、卒業時には本格的なチーズを自分の力で作れる<br>
                実践力の養成を目指します。</p>
            </div>
        </div>
    
        <div class = "course-introdunction2">
            <div class="course-content2">
                <p class="course-text2-1">必要な知識もしっかりと取得<p>
                <p class="course-text2-2">チーズ作りには、しっかりとした食に関する知識が<br>
                欠かせません。チーズアカデミーでは、一流講師陣による、<br>
                チーズ作りに必要ないろはを余すところなく学べます。<br>
                チーズそのものでなく、栄養学全般を学ぶことも<br>
                可能ですので、チーズ以外への展開も夢ではないでしょう。</p>
            </div>
            <img class="course-img2" src="../../src/assets/course_02.jpg" alt="画像です" >
        </div>

        <div class = "course-introdunction3">
        <img class="course-img3" src="../../src/assets/course_03.jpg" alt="画像です" >
            <div class="course-content3">
                <p class="course-text3-1">卒業制作はティスティング審査あり<p>
                <p class="course-text3-2">チーズアカデミーでは最後の2ヶ月間で卒業制作を実施。<br>
                卒業制作として、チーズ作りを実際に行います。卒業後、<br>
                一般参加によるティスティング審査があるため、作り手の<br>
                目線だけでなく、消費者の目線から、卒業制作作品としての<br>
                チーズを、しっかりと評価いただくことができます。</p>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style scoped>
    .course{
    text-align: center;
}

.course h1{
    color: #222222;
    font-size: 24px;
    font-weight: bold;
    padding-top: 30px;
}

.course-title1{
    padding-top: 30px;
    font-size: 14px;
}
.course-title2{
    padding-top: 20px;
    font-size: 14px;
}

.course-introdunction{
    display:flex;
    margin-top: 80px;
}

.course-img1{
    height: 400px;
    width: 600px;
}

.course-content{
    background-color: #fafafa;
    height: 400px;
    width: 1200px;

}

.course-text1{
    font-size: 24px;
    font-weight: bold;
    margin-left: 100px;
    margin-top: 120px;
}

.course-text2{
    font-size: 16px;
    margin-top: 40px;
    margin-left: 50px;
    line-height: 24px;
}
.course-introdunction2{
    display:flex;
    margin-top: 0;
}

.course-img2{
    height: 400px;
    width: 600px;
}

.course-content2{
    background-color: #fafafa;
    height: 400px;
    width: 1200px;

}

.course-text2-1{
    font-size: 24px;
    font-weight: bold;
    margin-left: 160px;
    margin-top: 120px;
}

.course-text2-2{
    font-size: 16px;
    margin-top: 40px;
    margin-left: 100px;
    line-height: 24px;

}

.course-introdunction3{
    display:flex;
    margin-top: 0;
}

.course-img3{
    height: 400px;
    width: 600px;
}

.course-content3{
    background-color: #fafafa;
    height: 400px;
    width: 1200px;

}

.course-text3-1{
    font-size: 24px;
    font-weight: bold;
    margin-left: 100px;
    margin-top: 120px;
}

.course-text3-2{
    font-size: 16px;
    margin-top: 40px;
    margin-left: 50px;
    line-height: 24px;
    max-width: 450px;
}

</style>
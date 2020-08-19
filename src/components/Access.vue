<template>
    <div id="access">
        <h1>Access</h1>
        <h2>会社情報</h2>
        <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.396444816524!2d139.71190211560247!3d35.667239180197576!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188c9fa9e2e881%3A0x35396adb5ba7ce03!2z44K444O844K644Ki44Kr44OH44Of44O85p2x5Lqs77yP6LW35qWt5a6244Ko44Oz44K444OL44Ki6aSK5oiQ5a2m5qCh77yI44OX44Ot44Kw44Op44Of44Oz44Kw77yJ!5e0!3m2!1sja!2sjp!4v1596954823004!5m2!1sja!2sjp" width="1200" height="350" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
        <table class="info">
            <tr>
            <th class="info-th">学校名</th>
            <td>チーズアカデミー東京</td>
            </tr>
            <tr>
            <th class="info-th">事務所所在地</th>
            <td>〒107-0061東京都港区北青山3-5-6 青朋ビル2F</td>
            </tr>
            <tr>
            <th class="info-th">TEL</th>
            <td>03-5413-5045</td>
            </tr>
            <tr>
            <th class="info-th">FAX</th>
            <td>03-5413-5046</td>
            </tr>
            <tr>
            <th class="info-th">MAIL</th>
            <td>dummy@cheeseacademy.tokyo</td>
            </tr>
        </table>
    </div>
</template>

<style scoped>
#access{
    margin-top: 60px;
    background-color: #fafafa;
    height: 930px;
    width: 1060px;
    margin: 0 auto;
}

#access h1{
    margin-top: 60px;
    text-align: center;
    font-size: 24px;
    font-weight: bold;
    padding-top: 60px;
}

#access h2{
    margin-top: 30px;
    text-align: center;
    font-size: 18px;
}

.map{
    margin-top: 60px;
    width: 1060px;
}

.info{
    margin-left: 320px;
    margin-top: 60px;
}
table{
    width: 100%;
}

.info-th{
    text-align: left;
    width: 15%;
    padding-top: 20px;
}

</style>
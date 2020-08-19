<template>
    <div>
        <div id="contact">
            <h1>CONTACT</h1>
            <p class="contact-text1">説明会お申し込み・お問い合わせ</p>
            <p class="contact-text2">ぜひ1度、足を運んでみませんか。説明会は随時開催中。<br>
                その他、お問い合わせもお気軽にどうぞ。お待ちしております。</p>
            <p class="contact-text3">※チーズアカデミーは実際には存在しません。<br>
                間違っても問い合わせしないようお願いいたします。</p>

            <v-app class="app">
                <v-form
                ref="form"
                v-model="valid"
                lazy-validation
                >
                <v-text-field
                    v-model="name"
                    :counter="10"
                    :rules="nameRules"
                    label="Name"
                    required
                ></v-text-field>
                <v-text-field
                    v-model="kana"
                    :counter="10"
                    :rules="nameRules"
                    label="かな"
                    required
                ></v-text-field>

                <v-text-field
                    v-model="email"
                    :rules="emailRules"
                    label="E-mail"
                    required
                ></v-text-field>

                <v-select
                    v-model="select"
                    :items="items"
                    :rules="[v => !!v || 'Item is required']"
                    label="チーズアカデミーを選んで理由"
                    required
                ></v-select>

                <v-checkbox
                    v-model="checkbox"
                    :rules="[v => !!v || 'You must agree to continue!']"
                    label="世界を変える準備はできてる?"
                    required
                ></v-checkbox>

                <v-btn
                    :disabled="!valid"
                    color="#F44336"
                    class="mr-12"
                    
                    @click="validate"
                >
                    Validate
                </v-btn>
                </v-form>
                </v-app>
        </div>
    </div>
</template>

<script>
export default {
data: () => ({
    valid: true,
    name: '',
    nameRules: [
    v => !!v || 'Name is required',
    v => (v && v.length <= 10) || 'Name must be less than 10 characters',
    ],
    email: '',
    emailRules: [
    v => !!v || 'E-mail is required',
    v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
    ],
    select: null,
    items: [
    '世界を変えたくなったから',
    'チーズで世界を変えたくなったから',
    '親に反対されてもチーズで世界を変えたくなったから',
    '世界を変える準備ができたから',
    ],
    checkbox: false,
}),
methods: {
    validate () {
    this.$refs.form.validate()
    },
    reset () {
    this.$refs.form.reset()
    },
    resetValidation () {
    this.$refs.form.resetValidation()
    },
},
}
</script>

<style scoped>
#contact{
    text-align: center;
}
#contact h1{
    margin-top: 60px;
    font-size: 24px;
    font-weight: bold;
}

.contact-text1{
    margin-top: 30px;
    font-size: 18px;
}
.contact-text2{
    margin-top: 60px;
    font-size: 18px;
}
.contact-text3{
    margin-top: 30px;
    font-size: 18px;
    margin-bottom: 140px;
}

.app{
    height: 700px;
}

</style>
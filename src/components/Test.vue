<template>
<v-app>
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
    class="mr-4"
    @click="validate"
>
    Validate
</v-btn>
</v-form>
</v-app>
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
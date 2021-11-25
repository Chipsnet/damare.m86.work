<template>
    <div>
        <div>
            <b-jumbotron class="jb-bg" fluid>
                <b-container class="text-white">
                    <h1 class="font-weight-bold">テキストチャットに力を。</h1>
                    <p class="font-weight-normal h5 mt-4">自分で運営できるDiscordの読み上げBot</p>
                </b-container>
            </b-jumbotron>
            <b-container class="text-center py-5">
                <h1>Damareとは？</h1>
                <div class="mt-5 h5">
                    <p>Damareは、Discordの読み上げBotです。</p>
                    <p>あなたのPCの上で動いて、Discordのチャットをボイスチャットで読み上げます。</p>
                    <div class="my-5">
                        <b-embed src="https://www.youtube.com/embed/kt_3HDIt3gQ"></b-embed>
                    </div>
                </div>
            </b-container>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style scoped>
    .jb-bg {
        background: rgb(0,212,255);
        background: linear-gradient(90deg, rgba(0,212,255,1) 15%, rgba(9,9,121,1) 72%, rgba(2,0,36,1) 100%);
    }
</style>
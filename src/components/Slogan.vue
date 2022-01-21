<template>
    <div class="content">
        <h2>{{slogan}}</h2>
        <p>Deixe o <b>Today’s Cards</b>, fazer parte do seu dia a dia.</p>
    </div>
</template>

<script>

export default {
    name: 'Slogan',
    props: {
        slogan: String
    }
}
</script>

<style scoped>
    .content {
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center
    }
    h2 {
        width:  60%;
        text-align:center;
        color: #fff;
        font-size: 2rem;
        margin-bottom: 0.5rem;
    }

    p {
        font-weight: 400;
        font-size: 1rem;

    }
</style>

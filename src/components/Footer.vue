<template>
    <div class="footer">
        <p>Escolha um Banco</p>
        <div class="cards">
            <div class="nubank" style="background: #820AD1;"><img class="img-card" src="../assets/bank-nubank.png" alt="Flag Nubank"></div>
            <div class="inter" style="background: #FF7A00;"><img class="img-card" src="../assets/bank-inter.svg" alt=""></div>
            <div class="c6bank" style="background: #D0D0CE; "><img class="img-card" src="../assets/bank-c6.svg" alt=""></div>
            <div class="santander" style="background: #FE0000; "><img  class="img-card" src="../assets/bank-santander.png" alt=""></div>
            <div class="next" style="background: #000; "><img class="img-card" src="../assets/bank-next.svg" alt=""></div>
            <div class="neon" style="background: #00BDE5; "><img  class="img-card" src="../assets/bank-neon.png" alt=""></div>
            <div class="original" style="background: #007929; "><img  class="img-card" src="../assets/bank-original.svg" alt=""></div>
        </div>
    </div>
</template>

<script>
export default {

}

</script>

<style scoped>
    .footer {
        margin-top:4rem;
    }
    .cards {
        display: flex;
        margin-top: 3rem
    }

    .cards > div {
        display: flex;
        padding: 0.5rem;
        width: 247px;
        cursor: pointer;
        justify-content: center;
        transition: 0.4s;
    }

    .cards > div:hover {
        transform: translateY(-10%);
    }
    .img-card {
        width:8rem;
    }
</style>
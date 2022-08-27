<template>
  <div class="container">
    <BarraIzq></BarraIzq>
    <LateralDerech></LateralDerech>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraIzq from '@/components/BarraIzquierdaComponent.vue';
import LateralDerech from '@/components/LateralDerechaComponent.vue';

export default defineComponent({
  components: {
    BarraIzq,
    LateralDerech,
  },
});
</script>

<style lang="scss">
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins',sans-serif;
}
body{
    background: lightblue;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
.container{
    position: relative;
    width: 100%;
    max-width: 1000px;
    min-height: 1000px;
    background: #fff;
    margin: 50px;
    display: grid;
    grid-template-columns: 1fr 2fr;
    box-shadow: 0 35px 55px rgba(0, 0, 0, 0.1);
}
@media (max-width:1000px)
{
    .container
    {
        margin: 10px;
        grid-template-columns: repeat(1,1fr);
    }
    .interest ul
    {
        grid-template-columns: repeat(2,1fr);
    }
}
@media (max-width:600px)
{
    .about .box
    {
        flex-direction: column;
    }
    .about .box .year_company
    {
        margin-bottom: 5px;
    }
    .interest ul
    {
        grid-template-columns: repeat(1,1fr);
    }
    .skills .box
    {
        grid-template-columns: repeat(1,1fr);
    }
}
</style>

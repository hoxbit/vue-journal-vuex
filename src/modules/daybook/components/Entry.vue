<template>
    <div class="entry-container mb-3 pointer p-2" @click="$router.push({name:'entry',params:{id:10}})">
        <!-- Titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021, jueves</span>
        </div>
        <!-- Descripcion -->
        <div class="entry-description">
            Deserunt occaecat do sint dolor consectetur quis voluptate incididunt ex adipisicing commodo. Occaecat commodo
            labore dolor aliqua excepteur sunt do do culpa eiusmod amet esse et. Incididunt tempor aliqua excepteur
            exercitation eiusmod quis veniam minim id incididunt voluptate. Officia velit incididunt elit ex.
        </div>
    </div>
</template>

<script>
 export default {

 }

</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }

    .entry-description {
        font-size: 12px;
    }
}
</style>

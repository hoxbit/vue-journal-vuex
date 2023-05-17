<template>
    <div class="entry-container mb-3 pointer p-2" @click="$router.push({name:'entry', params:{id:10}})">
        <!--Titulo-->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span>Julio</span>
            <span>2021, jueves</span>
        </div>
        <!--Descripcion-->
        <div class="entry-description">
            Nostrud consequat anim officia esse labore dolor sit reprehenderit et ex ea. Minim irure anim deserunt ipsum
            nulla. Cupidatat esse voluptate veniam deserunt proident veniam esse magna. Do mollit commodo ullamco aliquip
            consequat nisi est sit. Esse nulla irure mollit aliqua amet anim Lorem fugiat anim.
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
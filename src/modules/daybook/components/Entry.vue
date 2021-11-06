<template>
    <div 
        class="entry-container mb-3 pointer p-2"
        @click="$router.push({ name: 'entry', params: { id: 10} })"
    >
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">05</span>
            <span class="mx-1 fs-5">Noviembre</span>
            <span class="mx-2 fw-light">2021, Viernes</span>
        </div>

        <div class="entry-description">
            Lorem nostrud magna ullamco eiusmod ex commodo magna sit nulla do occaecat laborum. Sunt magna proident irure magna dolore laborum qui irure commodo voluptate pariatur excepteur. Elit cillum voluptate Lorem occaecat cillum labore nostrud.
        </div>
    </div>
</template>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    &:hover {
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    };

    .entry-description {
        font-size: 12px;
    }
}
</style>
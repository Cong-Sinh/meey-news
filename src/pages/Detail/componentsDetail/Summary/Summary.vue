<template>
    <p class="text-grey7 text-sm italic py-3 font-normal" :summary="summary">
        {{ summary }}

    </p>
</template>

<script>
export default {
    props: {
        summary: {
            type: String,
            default: "",
            riquery: true
        }
    }
}
</script>

<style></style>
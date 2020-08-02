<template>
    <div class="hello">
        <h1>I am {{name}}</h1>
    </div>
</template>

<script>
export default {
    name: "Know Me Page",
    props: {
        name: String
    }
}
</script>
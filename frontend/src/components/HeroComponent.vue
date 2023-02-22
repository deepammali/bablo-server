<template>
    <div class="container-fluid align-center">

        <img class="d-block mx-auto mt-4 mb-2" src="../assets/bablo-logo-removebg-preview.png" height="150" width="150">

        <div class="text-center">
            <h2 class="mt-2 display-6">
                Bablo is a peer-to-peer messaging platform
            </h2>
            <p class="lh-sm">
                {{ introText }}
            </p>
        </div>

    </div>
</template>

<script>
export default {
    name: "HeroComponent",
    props: {
        introText: String
    }
}
</script>
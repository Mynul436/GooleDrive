<template>
    <!-- <div> Navigation </div> -->

    <nav class="min-w-[200px]">
        <div class="h-[80px] px-3 flex items-center gap-3">
            <!-- <Link href="/">
                <ApplicationLogo
                    class="block h-9 w-auto fill-current text-gray-800"
                />
                <ApplicationLogo />
            </Link> -->
            <ApplicationLogo/>
        </div>
    </nav>
</template>

<script>
import { Link } from "@inertiajs/vue3";
import ApplicationLogo from "./ApplicationLogo.vue";
</script>

<style scoped></style>

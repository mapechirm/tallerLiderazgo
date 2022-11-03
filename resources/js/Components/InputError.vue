<template>
    <div v-show="message" class="text-danger">
        <strong>{{ message }}</strong>
    </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
    props: ["message"],
});
</script>

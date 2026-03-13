<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'ReversedMessage',
        data() {
            return {
                message: 'Hello Vue!',
            };
        },
        watch: {
            message(newValue: string, oldValue: string) {
                console.log(`new value: ${newValue}, old alue: ${oldValue}`)
            }
        }
    });
</script>

<template>
    <h2 class="heading"> I am {{ message }} </h2>
    <input type="text" v-model="message" placeholder="Enter your message" />
</template>
<template>
    <div class="icon" :class="{'rotate-180': rotate}">
        <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M17.4167 8.25L11 14.6667L4.58337 8.25" stroke="#111827" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
    </div>
</template>

<script lang="ts" setup>
import {defineProps} from "vue";
import type {PropType} from "vue";

const props = defineProps({
    rotate: {
        type: Boolean as PropType<boolean>,
        default: false,
    }
});
</script>
<template>
    <n-layout-header>
        <img src="https://i.gyazo.com/d936cdcc28e1f6d50c8b30eef7255d3d.png" height="50" />
    </n-layout-header>
</template>

<script>
import { defineComponent } from 'vue';
import { NLayoutHeader, NSpace, NAvatar, NH1, NButton } from 'naive-ui';

export default defineComponent({
    name: 'LuckyHeader',
    components: {
        NLayoutHeader,
        NSpace,
        NAvatar,
        NH1,
        NButton
    }
});
</script>

<style scoped>
.n-layout-header {
    background-color: #009ee1;
    padding: 16px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
</style>
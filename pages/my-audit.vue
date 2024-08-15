<template>
    <div>
        <van-tabs v-model="activeTab">
            <van-tab title="待审核">
                <div>111</div>
            </van-tab>
            <van-tab title="审核通过" />
            <van-tab title="审核驳回" />
        </van-tabs>
    </div>
</template>

<script setup lang="ts">
const activeTab = ref(0);
</script>

<style scoped></style>

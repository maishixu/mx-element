<script setup>
import { ref } from 'vue';
import Input from '@/components/Input/Input.vue';
const test = ref('');
</script>
<template>
  <Input v-model="test" placeholder="请输入..." type="textarea"> </Input>
</template>

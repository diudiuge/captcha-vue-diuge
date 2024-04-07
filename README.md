# Sliding verification code tool

This tool mainly provides developers with a simple and easy-to-use verification code system that can be deployed by themselves.

## Example

```vue
<script setup>
import { Hccaptcha } from 'hccaptcha-vue';
import { ref } from 'vue';

const captcha = ref(null), code = ref(undefined);

// Refresh
// captcha.value.refresh();
// Reset
// captcha.value.reset();
</script>

<template>
    <Hccaptcha ref="captcha" v-model:code="code" />
</template>
```

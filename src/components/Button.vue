<template>
 <button :style="{ background: color }" class="btn">{{label}}</button>
</template>



<script>
export default {
  props: {
    label: String,
    color: String
  }
}
</script>


<template>
  <div>
    <h2>{{ Name }}</h2>
    <p>{{ LongDesc }}</p>
  </div>
  <div class="References">
    <ul>
      <li>
        {{ References }}
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  props: ['Name', 'LongDesc', 'References'],
};
</script>
<style lang="scss"></style>

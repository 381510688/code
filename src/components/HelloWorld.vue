<template>
  <div>
    <div>Hello {{person.name}}</div>
    <div>Updated次数：{{count}}</div>
  </div>
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    person: Object
  },
  data() {
    return {
      count: 0
    };
  },
  updated() {
    this.count++;
  }
};
</script>
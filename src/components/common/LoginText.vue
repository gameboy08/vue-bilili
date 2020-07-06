<template>
  <div>
    <van-field
      :label="label"
      :type="type"
      :placeholder="placeholder"
      :rule="rule"
      v-model="content"
    ></van-field>
  </div>
</template>

<script>
export default {
  data() {
    return {
      content: ''
    }
  },
  props: ["label", "type", "placeholder", "rule"],
  methods: {
    handleInput() {
      const rule = new RegExp(this.rule)
      if(rule.test(this.content)) {
        this.$emit('inputChange', this.content)
      }
    }
  },
  watch: {
    content() {
      this.handleInput()
    }
  }
};
</script>

<style lang="scss"></style>

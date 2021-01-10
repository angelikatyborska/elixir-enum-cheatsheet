<template>
  <span :class="className" :title="ariaLabel">
    <span class="sr-only">{{ariaLabel}}</span>
  </span>
</template>

<script>
export default {
  name: 'shape',
  props: {
    shape: String,
    color: String,
    size: String,
  },
  data() { return {}; },
  computed: {
    className() {
      return `shape ${this.shape || 'undefined-shape'} ${this.color} ${this.size || ''}`;
    },
    ariaLabel() {
      const colors = { color1: 'purple', color2: 'blue', color3: 'pink' };
      const color = colors[this.color];
      const words = [this.size, color, this.shape || 'shape'].filter(x => x);

      if (words.length > 1) {
        return words.join(' ');
      }

      return 'any shape of any color';
    },
  },
};
</script>

<style scoped lang="scss">
.shape {
  display: inline-block;
  width: var(--shape-size);
  height: var(--shape-size);
  background-color: var(--undefined-shape-color);
  border: var(--shape-border-size) solid var(--shape-border-color);

  .code & {
    width: var(--small-shape-size);
    height: var(--small-shape-size);
  }

  &.smaller {
    width: calc(var(--shape-size) * 0.6);
    height: calc(var(--shape-size) * 0.6);
  }

  &.small {
    width: calc(var(--shape-size) * 0.8);
    height: calc(var(--shape-size) * 0.8);
  }

  &.big {
    width: calc(var(--shape-size) * 1.2);
    height: calc(var(--shape-size) * 1.2);
  }
}

.undefined-shape {
  border-top-left-radius: 50%;
  border-bottom-right-radius: 50%;
}

.circle {
  border-radius: 50%;
}

$stripe-width: 2px;
$stripe-opacity: 0.65;

.color1 {
    background-color: var(--shape-color1);
    background: repeating-linear-gradient(
        to right,
        rgba(255, 255, 255, 0),
        rgba(255, 255, 255, 0) $stripe-width * 0.5,
        rgba(255, 255, 255, $stripe-opacity) $stripe-width * 0.5,
        rgba(255, 255, 255, $stripe-opacity) $stripe-width * 1.5,
        rgba(255, 255, 255, 0) $stripe-width * 1.5,
        rgba(255, 255, 255, 0) $stripe-width * 2

    ),
    linear-gradient(to right, var(--shape-color1) 0%, var(--shape-color1) 100%);
}

.color2 {
  background-color: var(--shape-color2);
}

.color3 {
    background-color: var(--shape-color3);
    background: repeating-linear-gradient(
        to bottom,
        rgba(255, 255, 255, 0),
        rgba(255, 255, 255, 0) $stripe-width * 0.5,
        rgba(255, 255, 255, $stripe-opacity) $stripe-width * 0.5,
        rgba(255, 255, 255, $stripe-opacity) $stripe-width * 1.5,
        rgba(255, 255, 255, 0) $stripe-width * 1.5,
        rgba(255, 255, 255, 0) $stripe-width * 2
    ),
    linear-gradient(to right, var(--shape-color3) 0%, var(--shape-color3) 100%);
}

</style>

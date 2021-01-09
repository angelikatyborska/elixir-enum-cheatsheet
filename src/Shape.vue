<template>
  <span :class="className" :title="ariaLabel" :ariaLabel="ariaLabel">
    <svg v-if="!shape" viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg">
      <polygon points="22.246999740600586 1.1150000095367432 38.893001556396484 6.9070000648498535 35.9900016784668 38.89400100708008 11.031000137329102 38.90800094604492 1.1399999856948853 24.117000579833984 7.01200008392334 1.1260000467300415"/>
    </svg>
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
svg {
  overflow: visible;
}

.shape {
  display: inline-block;
  width: var(--shape-size);
  height: var(--shape-size);

  &:not(.undefined-shape) {
    background-color: var(--undefined-shape-color);
    border: var(--shape-border-size) solid var(--shape-border-color);
  }

  .code & {
    width: var(--small-shape-size);
    height: var(--small-shape-size);

    svg * {
      stroke-width: calc(var(--shape-border-size) * var(--svg-ratio) / var(--small-shape-ratio));
    }
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

  svg {
    display: inline-block;
    vertical-align: top;

    * {
      fill: var(--undefined-shape-color);
      stroke-width: calc(var(--shape-border-size) * var(--svg-ratio));
      stroke: var(--shape-border-color);
    }
  }
}

.circle {
  border-radius: 50%;
}

.color1 {
  svg * {
    fill: var(--shape-color1);
  }

  &:not(.undefined-shape) {
    background-color: var(--shape-color1);
  }
}

.color2 {
  svg * {
    fill: var(--shape-color2);
  }

  &:not(.undefined-shape) {
    background-color: var(--shape-color2);
  }
}

.color3 {
  svg * {
    fill: var(--shape-color3);
  }

  &:not(.undefined-shape) {
    background-color: var(--shape-color3);
  }
}

</style>

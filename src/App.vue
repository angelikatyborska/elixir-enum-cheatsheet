<template>
  <main>
    <h1>Elixir Enum Cheatsheet</h1>
    <div class="grid">

      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#filter/2">filter</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape shape="square"></shape><code>?</code>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="square" color="color3"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map/2">map</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape color="color2"></shape>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color2"></shape><code>,</code>
          <shape shape="square" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map_every/3">map_every</a></em>(2, fn </code>
        <shape></shape>
        <code> -> </code>
        <shape color="color2"></shape>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color2"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find/2">find</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape shape="circle"></shape><code>?</code>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <shape shape="circle" color="color2"></shape>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find_index/2">find_index</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape shape="circle"></shape><code>?</code>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>1</code>
      </div>

      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="square" color="color2"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#count/1">count</a></em>()</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>4</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#member?/2">member?</a></em>(</code>
        <shape shape="square" color="color3"></shape>
        <code>)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>true</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#all?/2">all?</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape color="color3"></shape><code>?</code>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>false</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#any?/2">any?</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape color="color3"></shape><code>?</code>
        <code> end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>true</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color2"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take/2">take</a></em>(2)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color2"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_every/2">take_every</a></em>(2)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape><code>,</code>
          <shape shape="square" color="color2"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_while/2">take_while</a></em>(fn </code>
        <shape></shape>
        <code> -> </code>
        <shape shape="circle"></shape>
        <code>? end)</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color3"></shape>
        </div>
        <code>]</code>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#random/1">random</a></em>()</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <shape shape="square" color="color3"></shape>
      </div>


      <div class="input">
        <code>[</code>
        <div class="list">
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="square" color="color3"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape>
        </div>
        <code>]</code>
      </div>
      <div class="code">
        <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#shuffle/1">shuffle</a></em>()</code>
      </div>
      <div class="arrow">→</div>
      <div class="output">
        <code>[</code>
        <div class="list">
          <shape shape="circle" color="color2"></shape><code>,</code>
          <shape shape="circle" color="color1"></shape><code>,</code>
          <shape shape="square" color="color1"></shape><code>,</code>
          <shape shape="square" color="color3"></shape>
        </div>
        <code>]</code>
      </div>

    </div>
  </main>
</template>

<script>

import Shape from './Shape.vue';

export default {
  name: 'app',
  components: { Shape },
  data() {},
};
</script>

<style lang="scss">
$breakpoint1: 640px;
$breakpoint2: 900px;
$text-color: #3f2947;

:root {
  --svg-ratio: 1;
  --small-shape-ratio: 0.5;
  --shape-size: 2rem;
  --small-shape-size: 1.2rem;
  --undefined-shape-color: #ccc;
  --shape-border-color: #{$text-color};
  --shape-border-size: 1px;
  --shape-color1: #a19bf7;
  --shape-color2: #9bccf7;
  --shape-color3: #f49bf7;
}

html {
  background-color: #f2f2f9;
  color: $text-color;
  font-size: 16px;

  @media screen and (min-width: $breakpoint1) {
    font-size: 18px;
  }
}

h1 {
  font-size: 2rem;
  margin-top: 40px;
  font-weight: normal;
}

main {
  max-width: 1200px;
  margin: 0 auto;
  font-family: 'Roboto', sans-serif;
  font-size: 1.3rem;
}

code {
  font-family: 'Roboto Mono', monospace;
  white-space: pre;
}

.grid {
  display: grid;
  align-items: center;
  grid-row-gap: 10px;
  margin: 20px 0 40px 0;
  padding: 20px;
  background-color: white;
  border-radius: 2px;
  border: 1px solid rgba($text-color, 0.2);
  box-shadow: 2px 2px 6px rgba($text-color, 0.1);

  @media screen and (min-width: $breakpoint1) {
    grid-template-columns: 1fr 1fr auto 1fr;
    padding: 40px;
    grid-column-gap: 20px;
    grid-row-gap: 30px;
  }
}


.input, .output, .code {
  display: flex;
  align-items: center;
}

.input {
  @media screen and (min-width: $breakpoint1) {
    justify-content: right;
  }
}

.output {
  margin-bottom: 30px;

  @media screen and (min-width: $breakpoint1) {
    margin-bottom: 0;
  }
}

.list {
  display: inline-flex;
}

.code {
  em {
    font-style: normal;
    font-weight: bold;
  }

  a {
    color: inherit;
  }
}


</style>

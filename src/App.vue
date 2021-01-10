<template>
  <div>
    <main>
      <h1>Elixir Enum Cheatsheet</h1>
      <div class="grid">

        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#filter/2">filter</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape shape="square"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#reject/2">reject</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape shape="square"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map/2">map</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape color="color2"></shape>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map_every/3">map_every</a></em><span class="token punctuation">(</span><span class="token number">2</span>, <span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape color="color2"></shape>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find/2">find</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape shape="circle"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <shape shape="circle" color="color2"></shape>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find_index/2">find_index</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape shape="circle"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token number">1</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#at/2">at</a></em><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <shape shape="circle" color="color2"></shape>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#count/1">count</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token number">4</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#count/1">count</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape color="color1"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token number">1</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="big"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="smaller"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#sort/1">sort</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="smaller"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="big"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="big"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="smaller"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#sort/2">sort</a></em><span class="token punctuation">(</span><span class="token atom">:desc</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="big"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="smaller"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="big"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="smaller"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#max/1">max</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <shape shape="square" color="color1" size="big"></shape>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1" size="big"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="smaller"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1" size="small"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#min/1">min</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <shape shape="square" color="color1" size="smaller"></shape>
        </div>

        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#member?/2">member?</a></em><span class="token punctuation">(</span></code>
          <shape shape="square" color="color3"></shape>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token atom">true</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#all?/2">all?</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape color="color3"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token atom">false</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#any?/2">any?</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape color="color3"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code><span class="token atom">true</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take/2">take</a></em><span class="token punctuation">(</span>2<span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_every/2">take_every</a></em><span class="token punctuation">(</span>2<span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_while/2">take_while</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> </code>
          <shape shape="circle"></shape>
          <code>?<span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/2">chunk_every</a></em>
            <span class="token punctuation">(</span>3<span class="token punctuation">,</span> 3<span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/2">chunk_every</a></em><span class="token punctuation">(</span>3<span class="token punctuation">,</span> 3<span class="token punctuation">,</span><span class="token atom"> :discard</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/2">chunk_every</a></em><span class="token punctuation">(</span>3<span class="token punctuation">,</span> 3<span class="token punctuation">, </span></code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/2">chunk_every</a></em>
            <span class="token punctuation">(</span>3, 2<span class="token punctuation">)</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_by/2">chunk_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#random/1">random</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
            <span v-bind:key="shape[2]" v-for="(shape, index) in shuffle([['square', 'color2', 0], ['circle', 'color3', 1], ['square', 'color3', 2], ['square', 'color1', 3]])">
              <shape :shape="shape[0]" :color="shape[1]" v-if="index === 0"></shape>
            </span>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#shuffle/1">shuffle</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <span v-bind:key="shape[2]" v-for="(shape, index) in shuffle([['square', 'color2', 0], ['circle', 'color3', 1], ['square', 'color3', 2], ['square', 'color1', 3]])">
              <shape :shape="shape[0]" :color="shape[1]"></shape><code v-if="index < 3" class="token punctuation">,</code>
            </span>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#reverse/1">reverse</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#uniq/1">uniq</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#uniq_by/2">uniq_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#dedup/1">dedup</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#intersperse/2">intersperse</a></em><span class="token punctuation">(</span></code>
          <shape shape="circle" color="color2"></shape>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#zip/1">zip</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <code class="token punctuation">{</code>
            <div class="list">
              <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
              <shape shape="square" color="color2"></shape>
            </div>
            <code class="token punctuation">},</code>
            <code class="token punctuation">{</code>
            <div class="list">
              <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
              <shape shape="square" color="color3"></shape>
            </div>
            <code class="token punctuation">}</code>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <code class="token punctuation">{</code>
            <div class="list">
              <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
              <shape shape="square" color="color2"></shape>
            </div>
            <code class="token punctuation">},</code>
            <code class="token punctuation">{</code>
            <div class="list">
              <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
              <shape shape="square" color="color3"></shape>
            </div>
            <code class="token punctuation">}</code>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#unzip/1">unzip</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#group_by/2">group_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <div class="lines">
            <div class="line">
              <code class="token punctuation">%{</code>
              <shape color="color3"></shape>
              <code> => </code><code class="token punctuation">[</code>
              <div class="list">
                <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
                <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
                <shape shape="square" color="color3"></shape>
              </div>
              <code class="token punctuation">], </code>
            </div>
            <div class="line">
              <code class="indentation"></code>
              <shape color="color1"></shape>
              <code> => </code><code class="token punctuation">[</code>
              <div class="list">
                <shape shape="square" color="color1"></shape>
              </div>
              <code class="token punctuation">]}</code>
            </div>
          </div>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#frequencies/1">frequencies</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <div class="lines">
            <div class="line">
              <code class="token punctuation">%{</code>
              <shape color="color3" shape="square"></shape>
              <code> => <span class="token number">2</span></code><code class="token punctuation">,</code>
            </div>
            <div class="line">
              <code class="indentation"></code>
              <shape color="color1" shape="square"></shape>
              <code> => <span class="token number">1</span></code><code class="token punctuation">,</code>
            </div>
            <div class="line">
              <code class="indentation"></code>
              <shape color="color3" shape="circle"></shape>
              <code> => <span class="token number">1</span></code><code class="token punctuation">}</code>
            </div>
          </div>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div class="code">
          <code>|> Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#frequencies_by/2">frequencies_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" aria-label="returns" title="returns">→</div>
        <div class="output">
          <code class="token punctuation">%{</code>
          <shape color="color3"></shape>
          <code> => <span class="token number">3</span></code><code class="token punctuation">, </code>
          <shape color="color1"></shape>
          <code> => <span class="token number">1</span></code><code class="token punctuation">}</code>
        </div>

      </div>
    </main>

    <footer>
      Created by <a href="https://angelika.me">Angelika Tyborska</a>
    </footer>
  </div>
</template>

<script>

import Shape from './Shape.vue';

export default {
  name: 'app',
  components: { Shape },
  data() {},
  methods: {
    shuffle(a) {
      const b = [...a];
      for (let i = b.length - 1; i > 0; i -= 1) {
        const j = Math.floor(Math.random() * (i + 1));
        [b[i], b[j]] = [b[j], b[i]];
      }
      return b;
    },
  },
};
</script>

<style lang="scss">
$breakpoint1: 640px;
$breakpoint2: 900px;
$text-color: #3f2947;
$keyword-color: #2e2e70;
$punctuation-color: #7c7899;
$number-color: #1d8e6e;
$background-color: #f2f2f9;
$margin-mini: 4px;
$margin-small: 8px;
$margin-medium: 16px;
$margin-big: 32px;
$margin-huge: 64px;
$wrapper-border-color: rgba($text-color, 0.2);

:root {
  --svg-ratio: 1;
  --small-shape-ratio: 0.5;
  --shape-size: 1.2rem;
  --small-shape-size: 0.6rem;
  --undefined-shape-color: #{darken($background-color, 5)};
  --shape-border-color: #{$text-color};
  --shape-border-size: 1px;
  --shape-color1: #a19bf7;
  --shape-color2: #9bccf7;
  --shape-color3: #f49bf7;
}

html {
  background-color: $background-color;
  color: $text-color;
  font-size: 18px;

  @media screen and (min-width: $breakpoint1) {
    font-size: 22px;
  }

  a {
    color: inherit;
  }
}

h1 {
  font-size: 1.4rem;
  margin-top: $margin-big;
  font-weight: normal;
}

main, footer {
  max-width: 1240px;
  margin: 0 auto;
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
}

footer {
  text-align: center;
  margin: 1rem auto;
  font-size: 0.6rem;
}

code {
  font-family: 'Roboto Mono', monospace;
  white-space: pre;
}

.grid {
  display: grid;
  align-items: center;
  grid-row-gap: 10px;
  margin: $margin-medium 0 $margin-big 0;
  padding: $margin-big $margin-medium;
  background-color: lighten($background-color, 10);
  border-radius: 2px;
  border: 1px solid $wrapper-border-color;
  box-shadow: 2px 2px 6px rgba($text-color, 0.1);
  overflow: auto;

  @media screen and (min-width: $breakpoint1) {
    grid-template-columns: 1fr 1fr auto 1fr;
    padding: $margin-big;
    grid-column-gap: $margin-medium;
    grid-row-gap: $margin-big;
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
  &:not(:last-child) {
    margin-bottom: $margin-big;
    padding-bottom: $margin-big;
    border-bottom: 1px solid $wrapper-border-color;
  }

  @media screen and (min-width: $breakpoint1) {
    &:not(:last-child) {
      margin-bottom: 0;
      padding-bottom: 0;
      border-bottom: 0;
    }
  }
}

.list {
  display: inline-flex;
  align-items: center;
}

.code {
  em {
    font-style: normal;
    font-weight: bold;
  }
}

.line {
  display: flex;
  align-items: center;
  white-space: pre;

  &:not(:last-child) {
    margin-bottom: 0.5em;
  }
}

.indentation:before {
  content: '  '
}

.token {
  &.keyword {
    color: $keyword-color;
  }

  &.punctuation {
    color: $punctuation-color;
  }

  &.number, &.atom {
    color: $number-color;
  }
}


</style>

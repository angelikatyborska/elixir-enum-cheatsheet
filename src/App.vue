<template>
  <div>
    <main>
      <h1>Elixir Enum Cheatsheet</h1>
      <div class="grid">

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
        <div id="reduce/3" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#reduce/3">reduce</a></em><span class="token punctuation">([], </span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token punctuation">, </code>
          <code>acc</code>
          <code class="token operator"> -> </code>
          <code class="token punctuation">[</code>
          <shape color="color2"></shape>
          <code class="token operator"> | </code>
          <code>acc</code>
          <code class="token punctuation">]</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
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
        <div id="map/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map/2">map</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color2"></shape>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="map_every/3" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map_every/3">map_every</a></em><span class="token punctuation">(</span><span class="token number">2</span>, <span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color2"></shape>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="filter/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#filter/2">filter</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="square"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="reject/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#reject/2">reject</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="square"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="find/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find/2">find</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="circle"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="find_index/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#find_index/2">find_index</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="circle"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="at/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#at/2">at</a></em><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <shape shape="circle" color="color2"></shape>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="with_index/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#with_index/1">with_index</a></em><span class="token punctuation">()</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <code class="token punctuation">{</code>
            <shape shape="circle" color="color1"></shape>
            <code class="token punctuation">,</code>
            <code class="token number">0</code>
            <code class="token punctuation">},{</code>
            <shape shape="circle" color="color2"></shape>
            <code class="token punctuation">,</code>
            <code class="token number">1</code>
            <code class="token punctuation">},{</code>
            <shape shape="circle" color="color3"></shape>
            <code class="token punctuation">,</code>
            <code class="token number">2</code>
            <code class="token punctuation">}</code>
          </div>
          <code class="token punctuation">]</code>
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
        <div id="count/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#count/1">count</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="count/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#count/2">count</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color1"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code><span class="token number">1</span></code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code class="token punctuation">]</code>
        </div>
        <div id="concat/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#concat/1">concat</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">,</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>


        <div class="input">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="join/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#join/2">join</a></em>
            <span class="token punctuation">(</span>
            <span class="token string">" ~ "</span>
            <span class="token punctuation">)</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token string">"</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token string"> ~ </code>
            <shape shape="circle" color="color3"></shape><code class="token string"> ~ </code>
            <shape shape="circle" color="color2"></shape><code class="token string"> ~ </code>
            <shape shape="circle" color="color3"></shape>
          </div>
          <code class="token string">"</code>
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
        <div id="sort/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#sort/1">sort</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="sort/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#sort/2">sort</a></em><span class="token punctuation">(</span><span class="token atom">:desc</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="max/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#max/1">max</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="min/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#min/1">min</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="empty?/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#empty?/1">empty?</a></em><span class="token punctuation">()</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="member?/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#member?/2">member?</a></em><span class="token punctuation">(</span></code>
          <shape shape="square" color="color3"></shape>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="all?/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#all?/2">all?</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color3"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="any?/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#any?/2">any?</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color3"></shape><code>?</code>
          <code><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="take/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take/2">take</a></em><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="take_every/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_every/2">take_every</a></em><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="take_while/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_while/2">take_while</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="circle"></shape>
          <code>?<span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="drop/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#drop/2">drop</a></em><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
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
        <div id="drop_every/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#drop_every/2">drop_every</a></em><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
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
        <div id="drop_while/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#drop_while/2">drop_while</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape shape="circle"></shape>
          <code>?<span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color2"></shape>
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
        <div id="slice/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#slice/2">slice</a></em><span class="token punctuation">(</span><span class="token number">2..3</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
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
        <div id="split/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#split/2">split</a></em><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">],</code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color2"></shape>
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
        <div id="chunk_every/4" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/4">chunk_every</a></em>
            <span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span><span class="token number"> 3</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="chunk_every/4-3" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/4">chunk_every</a></em><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span><span class="token number"> 3</span><span class="token punctuation">, </span></code>
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape>
          </div>
          <code class="token punctuation">]</code>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="chunk_every/4-2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/4">chunk_every</a></em><span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span><span class="token number"> 3</span><span class="token punctuation">,</span><span class="token atom"> :discard</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="chunk_every/4-4" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_every/4">chunk_every</a></em>
            <span class="token punctuation">(</span><span class="token number">3</span><span class="token punctuation">,</span><span class="token number"> 2</span><span class="token punctuation">)</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="chunk_by/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#chunk_by/2">chunk_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="random/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#random/1">random</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="take_random/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#take_random/2">take_random</a></em>
            <span class="token punctuation">(</span>
            <span class="token number">2</span>
            <span class="token punctuation">)</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <span v-bind:key="shape[2]" v-for="(shape, index) in shuffle([['square', 'color2', 0], ['circle', 'color3', 1], ['square', 'color3', 2], ['square', 'color1', 3]])">
              <shape :shape="shape[0]" :color="shape[1]" v-if="index < 2"></shape><code v-if="index < 1" class="token punctuation">,</code>
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
        <div id="shuffle/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#shuffle/1">shuffle</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="reverse/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#reverse/1">reverse</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="uniq/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#uniq/1">uniq</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="uniq_by/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#uniq_by/2">uniq_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="dedup/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#dedup/1">dedup</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="intersperse/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#intersperse/2">intersperse</a></em><span class="token punctuation">(</span></code>
          <shape shape="circle" color="color2"></shape>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
          <div class="list">
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color1"></shape>
          </div>
          <code class="token punctuation">]</code>
        </div>
        <div id="map_intersperse/3" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#map_intersperse/3">map_intersperse</a></em><span class="token punctuation">(</span></code>
          <shape shape="circle" color="color2"></shape>
          <code class="token punctuation">, </code>
          <code><span class="token keyword">fn </span></code>
          <shape></shape>
          <code class="token operator"> -> </code>
          <shape color="color3"></shape>
          <code><span class="token keyword"> end</span></code>
          <code><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">[</code>
          <div class="list">
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape><code class="token punctuation">,</code>
            <shape shape="circle" color="color2"></shape><code class="token punctuation">,</code>
            <shape shape="square" color="color3"></shape>
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
        <div id="zip/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#zip/1">zip</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="unzip/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#unzip/1">unzip</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
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
        <div id="group_by/3" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#group_by/3">group_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <div class="lines">
            <div class="line">
              <code class="token punctuation">%{</code>
              <shape color="color3"></shape>
              <code class="token operator"> => </code><code class="token punctuation">[</code>
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
              <code class="token operator"> => </code><code class="token punctuation">[</code>
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
        <div id="frequencies/1" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#frequencies/1">frequencies</a></em>
            <span class="token punctuation">()</span>
          </code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <div class="lines">
            <div class="line">
              <code class="token punctuation">%{</code>
              <shape color="color3" shape="square"></shape>
              <code><span class="token operator"> => </span><span class="token number">2</span></code><code class="token punctuation">,</code>
            </div>
            <div class="line">
              <code class="indentation"></code>
              <shape color="color1" shape="square"></shape>
              <code><span class="token operator"> => </span><span class="token number">1</span></code><code class="token punctuation">,</code>
            </div>
            <div class="line">
              <code class="indentation"></code>
              <shape color="color3" shape="circle"></shape>
              <code><span class="token operator"> => </span><span class="token number">1</span></code><code class="token punctuation">}</code>
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
        <div id="frequencies_by/2" class="code">
          <code><span class="token operator">|> </span>Enum.<em><a href="https://hexdocs.pm/elixir/Enum.html#frequencies_by/2">frequencies_by</a></em><span class="token punctuation">(</span><span class="token keyword">fn </span></code>
          <shape></shape>
          <code> -> color<span class="token punctuation">(</span></code>
          <shape></shape>
          <code><span class="token punctuation">)</span><span class="token keyword"> end</span><span class="token punctuation">)</span></code>
        </div>
        <div class="arrow" title="returns">
          <span aria-hidden="true">→</span><span class="sr-only">returns</span>
        </div>
        <div class="output">
          <code class="token punctuation">%{</code>
          <shape color="color3"></shape>
          <code> => <span class="token number">3</span></code><code class="token punctuation">, </code>
          <shape color="color1"></shape>
          <code> => <span class="token number">1</span></code><code class="token punctuation">}</code>
        </div>

      </div>
    </main>

    <aside>
      <h2 id="legend">Symbol reference</h2>
      <ul class="legend">
        <li><shape></shape> means any shape of any color</li>
        <li><shape shape="square"></shape> means a square of any color</li>
        <li><shape shape="circle"></shape> means a circle of any color</li>
        <li><shape color="color1"></shape> means any purple shape or the color purple</li>
        <li><shape color="color2"></shape> means any blue shape or the color blue</li>
        <li><shape color="color3"></shape> means any pink shape or the color pink</li>
      </ul>
    </aside>

    <footer>
      <p><a href="https://github.com/angelikatyborska/elixir-enum-cheatsheet/issues">Report a problem</a>.</p>
      <p>Created by <a href="https://angelika.me">Angelika Tyborska</a>.</p>
    </footer>
  </div>
</template>

<script>

import Shape from './Shape.vue';

export default {
  name: 'app',
  components: { Shape },
  data() { return {}; },
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
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}

$breakpoint1: 640px;
$breakpoint2: 900px;
$breakpoint3: 1260px;
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
  --small-shape-ratio: 0.5;
  --shape-size: 1.1rem;
  --small-shape-size: 0.55rem;
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
    font-size: 20px;
  }

  @media screen and (min-width: $breakpoint3) {
    font-size: 21px;
  }

  a {
    color: inherit;
  }
}

body {
  margin: $margin-small;

  @media screen and (min-width: $breakpoint1) {
    margin: $margin-medium;
  }

  @media screen and (min-width: $breakpoint2) {
    margin: $margin-big;
  }

  @media screen and (min-width: $breakpoint3) {
    margin: $margin-small;
  }
}

h1 {
  font-size: 1.4rem;
  margin-top: $margin-big;
  font-weight: normal;
}

main, aside, footer {
  max-width: 1240px;
  margin: 0 auto;
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
}

footer, aside {
  margin: 1rem auto;
}

aside {
  font-size: 0.8rem;
}

footer {
  text-align: center;
  font-size: 0.6rem;
}

code {
  font-family: 'Roboto Mono', monospace;
  white-space: pre;
}

.grid {
  display: grid;
  grid-row-gap: $margin-small;
  margin: $margin-medium 0 $margin-big 0;
  padding: $margin-big $margin-medium;
  background-color: lighten($background-color, 10);
  border-radius: 2px;
  border: 1px solid $wrapper-border-color;
  box-shadow: 2px 2px 6px rgba($text-color, 0.1);
  overflow: auto;

  @media screen and (min-width: $breakpoint2) {
    grid-template-columns: 1fr auto 3fr;
    padding: $margin-big;
    grid-row-gap: 0;
  }

  @media screen and (min-width: $breakpoint3) {
    grid-template-columns: 1fr 1fr auto 1fr;
  }
}

@media screen and (min-width: $breakpoint2) {
  .code {
    grid-column: 2 / 4;
  }

  .arrow {
    grid-column: 2 / 3;
  }

  .output {
    grid-column: 3 / 4;
  }
}

@media screen and (min-width: $breakpoint3) {
  .code {
    grid-column: 2 / 3;
  }

  .arrow {
    grid-column: 3 / 4;
  }

  .output {
    grid-column: 4 / 5;
  }
}

.input, .output, .code, .arrow {
  display: flex;
  align-items: center;
}

.input, .arrow {
  @media screen and (min-width: $breakpoint2) {
    justify-content: right;
  }
}

.output {
  margin-bottom: $margin-big;
  padding-bottom: $margin-big;
  border-bottom: 1px solid $wrapper-border-color;
}

@media screen and (min-width: $breakpoint2) {
  .input, .code {
    padding-top: $margin-big;
    padding-bottom: $margin-medium;
  }
  .output, .arrow {
    padding-bottom: $margin-big;
    border-bottom: 1px solid $wrapper-border-color;
    margin-bottom: 0;
  }
}

@media screen and (min-width: $breakpoint3) {
  .input, .code, .output, .arrow {
    padding-top: $margin-big;
    padding-bottom: $margin-big;
    border-bottom: 1px solid $wrapper-border-color;
    margin-bottom: 0;
  }
}

.arrow {
  padding-right: $margin-medium;
  display: flex;
  align-items: flex-start;
}

@media screen and (min-width: $breakpoint2) {
  .input {
    padding-right: $margin-medium;
  }
}

@media screen and (min-width: $breakpoint3) {
  .arrow {
    padding-left: $margin-medium;
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

  &.punctuation, &.operator {
    color: $punctuation-color;
  }

  &.number, &.atom, &.string {
    color: $number-color;
  }
}

.arrow {
  color: $punctuation-color;
}

.legend {
  list-style: none;
  display: grid;
  justify-content: start;
  margin: 0 0 $margin-big 0;
  padding: 0;
  grid-template-columns: auto;
  grid-column-gap: $margin-medium;
  grid-row-gap: $margin-small;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr;
  grid-auto-flow: column;

  @media screen and (min-width: $breakpoint1) {
    grid-template-columns: auto auto;
    grid-template-rows: 1fr 1fr 1fr;
    margin: 0 0 $margin-huge 0;
  }

  .shape {
    vertical-align: middle;
  }
}

</style>

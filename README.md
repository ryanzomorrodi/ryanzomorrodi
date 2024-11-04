<style>
  html {
    color: #1a1a1a;
    background-color: #fdfdfd;
  }
  body {
    margin: 0 auto;
    max-width: 36em;
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 50px;
    padding-bottom: 50px;
    hyphens: auto;
    overflow-wrap: break-word;
    text-rendering: optimizeLegibility;
    font-kerning: normal;
  }
  @media (max-width: 600px) {
    body {
      font-size: 0.9em;
      padding: 12px;
    }
    h1 {
      font-size: 1.8em;
    }
  }
  @media print {
    html {
      background-color: white;
    }
    body {
      background-color: transparent;
      color: black;
      font-size: 12pt;
    }
    p, h2, h3 {
      orphans: 3;
      widows: 3;
    }
    h2, h3, h4 {
      page-break-after: avoid;
    }
  }
  p {
    margin: 1em 0;
  }
  a {
    color: #1a1a1a;
  }
  a:visited {
    color: #1a1a1a;
  }
  img {
    max-width: 100%;
  }
  svg {
    height: auto;
    max-width: 100%;
  }
  h1, h2, h3, h4, h5, h6 {
    margin-top: 1.4em;
  }
  h5, h6 {
    font-size: 1em;
    font-style: italic;
  }
  h6 {
    font-weight: normal;
  }
  ol, ul {
    padding-left: 1.7em;
    margin-top: 1em;
  }
  li > ol, li > ul {
    margin-top: 0;
  }
  blockquote {
    margin: 1em 0 1em 1.7em;
    padding-left: 1em;
    border-left: 2px solid #e6e6e6;
    color: #606060;
  }
  code {
    font-family: Menlo, Monaco, Consolas, 'Lucida Console', monospace;
    font-size: 85%;
    margin: 0;
    hyphens: manual;
  }
  pre {
    margin: 1em 0;
    overflow: auto;
  }
  pre code {
    padding: 0;
    overflow: visible;
    overflow-wrap: normal;
  }
  .sourceCode {
   background-color: transparent;
   overflow: visible;
  }
  hr {
    background-color: #1a1a1a;
    border: none;
    height: 1px;
    margin: 1em 0;
  }
  table {
    margin: 1em 0;
    border-collapse: collapse;
    width: 100%;
    overflow-x: auto;
    display: block;
    font-variant-numeric: lining-nums tabular-nums;
  }
  table caption {
    margin-bottom: 0.75em;
  }
  tbody {
    margin-top: 0.5em;
    border-top: 1px solid #1a1a1a;
    border-bottom: 1px solid #1a1a1a;
  }
  th {
    border-top: 1px solid #1a1a1a;
    padding: 0.25em 0.5em 0.25em 0.5em;
  }
  td {
    padding: 0.125em 0.5em 0.25em 0.5em;
  }
  header {
    margin-bottom: 4em;
    text-align: center;
  }
  #TOC li {
    list-style: none;
  }
  #TOC ul {
    padding-left: 1.3em;
  }
  #TOC > ul {
    padding-left: 0;
  }
  #TOC a:not(:hover) {
    text-decoration: none;
  }
  code{white-space: pre-wrap;}
  span.smallcaps{font-variant: small-caps;}
  div.columns{display: flex; gap: min(4vw, 1.5em);}
  div.column{flex: auto; overflow-x: auto;}
  div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
  /* The extra [class] is a hack that increases specificity enough to
     override a similar rule in reveal.js */
  ul.task-list[class]{list-style: none;}
  ul.task-list li input[type="checkbox"] {
    font-size: inherit;
    width: 0.8em;
    margin: 0 0.8em 0.2em -1.6em;
    vertical-align: middle;
  }
  /* CSS for syntax highlighting */
  pre > code.sourceCode { white-space: pre; position: relative; }
  pre > code.sourceCode > span { line-height: 1.25; }
  pre > code.sourceCode > span:empty { height: 1.2em; }
  .sourceCode { overflow: visible; }
  code.sourceCode > span { color: inherit; text-decoration: inherit; }
  div.sourceCode { margin: 1em 0; }
  pre.sourceCode { margin: 0; }
  @media screen {
  div.sourceCode { overflow: auto; }
  }
  @media print {
  pre > code.sourceCode { white-space: pre-wrap; }
  pre > code.sourceCode > span { display: inline-block; text-indent: -5em; padding-left: 5em; }
  }
  pre.numberSource code
    { counter-reset: source-line 0; }
  pre.numberSource code > span
    { position: relative; left: -4em; counter-increment: source-line; }
  pre.numberSource code > span > a:first-child::before
    { content: counter(source-line);
      position: relative; left: -1em; text-align: right; vertical-align: baseline;
      border: none; display: inline-block;
      -webkit-touch-callout: none; -webkit-user-select: none;
      -khtml-user-select: none; -moz-user-select: none;
      -ms-user-select: none; user-select: none;
      padding: 0 4px; width: 4em;
    }
  pre.numberSource { margin-left: 3em;  padding-left: 4px; }
  div.sourceCode
    { color: #24292e;  }
  @media screen {
  pre > code.sourceCode > span > a:first-child::before { text-decoration: underline; }
  }
  code span { color: #24292e; } /* Normal */
  code span.al { color: #ff5555; font-weight: bold; } /* Alert */
  code span.an { color: #6a737d; } /* Annotation */
  code span.at { color: #d73a49; } /* Attribute */
  code span.bn { color: #005cc5; } /* BaseN */
  code span.bu { color: #d73a49; } /* BuiltIn */
  code span.cf { color: #d73a49; } /* ControlFlow */
  code span.ch { color: #032f62; } /* Char */
  code span.cn { color: #005cc5; } /* Constant */
  code span.co { color: #6a737d; } /* Comment */
  code span.cv { color: #6a737d; } /* CommentVar */
  code span.do { color: #6a737d; } /* Documentation */
  code span.dt { color: #d73a49; } /* DataType */
  code span.dv { color: #005cc5; } /* DecVal */
  code span.er { color: #ff5555; text-decoration: underline; } /* Error */
  code span.ex { color: #d73a49; font-weight: bold; } /* Extension */
  code span.fl { color: #005cc5; } /* Float */
  code span.fu { color: #6f42c1; } /* Function */
  code span.im { color: #032f62; } /* Import */
  code span.in { color: #6a737d; } /* Information */
  code span.kw { color: #d73a49; } /* Keyword */
  code span.op { color: #24292e; } /* Operator */
  code span.ot { color: #6f42c1; } /* Other */
  code span.pp { color: #d73a49; } /* Preprocessor */
  code span.re { color: #6a737d; } /* RegionMarker */
  code span.sc { color: #005cc5; } /* SpecialChar */
  code span.ss { color: #032f62; } /* SpecialString */
  code span.st { color: #032f62; } /* String */
  code span.va { color: #e36209; } /* Variable */
  code span.vs { color: #032f62; } /* VerbatimString */
  code span.wa { color: #ff5555; } /* Warning */
</style>

<style>
body {
  box-sizing: border-box;
  min-width: 200px;
  max-width: 980px;
  margin: 0 auto;
  padding: 45px;
}
</style> 

<body class="markdown-body">

<div class="sourceCode" id="cb1"><pre
class="sourceCode yaml"><code class="sourceCode yaml"><span id="cb1-1"><a href="#cb1-1" aria-hidden="true" tabindex="-1"></a><span class="fu">name</span><span class="kw">:</span><span class="at"> Ryan Zomorrodi</span></span>
<span id="cb1-2"><a href="#cb1-2" aria-hidden="true" tabindex="-1"></a><span class="fu">from</span><span class="kw">:</span><span class="at"> Chicago</span></span>
<span id="cb1-3"><a href="#cb1-3" aria-hidden="true" tabindex="-1"></a><span class="fu">url</span><span class="kw">:</span><span class="at"> <a href="https://ryanzomorrodi.github.io">ryanzomorrodi.github.io</a></span></span>
<span id="cb1-4"><a href="#cb1-4" aria-hidden="true" tabindex="-1"></a><span class="fu">role</span><span class="kw">:</span><span class="at"> Research Associate</span></span>
<span id="cb1-5"><a href="#cb1-5" aria-hidden="true" tabindex="-1"></a><span class="fu">company</span><span class="kw">:</span><span class="at"> Children&#39;s Environmental Health Initiative</span></span>
<span id="cb1-6"><a href="#cb1-6" aria-hidden="true" tabindex="-1"></a><span class="fu">education</span><span class="kw">:</span></span>
<span id="cb1-7"><a href="#cb1-7" aria-hidden="true" tabindex="-1"></a><span class="at">  </span><span class="kw">-</span><span class="at"> </span><span class="fu">name</span><span class="kw">:</span><span class="at"> MS in Health Analytics</span></span>
<span id="cb1-8"><a href="#cb1-8" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">institution</span><span class="kw">:</span><span class="at"> University of Illinois Chicago</span></span>
<span id="cb1-9"><a href="#cb1-9" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">dates</span><span class="kw">:</span><span class="at"> </span><span class="kw">[</span><span class="st">&quot;2023-08&quot;</span><span class="kw">,</span><span class="at"> </span><span class="st">&quot;Present&quot;</span><span class="kw">]</span></span>
<span id="cb1-10"><a href="#cb1-10" aria-hidden="true" tabindex="-1"></a><span class="at">  </span><span class="kw">-</span><span class="at"> </span><span class="fu">name</span><span class="kw">:</span><span class="at"> BS in Biology</span></span>
<span id="cb1-11"><a href="#cb1-11" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">institution</span><span class="kw">:</span><span class="at"> University of Illinois Chicago</span></span>
<span id="cb1-12"><a href="#cb1-12" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">dates</span><span class="kw">:</span><span class="at"> </span><span class="kw">[</span><span class="st">&quot;2019-08&quot;</span><span class="kw">,</span><span class="at"> </span><span class="st">&quot;2023-05&quot;</span><span class="kw">]</span></span>
<span id="cb1-13"><a href="#cb1-13" aria-hidden="true" tabindex="-1"></a><span class="fu">projects</span><span class="kw">:</span></span>
<span id="cb1-14"><a href="#cb1-14" aria-hidden="true" tabindex="-1"></a><span class="at">  </span><span class="kw">-</span><span class="at"> </span><span class="fu">name</span><span class="kw">:</span><span class="at"> Rate Stabilizing Toolbox</span></span>
<span id="cb1-15"><a href="#cb1-15" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">language</span><span class="kw">:</span><span class="at"> Python</span></span>
<span id="cb1-16"><a href="#cb1-16" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">url</span><span class="kw">:</span><span class="at"> </span></span>
<span id="cb1-17"><a href="#cb1-17" aria-hidden="true" tabindex="-1"></a><span class="at">  </span><span class="kw">-</span><span class="at"> </span><span class="fu">name</span><span class="kw">:</span><span class="at"> centr</span></span>
<span id="cb1-18"><a href="#cb1-18" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">language</span><span class="kw">:</span><span class="at"> R</span></span>
<span id="cb1-19"><a href="#cb1-19" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">url</span><span class="kw">:</span><span class="at"> <a href="https://ryanzomorrodi.github.io/centr">ryanzomorrodi.github.io/centr</a></span></span>
<span id="cb1-20"><a href="#cb1-20" aria-hidden="true" tabindex="-1"></a><span class="at">  </span><span class="kw">-</span><span class="at"> </span><span class="fu">name</span><span class="kw">:</span><span class="at"> healthatlas </span></span>
<span id="cb1-21"><a href="#cb1-21" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">language</span><span class="kw">:</span><span class="at"> R</span></span>
<span id="cb1-22"><a href="#cb1-22" aria-hidden="true" tabindex="-1"></a><span class="at">    </span><span class="fu">url</span><span class="kw">:</span><span class="at"> <a href="https://ryanzomorrodi.github.io/healthatlas">ryanzomorrodi.github.io/healthatlas</a></span></span></code></pre></div>

</body>
</html>

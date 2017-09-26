# checkme
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
<p>This cheatsheet is specifically <em>Markdown Here's</em> version of Github-flavored Markdown. This differs slightly in styling and syntax from what Github uses, so what you see below might vary a little from what you get in a <em>Markdown Here</em> email, but it should be pretty close.</p>
<p>You can play around with Markdown on our <a href="http://www.markdown-here.com/livedemo.html">live demo page</a>.</p>
<p>(If you're not a Markdown Here user, check out the <a href="./Markdown-Cheatsheet">Markdown Cheatsheet</a> that is not specific to MDH. But, really, you should also use Markdown Here, because it's awesome. <a href="http://markdown-here.com">http://markdown-here.com</a>)</p>
<h5>
<a id="user-content-table-of-contents" class="anchor" href="#table-of-contents" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewbox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h5>
<p><a href="#headers">Headers</a><br>
<a href="#emphasis">Emphasis</a><br>
<a href="#lists">Lists</a><br>
<a href="#links">Links</a><br>
<a name="user-content-headers"></a>
<h2>
<a name="user-content-links"></a>
<h2>
<a id="user-content-links" class="anchor" href="#links" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewbox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Links</h2>
<p>There are two ways to create links.</p>
<pre lang="no-highlight"><code>[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or &lt;http://www.example.com&gt; and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
</code></pre>
<p><a href="https://www.google.com">I'm an inline-style link</a></p>
<p><a href="https://www.mozilla.org">I'm a reference-style link</a></p>
<p><a href="http://slashdot.org">You can use numbers for reference-style link definitions</a></p>
<p>Or leave it empty and use the <a href="http://www.reddit.com">link text itself</a></p>
<p>URLs and URLs in angle brackets will automatically get turned into links.
<a href="http://www.example.com">http://www.example.com</a> or <a href="http://www.example.com">http://www.example.com</a> and sometimes
example.com (but not on Github, for example).</p>
<p>Some text to show that the reference links can follow later.</p>
<a name="user-content-images"></a>
<h2>
<a id="user-content-images" class="anchor" href="#images" aria-hidden="true"><svg aria-hidden="true" class="octicon octicon-link" height="16" version="1.1" viewbox="0 0 16 16" width="16"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Images</h2>
<pre lang="no-highlight"><code>Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
</code></pre>
<p>Here's our logo (hover to see the title text):</p>
<p>Inline-style:
<img src="https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png" alt="alt text" title="Logo Title Text 1"></p>
<p>Reference-style:
<img src="https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png" alt="alt text" title="Logo Title Text 2"></p>
<a name="user-content-code"></a>
<h2>

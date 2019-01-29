# Header-and-Footer-example

<p>Here is a possible simple header and a footer example made with help of HTML and CSS.</p>
<p>You can check a live preview on: <a href="https://negrut112.github.io/header-and-footer-example/">https://negrut112.github.io/header-and-footer-example/</a></p>

<img src="https://i.imgur.com/QqiRM4w.png">

## HTML
<p>I’ve started with the &lt;head&gt; tags I inserted the the title, setting the page to follow device witdth, character encoding, the mayer reset, a external rosource link for css file.</p>

<pre><code>&lt;meta charset=“utf-8”&gt;<br>
&lt;meta name=“viewport” content=“width=device-width”&gt;<br>
&lt;link rel=“stylesheet” href=&quot;<a href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.css">https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.css</a>“&gt;<br>
&lt;link href=”<a href="https://fonts.googleapis.com/css?family=Raleway%7CRubik:400">https://fonts.googleapis.com/css?family=Raleway|Rubik:400</a>&quot; rel=“stylesheet”&gt;<br>
&lt;link rel=“stylesheet” type=“text/css” href=“main.css”&gt;<br>
&lt;title&gt;Header and Footer&lt;/title&gt;</code></pre>

<p>Inside the header tags I put the image with the logo company and 2 headings describing company name and location. The footer is composed by navigation with a specific class having some useful links, a wrapper, and a line describing the company identity.</p>

<pre><code>&lt;header&gt;<br>
&lt;img src=&quot;<a href="https://i.imgur.com/GCNudvW.jpg">https://i.imgur.com/GCNudvW.jpg</a>&quot; alt=“Global Travel”&gt;<br>
&lt;h1&gt;Global Travel Blog&lt;/h1&gt;<br>
&lt;h2&gt;Mother Earth&lt;/h2&gt;<br>
&lt;/header&gt;</p>
<p>&lt;footer&gt;<br>
&lt;div class=“wrapper”&gt;<br>
&lt;small&gt;©2019 &lt;strong&gt;Awesome Company&lt;/strong&gt;, All Rights Reserved&lt;/small&gt;<br>
&lt;nav class=“footer-nav”&gt;<br>
&lt;a href=&quot;#&quot;&gt;Back to Top&lt;/a&gt;<br>
&lt;a href=&quot;#&quot;&gt;Terms of Use&lt;/a&gt;<br>
&lt;a href=&quot;#&quot;&gt;Privacy&lt;/a&gt;<br>
&lt;/nav&gt;<br>
&lt;/div&gt;<br>
&lt;/footer&gt;</code></pre>

## CSS

<p>The CSS helped to customized the elements from HTML part, for example:</p>

<pre><code>header h1 { // selecting header and h1 tags<br>
font-family: ‘Rubik’, sans-serif; // used fonts, if not available first one will use next one<br>
font-size: 1.25rem; // font size 1rem = 16px =&gt; font-size=16*1.25<br>
color: #555; // color<br>
margin: .67rem 0; // margin around the element<br>
}
<p>footer {<br>
background: url(’<a href="http://i.imgur.com/f4jGhSF.png">http://i.imgur.com/f4jGhSF.png</a>') repeat center; // we can set customized the footer with CSS as well<br>
display: table; // element will behave like a table element<br>
width: 100vw; // 100% of the viewport width<br>
height: 8rem; // 8*16px<br>
text-align: center; // text align<br>
padding: 1rem; // space around elements<br>
font-family: ‘Arial’, sans-serif; // used fonts<br>
font-size: .875rem; // font size<br>
}</code></pre>

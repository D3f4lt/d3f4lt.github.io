---
layout:     post
title:      Kenalan Dengan Markdown
date:       2014-06-09 12:32:18
summary:    Dengan Markdown memungkinkan untuk membuat sebuah format html dengan sangat sederhana dan hemat. (easy-to-read dan easy-to write)
categories: pengetahuan post
---

![Maarkdown](https://octodex.github.com/images/collabocats.jpg)
## Apa itu Markdown? ##

Markdown merupakan gaya penulisan text-to-HTML yang digunakan untuk membuat konten tertentu pada suatu web dengan kata lain konversi penulisan format berupa plain text yang dikonversi menjadi html pada web. Dengan Markdown memungkinkan untuk membuat sebuah format html dengan sangat sederhana dan hemat. (easy-to-read dan easy-to write)

Markdown dibuat pertama kali oleh John Gruber sejak 2004 dengan bahasa Perl. Tujuan utama dari pembuatan Markdown adalah untuk mempermudah penulisan format plain text dan sebagai opsi untuk bisa mengkonversinya ke HTML dan XHTML.

Pada saat ini markdown seringkali digunakan untuk membangun tampilan halaman web atau postingan blog dan semacamnya. Bahkan, situs web yang terkenal seperti GitHub, Reddit, Sackoverflow dan SourceForge sudah menggunakannya.

## Penulisan Markdown

{% highlight markdown %}
# Markdown

**Markdown** is a text-to-HTML conversion tool for web writers. 
Markdown allows you to write using an *easy-to-read*, *easy-to-write* plain text format, 
then convert it to structurally valid XHTML (or HTML).

[Markdown](http://daringfireball.net/projects/markdown/ "Markdown")

"Markdown" is two things:

1. Plain text formatting syntax
2. Software tool

{% endhighlight %}

## Penulisan Format HTML

{% highlight html %}
<h1>Markdown</h1>

<p><strong>Markdown</strong> is a text-to-HTML conversion tool for web writers. 
Markdown allows you to write using an <em>easy-to-read</em>, <em>easy-to-write</em> plain text format, 
then convert it to structurally valid XHTML (or HTML).</p>

<p><a href="http://daringfireball.net/projects/markdown/" title="Markdown">Markdown</a></p>

<p>"Markdown" is two things:</p>

<ol>
	<li>Plain text formatting syntax</li>
	<li>Software tool</li>
</ol>

{% endhighlight %}

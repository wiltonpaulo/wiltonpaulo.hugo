+++
author = "Wilton"
title = "Hello World"
date = "2022-06-19"
description = "Thatโs the first post on this blog/site. So. I decided to improve my writing skills in english and share them with everyone."
tags = [
    "cloud",
    "engineer",
    "devops"
]
thumbnail = "images/hello_world.png"
+++

Thatโs the first post on this blog/site. So. I decided to improve my writing skills in english and share them with everyone.

<!--more-->

The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes).

To enable emoji globally, set `enableEmoji` to `true` in your site's [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.

<p><span class="nowrap"><span class="emojify">๐</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">๐</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">๐</span> <code>:speak_no_evil:</code></span></p>
<br>

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

---

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.

{{< highlight html >}}
.emoji {
font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
}
{{< /highlight >}}

{{< css.inline >}}

<style>
.emojify {
	font-family: Apple Color Emoji, Segoe UI Emoji, NotoColorEmoji, Segoe UI Symbol, Android Emoji, EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
  .nowrap {
    display: block;
    margin: 25px 0;
  }
}
</style>

{{< /css.inline >}}

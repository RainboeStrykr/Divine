# Divine by RainboeStrykr
## [Website](rainboestrykr.repl.co) 
*Free for personal and commercial use under the CCA 3.0 license*


**This is Divine, a single page, single screen responsive site template. Real simple.
Makes heavy use of CSS animation (something I've been messing with a lot lately).
Should work well as a landing page that just directs folks to your stuff elsewhere
on the www. Sass sources are also included, so if you've never used Sass and you're
interested in giving it a try, head on over to sass-lang.com (and if not, you can
safely delete the "sass/" folder).**


> Questions/comments/issues = just email me or comment on the Githib Repo. Have fun!



#### The Scrolling Background:

	This relies entirely on CSS to do its thing, which is cool, but that makes
	changing it a bit weird/tricky at first. You can still use pretty much any image
	you want, but for best results make sure yours is:

	- Horizontally tileable.
	- Wide and short.
	- About 1500px wide.
	- Fades to a solid color either at the top of bottom (which is used to fill
	  the empty space above or below your image).

	Now, there are two ways to use it: with CSS, or with Sass:

	CSS:

		Look for this line in css/style.css (line 108 as of this writing):

			background: #348cb2 url("images/bg.jpg") bottom left;

		and use it to set the page background color, URL, and placement of
		your image. It should be as close to 1500px wide as you can get it.

	Sass:

		Set the value of $bg to the page background color, URL, and placement
		of your image. Change $bg-width if your image is something other than
		1500px wide.


Credits:

> 	Icons:
		Font Awesome (fontawesome.io)


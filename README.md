# LASA Science Olympiad
This is the website for LASA SciO.

## Project structure
The root directory contains the main html files, or what you see in the navbar (Useful links, Contact, Blog, etc)

The img directory should contain images. If you need to add images, add it here and then reference it.

The posts directory has html files for individual posts.

The css, fonts, and js directory contain css, fonts, and javascript. You shouldn't need to change these.

You may be asking "why is this so inelegant? Why didn't you use jekyll?". It's because it's too much work, man. 

## Adding a post

Jekyll is honestly more trouble than it's worth. Instead:

1. Open blog.html in a text editor (not the browser)
2. Scroll down to blog posts
3. Copy the
    div class="blogpost-header"
and create a new blogpost header. This looks like:

	<div class="blogpost-header">
		    <div class="col-lg-8 col-lg-offset-1">
			<article class="post">
			    <header class="post-header">
				<span class="post-meta">
				    Posted by Neil Patil on
				    <time datetime="2014-08-11">August 11, 2014</time>
				</span>
				<h2 class="post-title"><a href="posts/new-website.html">New Website!</a>
				</h2>
			    </header>
			    <section class="post-excerpt">
				<p>We've created a new website for LASA SciO (this one).</p>
			    </section>
			</article>
			<hr class="section-heading-spacer">
			<div class="clearfix"></div>
		    </div>
		</div>

4. Update
	class="post-meta"
to the correct author and datetime.
5. Change the post title header.
6. Change the post excerpt.
7. Make the link reference the html file in the posts folder. This means changing the 
	<a href="posts/new-website.html">
to a new .html file.
8. Create the .html file in the posts directory.
9. Copy-paste one of the other posts into this file.
10. Update the post content.

If you need help, email (neilpatil215@gmail.com)[neilpatil215@gmail.com]

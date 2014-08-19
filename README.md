# LASA Science Olympiad
This is the website for LASA SciO, containing blog posts, contact info, an about page, etc. It can be found (here.)[http://lasa-scio.github.io]

## Project structure
The root directory contains the main html files, or what you see in the navbar (links, contact, blog, etc)

The posts directory has HTML files for individual posts. These are referenced from blog.html, which contains post header info (the title and an excerp) and a link to the full post, so the user can read the full blog post details here.

The img directory should contain images. If you need to add images, add them here.

The css, fonts, and js directory contain CSS, fonts, and Javascript. You shouldn't need to change these.


## Adding a post

Hopefully, you know some basic HTML.

1. Open blog.html in a text editor.
2. Scroll down to the blog posts markup.
3. Copy and paste the contents of ```<div class="blogpost-header"```
and create a new blogpost header. This looks like:
```
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
```

4. Update the contents of ```<span class="post-meta"``` to the correct author and datetime.
5. Change the title of the post.
6. Change the post excerpt.
7. Make the link reference the html file in the posts folder. This means changing the ```<a href="posts/new-website.html">``` to something like ```<a href="posts/new-post.html">```
8. Create the newly referenced .html file in the posts directory.
9. Copy-paste the contents of another post in the posts directory into this file.
10. Update the post content.


You may be asking "Why is this so inelegant? Why didn't you use jekyll?". It's because it's too much work, man. We'll only need to add a handful of posts throughout the year and I have limited time.

If you need help, email (neilpatil215@gmail.com)[neilpatil215@gmail.com]

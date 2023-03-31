# LASA Science Olympiad
This is the website for LASA SciO, built using Jekyll. It can be found at http://lasascioly.com

## Project structure
The \_layouts directory contains the default (primary) layout, which includes the navbar and the footer. Any additional pages should use this layout.

The root directory contains the main html files, or what you see in the navbar (index, news, history, etc). All of them extend the default layout.

The root directory also contains \_config.yaml, which is the global configuration file for Jekyll.

The \_posts directory contains markdown files for individual posts. These appear in chronological order on the news page (news.html).

The assets directory contains static assets such as images, fonts, Javascript, and CSS. Any images should go in the assets/img directory.


## Adding a post

1. Open the \_posts directory.
2. Copy a post to use as a template.
3. IMPORTANT: Name the new post using the format "year-month-day-name.md" (e. g. "2017-11-8-cyfalls.md"). This is how Jekyll will know the date of the post, and thus how to order it.
4. Edit the file. The title and author(s) go at the top, between the `---`. The content goes below, and uses Markdown syntax.
5. If you want to include an image, place the image in the assets/img directory. In the post content, link to the image using the syntax `![](assets/img/name_of_image.jpg)`. Make sure the image is on a line by itself with an empty line above and below.

If you have any questions about LASA Science Olympaid or would like to learn more about our team please email us at [lasa.scioly@gmail.com](mailto:lasa.scioly@gmail.com).

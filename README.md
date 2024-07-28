# Notes for future me
1. This is built on minima theme. Instructions for modifying the layout and contents require following the description of [`minima` theme][minima].
2. _layouts/newHome.html combines frontpage.md (About me) and publications. 
3. Publications are also separately rendered through a publicationList.md (to have it in header). The layout for this is publications.html. This is redundant and needs to be modified. Idea: In future, replace publications in newHome.html with posts. [`minima starter`][https://github.com/jsanz/gh-pages-minima-starter] has posts in the place of publications. 
4. Many layouts are already present in the [`minima` theme][minima]. I had to manually create new layouts to have it my way (inefficient). 



# gh-pages-minima-starter

This is a template and some instructions for running Github Pages with the [`minima` theme][minima]. This repo has what I consider the minimum pieces for a personal blog using [Jekyll][jk] and [Github Pages][gh-site]:

* Frontpage that includes your last blog posts: `_pages/frontpage.md`
* Archive for all your posts: `_pages/archive.md`
* About page: `_pages/about.md`
* Minimum 404 page: `_pages/404.md`
* Minimum metadata in the `_config.yml`
* Example CSS change inside `assets/main.scss`
* Custom footer template `_includes/footer.html`

Check out the excellent [`minima` theme][minima] documentation for further details and customization and the [official docs][gh] for more details on how Github Pages work.

For more details on how to set it up locally, create content, use Github interface, etc. feel free to visit this [website post][dev] or the source code here.

Do you have questions? feel free to [open an issue](https://github.com/jsanz/gh-pages-minima-starter/issues/new/choose) or [contact me](https://jorgesanz.net/contact).

Enjoy!!

[gh-site]: https://pages.github.com/
[jk]: https://jekyllrb.com/
[minima]: https://github.com/jekyll/minima/tree/2.5-stable
[gh]: https://help.github.com/en/github/working-with-github-pages
[gh-settings]: https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
[dev]: https://jsanz.github.io/gh-pages-minima-starter/2020/04/17/local-env.html
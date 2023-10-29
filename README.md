# How to use github pages

-   NOTE: You can only host static websites on github pages

Static sites: Site that only uses html, css, and javascript. Can't use flask/python/django, node.js/express, etc.

1. Go to settings.
2. Go to pages
3. For "Source" set it as main or the branch you want the site to use.

index.html: This is the landing page for github. The name "index.html" is special as
it will automatically launch this page first as the starting page.

# Note about using html links

1. Notice that every time you go to a page, it keeps ".html" at the end of the url
2. This may look unprofessional/ulgy for some, and you can actually remove the file ext.
3. For links you can remove the ext and instead of "about.html" you can do "about".
   Also for linking to "index.html" you can just do "./". Just leave the slash, and
   this lets github pages know that you are linking to index.html
4. However note that by doing this, your site won't redirect properly on your local machine, but
   on github pages it will work.

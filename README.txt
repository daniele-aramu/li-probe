LinkedIn link-preview probe (plan .agent/plans/20261028-1400_linkedin-article-previews.md, POC).
og:image and og:url must be absolute: replace __BASE__ in the four .html files with the Pages URL, e.g.
  sed -i 's#__BASE__#https://<user>.github.io/<repo>#g' *.html
Then inspect each page at https://www.linkedin.com/post-inspector/ and record per page: image shown? cropped how? warnings?

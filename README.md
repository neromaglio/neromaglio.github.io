# SP4Sci website

This repository contains the source code of my personal website.
It is powered by `hugo` ( [https://gohugo.io/](https://gohugo.io/) ).
The idea is to express the content using the Markdown format, then use hugo to generate the actual html and css content.
It uses dev ops to autmatically build the server and deploy the new website whenever there is a content update.

# How to run it locally to test it

```
hugo --minify --gc --cleanDestinationDir --baseURL "http://localhost:1313" server
```


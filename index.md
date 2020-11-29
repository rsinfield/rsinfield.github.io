---
title: Use tabs to organize content
output:
  html_document:
    template:
    # test with the template before #1547
    #- https://raw.githubusercontent.com/rstudio/rmarkdown/3a502fa8e85425aa7af723c1b4d2eecda9d7c632/inst/rmd/h/default.html
    # test with the template modified by #1547
    #- https://raw.githubusercontent.com/rstudio/rmarkdown/c6d06159c4860d45d0cfb09b79b39ade5f8a215b/inst/rmd/h/default.html
    # test with the current PR
    - https://raw.githubusercontent.com/RLesur/rmarkdown/bugfix/issue-1577/inst/rmd/h/default.html
runtime: shiny

---


## Robert Sinfield test reel  {.tabset}  

### Arcgis online

<a href="/test_echarts.html">Page 2</a>

Note the relative link starting with a slash before the html file.

The index.md is used to customize the github page's home page, 
The following link directs to the slide.



[slide link](/test_echarts.html)




### Distribution of GP practice registered population
<a href="https://nelcsu.maps.arcgis.com/apps/webappviewer/index.html?id=771aca46caeb43a388dcf21beced7814" target="_blank">full screen version</a>


<style>
.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}

.testiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}

.rsiframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>



<div class="resp-container">
    <iframe class="testiframe" src="https://nelcsu.maps.arcgis.com/apps/webappviewer/index.html?id=771aca46caeb43a388dcf21beced7814">
      Fallback text here for unsupporting browsers, of which there are scant few.
    </iframe>
</div>

<div class="resp-container">
<iframe class="rsiframe"
src="https://arcgis.com/apps/webappviewer/index.html?id=771aca46caeb43a388dcf21beced7814"></iframe>
</div>
# GBD3



**GBD3 for pathology atlas repositories**


```
see [make-html-WSI](https://github.com/pathologyatlas/make-html-WSI) for more information and [TODO](https://github.com/pathologyatlas/TODO) to add cases
```

```
In this README file replace the following:
GBD3 with description of file in English
GBD3 with description of file in Turkish
GBD3 with repository name

```


```
update html file <head>

<title>GBD3 GBD3</title>

<meta name="keywords" content="GBD3, GBD3, patoloji, atlas, pathology, whole slide image">

<meta name="description" content="GBD3 GBD3">

```



```zsh

vips dzsave HE.svs HE

```



```
update html file to match .dzi file

```


```
add to begining of qmd page

---
description: |
    GBD3
    GBD3
date: last-modified
categories: [GBD3]
page-layout: full
bibliography: references.bib
---

```



> consider using git_push.sh script to upload files to github, since the number of generated files is huge

> after upload complete, do not forget to activate github pages for the new repository



```{r language GBD3, echo=FALSE, include=TRUE}
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```




```{asis, echo = (language == "TR")}
## GBD3 {#sec-GBD3}
```


```{asis, echo = (language == "EN")}
## GBD3 {#sec-GBD3}
```


```{r GBD3 screenshot, eval=TRUE, include=FALSE}
if (!file.exists("./screenshots/GBD3_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/GBD3/HE.html",
  file = "./screenshots/GBD3_screenshot.png"
)
}
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
knitr::include_url(url = "https://images.patolojiatlasi.com/GBD3/HE.html")
```

```{r, echo=FALSE, include=FALSE, eval=FALSE}
#| label: GBD3_screenshot
#| fig-cap: "GBD3"
knitr::include_graphics("./screenshots/GBD3_screenshot.png")
```


::: {.content-hidden when-format="html"}
GBD3
:::

::: {.content-visible when-format="pdf"}
GBD3
:::



```{asis, echo = (language == "TR")}

**GBD3**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD3_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD3/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD3/HE.html)
```


```{asis, echo = ((language=="TR") & (output_type=="html"))}
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD3/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment} 
asis, echo = (language == "TR")

**GBD3**


[![İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/GBD3_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD3/HE_annotated.html) [İşaretlenmiş mikroskopik görüntüleri Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/GBD3/HE_annotated.html)

İşaretlenmiş mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/GBD3/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>

```



```{comment}
asis, echo = (language == "TR")



<button id="tani-case-GBD3-btn">Tanıyı Göster</button>
<div id="answer-GBD3" style="display: none;">GBD3</div>

<script>
  const showAnswer-GBD3Btn = document.getElementById('tani-case-GBD3-btn');
  const answer-GBD3 = document.getElementById('answer-GBD3');

  showAnswer-GBD3Btn.addEventListener('click', () => {
    if (answer-GBD3.style.display === 'none') {
      answer-GBD3.style.display = 'block';
      showAnswer-GBD3Btn.textContent = 'Tanıyı Gizle';
    } else {
      answer-GBD3.style.display = 'none';
      showAnswer-GBD3Btn.textContent = 'Tanıyı Göster';
    }
  });
</script>

```

```{comment}
asis, echo = ((language=="TR") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="TR") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```





```{asis, echo = (language == "EN")}

**GBD3**

[![Click for Full Screen WSI](./screenshots/GBD3_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD3/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/GBD3/HE.html)


```



```{asis, echo = ((language == "EN") & (output_type=="html"))} 

See Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD3/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```


```{comment}
asis, echo = (language == "EN")

**GBD3**

[![Click for Full Screen Annotated WSI](./screenshots/GBD3_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/GBD3/HE_annotated.html) [Click for Full Screen Annotated WSI](https://images.patolojiatlasi.com/GBD3/HE_annotated.html)


See Annotated Microscopy with viewer: 

<iframe src="https://images.patolojiatlasi.com/GBD3/HE_annotated.html" style="height:600px;width:100%;" data-external="1"></iframe>



```

```{comment}
asis, echo = (language == "EN")

<button id="dx-case-GBD3-btn">Show the Diagnosis</button>
<div id="answer-GBD3" style="display: none;">GBD3</div>

<script>
  const showAnswer-GBD3Btn = document.getElementById('dx-case-GBD3-btn');
  const answer-GBD3 = document.getElementById('answer-GBD3');

  showAnswer-GBD3Btn.addEventListener('click', () => {
    if (answer-GBD3.style.display === 'none') {
      answer-GBD3.style.display = 'block';
      showAnswer-GBD3Btn.textContent = 'Hide the Diagnosis';
    } else {
      answer-GBD3.style.display = 'none';
      showAnswer-GBD3Btn.textContent = 'Show the Diagnosis';
    }
  });
</script>

```


```{comment}
r, eval=TRUE, echo=FALSE, include=FALSE, error=TRUE
if (!file.exists("./screenshots/GBD3_screenshot.png")) {

url <- "https://img.youtube.com/vi/U9glkfQLTm4/maxresdefault.jpg"
download.file(url, destfile = "./screenshots/GBD3_screenshot.png", mode = "wb")
}

**GBD3**

[![Video İçin Tıklayın](./screenshots/GBD3_screenshot.png){width="25%"}](https://www.youtube.com/watch?v=) [Video İçin Tıklayın](https://www.youtube.com/watch?v=)

```




```{comment}
asis, echo = ((language=="EN") & (output_type=="html"))

{{< video https://www.youtube.com/embed/ >}}

```

```{comment}
asis, echo = ((language=="EN") & (output_type!="html"))

[https://www.youtube.com/watch?v=](https://www.youtube.com/watch?v=)

```


```{comment}
=html
<iframe src="https://images.patolojiatlasi.com/GBD3/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>
```

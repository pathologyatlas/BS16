







```
r language BS16, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis metastatik karsinom, omentum TR, echo = (language == "TR")
## BS16 - metastatik karsinom, omentum {#sec-BS16 }
```


```
asis metastatic carcinoma, omentum EN, echo = (language == "EN")
## BS16 - metastatic carcinoma, omentum {#sec-BS16 }
```






```
r BS16 screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/BS16-HE_screenshot.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/BS16/HE.html",
  file = "./screenshots/BS16-HE_screenshot.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/BS16/HE.html](https://images.patolojiatlasi.com/BS16/HE.html)





```
asis, echo = (language == "TR")

**metastatik karsinom, omentum**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/BS16-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS16/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/BS16/HE.html)
```

```
asis, echo = (language == "EN")

**metastatic carcinoma, omentum**

[![Click for Full Screen WSI](./screenshots/BS16-HE_screenshot.png){width="25%"}](https://images.patolojiatlasi.com/BS16/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/BS16/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/BS16/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/BS16/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

metastatik karsinom, omentum

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

metastatic carcinoma, omentum

:::

```









:::::











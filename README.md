<a href="https://github.com/yuri-bizzoni/EmoArc"><img src="https://github.com/yuri-bizzoni/EmoArc/raw/main/static/longer_arcs.png" width="100%" height="110" align="right" /></a>  
<br>  
<br>  

# EmotionArcs [![Static Badge](https://img.shields.io/badge/acl-LaTeCH-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKAAAABwAgMAAADkn5ORAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAgY0hSTQAAeiYAAICEAAD6AAAAgOgAAHUwAADqYAAAOpgAABdwnLpRPAAAAAlQTFRFAAAA7R4k7RwkoncKaQAAAAF0Uk5TAEDm2GYAAAAJcEhZcwAACxMAAAsTAQCanBgAAAJVSURBVFjD7Zc7ksMwDEPTpMnptmGD023DhqdcApCT2NvYnJTxTH7K09CiSAi+3b7X23VHIQLxQbAiA/lREJFAzsCIyOQLUZVcQvCjYx9CnwZLYxwuENI0zUZNQUbtmw8mJHsePzt6z5qBDVX/lcxwpXZO6a4enoFKSFZTvRoCXIuwnIJgVKAa1JqgdTSHIahUdIq6CHQTTDTSuZ+B/ZuJ8ZqwtpOz+3ZmYJaKIXLVG/evv2pwBopy0MVoN8GJM1D5SFc/3AX9zowFZqAiKT+K6mrztCHIPoCaQcrEmGyJXmPmDOwKcBmk+iHUXKW5QzBiKwgo3SFFgMJPQQ7Gz/vYfaEzEJSRxO8O5NTCELTS1TF0/ivc06AkL2sX+hFWwiFIpas8gCGNmYFSThwTLiWoGahujUN6WgBZJ0NQ+o4d+IDldAaGy3aXHpZZK3XOQGvefgvvkqwYgrQEnfE9WBKCGIJs/8MWPiQEmIIUpWNRgCdoDUElgoUqRUke7kjLtIafAn0a1Flhped/9g2wQZLLyasgj9yKzXj55JT4ydvgJSznwfZuPVQRyxttJ6jekNdBtb+NUdhplY4O9jDLpa6DaQcn/1aAK8xHk/J1HWRM0CF5gg63lS2b2eugV2LpxMr+2td3m3QN1OazIGwNZbyWMrzq8SxYKzRrNL0OuTme9/I0cRVMLIte9gnhHijXbb0WcxpUPGCVlsL1Uio2h/N8WDkN2nLRc0HGCzov5Wwq483KnQZ1mtlZOtjm5NxwhQmY6zGiKFd6GGCr5noOyKvg9/peo+sPhLv+BGIWS+UAAAAldEVYdGRhdGU6Y3JlYXRlADIwMTMtMDgtMDRUMjE6NTc6MjkrMDg6MDAj62PfAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDEzLTA4LTA0VDIxOjU3OjI5KzA4OjAwUrbbYwAAAABJRU5ErkJggg==)](https://aclanthology.org/2024.latechclfl-1.7.pdf) <a href="https://centre-for-humanities-computing.github.io/fabula-net/"><img src="https://github.com/yuri-bizzoni/EmoArc/raw/main/static/fabulanet_logo.png" width="15%" align="right" /></a>

This is the repository for the data for our paper "EmotionArcs: Emotion Arcs for 9,000 Literary Texts", Öhman et al. (2024), at _the 8th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature_ (LaTeCH-CLfL 2024), St. Julians, Malta.

It is a dataset comprising emotional arcs and intensities from over 9,000 English novels (1880-2000), assembled to understand the dynamics of emotions represented in text and how these emotions may influence a novel’s reception and perceived quality.

- NRC emotions (anger, disgust, fear, anticipation, surprise, trust, sadness, joy)
- NRC emotion dictionary expanded for the literary domain using Word2Vec

<br>


## ⚡ Data included

- Data for 9,000 titles
- Author, title & year
- Emotion intensities
- Emotion arcs

Available formats: [.xlsx](https://docs.google.com/spreadsheets/d/1i5RkZAZcT7IGrl3gmeadNeVzuHPJ9Bwek283YrA0RdE/edit?usp=sharing), [.json](https://github.com/yuri-bizzoni/EmoArc/raw/main/data/)

<br>

## 🔬 Example

| BOOK_ID          |      TITLE      |   AUTH_FIRST       | AUTH_LAST | PUBL_DATE    |     ARC_ang         | ARC_fea        | ... | INTENS_ang |  INTENS_joy | ...    |
| ---------------- | --------------- |------------------- |-----------|--------------|---------------------|----------------|-----|------------|-------------|--------|
| 25732            |  Infinite Jest  |   David Foster     | Wallace   |      1996    |     0.758,0.901...  | 1.451,1.601... | ... | 70.44      |  102.37     | ...    |
| 20636            |  Dune           |   Frank            | Herbert   |      1965    |     2.918,5.031...  | 4.164,4.231... | ... | 89.95      |  92.39      | ...    |
| 22741            |  Beloved        |   Toni             | Morrison  |      1987    |     7.603,5.461...  | 7.806,6.235... | ... | 63.46      |  136.63     | ...    |
| 21974            |  The Gunslinger |   Stephen          | King      |      1982    |     2.627,0.581...  | 3.308,1.764... | ... | 84.02      |  102.07     | ...    |
| 86               |  The Portrait of a Lady |   Henry    | James     |      1881    |     0.792,4.212...  | 2.381,4.672... | ... | 40.59      |  169.74     | ...    |



<br>

## 📖 Documentation


| Documentation              |                                                                                    |
| -------------------------- | ---------------------------------------------------------------------------------- |
| 👩‍💻 **[Notebook]**           | A notebook showing an example usage of the arcs.                              |
| 📄 **[Paper]**              | The EmotionArcs paper.                                                        |
| 📚 **[Citation]**           | Bibtex citation.                                                              | 


[Paper]: https://aclanthology.org/2024.latechclfl-1.7.pdf
[Citation]: https://github.com/yuri-bizzoni/EmoArc/raw/main/citation.txt
[Notebook]: https://github.com/yuri-bizzoni/EmoArc/blob/226ed2a0735cfa439c67f2dfc346dc114a4207a4/notebook.ipynb





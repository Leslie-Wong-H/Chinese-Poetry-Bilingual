# Chinese-Poetry-Bilingual
### What is the definition of this repository?
A database of Chinese Poetry in json format
 with both Chinese and English versions.


### Why do I want to build this database?
Mainly inspired by the high-stared repository
 <i>chinese-poetry</i>, the author of which aims 
 to provide chinese users an quick way to get 
 exposed to traditional Chinese culture. 
 Then, it occurs to me that why not build a similar 
 database, but in English? According to my experience, I notice that
 a lot of native English speakers like to pick some Chinese culture sentences
 during their conversation. To enrich their understanding of Chinese culture,
 this repository is born.
 The repository focuses 
 on offering developers who are native English speakers and 
 interested in traditional Chinese culture an original database 
 which can be used to their projects, forming an mysterious beauty from 
 ancient China. 



### How does this repository work?
The repository is written in json format, and organized the
document tree as dynasties-works. 

Id format: \*\-****  
    eg. 1-0001  
The first number: 1->Tang dynasty, 2->Song dynasty, 3->Qing dynasty)

### Directories
```
.
├── id
├── English
    ├── title
    ├── dynasty
    ├── author
    └── content
├── Chinese
    ├── title
    ├── dynasty
    ├── author
    └── content
└── tag
```

<b>By the way,the repository is still constructing.</b>

#### A concrete example:
```json
[
    {
    "id": "1-0001",
    
    "English":{
      "title":"Home-Coming",
      "dynasty":"Tang",
      "author": "He Zhizhang",
      "content":[
      "Oh, I return to the homeland I left while young,",
      "Thinner has grown my hair, though I speak the same tongue.",
      "My children, whom I meet, do not know who am I,",
      "Where are you from, dear sir?\" they ask with beaming eyes."
      ]
      },
      
      
    "Chinese":{
      "title":"回乡偶书",
      "dynasty":"唐",
      "author":"贺知章",
      "content":[
      "少小离家老大回，",
      "乡音无改鬓毛衰。",
      "儿童相见不相识，",
      "笑问客从何处来。"
      ]
      },
      
     "tags": [
     "homesick"
     ]
    }
     
    
 ]


```
### Tag Classification
> 
>    - Age 
>    - Ambition
>    - Autumn
>    - Border
>    - Class
>    - Dream
>    - Farewell
>    - Friendship
>    - Frustration
>    - History
>    - Homesick
>    - Honor
>    - Landscape
>    - Love 
>    - Longing
>    - Military
>    - Mountain
>    - Music
>    - Night
>    - Optimism
>    - Reunion
>    - Sadness
>    - Season
>    - Silence
>    - Solitude
>    - Spring
>    - Summer
>    - Voyage
>    - Windy
>    - Wine
>    - Winter
### License

Chinese_Poetry_Bilingual is published under the<b> 
Apache License, Version 2.0.</b>

Thanks for your supporting. 


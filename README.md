Modern Chinese Literature Adverbial Marker Datatset (LaTeCH-CLfL-2021)
===================================================
We release our manually annotated adverbial marker dataset on modern Chinese literary works, which was constructed and used in our paper "Unsupervised Adverbial Identification in Modern Chinese Literature". The paper was accepted by the LaTeCH-CLfL 2021 Conference (https://aclanthology.org/2021.latechclfl-1.10/).

## Description of the Dataset
- The "manually annotated modern Chinese literature works.zip" ZIP file contains the modern Chinese literature works of four prominent Chinese authors — Guo Moruo, Lao She, Lu Xun, and Mao Dun. These works are collected from the Baiwan Shuku website (http://www.millionbook.com/mj/index.html). A native speaker of Chinese with formal training in linguistics annotated three words (慢慢 'slow', 客气 'courteous', and 高兴 'happy') in this corpus using tag \<adv\>adverb\</adv\> (e.g. \<adv\>慢慢地\</adv\>).
- The "evaluation data.zip" ZIP file is the extracted 1,057 occurrences we used for evaluation, including 447 DE-adverbial instances, 465 DI-adverbial instances and 145 instances that are not adverbials.
- The "modern Chinese literature works annotated by code.zip" ZIP file contains the modern Chinese literature works, which the adverbial was annotated by our proposed unsupervised method.

## Citation
If you use our adverbial marker dataset in your reseasrch work, please cite us.
```
@inproceedings{xie-etal-2021-unsupervised,
    title = "Unsupervised Adverbial Identification in Modern Chinese Literature",
    author = "Xie, Wenxiu  and
      Lee, John  and
      Zhan, Fangqiong  and
      Han, Xiao  and
      Chow, Chi-Yin",
    booktitle = "Proceedings of the 5th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature",
    month = Nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic (online)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.latechclfl-1.10",
    doi = "10.18653/v1/2021.latechclfl-1.10",
    pages = "91-95",
}
```

Standard and Non-standard Adverbial Markers: a Diachronic Analysis in Modern Chinese Literature  
===================================================  
We release the raw data we used to generate Figures 1 to 5 that plot the DE ratio for each year during which the author’s works contained at least 5 instances of DE-/DI-adverbials. This paper was accepted by the LaTeCHCLfL 2023 Conference(https://aclanthology.org/2023.latechclfl-1.1/).

## Description of the Dataset
- The "Data of Diachronic Analysis in Modern Chinese Literature (Figures 1-5).zip" ZIP file contains the raw data we used to produce Figures 1 to 5 in our paper. The data format of each author file (e.g. Guomoruo_year.txt) is:  
'automatically annotated  adverbial'\_!\_'year of the work the adverbial appeared'\_!\_'corresponding sentence of the adverbial'  

## Citation
If you use our data of diachronic analysis in your reseasrch work, please cite us.  
```
@inproceedings{lee-etal-2023-standard,
    title = "Standard and Non-standard Adverbial Markers: a Diachronic Analysis in Modern Chinese Literature",
    author = "Lee, John  and
      Zhan, Fangqiong  and
      Xie, Wenxiu  and
      Han, Xiao  and
      Chow, Chi-Yin  and
      Lam, Kam-Yiu",
    booktitle = "Proceedings of the 7th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature",
    month = May,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.latechclfl-1.1",
    pages = "1-9",
}
```

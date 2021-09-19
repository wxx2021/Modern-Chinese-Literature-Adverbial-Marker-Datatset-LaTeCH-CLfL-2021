Modern Chinese Literature Adverbial Marker Datatset (LaTeCH-CLfL-2021)
===================================================
We release our manually annotated adverbial marker dataset on modern Chinese literary works, which was constructed and used in our paper "Unsupervised Adverbial Identification in Modern Chinese Literature". The paper was accepted by the LaTeCH-CLfL 2021 Conference (https://sighum.wordpress.com/events/latech-clfl-2021/accepted-papers/).

## Description of the Dataset
- The "manually annotated modern Chinese literature works.zip" ZIP file contains the modern Chinese literature works of four prominent Chinese authors — Guo Moruo, Lao She, Lu Xun, and Mao Dun. These works are collected from the Baiwan Shuku website (http://www.millionbook.com/mj/index.html). A native speaker of Chinese with formal training in linguistics annotated three words (慢慢 'slow', 客气 'courteous', and 高兴 'happy') in this corpus using tag \<adv\>adverb\</adv\> (e.g. \<adv\>慢慢地\</adv\>).
- The "evaluation data.zip" ZIP file is the extracted 1,057 occurrences we used for evaluation, including 447 DE-adverbial instances, 465 DI-adverbial instances and 145 instances that are not adverbials.
- The "modern Chinese literature works annotated by code.zip" ZIP file contains the modern Chinese literature works, which the adverbial was annotated by our proposed unsupervised method.

## Citation
If you use our adverbial marker dataset in your reseasrch work, please cite us.
```
@InProceedings{Xie-AdverbialMarker,
  author    = {Xie, Wenxiu and Lee, John S. Y. and Zhan, Fangqiong and Han, Xiao and Chow, Chi-Yin},
  title     = {Unsupervised Adverbial Identification in Modern Chinese Literature},
  booktitle = {The 5th Joint SIGHUM Workshop on Computational Linguistics for Cultural Heritage, Social Sciences, Humanities and Literature},
  month     = {September},
  year      = {2021}
}
```

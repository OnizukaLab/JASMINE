# JASMINE
We created a Japanese text simplification parallel corpus in the medical domain using articles from patients' [weblog](https://www.tobyo.jp/).
This parallel corpus is created by replacing disease names, symptoms, and other expressions in sentences written by patients with medical term.
We release 1,425 sentence pairs.
Please use this data for evaluating Japanese medical text simplification models.


If you wish to use the corpus, please apply through this [Google Form](https://forms.gle/DpvrvCum76y5L6VLA) (please provide your name, affiliation, email address, and the purpose of using the JASMINE corpus).

# Examples
The complex and simple sentences are paired in tab-separated format.
The first column contains the complex sentences, and the second column contains the simple sentences.
|Complex|Simple|
|---|---|
|そして25日夜から微熱が4日間続いた。|そして25日の夜から微熱が4日続きました。|
|食欲不振であった。|食欲もなかったです。|

# Research
Koki Horiguchi, Tomoyuki Kajiwara, Yuki Arase, Takashi Ninomiya.  
Evaluation Dataset for Japanese Medical Text Simplification.  
NAACL SRW 2024. [[PDF](https://aclanthology.org/2024.naacl-srw.23/)]

# Licence
Creative Commons Attribution 4.0 International License (CC BY 4.0)

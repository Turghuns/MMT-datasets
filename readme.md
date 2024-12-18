# Multimodal Machine Translation Datasets

* Prepared by Turghun Tayir

1. The following languages are covered:

- English
- Chinese
- German
- Japanese
- Uyghur
- Ukrainian
- Turkish



## Fine tuning
 
### Multi30 Datasets

1. The data set originally included **[English, German](https://aclanthology.org/W16-3210.pdf)** and **[Ukrainian](https://aclanthology.org/2023.unlp-1.7.pdf)**.
2. **[Chinese and Uyghur](https://dl.acm.org/doi/pdf/10.1145/3652161)** are manually translated from English
3. Japanese and Turkish are translated from English using **[NLLB-200](https://research.facebook.com/publications/no-language-left-behind/)**.
4. Please cite **[paper](https://aclanthology.org/2023.unlp-1.7.pdf)** for Ukrainian and **[paper](https://aclanthology.org/W16-3210.pdf)** for English and German.


## Pair pre-training

### MSCOCO Datasets

1. German, Chinese and Uyghur is translated from English using **[lingvanex](https://lingvanex.com/translate/)** translator.
2. Japanese, Ukrainian and Turkish are translated from English using **[NLLB-200](https://research.facebook.com/publications/no-language-left-behind/)**.


```
The MSCOCO Datasets is mscoco2014, which consists of text and images, with 123,287 images and five caption for each image.
The 123287 data contains the training and validation set of mscoco2014. Each file containing 123,287*5=616435 sentences, because each image has 5 caption sentences.
```

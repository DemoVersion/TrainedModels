TrainedModels
=============================
Trained Neural Machine Translation Models
------------------------------
About Software
==============================
I've published Neural Machine Translation models for English to Persian and vice versa from OpenSubtitle2016 dataset at this repository. Over time, if any other free Parallel Corpus is found in English/Persian, I'll publish more models here as soon as possible.

For translate using these models, use the [translate.lua](http://opennmt.net/OpenNMT/options/translate/) from [OpenNMT](https://github.com/OpenNMT/OpenNMT/).

| Model Name              | Source Vocab Size | Target Vocab Size | # of Epoch  | Perplexity  |Download Link  |
| ----------------------- |:-----------------:|:-----------------:|:-----------------:|:-----------------:|  -----:|
| OpenSubtitles2016_en_fa | 100k              | 100k              | 20 | 12.62 | [Download](https://1drv.ms/u/s!AnSE9VRFm2dwhFmgrYO7dnqqhRU6) |
| OpenSubtitles2016_fa_en | 100k              | 100k              | 20 | 7.91 | [Download](https://1drv.ms/u/s!AnSE9VRFm2dwhFppgFJbnq-yEwCV) |

These models are Trained using [OpenNMT](https://github.com/OpenNMT/OpenNMT/), See more details about the models here:
| Parameter             | Value |
| --------------------- | ----- |
| -src_word_vec_size    | 500   |
| -tgt_word_vec_size    | 500   |
| -layers               | 2     |
| -encoder_type         | brnn  |

License
==============================
These trained models are as free as the DataSet, for more information about the license, see OpenSubtitles2016 here : http://opus.lingfil.uu.se/OpenSubtitles2016.php

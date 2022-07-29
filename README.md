# CLTS-Dataset
CLTS: A ***C***hinese ***L***ong ***T***ext ***S***ummarization Dataset

## Introduction
Currently, there are two issues in automatic summarization dataset for Chinese: (1) There are fewer Chinese datasets. (2) There is a lack of Chinese long text datasets, and most existing datasets contain short texts, which can only be used to generate a title from short text.

CLTS is a new Chinese long text summarization dataset, extracted from the Chinese news website [ThePaper.cn](https://www.thepaper.cn). The resulting version of the dataset contains more than 180,000 **long-sequence pairs**, where each article consists of multiple paragraphs and each summary consists of multiple sentences. 

The dataset is introduced in [CLTS: A New Chinese Long Text Summarization Dataset](https://link.springer.com/chapter/10.1007%2F978-3-030-60450-9_42).

## Properties
The comparison result of CLTS to other datasets is shown in the table below. For Chinese dataset, length is the number of Chinese characters, while for English, it is the number of words.
 |           Dataset         | CLTS       |    LCSTS   |  CNN/DM     |
 |:-------------------------:| :--------: | :--------: | :---------: |
 |      Dataset Size         | 185,397    | 2,412,363  |   312,085   |
 |    Training Set Size      | 148,317    | 2,400,591  |   287,227   |
 |    Max Article Length     | **6130**   |    135     |  2173       |
 |    Mean Article Length    |**1363.69** |   88.65    |   687.09    |
 |    Mean Summary Length    | **58.12**  |  16.09     |   48.49     |

## Samples
We select some samples from the dataset and you can see them in [samples.txt](https://github.com/lxj5957/CLTS-Dataset/blob/master/samples.txt)

## Download
We split the corpus into three parts, including training, validation and test set. The data can be downloaded from the link [here](https://pan.baidu.com/s/1skhl1HKUfRyFa7z3t8dH-g). And the password is ***iucp***. 

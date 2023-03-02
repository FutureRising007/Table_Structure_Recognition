# TABLE STRUCTURE RECOGNITION

## 1. OBJECTIVE OF RESEARCH - 
Data mining is widely used to identify patterns and anomalies in large datasets, with financial documents serving as a crucial source for businesses. Extracting financial information correctly and efficiently is vital to prevent data forgery and identify significant issues in business activities. Tables are a primary format for presenting key figures in financial documents, <b>but their style and format can vary, making table recognition a critical step in financial data forgery prevention</b>. While academic and commercial approaches exist to recognize tables in various document formats, there is limited work on image-based table recognition in real-world scenarios, with limited training data being the main technical challenge. 

<b>The proposed challenge aims to explore the latest techniques for recognizing table structures in real financial documents and focuses on identifying the row and column count of tables from an image of a financial document.</b>



## 2. RESEARCH WORK IN THE TOPIC - 

* *CODE means official code and CODE means not official code

*Conf.* | *Date* | *Title* | *Highlight* | *code* |
:---: | :---: |:--- | :---: | :---: |
ACM-MM | 2022 |[TSRFormer: Table Structure Recognition with Transformers](https://arxiv.org/pdf/2208.04921.pdf) | Detection | No |
CVPR | 2022 |[TableFormer: Table Structure Understanding with Transformers.](https://arxiv.org/pdf/2203.01017.pdf) | Sequence | No |
CVPR | 2022 |[Neural Collaborative Graph Machines for Table Structure Recognition](https://arxiv.org/pdf/2111.13359.pdf) | GNN | No |
CVPR | 2022 |[PubTables-1M: Towards comprehensive table extraction from unstructured documents](https://arxiv.org/pdf/2110.00061v3.pdf) | Dataset | [*CODE](https://github.com/microsoft/table-transformer)<br>![](https://img.shields.io/github/stars/microsoft/table-transformer.svg?style=social) |
arXiv | 2021/5/23 |[Multi-Type-TD-TSR -- Extracting Tables from Document Images using a Multi-stage Pipeline for Table Detection and Table Structure Recognition: from OCR to Structured Table Representations](https://arxiv.org/pdf/2105.11021.pdf) | Others | [*CODE](https://github.com/Psarpei/Multi-Type-TD-TSR)<br>![](https://img.shields.io/github/stars/Psarpei/Multi-Type-TD-TSR.svg?style=social)  |
ACM-MM | 2021 |[Show, Read and Reason: Table Structure Recognition with Flexible Context Aggregator](https://dl.acm.org/doi/pdf/10.1145/3474085.3481534?casa_token=zwKnfTC97hwAAAAA:FnqKd6otw4v7LZQq_XvJzk_RLvit8ohPCOIafevI68zxXl1KocUVxIlBg9W1VsHQ57SShne6486BUw) | GNN | No |
ICCV | 2021 |[Parsing Table Structures in the Wild](https://openaccess.thecvf.com/content/ICCV2021/papers/Long_Parsing_Table_Structures_in_the_Wild_ICCV_2021_paper.pdf) | Detection | No |
ICCV | 2021 |[TGRNet: A Table Graph Reconstruction Network for Table Structure Recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Xue_TGRNet_A_Table_Graph_Reconstruction_Network_for_Table_Structure_Recognition_ICCV_2021_paper.pdf) | GNN | [*CODE](https://github.com/xuewenyuan/TGRNet)<br>![](https://img.shields.io/github/stars/xuewenyuan/TGRNet.svg?style=social) |
ICDAR Competition | 2021 |[ICDAR 2021 Competition on Scientific Literature Parsing](https://arxiv.org/pdf/2106.14616v1.pdf) | Dataset | [*CODE](https://github.com/ibm-aur-nlp/PubLayNet)<br>![](https://img.shields.io/github/stars/ibm-aur-nlp/PubLayNet.svg?style=social) |
ICDAR Competition | 2021 |[PingAn-VCGroup's Solution for ICDAR 2021 Competition on Scientific Literature Parsing Task B: Table Recognition to HTML](https://arxiv.org/pdf/2105.01848v1.pdf) | Sequence | [*CODE](https://github.com/JiaquanYe/TableMASTER-mmocr)<br>![](https://img.shields.io/github/stars/JiaquanYe/TableMASTER-mmocr.svg?style=social) |
ICDAR Competition | 2021 |[LGPMA: Complicated Table Structure Recognition with Local and Global Pyramid Mask Alignment](https://arxiv.org/pdf/2105.06224.pdf) | Others | [*CODE](https://github.com/hikopensource/DAVAR-Lab-OCR)<br>![](https://img.shields.io/github/stars/hikopensource/DAVAR-Lab-OCR.svg?style=social) |
WACV | 2021 |[Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context](https://openaccess.thecvf.com/content/WACV2021/papers/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.pdf) | Others | No |
CVPR Workshop | 2020 |[CascadeTabNet: An approach for end to end table detection and structure recognition from image-based documents](https://arxiv.org/pdf/2004.12629v2.pdf) | Others | [*CODE](https://github.com/DevashishPrasad/CascadeTabNet)<br>![](https://img.shields.io/github/stars/DevashishPrasad/CascadeTabNet.svg?style=social) |
ECCV | 2020 |[Image-based table recognition: data, model, and evaluation](https://arxiv.org/pdf/1911.10683v5.pdf) | Dataset | [*CODE](https://github.com/ibm-aur-nlp/PubTabNet)<br>![](https://img.shields.io/github/stars/ibm-aur-nlp/PubTabNet.svg?style=social) |
ECCV | 2020 |[Table structure recognition using top-down and bottom-up cues](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730069.pdf) | Others | [*CODE](https://github.com/sachinraja13/TabStructNet)<br>![](https://img.shields.io/github/stars/sachinraja13/TabStructNet.svg?style=social) |
LREC | 2020 |[TableBank: A Benchmark Dataset for Table Detection and Recognition](https://arxiv.org/abs/1903.01949) | Dataset | [*CODE](https://github.com/doc-analysis/TableBank)<br>![](https://img.shields.io/github/stars/doc-analysis/TableBank.svg?style=social) |
arXiv | 2019/8/28 |[Complicated table structure recognition](https://arxiv.org/pdf/1908.04729.pdf) | Others | [*CODE](https://github.com/Academic-Hammer/SciTSR)<br>![](https://img.shields.io/github/stars/Academic-Hammer/SciTSR.svg?style=social)  |
ICDAR | 2019 |[Rethinking Table Recognition using Graph Neural Networks](https://arxiv.org/pdf/1905.13391v2.pdf) | GNN | [*CODE](https://github.com/shahrukhqasim/TIES-2.0)<br>![](https://img.shields.io/github/stars/shahrukhqasim/TIES-2.0.svg?style=social) |
ICDAR | 2019 |[Tablenet: Deep learning model for end-to-end table detection and tabular data extraction from scanned document images](https://arxiv.org/pdf/2001.01469.pdf) | Others | No |
ICDAR | 2019 |[Res2tim: Reconstruct syntactic structures from table images.](https://ieeexplore.ieee.org/document/8978027) | Others | [*CODE](https://github.com/xuewenyuan/ReS2TIM)<br>![](https://img.shields.io/github/stars/xuewenyuan/ReS2TIM.svg?style=social) |
ICDAR | 2017 |[Deepdesrt: Deep learning for detection and structure recognition of tables in document images](https://www.dfki.de/fileadmin/user_upload/import/9672_PID4966073.pdf) | Others | No |

## 3. DATASETS -
### 3.1 INTRODUCTION: 

|Dataset|Description|dataset link|
|----|----|----|
|TableBank|**English** TableBank is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables.**It only contain cell Topology groudtruth**|[TableBank](https://github.com/doc-analysis/TableBank)|
|SciTSR|***English** SciTSR is a large-scale table structure recognition dataset, which contains 15,000 tables in PDF format and their corresponding structure labels obtained from LaTeX source files.**It contain cell Topology, cell content groudtruth**|[SciTSR](https://github.com/Academic-Hammer/SciTSR)|
|PubTabNet|**English** PubTabNet is a large dataset for image-based table recognition, containing 568k+ images of tabular data annotated with the corresponding HTML representation of the tables.**It contain cell Topology, cell content and non-blank cell location groudtruth**|[PubTabNet](https://github.com/ibm-aur-nlp/PubTabNet)|
|FinTabNet|**English** This dataset contains complex tables from the annual reports of S&P 500 companies with detailed table structure annotations to help train and test structure recognition.|[FinTabNet](https://developer.ibm.com/exchanges/data/all/fintabnet/)|
|PubTables-1M|**English** A large, detailed, high-quality dataset for training and evaluating a wide variety of models for the tasks of table detection, table structure recognition, and functional analysis.|[PubTables-1M](https://github.com/microsoft/table-transformer)|
|WTW|**English and Chinese** WTW-Dataset is the first wild table dataset for table detection and table structure recongnition tasks, which is constructed from photoing, scanning and web pages, covers 7 challenging cases like: (1)Inclined tables, (2) Curved tables, (3) Occluded tables or blurredtables (4) Extreme aspect ratio tables (5) Overlaid tables, (6) Multi-color tables and (7) Irregular tables in table structure recognition.**It contain cell Topology, all cell location groudtruth**|[WTW](https://github.com/wangwen-whu/wtw-dataset)|
|TNCR|**English** a new table dataset with varying image quality collected from open access websites.TNCR contains 9428 labeled tables with approximately 6621 images.their classification into 5 different classes(Full Lined,Merged Cells,No lines,Partial Lined,Partial Lined Merged Cells).|[TNCR](https://github.com/abdoelsayed2016/TNCR_Dataset)|
|TAL_OCR_TABLE|**Chinese** TAL_OCR_TABLE dataset come from TAL Form Recognition Technology Challenge.The data of comes from the real homework of students in the education scene and the scene of the test paper. It contain 16k train image and 4k test image**It contain cell Topology, cell content and all cell location groudtruth**|[TAL_OCR_TABLE](https://www.heywhale.com/home/competition/606d6fff0e04ac0017c3bf7f/content/1)|

### 3.2 COMPARISION OF DATASETS:
|Dataset|Cell Topology|Cell content|Cell Location|Table Location|
|----|----|----|----|----|
|TableBank|✓|✕|✕|✓|
|SciTSR|✓|✓|✕|✓|
|PubTabNet|✓|✓|✓<sup>†|✓|
|FinTabNet|✓|✓|✓<sup>†|✓|
|PubTables-1M|✓|✓|✓|✓|
|WTW|✓|✕|✓|✓|
|TNCR|✕|✕|✕|✓|
|TAL_OCR_TABLE|✓|✓|✓|✓|

<sup>†</sup> For these datasets, cell bounding boxes are given for non-blank cells only and exclude any non-text portion of a cell.
  
## 4. PRE-TRAINED MODELS & THEIR NOTEBOOKS - 
  
*Model* | *Notebook(Google Colab)* |
:---: | :---: |
CascadeTabNet| https://colab.research.google.com/drive/1hvguI08b0vTJ8WAUMcG7t9pVaf4xb8Hc?usp=share_link|
Table Transformer| https://colab.research.google.com/drive/1tfkbSlukfRgkuXKpV1yzG-CX0v2yadlj?authuser=2#scrollTo=_819yZ8sABN6|
YOLO | https://colab.research.google.com/drive/1b2cqhp2KHpWh4HJZpwR2-iM3NlIE9waQ?usp=share_link|
Multi-Type TD TSR | https://colab.research.google.com/drive/1sODx1likW2ubE6s019B-6Z7UFihD5wHv?authuser=3#scrollTo=y7Lk83F88NHW|
RetinaNet | https://colab.research.google.com/drive/1mpvbfLicRNvT4trj6ALnGyewUw9Hzbk_?usp=share_link|
TableNet | https://colab.research.google.com/drive/1sHl73sjGjt-eeEtNsr2dov-8Q0ea9AQc?usp=share_link|
SSD | https://colab.research.google.com/drive/12slrZG5skLgN6xKooCiiYdMvD9BVOQ8H?usp=share_link|
  
## 5. OUR RESEARCH WORK (TIMELINE) - 
### 5.1 EXAMINING THE PATTERNS OF THE LATEST MODELS: 
  * For Evaluation We considered Three Models:-
      * CascadeTabNet
      * Multi-Type-TD-TSR
      * TGRNet
      
     The Detailed report of the work can be found <a href="https://github.com/FutureRising007/Table_Structure_Recognition/tree/main/5.2%20Re-Evaluation%20of%20the%20Pre-Trained%20Models/Reproduced_Results">here<a/>.

### 5.2 RE-EVALUATION OF THE PRETRAINED MODELS: 
  * The aforementioned pre-trained models were tested on <a href="https://github.com/xuewenyuan/TGRNet">`TableGraph24k`</a> that was unfamiliar to each model to assess their capabilities in predicting bounding borders and extracting structures. The results for all the three types can be seen <a href="https://github.com/FutureRising007/Table_Structure_Recognition/tree/main/5.1%20Examining%20the%20Patterns%20of%20the%20Latest%20Models">here</a>.
  

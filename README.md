# Tracking Progress in Natural Language Processing

## Table of contents

### English

- [Automatic speech recognition 自动语音识别](english/automatic_speech_recognition.md)
- [CCG 组合分类语法](english/ccg.md)
- [Common sense 常识](english/common_sense.md)
- [Constituency parsing 成分句法分析](english/constituency_parsing.md)
- [Coreference resolution 指代消解](english/coreference_resolution.md)
- [Dependency parsing 依赖解析](english/dependency_parsing.md)
- [Dialogue 对话](english/dialogue.md)
- [Domain adaptation 域自适应](english/domain_adaptation.md)
- [Entity linking 实体链接](english/entity_linking.md)
- [Grammatical error correction 语法错误校正](english/grammatical_error_correction.md)
- [Information extraction 信息提取](english/information_extraction.md)
- [Language modeling 语言模型](english/language_modeling.md)
- [Lexical normalization 词法归一化](english/lexical_normalization.md)
- [Machine translation 机器翻译](english/machine_translation.md)
- [Missing elements 遗失元素](english/missing_elements.md)
- [Multi-task learning 多任务学习](english/multi-task_learning.md)
- [Multi-modal 多模态](english/multimodal.md)
- [Named entity recognition 命名实体识别](english/named_entity_recognition.md)
- [Natural language inference 自然语言推理](english/natural_language_inference.md)
- [Part-of-speech tagging 词性标记](english/part-of-speech_tagging.md)
- [Question answering 问答任务](english/question_answering.md)
- [Relation prediction 关联预测](english/relation_prediction.md)
- [Relationship extraction 关联提取](english/relationship_extraction.md)
- [Semantic textual similarity 语义文本相似性](english/semantic_textual_similarity.md)
- [Semantic parsing 语义解析](english/semantic_parsing.md)
- [Semantic role labeling 语义角色标注](english/semantic_role_labeling.md)
- [Sentiment analysis 情绪分析](english/sentiment_analysis.md)
- [Shallow syntax 浅语法](english/shallow_syntax.md)
- [Simplification 简化](english/simplification.md)
- [Intent Detection and Slot Filling 意向检测和插槽填充](english/intent_detection_slot_filling.md)
- [Stance detection 姿态检测](english/stance_detection.md)
- [Summarization 总结](english/summarization.md)
- [Taxonomy learning 分类学习](english/taxonomy_learning.md)
- [Temporal processing 时间处理](english/temporal_processing.md)
- [Text classification 文本分类](english/text_classification.md)
- [Word sense disambiguation 词义消歧](english/word_sense_disambiguation.md)

### Chinese

- [Entity linking](chinese/chinese.md#entity-linking)
- [Chinese word segmentation 中文分词](chinese/chinese_word_segmentation.md)

### Hindi

- [Chunking](hindi/hindi.md#chunking)
- [Part-of-speech tagging](hindi/hindi.md#part-of-speech-tagging)
- [Machine Translation](hindi/hindi.md#machine-translation)

### Vietnamese

- [Dependency parsing](vietnamese/vietnamese.md#dependency-parsing)
- [Machine translation](vietnamese/vietnamese.md#machine-translation)
- [Named entity recognition](vietnamese/vietnamese.md#named-entity-recognition)
- [Part-of-speech tagging](vietnamese/vietnamese.md#part-of-speech-tagging)
- [Word segmentation](vietnamese/vietnamese.md#word-segmentation)

### Spanish

- [Entity linking](spanish/entity_linking.md#entity-linking)

### Portuguese

- [Question Answering](portuguese/question_answering.md)

### Nepali

- [Machine Translation](nepali/nepali.md#machine-translation)

This document aims to track the progress in Natural Language Processing (NLP) and give an overview
of the state-of-the-art (SOTA) across the most common NLP tasks and their corresponding datasets.

It aims to cover both traditional and core NLP tasks such as dependency parsing and part-of-speech tagging
as well as more recent ones such as reading comprehension and natural language inference. The main objective
is to provide the reader with a quick overview of benchmark datasets and the state-of-the-art for their
task of interest, which serves as a stepping stone for further research. To this end, if there is a 
place where results for a task are already published and regularly maintained, such as a public leaderboard,
the reader will be pointed there.

If you want to find this document again in the future, just go to [`nlpprogress.com`](https://nlpprogress.com/)
or [`nlpsota.com`](http://nlpsota.com/) in your browser.

### Contributing

#### Guidelines

**Results** &nbsp; Results reported in published papers are preferred; an exception may be made for influential preprints.

**Datasets** &nbsp; Datasets should have been used for evaluation in at least one published paper besides 
the one that introduced the dataset.

**Code** &nbsp; We recommend to add a link to an implementation 
if available. You can add a `Code` column (see below) to the table if it does not exist.
In the `Code` column, indicate an official implementation with [Official](http://link_to_implementation).
If an unofficial implementation is available, use [Link](http://link_to_implementation) (see below).
If no implementation is available, you can leave the cell empty.

#### Adding a new result

If you would like to add a new result, you can just click on the small edit button in the top-right
corner of the file for the respective task (see below).

![Click on the edit button to add a file](img/edit_file.png)

This allows you to edit the file in Markdown. Simply add a row to the corresponding table in the
same format. Make sure that the table stays sorted (with the best result on top). 
After you've made your change, make sure that the table still looks ok by clicking on the
"Preview changes" tab at the top of the page. If everything looks good, go to the bottom of the page,
where you see the below form. 

![Fill out the file change information](img/propose_file_change.png)

Add a name for your proposed change, an optional description, indicate that you would like to
"Create a new branch for this commit and start a pull request", and click on "Propose file change".

#### Adding a new dataset or task

For adding a new dataset or task, you can also follow the steps above. Alternatively, you can fork the repository.
In both cases, follow the steps below:

1. If your task is completely new, create a new file and link to it in the table of contents above.
2. If not, add your task or dataset to the respective section of the corresponding file (in alphabetical order).
3. Briefly describe the dataset/task and include relevant references. 
4. Describe the evaluation setting and evaluation metric.
5. Show how an annotated example of the dataset/task looks like.
6. Add a download link if available.
7. Copy the below table and fill in at least two results (including the state-of-the-art)
  for your dataset/task (change Score to the metric of your dataset). If your dataset/task
  has multiple metrics, add them to the right of `Score`.
1. Submit your change as a pull request.
  
| Model           | Score  |  Paper / Source | Code |
| ------------- | :-----:| --- | --- |
|  |  |  | |


### Wish list

These are tasks and datasets that are still missing:

- Bilingual dictionary induction
- Discourse parsing
- Keyphrase extraction
- Knowledge base population (KBP)
- More dialogue tasks
- Semi-supervised learning
- Frame-semantic parsing (FrameNet full-sentence analysis)

### Exporting into a structured format

You can extract all the data into a structured, machine-readable JSON format with parsed tasks, descriptions and SOTA tables. 

The instructions are in [structured/README.md](structured/README.md).

### Instructions for building the site locally

Instructions for building the website locally using Jekyll can be found [here](jekyll_instructions.md).



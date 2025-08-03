# editpro
Data for Learning to Model Editing Processes by Machel Reid and Graham Neubig.

Paper: https://aclanthology.org/2022.findings-emnlp.280/

Please use the following citation:

```bibtex
@inproceedings{reid-neubig-2022-learning,
    title = "Learning to Model Editing Processes",
    author = "Reid, Machel  and
      Neubig, Graham",
    editor = "Goldberg, Yoav  and
      Kozareva, Zornitsa  and
      Zhang, Yue",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2022",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-emnlp.280/",
    doi = "10.18653/v1/2022.findings-emnlp.280",
    pages = "3822--3832",
    abstract = "Most existing sequence generation models produce outputs in one pass, usually left-to-right. However, this is in contrast with a more natural approach that humans use in generating content; iterative refinement and editing. Recent work has introduced edit-based models for various tasks (such as neural machine translation and text style transfer), but these generally model a single edit step. In this work, we propose modeling editing processes, modeling the whole process of iteratively generating sequences. We form a conceptual framework to describe the likelihood of multi-step edits, and describe neural models that can learn a generative model of sequences based on these multistep edits. We introduce baseline results and metrics on this task, finding that modeling editing processes improves performance on a variety of axes on both our proposed task and related downstream tasks compared to previous single-step models of edits."
}
```

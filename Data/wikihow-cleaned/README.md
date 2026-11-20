---
license: cc-by-nc-sa-3.0
task_categories:
- summarization
- text-generation
language:
- en
size_categories:
- 100K<n<1M
---
A cleaned version of the Wikihow dataset for abstractive text summarization.

# Changes made
Changes to the original dataset include:
- All words have been made lowercase
- All punctuation removed except ".", "," and "-"
- Spaces added before and after all punctuation
- NA values dropped from dataset
- Leading and trailing newline and space characters removed

These changes allow for easier tokenization.

# Citation

```
@misc{koupaee2018wikihow,
    title={WikiHow: A Large Scale Text Summarization Dataset},
    author={Mahnaz Koupaee and William Yang Wang},
    year={2018},
    eprint={1810.09305},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
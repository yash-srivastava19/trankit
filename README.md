## A Modified Fork of Trankit to exploit rich features

<h2 align="center">Trankit: A Light-Weight Transformer-based Python Toolkit for Multilingual Natural Language Processing</h2>

<div align="center">
    <a href="https://github.com/nlp-uoregon/trankit/blob/master/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/nlp-uoregon/trankit.svg?color=blue">
    </a>
    <a href='https://trankit.readthedocs.io/en/latest/?badge=latest'>
    <img src='https://readthedocs.org/projects/trankit/badge/?version=latest' alt='Documentation Status' />
    </a>
    <a href="http://nlp.uoregon.edu/trankit">
        <img alt="Demo Website" src="https://img.shields.io/website/http/trankit.readthedocs.io/en/latest/index.html.svg?down_color=red&down_message=offline&up_message=online">
    </a>
    <a href="https://pypi.org/project/trankit/">
        <img alt="PyPI Version" src="https://img.shields.io/pypi/v/trankit?color=blue">
    </a>
    <a href="https://pypi.org/project/trankit/">
        <img alt="Python Versions" src="https://img.shields.io/pypi/pyversions/trankit?colorB=blue">
    </a>
</div>

[Our technical paper](https://arxiv.org/pdf/2101.03289.pdf) for Trankit won the Outstanding Demo Paper Award at [EACL 2021](https://2021.eacl.org/). Please cite the paper if you use Trankit in your research.

```bibtex
@inproceedings{nguyen2021trankit,
      title={Trankit: A Light-Weight Transformer-based Toolkit for Multilingual Natural Language Processing}, 
      author={Nguyen, Minh Van and Lai, Viet Dac and Veyseh, Amir Pouran Ben and Nguyen, Thien Huu},
      booktitle="Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics: System Demonstrations",
      year={2021}
}
```

Proceed to the original trankit repo to see the installation instruction.

## Why this fork ?

I wanted to have a language analyzer toolkit that made use of Transformer(and preferably, adapters) - and then I came across Trankit. But, more than the annotated features, I was more interested in the rich embeddings that each module produced. These embedding features(and the actual linguistic features) I believe are really important to guide system toward better language understanding.

I could've made a toolkit by hand, but this fork actually really works, so why not??

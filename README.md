# IR From Bag-of-words to BERT and Beyond through Practical Experiments

This is the official repository of "*IR From Bag-of-words to BERT and Beyond through Practical Experiments*", a [CIKM 2021](https://www.cikm2021.org/) full-day tutorial with [PyTerrier](https://github.com/terrier-org/pyterrier) and [OpenNIR](https://opennir.net) search toolkits.

> This is an updated edition of our previous [ECIR 2021 Tutorial](https://github.com/terrier-org/ecir2021tutorial)

# Contents

* Part 1: Classical IR: indexing, retrieval and evaluation 
  - [Slides](slides/part1.pdf)
  - [Notebook](notebooks/notebook1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook1.ipynb)
* Part 2: Modern Retrieval Architectures: PyTerrier data model and operators, towards re-rankers and learning-to-rank
  - [Slides](slides/part2.pdf)
  - [Notebook](notebooks/notebook2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook2.ipynb)
* Part 3: Contemporary Retrieval Architectures: Neural re-rankers such as BERT, EPIC, T5 and neural inverted index augmentation such as DeepCT and Doc2Query
  - [Slides](slides/part3.pdf)
  - [Notebook](notebooks/notebook3.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook3.ipynb)
* Part 4: Recent Advances beyond the classical inverted index: learned sparse retrieval, dense retrieval, nearest neighbour search
  - [Slides](slides/part4.pdf)
  - [DeepImpact Notebook](notebooks/notebook4_1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook4_1.ipynb)
  - [ANCE Notebook](notebooks/notebook4_2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook4_2.ipynb)
  - [ColBERT Notebook](notebooks/notebook4_3.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/cikm2021tutorial/blob/main/notebooks/notebook4_3.ipynb)

# Schedule

Our tutorial will run twice on Friday 5th November 2021, with live lab sessions.

 Suggested viewing:
  - Europe, Africa, West/South/Central Asia: Run 1
  - North/South America: Run 2
  - East Asia and Oceania: Run 1 (parts 1 & 2), followed by Run 2 (parts 3 & 4)

**Run 1**: Aligned with Europe, Africa, and West/South/Central Asia, partially accessible to East Asia/Oceania

| London (GMT) | Content | Live | Johannesburg (GMT+2) | Delhi (GMT+5:30) | Beijing (GMT+8) | Brisbane (GMT+10)|
|-----|---------|:---:|---------|--------|--------|---------|
| 0900-1000 | part 1 slides | ✅ | 1100-1200 | 1430-1530 | 1700-1800 | 1900-2000 |
| 1000-1030 | part 1 lab | ✅    | 1200-1230 | 1530-1600 | 1800-1830 | 2000-2030 |
| 1030-1100 | break | ☕         | 1230-1300 | 1600-1630 | 1830-1900 | 2030-2100 |
| 1100-1200 | part 2 slides | ✅ | 1300-1400 | 1630-1730 | 1900-2000 | 2100-2200 |
| 1200-1230 | part 2 lab | ✅    | 1400-1430 | 1730-1800 | 2000-2030 | 2200-2230 |
| 1230-1330 | break | ☕         | 1430-1530 | 1800-1900 |
| 1330-1430 | part 3 slides | ✅ | 1530-1630 | 1900-2000 |
| 1430-1500 | part 3 lab | ✅    | 1630-1700 | 2000-2030 |
| 1500-1530 | break | ☕         | 1700-1730 | 2030-2100 |
| 1530-1630 | part 4 slides | ✅ | 1730-1830 | 2100-2200 |
| 1630-1700 | part 4 lab | ✅    | 1830-1900 | 2200-2230 |

**Run 2**: Aligned with North/South America, partially accessible to East Asia/Oceania


| LA (GMT-7) | Content | Live | New York (GMT-4) | São Paulo (GMT-3) | Beijing (GMT+8) | Brisbane (GMT+10)|
|-----|-------|:--:|------|-----------|------------|-----------|
| 1100-1200 | part 1 slides | 🎥  | 1400-1500 | 1500-1600 |
| 1200-1230 | part 1 lab | ✅     | 1500-1530 | 1600-1630 |
| 1230-1300 | break | ☕          | 1530-1600 | 1630-1700 |
| 1300-1400 | part 2 slides  | 🎥 | 1600-1700 | 1700-1800 |
| 1400-1430 | part 2 lab | ✅     | 1700-1730 | 1800-1830 |
| 1430-1530 | break | ☕          | 1730-1830 | 1830-1930 |
| 1530-1630 | part 3 slides  | 🎥 | 1830-1930 | 1930-2030 | 0630-0730 (6 Nov) | 0830-0930 (6 Nov) |
| 1630-1700 | part 3 lab | ✅     | 1930-2000 | 2030-2100 | 0730-0800 (6 Nov) | 0930-1000 (6 Nov) |
| 1700-1730 | break | ☕          | 2000-2030 | 2100-2130 | 0800-0830 (6 Nov) | 1000-1030 (6 Nov) |
| 1730-1830 | part 4 slides  | 🎥 | 2030-2130 | 2130-2230 | 0830-0930 (6 Nov) | 1030-1030 (6 Nov) |
| 1830-1900 | part 4 lab | ✅     | 2130-2200 | 2230-2300 | 0930-1000 (6 Nov) | 1030-1200 (6 Nov) |

We are thankful to Luca and Eugene for supporting additional live labs, and for CIKM 2021 volunteers, for being able to support this schedule.

# Authors

* [Sean MacAvaney](https://macavaney.us), University of Glasgow, UK
* [Craig Macdonald](http://www.dcs.gla.ac.uk/~craigm/), University of Glasgow, UK
* [Nicola Tonellotto](http://tonellotto.github.io), University of Pisa, IT

Contributors to Live Labs:

* [Luca Soldaini](https://soldaini.net/), Amazon, US
* [Eugene Yang](https://www.eugene.zone/), Johns Hopkins University, US



# Useful Links

 - PyTerrier: [[Github](https://github.com/terrier-org/pyterrier)] [[Documentation](https://pyterrier.readthedocs.io/en/latest/)]
 - OpenNIR: [[Github](https://github.com/Georgetown-IR-Lab/OpenNIR)] [[Documentation](https://opennir.net/)]
 - PyTerrier_ColBERT: [[Github](https://github.com/terrierteam/pyterrier_colbert)]
 - PyTerrier_T5: [[Github](https://github.com/terrierteam/pyterrier_t5)]
 - PyTerrier_doc2query: [[Github](https://github.com/terrierteam/pyterrier_doc2query)]
 - PyTerrier_DeepCT: [[Github](https://github.com/terrierteam/pyterrier_deepct)]
 - PyTerrier_ANCE: [[Github](https://github.com/terrierteam/pyterrier_ance)]
 - PyTerrier_DeepImpact [[Github](https://github.com/terrierteam/pyterrier_deepimpact)]

# Citation Policy

If you make using of any of these slides, notebooks, or additional PyTerrier plugins, please cite our tutorial abstract:

```bibtex

@inproceedings{cikm2021-tut-bow2b,
  author = {MacAvaney, Sean and Macdonald, Craig and Tonellotto, Nicola},
  title = {IR From Bag-of-words to BERT and Beyond through Practical Experiments: A CIKM 2021 tutorial with PyTerrier and OpenNIR},
  booktitle = {Proceedings of CIKM 2021},
  year = {2021}
}

```

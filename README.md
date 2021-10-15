# IR From Bag-of-words to BERT and Beyond through Practical Experiments

This is the official repository of "*IR From Bag-of-words to BERT and Beyond through Practical Experiments*", a [CIKM 2021](https://www.cikm2021.org/) full-day tutorial with [PyTerrier](https://github.com/terrier-org/pyterrier) and [OpenNIR](https://opennir.net) search toolkits.

> This is an updated edition of our previous [ECIR 2021 Tutorial](https://github.com/terrier-org/ecir2021tutorial)

# Contents

* Part 1: Classical IR: indexing, retrieval and evaluation 
* Part 2: Modern Retrieval Architectures: PyTerrier data model and operators, towards re-rankers and learning-to-rank
* Part 3: Contemporary Retrieval Architectures: Neural re-rankers such as BERT, EPIC, ColBERT
* Part 4: Recent Advances beyond the classical inverted index: neural inverted index augmentation, nearest neighbor search, dense retrieval


# Schedule

Our tutorial will run twice on Friday 5th November 2021, with live lab sessions.

 Suggested viewing:
  - Western Europe: Run 1
  - North/South America: Run 2
  - Asia and Oceania: Run 1 (parts 1 & 2), followed by Run 2 (parts 3 & 4)

**Run 1**: Aligned with Western Europe, partially accessible to Americas or Asia/Oceania

| London (GMT) | Content | Live | Beijing (GMT+8) | Brisbane (GMT+10)|
|-----|---------|---|-----------------|-----------------|
| 0900-1000 | part 1 slides | :heavy_check_mark: | 1700-1800 | 1900-2000 |
| 1000-1030 | part 1 lab | :heavy_check_mark:    | 1800-1830 | 2000-2030 |
| 1030-1100 | break | ☕                         | 1830-1900 | 2030-2100 |
| 1100-1200 | part 2 slides | :heavy_check_mark: | 1900-2000 | 2100-2200 |
| 1200-1230 | part 2 lab | :heavy_check_mark:    | 2000-2030 | 2200-2230 |
| 1230-1330 | break | ☕                         | 
| 1330-1430 | part 3 slides | :heavy_check_mark: |
| 1430-1500 | part 3 lab | :heavy_check_mark:    |
| 1500-1530 | break | ☕                         |
| 1530-1630 | part 4 slides | :heavy_check_mark: |
| 1630-1700 | part 4 lab | :heavy_check_mark:    |

**Run 2**: Aligned with North/South America, partially accessible to Asia/Oceania


| LA (GMT-7) | Content | Live | New York (GMT-4) | Beijing (GMT+8) | Brisbane (GMT+10)|
|-----|-------|--|------|-----------|-----------------------|
| 1000-1100 | part 1 slides | 🎥              | 1300-1400 |
| 1100-1130 | part 1 lab | :heavy_check_mark: | 1400-1430 |
| 1130-1200 | break | ☕                      | 1430-1500 |
| 1200-1300 | part 2 slides  | 🎥             | 1500-1600 |
| 1300-1330 | part 2 lab | :heavy_check_mark: | 1600-1630 |
| 1330-1430 | break | ☕                      | 1630-1730 |
| 1430-1530 | part 3 slides  | 🎥             | 1730-1830 | 0530-0630 (6 Nov) | 0730-0830 (6 Nov) |
| 1530-1600 | part 3 lab | :heavy_check_mark: | 1830-1900 | 0630-0700 (6 Nov) | 0830-0900 (6 Nov) |
| 1600-1630 | break | ☕                      | 1900-1930 | 0700-0730 (6 Nov) | 0900-0930 (6 Nov) |
| 1630-1730 | part 4 slides  | 🎥             | 2030-2130 | 0730-0830 (6 Nov) | 0930-1030 (6 Nov) |
| 1730-1800 | part 4 lab | :heavy_check_mark: | 2130-2200 | 0830-0900 (6 Nov) | 1030-1100 (6 Nov) |

We are thankful to Luca and Eugene for supporting additional live labs, and for CIKM 2021 volunteers, for being able to support this schedule.

# Authors

* [Sean MacAvaney](https://macavaney.us), University of Glasgow, UK
* [Craig Macdonald](http://www.dcs.gla.ac.uk/~craigm/), University of Glasgow, UK
* [Nicola Tonellotto](http://tonellotto.github.io), University of Pisa, IT

Contributors to Live Labs:

* [Luca Soldini](https://soldaini.net/), Amazon, US
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

@inproceedings{ecir2021-tut-bow2b,
  author = {MacAvaney, Sean and Macdonald, Craig and Tonellotto, Nicola},
  title = {IR From Bag-of-words to BERT and Beyond through Practical Experiments: A CIKM 2021 tutorial with PyTerrier and OpenNIR},
  booktitle = {Proceedings of CIKM 2021},
  year = {2021}
}

```

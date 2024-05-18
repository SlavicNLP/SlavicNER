# SlavicNER
Cross-lingual Named Entity Corpus for Slavic Languages

# Resources and Technical Documentation

- Paper: https://aclanthology.org/2024.lrec-main.369
- Annotation guidelines: https://arxiv.org/pdf/2404.00482
- Baseline models: https://huggingface.co/SlavicNLP
- SlavicNER Corpus: https://github.com/SlavicNLP/SlavicNER (this repo)

# Citation

```
@inproceedings{piskorski-etal-2024-cross-lingual,
    title = {Cross-lingual Named Entity Corpus for {S}lavic Languages},
    author = "Piskorski, Jakub  and
      Marci{\'n}czuk, Micha{\l}  and
      Yangarber, Roman",
    editor = "Calzolari, Nicoletta  and
      Kan, Min-Yen  and
      Hoste, Veronique  and
      Lenci, Alessandro  and
      Sakti, Sakriani  and
      Xue, Nianwen",
    booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics,
       Language Resources and Evaluation (LREC-COLING 2024)",
    month = may,
    year = "2024",
    address = "Torino, Italy",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.lrec-main.369",
    pages = "4143--4157",
    abstract = "This paper presents a corpus manually annotated with named entities for six Slavic
       languages {---} Bulgarian, Czech, Polish, Slovenian, Russian, and Ukrainian.
       This work is the result of a series of shared tasks, conducted in 2017{--}2023 as a part
       of the Workshops on Slavic Natural Language Processing. The corpus consists of 5,017 documents
       on seven topics. The documents are annotated with five classes of named entities.
       Each entity is described by a category, a lemma, and a unique cross-lingual identifier.
       We provide two train-tune dataset splits {---} single topic out and cross topics.
       For each split, we set benchmarks using a transformer-based neural network architecture
       with the pre-trained multilingual models {---} XLM-RoBERTa-large for named entity mention
       recognition and categorization, and mT5-large for named entity lemmatization and linking.",
}
```

# Acknowledgements

We are grateful to the following people for contributing to the annotation of the data or other activities which contributed to the creation of the presented dataset: Bogdan Babych, Anna Dmitrieva, Zara Kancheva, Olga Kanishcheva, Anisia Katinskaia, Laska Laskova, Maria Lebedeva, Preslav Nakov, Petya Osenova, Lidia Pivovarova, Senja Pollak,
Pavel Pribáň, Ivaylo Radev, Kiril Simov,  Marko Robnik-Šikonja, Piotr Rybak, Jan Šnajder, Vasyl Starko, and Josef Steinberger.

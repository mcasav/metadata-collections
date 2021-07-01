# metadata-collections

Here we provide the metadata-extended parts of previously annotated abusive language datasets.

Each collection contains a set of discretized metadata features, associated to tweets used as samples in abusive language detection tasks.
For each metadata collection, we provide a "Dataset Index" that matches their original identifier from their respective abusive language dataset, with two exceptions:

For Waseem Dataset, we considered the original order of the samples and added a new index:
Dataset_Index "#1" references tweet id "572342978255048705" and Dataset_Index "#16907" references tweet id "569363477095174145".

For the Benevolent Sexism Dataset, we considered the original order of the samples and added a new index:
Dataset Index "#1" references tweet id "839880162586071040" and Dataset Index "#7205" references tweet id "839850933987196928".

The "user:masked_username" feature is independent between datasets (username_1 from one collection isn't the same as username_1 from a different file, except between "Waseem" and "Benevolent Sexism").

These collections are meant to be used together with their respective abusive language dataset. For samples and labels, please refer to the original works.

If using `Waseem_MD.csv`, consult:
~~~
@InProceedings{waseem-hovy:2016:N16-2,
  author    = {Waseem, Zeerak  and  Hovy, Dirk},
  title     = {Hateful Symbols or Hateful People? Predictive Features for Hate Speech Detection on Twitter},
  booktitle = {Proceedings of the NAACL Student Research Workshop},
  month     = {June},
  year      = {2016},
  address   = {San Diego, California},
  publisher = {Association for Computational Linguistics},
  pages     = {88--93},
  url       = {http://www.aclweb.org/anthology/N16-2013}
}
~~~

If using `BenevSexism_MD.csv`, consult:
~~~
@inproceedings{jha2017does,
  title={When does a compliment become sexist? analysis and classification of ambivalent sexism using twitter data},
  author={Jha, Akshita and Mamidi, Radhika},
  booktitle={Proceedings of the Second Workshop on NLP and Computational Social Science},
  pages={7--16},
  year={2017}
}
~~~

If using `Hatebase_Twitter_MD.csv`, consult:
~~~
@inproceedings{hateoffensive,
  title = {Automated Hate Speech Detection and the Problem of Offensive Language},
  author = {Davidson, Thomas and Warmsley, Dana and Macy, Michael and Weber, Ingmar}, 
  booktitle = {Proceedings of the 11th International AAAI Conference on Web and Social Media},
  series = {ICWSM '17},
  year = {2017},
  location = {Montreal, Canada},
  pages = {512-515}
  }
~~~

If using `MEX-A3T-2018_MD.csv`, consult:
~~~
@inproceedings{inproceedings,
  author = {Carmona, Miguel Angel and Guzmán-Falcón, Estefanía and Montes, Manuel and Escalante, Hugo Jair and Villaseñor-Pineda, Luis and Reyes-Meza, Veronica and     Rico-Sulayes, Antonio},
  year = {2018},
  month = {08},
  pages = {},
  title = {Overview of MEX-A3T at IberEval 2018: Authorship and aggressiveness analysis in Mexican Spanish tweets}
}
~~~

If using `hatEval_ENG_MD.csv` or `hatEval_SPAN_MD.csv`, consult:
~~~
@inproceedings{basile-etal-2019-semeval,
  title = "{S}em{E}val-2019 Task 5: Multilingual Detection of Hate Speech Against Immigrants and Women in {T}witter",
  author = "Basile, Valerio  and
      Bosco, Cristina  and
      Fersini, Elisabetta  and
      Nozza, Debora  and
      Patti, Viviana  and
      Rangel Pardo, Francisco Manuel  and
      Rosso, Paolo  and
      Sanguinetti, Manuela",
  booktitle = "Proceedings of the 13th International Workshop on Semantic Evaluation",
  month = jun,
  year = "2019",
  address = "Minneapolis, Minnesota, USA",
  publisher = "Association for Computational Linguistics",
  url = "https://www.aclweb.org/anthology/S19-2007",
  doi = "10.18653/v1/S19-2007",
  pages = "54--63",
}
~~~

If using `HASOC_MD.csv`, consult:
~~~
@inproceedings{inproceedings,
  author = {Majumder, Prasenjit and Patel, Daksh and Modha, Sandip and Mandl, Thomas},
  year = {2019},
  month = {12},
  pages = {},
  title = {Overview of the HASOC track at FIRE 2019: Hate Speech and Offensive Content Identification in Indo-European Languages},
  doi = {10.1145/3368567.3368584}
}
~~~

If using `MEX-A3T-2020_MD.csv`, consult:
~~~
@inproceedings{aragon2020overviewv2,
  title={Overview of {MEX-A3T} at {IberLEF} 2020: Fake news and {Aggressiveness Analysis in Mexican Spanish}},
  author={Arag{\'o}n, Mario Ezra and Jarqu{\'i}n, Horacio and Montes-y-G{\'o}mez, Manuel and Escalante, Hugo Jair and Villase{\~{n}}or-Pineda, Luis and G{\'o}mez       Adorno, Helena and Bel-Enguix, Gemma and Posadas-Dur{\'a}n, Juan-Pablo},
  booktitle={Notebook Papers of 2nd SEPLN Workshop on Iberian Languages Evaluation Forum (IberLEF), Malaga, Spain, September},
  year={2020}
}
~~~

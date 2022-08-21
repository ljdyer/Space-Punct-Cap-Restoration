### Authors

| Name  | Contact |
| ------------- | ------------- |
| Anthony Hughes¹ | [A.J.Hughes2@wlv.ac.uk](mailto:A.J.Hughes2@wlv.ac.uk) |
| Laurence Dyer¹ | [L.J.Dyer@wlv.ac.uk](mailto:L.J.Dyer@wlv.ac.uk) / [ljdyer@gmail.com](mailto:ljdyer@gmail.com) |
| Dhwani Shah | [D.R.Shah2@wlv.ac.uk](mailto:D.R.Shah2@wlv.ac.uk) |
| Burcu Can | [B.Can@wlv.ac.uk](mailto:B.Can@wlv.ac.uk) |

¹Anthony Hughes and Laurence Dyer contributed equally to this work as first authors.

### Code repositories

#### Evaluation metrics

| Repo name  | Description |
| ------------- | ------------- |
| [Feature Restorer Metric Getter](https://github.com/ljdyer/Feature-Restorer-Metric-Getter)  | A Python class for calculating precision/recall/F-score and word error rate (WER) metrics for the outputs of feature restoration models against reference strings.  |

#### Models

| Repo name  | Model name(s) in paper | Description |
| ------------- | ------------- | ------------- |
| [Naive Bayes Space Restorer](https://github.com/ljdyer/Naive-Bayes-Space-Restorer) | NB | A Python class to enable convenient training of a Naive Bayes-based statistical model for restoration of spaces to unsegmented streams of input characters.
| [BiLSTM Char Feature Restorer](https://github.com/ljdyer/BiLSTM-Char-Feature-Restorer/) | BiLSTMCharSpace, BiLSTMCharE2E | A Python class to enable convenient training of BiLSTM character-level models for restoration of features such as spaces, punctuation, and capitalisation to unsegmented streams of input characters.
| [CRF for Punctuation Restoration](https://github.com/anthonyhughes/crf-punctuation-restoration) | CRF | Conditional Random Fields model for a punctuation restoration task.
| [Punctuation Restoration using Transformer Models](https://github.com/anthonyhughes/finetuning-en-punctuation-restoration) | BERTBiLSTM | An extension of the paper Punctuation Restoration using Transformer Models for High-and Low-Resource Languages accepted at the EMNLP workshop W-NUT 2020.

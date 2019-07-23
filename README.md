# nepali-translator

The parallel data can be downloaded from [here](https://drive.google.com/open?id=1UThfJKJFvDgTu263DNbz-WPNLqoARZ_0).

The report is available [here](https://drive.google.com/open?id=16F4e1Wr3ElosFnoVfZrEId4N0be2JPG4).

`data_cleaning` directory has the scripts that implement the cleaning methods discussed in the report.

`translator` directory has a working interface for the translator. Model files that realize the BLEU scores mentioned in the report will be made available soon.

## Requirements
* torch
* fairseq
* sentencepiece
* sacremoses
* [indic_nlp_library](https://github.com/anoopkunchukuttan/indic_nlp_library) [copy to `translator/modules/indic_nlp_library`]
* flask
* lxml
* python-docx

After requirements and models are in place, run `python app/app.py` from `translator` directory.

Additional updates will be made to this repo as felt necessary.

## Citation
If you use any part of this project in your work, please cite:

```bibtex
@inproceedings{,
  title={Nepali Translator},
  author={Duwal, Sharad and Manandhar, Amir and Maskey, Saurav and Hada, Subash},
  year={2019}
}
```

For the completion of sixth semester in Computer Science program at Kathmandu University. July 2019.
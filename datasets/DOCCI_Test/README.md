The dataset is presented in `jsonl` format and consists of dense human-authored image descriptions using IIW's annotation framework and human SxS comparisons on 100 images sampled from [DOCCI](https://github.com/google/docci) test set.


| key       | interpretation | 
| :-------- | :------ |
| DOCCI   |   human-authored description from DOCCI's annotation framework  |
| IIW   |   human-authored description from IIW's annotation framework  |
| image   |   image identifier as defined in DOCCI's dataset  |
| metrics/* | 5 point scale comparison between IIW and DOCCI's human-authored description as described in the IIW paper.|

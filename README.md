<h2>ImageInWords: Unlocking Hyper-Detailed Image Descriptions</h2> 

arXiv: https://arxiv.org/abs/2405.02793

Please visit the [webpage](https://google.github.io/imageinwords) for all the information about the IIW project, data, visualizations, and much more. The data can be downloaded directly from the `datasets/` folder, as well as from Huggingface (see below).

<img src="static/images/Abstract/1_white_background.png">
<img src="static/images/Abstract/2_white_background.png">


Please reach out to iiw-dataset@google.com for thoughts/feedback/questions/collaborations.

License: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

<h3>Other resources</h3>

<h4>&#129303;Hugging Face&#129303;</h4>

<li><a href="https://huggingface.co/datasets/google/imageinwords">Dataset</a></li>

```python
from datasets import load_dataset

# `name` can be one of: IIW-400, DCI_Test, DOCCI_Test, CM_3600, LocNar_Eval
# refer: https://github.com/google/imageinwords/blob/main/datasets/README.md
dataset = load_dataset("google/imageinwords", token="YOUR_HF_ACCESS_TOKEN", name="IIW-400")
```

<li><a href="https://huggingface.co/spaces/google/imageinwords-explorer">Dataset-Explorer</a></li>

<h3>Cite</h3>

If you use our data or refer to our work, please include the following citation
```
@misc{garg2024imageinwords,
      title={ImageInWords: Unlocking Hyper-Detailed Image Descriptions}, 
      author={Roopal Garg and Andrea Burns and Burcu Karagol Ayan and Yonatan Bitton and Ceslee Montgomery and Yasumasa Onoe and Andrew Bunner and Ranjay Krishna and Jason Baldridge and Radu Soricut},
      year={2024},
      eprint={2405.02793},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

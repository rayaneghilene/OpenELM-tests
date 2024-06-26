# OpenELM-tests (colab)
This repository contains text generation and classification, using the OpenELM model released by Apple.


<div style=" text-align:right;width:300px; display:block; margin:auto;" >
    <img src="https://github.com/rayaneghilene/OpenELM-tests/assets/100053511/7b7b7a92-8043-41ae-9cdb-20dce64b24ed" alt="image" >
</div>



## Usage
The OpenELM models are using the llama-2-7b Tokenizer : ```meta-llama/Llama-2-7b-hf```

You must request access to the model llama2: https://huggingface.co/meta-llama/Llama-2-7b-chat-hf

The notebooks provided in this repo are straightforward, just clone the repo using the following:
```
git clone https://github.com/rayaneghilene/OpenELM-tests.git
```

## Requirements 


**Install the latest version of transformers from GitHub**
```
!pip install git+https://github.com/huggingface/transformers.git@main
```


## Reference

Paper : https://arxiv.org/abs/2404.14619

```
  @article{mehtaOpenELMEfficientLanguage2024,
      title = {{OpenELM}: {An} {Efficient} {Language} {Model} {Family} with {Open}-source {Training} and {Inference} {Framework}},
      shorttitle = {{OpenELM}},
      url = {https://arxiv.org/abs/2404.14619v1},
      language = {en},
      urldate = {2024-04-24},
      journal = {arXiv.org},
      author = {Mehta, Sachin and Sekhavat, Mohammad Hossein and Cao, Qingqing and Horton, Maxwell and Jin, Yanzi and Sun, Chenfan and Mirzadeh, Iman and Najibi, Mahyar and Belenko, Dmitry and Zatloukal, Peter and Rastegari, Mohammad},
      month = apr,
      year = {2024},
  }
  
  @inproceedings{mehta2022cvnets, 
       author = {Mehta, Sachin and Abdolhosseini, Farzad and Rastegari, Mohammad}, 
       title = {CVNets: High Performance Library for Computer Vision}, 
       year = {2022}, 
       booktitle = {Proceedings of the 30th ACM International Conference on Multimedia}, 
       series = {MM '22} 
  }
```


## Contact
Contact me at rayane.ghilene@ensea.fr If you have any questions

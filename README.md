# ganVanGogh

Web App that generates paintings in the Vincent Van Gogh style by prompt. Uses CLIP and VQGAN models.
Weights are also accessible here: https://drive.google.com/file/d/1eI8j4zOi1L2BINO-6Ml7vZDguwioXdrY/view?usp=sharing

## Usage
```
conda create --name vqgan python=3.9
conda activate vqgan
pip install -r requirements.txt
python app.py
```
Will run web app on localhost:5000
![alt text](https://github.com/blaneart/ganVanGogh/blob/main/samples/webpage.png?raw=true)

## Citations
```
@misc{unpublished2021clip,
    title  = {CLIP: Connecting Text and Images},
    author = {Alec Radford, Ilya Sutskever, Jong Wook Kim, Gretchen Krueger, Sandhini Agarwal},
    year   = {2021}
}
```
```
@misc{esser2020taming,
      title={Taming Transformers for High-Resolution Image Synthesis}, 
      author={Patrick Esser and Robin Rombach and Björn Ommer},
      year={2020},
      eprint={2012.09841},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

# checklist-irony
Code to get started

Create a checklist for Irony detection and use it to evaluate the Irony Detection model proposed by Camacho-Collados et al. (2022). The model can be found on Huggingface (https://huggingface.co/cardiffnlp/roberta-base-irony?library=transformers). 

## Getting started with anaconda (recommended)

Please create a new conda environment using the `environment.yml` file as follows: from this directory, run:

```
# create the evironment
conda env create -f environment.yml
# launch the environment
conda activate irony
# launch jupyter lab
jupyter lab
```

Then use the notebook (IronyModel.ipynb) to run the model. 


## Getting started without anaconda

Follow the instructions on HuggingFace to run the irony detection model: https://huggingface.co/cardiffnlp/roberta-base-irony?library=transformers


## References

Camacho-Collados, J., Rezaee, K., Riahi, T., Ushio, A., Loureiro, D., Antypas, D., Boisson, J., Anke, L.E., Liu, F. and Martínez-Cámara, E., 2022, December. TweetNLP: Cutting-Edge Natural Language Processing for Social Media. In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing: System Demonstrations (pp. 38-49).

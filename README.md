# Conditional Variational AutoEncoder

This is model can generate generate it's own handwritten digits given a number to generate, and a noise image.  

This is a repository for my autoencoder project. To view the results of the model's image generation, select the autoEncoder.ipynb file, and scroll to
the very bottom, where you can find the generative imgage capabilites under a section called: 
_Generate new handwritten digits given a noise image, and a desired number_. The structure and source code for the model, in addition to
the simpler VAE model are also all in the autoEncoder.ipynb file. 

### TO RUN THE CODE, DO THIS:

In a powershell terminal (in this directory) (also in vscode), do these commands:

```
$ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
$ python -m venv .venv
$ .venv\Scripts\activate
$ pip install -r requirements.txt
$ pip install ipykernel
$ python -m ipykernel install --user --name=.venv
```


After doing this, make sure that the kernel is running this .venv by checking the box
at the top right of the screen. If it is not, then click on the button, and then look for 
the .venv enviornment under python. 

Once you are done, use the command

```$ deactivate```

to deactivate the virual enviornment. 

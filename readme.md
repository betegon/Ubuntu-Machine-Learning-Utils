# UBUNTU MACHINE LEARNING UTILS

This repository contains a set of utils that are useful when you are about to set a machine for machine learning projects.


## ANACONDA
In order to use any of these utils, you first need to install *Anaconda* from [Anaconda page](https://www.anaconda.com/distribution/).

## Conda tab completion
`conda` does not have any tab completion by default, making it difficult to activate repositories or use any conda commands witouth typing a help / list command.

Type this in your terminal to install conda completion.
```bash
conda install -c tartansandal conda-bash-completion
```
A reboot is required after installing the completion package. 
 
Reference: [https://github.com/conda/conda/issues/9178](https://github.com/conda/conda/issues/9178)

## Anaconda-Navigator Desktop entry
As Ubuntu does not have a desktop entry for *Anaconda-Navigator*, it is a good idea to create one. *Anaconda* is a tool you will want to use daily in your ML projects. 

I personally prefer using a terminal for managing *Anaconda* but the navigator lets you dive into your *Anaconda* first steps.

### Steps
1.  Modify *betegon* with your Ubuntu username.
2.  Be sure you have python 3.7 installed in *Anaconda*, if other version, change it in the file.
3.  Move `Anaconda.desktop` to `/usr/share/applications` with root permissions.
	* `mv Anaconda.desktop /usr/share/applications`


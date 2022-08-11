# lung-cancer-predict

![cidar image](https://images.pexels.com/photos/247040/pexels-photo-247040.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

[comment]: <> (This template serves to be used as a guide to write good documentation for github repositories)

[comment]: <> (Exemplo de READMEhttps://github.com/kefranabg/readme-md-generator)

[comment]: <> (Resoruces used to make this:
https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
)

---------------------------------------------------------------------------------------------------------

### What your application does?

This projects uses this [Dataset](https://www.kaggle.com/datasets/nancyalaswad90/lung-cancer) to build an artificial neural netowkr that predicts if a certan person will get lung cancer or not. based on 15 parameters. Some are: smoking, age anxiety shortness of breath...
 
 
### Why you used the technologies you used?

I used 3 python libraries and a framework:

- numpy

- pandas

- torchinfo

The framework was the PyTorch framework

Pandas and numpy for reading the .csv file to later convert it to a tensor with the Pytorch library.

The torch lubrary was used, because it is the framework [most used](https://paperswithcode.com/trends) now adays to do research in machine learning projects.
    
### Some of the challenges you faced and features you hope to implement in the future?

The biggest challenge so far is understanding the size of the neural netowrk, since this is my first by my own machine learning project.


-----


-----


# Table of Contents

### [ How to Install and Run the Project ](#How_to_install)

### [ How to Use the Project ](#How_to_use)



-----


<a name="How_to_install">

#### How to Install and Run the Project

Note: This instalation is on python 3.10.4 in a PC with the OS ubuntu 22.04
```
pip install --upgrade pip

pip install virtualenv
```
Then we create an virtual enviroment and activate it:

```
virtualenv envname

source envname/bin/activate
```
Now we install the libraries

```
pip install torch pandas=1.4.3 numpy=1.23.0 torchinfo jupyter
```

Now we just write in the command line:
```
jupyter notebok
```

And there we go!

Are are done and we can now run the project
</a>

<a name="How_to_use">


#### How to Use the Project

Just run the jupyter notebook in this projects and everything should work fine.

</a>


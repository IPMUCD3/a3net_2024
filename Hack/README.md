# Hack Resources

[google drive for data](https://drive.google.com/drive/u/1/folders/13ySEme-B8XDMYgTZ8_rVpMarRUUGYbTw)

It is most straightforward to directly work with the above Google drive from colab,
since the files don't need to leave Google's servers in that case.
The way I figured out how to do this is as follows (there might be a better method):
1. open the above Google drive.
2. right-click on the file or folder you need.
3. click "Organize" -> "Add shortcut".
4. in "All locations", choose "My Drive" and click "Add".
5. in the colab instance, open the "Files" explorer on the left.
6. click "Mount Drive" icon.
7. you should be able to see the file now.
   To switch the colab working directory to your drive, type:
   ``cd "/content/drive/MyDrive/"``

## Image Classification / Regression / Generation Tutorials and Exercises
---------
All the material is available at:
[this link](https://github.com/cesarjesusvalls/A3NetRingImg)

contact person: Cesar Jesus-Valls

## Galaxy Cluster Masses with CNNs
please follow [this link](https://drive.google.com/drive/folders/1yLN3xN-1EU2HPYcbX68Z8SgLQcs1LpiI?usp=sharing)

Goal: the paper, notebook, and data set in the link above are for a project that uses a CNN to estimate the mass of a galaxy cluster from x-ray mock observations. In this hack, you will first recreate the paper’s results. Then you will apply a rotationally invariant CNN, and see if that approach improves the results!

contact person: Michelle Ntampaka

## Galaxy redshifts with Decision Trees
please follow [this link](https://archive.stsci.edu/hello-universe/3d-hst)

Goal: the notebook and data set in the link above are for a project that uses a decision tree to estimate the redshifts of galaxies. In this hack, you will explore other ML algorithms for using the same data to estimate galaxy redshifts. Scikit-Learn has a [flow chart](https://scikit-learn.org/1.3/tutorial/machine_learning_map/index.html) for selecting ML methods. Support Vector Regression might be an interesting technique to try.
Note: the Hello Universe notebook is also available on the [TIKE science platform](https://timeseries.science.stsci.edu/hub/spawn) (select the default environment to spin up an AWS server)

contact person: Michelle Ntampaka

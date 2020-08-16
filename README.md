# Assessing Mock Classes: An Empirical Study Data

## Objective

This repository contains the data extracted from 12 open-source projects regarding Java classes that was used to make the paper Assessing Mock Classes: An Empirical Study Data, by Gustavo Pereira and André Hora, accepted for publication at the [36th IEEE International Conference on Software Maintenance and Evolution](https://icsme2020.github.io/).

## Description

The data is contained in a text file separated by semicolons (';').
Each row describes the features of a single Java class. It has fifteen columns:

* **ProjectName**: String representing the project's name, stated as its name on GitHub

* **Filename**: String representing the name (path) of the file that contains the class

* **Classname**: String representing the name of the class

* **LOC**: Integer representing the number of code lines of the class

* **Visibility**: Indicates the Java visibility of the class (`private`, `protected`, `package` or `public`)

* **IsMock**: Boolean (`True` or `False`) representing whether the class is classified as mock class by the paper's heuristic or not

* **Extensions**: Integer (`0` or `1`) representing how many classes the current one extends

* **Implementations**: Integer (`0+`) representing how many interfaces the current classs implements

* **PrivateMethods**: Integer (`0+`) representing how many private methods the class have

* **ProtectedMethods**: Integer (`0+`) representing how many protected methods the class have

* **PackageMethods**: Integer (`0+`) representing how many package methods the class have

* **PublicMethods**: Integer (`0+`) representing how many public methods the class have

* **TotalMethods**: Integer (`0+`) representing how many methods in total the class have regardless of their visibilities

* **IsStaticClass**: Boolean (`True` or `False`) representing whether the class is or not static

* **MethodOverrides**: Integer (`0+`) representing how many of the class' methods are overriding others

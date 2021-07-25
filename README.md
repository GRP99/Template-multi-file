# Template multi-file or multi-directory
## Scripting in Natural Language Processing

For several software projects, solutions involving several files, several folders are common. Example: a file, a makefile, a manual, an example folder, etc. 

### mkfromTemplate
Program "mkfromTemplate" is capable of accepting a project name, and a description file of a template-multi-file and which creates the project's initial files and folders.

The template includes:
* metadata (author, email) to replace in the following elements
* tree (directory structure and smells to be created)
* template of each file

How to run:
```py
$ python mkfromTemplate.py $template_file $project_name
```

### mkfromDirectory
The "mkfromDirectory" program is capable of accepting files and folders from a project and generating a multi-file template for these parameters.

The directory includes:
* file "meta" with metadata
* files and folders

How to run:
```py
$ python mkfromDirectory.py $path_folder
```

### Team
![Gonçalo Pinto][grp-pic] | ![Etienne Costa][etienne-pic] | ![Luís Ribeiro][luis-pic]
:---: | :---: | :---:
[Gonçalo Pinto][grp] | [Etienne Costa][etienne]  | [Luís Ribeiro][luis]

[grp]: https://github.com/GRP99
[grp-pic]: https://github.com/GRP99.png?size=120
[etienne]: https://github.com/EtienneCosta
[etienne-pic]: https://github.com/EtienneCosta.png?size=120
[luis]: https://github.com/luis1ribeiro
[luis-pic]: https://github.com/luis1ribeiro.png?size=120

<div align="center">
  <sub>February 2021 - July 2021</sub>
</div>

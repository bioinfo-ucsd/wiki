# Bioinformatics Wiki

This is a collection of bioinformatics and computational biology best practices developed by Arya Massarat, Michael Cuoco, and other students of the UCSD Bioinformatics and Systems Biology (BISB) PhD Program.

## Viewing the published wiki

This repository is published automatically to [bioinfo-ucsd.github.io/wiki](https://bioinfo-ucsd.github.io/wiki) upon `push` to the `main` branch.

<!-- TODO: add contibuting guidelines -->

## Building the wiki on your computer

The conda environment is provided as `environment.yml`. This environment is used for all testing by Github Actions.

Once you have the environment installed and activated. Run the following command in your terminal:

```bash
jb build wiki/
```

You can then preview the book by opening the file `wiki/_build/html/index.html` in your browser.

If you would like to work with a clean build, you can empty the build folder by running:

```bash
jb clean wiki/
```

If jupyter execution is cached, this command will not delete the cached folder.

To remove the build folder (including `cached` executables), you can run:

```bash
jb clean --all wiki/
```

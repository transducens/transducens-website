
Source files for the website of the Transducens research group at Universitat d'Alacant. The website is [here](https://www.dlsi.ua.es/transducens/).

## Environment setup

Using the `conda` package manager is recommended. The following commands can be used to create a new environment and install the required packages:

```
conda create --name transducens-website --yes python==3.12
conda activate transducens-website
pip install -r requirements.txt
```


In case of needing to update the environment, the following command can be used:

```
conda remove --name transducens-website --all
```

## Local updates

During local development, the website can be locally served with the following command:

```
mkdocs serve
```

## Building the website

When the website is ready to be published, the static files can be generated with the following command:

```
mkdocs build
```

Make sure that the static files in the `site` directory are correct and then push the changes to the repository. The latest changes may now be pulled to the server.

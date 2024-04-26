# Steps for documentation

## Step 1 

1. Inside of  your project create a virtual environment:

``` python -m venv mkdocsvenv```

2. Activate the virtual environment

```'name\Scripts\activate'```


3. Install the packages

```
pip install mkdocs "mkdocstrings[python]"
```
4. Create Mkdocs instance 


```bash
mkdocs new .
```
5. Folder docs should be created and a file called mkdocs.yml

* In the docs folder you will find index.md file which is your homepage for your documentation.
* The mkdocs.yml it is used for structuring your documetion site by adding navications, plugins, site names.

6. Add your code documention:

* To add the documention of your code make sure you documentated your code.
* Then the docs folder create a new file 'name.md' in that you have to do ' ::: name.add ' the name is the name of your folder like API or SQL the add is the oython file that has the code in it.

7. Run your code:
```bash
mkdocs serve
```
8. Build the mkdocs:
```bash
mkdocs build
```


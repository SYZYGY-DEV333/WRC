# WRC

#### Webapp Rendering Container

WRC turns a webapp that would normally run in a web browser into a standalone app. It is written in Python with PyQt4. It comes with a sample calculator app to demonstrate.

## Unix setup instructions

- Download the source code. You can discard the `Calculator.html` file.
- open WRC in a text editor.
- Look for this:
```python
# CONFIG
load = 'Calculator.html'
```
- replace `Calculator.html with the main HTML file of your webapp; retain the quotes.
- make sure WRC is in the same directory as your webapp.
- Rename WRC to the name of the program.
- (optional) Turn into an excecutable with the following shell command: `chmod +x path/to/script`
- Run the script, and your webapp should appear.

## Windows setup instructions

- Download the source code. You can discard the `Calculator.html` file.
- open WRC in a text editor.
- Look for this:
```python
# CONFIG
load = 'Calculator.html'
```
- replace `Calculator.html with the main HTML file of your webapp; retain the quotes.
- make sure WRC is in the same directory as your webapp.
- Rename WRC to the name of the program.
- Compile the script to an EXE with a tool like http://py2exe.org/
- Run the EXE and the webapp should appear

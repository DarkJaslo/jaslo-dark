# jaslo-dark

<img src="https://raw.githubusercontent.com/DarkJaslo/jaslo-dark/master/img/cpp2.PNG" alt="Intro image" title = "Intro" width="99%" height="99%">

A Visual Studio Code theme with my personal preferences. It is intended to be progressively upgraded whenever I find both new stuff to add and time to do so.

#### (Intentionally) supports:
- C, C++
- Java
- Python
- JavaScript and TypeScript
- HTML & CSS
- Haskell
- Prolog
- SQL
 
If you're lucky, some other languages are already supported by the current settings, or at least a part of them. If it helps understand some things, this started as a C/C++ extension.

# Some screenshots

In advance: some of these may be a bit outdated. For the OCD people, yes, they have different sizes and all.

#### C
<img src="https://raw.githubusercontent.com/DarkJaslo/jaslo-dark/master/img/c1.PNG" alt="C example 1" title = "C example 1" width="99%" height="99%">

#### C++
<img src="https://raw.githubusercontent.com/DarkJaslo/jaslo-dark/master/img/cpp1.PNG" alt="C++ example 1" title = "C++ example 1" width="99%" height="99%">

#### Some HTML
<img src="https://raw.githubusercontent.com/DarkJaslo/jaslo-dark/master/img/html1.PNG" alt="HTML example 1" title = "HTML example 1" width="75%" height="99%">

#### Python
<img src="https://raw.githubusercontent.com/DarkJaslo/jaslo-dark/master/img/py1.PNG" alt="Python example 1" title = "Python example 1" width="80%" height="99%">

I'm being specific here, but I'm amazed at how much the colours change between different screens. It almost turns into a completely different theme.

# TODO
- Better colours for the _app_, not just the text.

### Re-releasing/updating
This last part is mainly for me:

1. Open vscode in the repo, hit Run>Start Debugging
2. On the other window, ctrl+shift+P>inspect editor tokens and scopes to see items
3. To update:
```sh
vsce package
vsce publish
```

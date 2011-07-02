# Textmate Bundle for Squirrel

Syntax highlighting and a few snippets for the [Squirrel Language](http://www.squirrel-lang.org)

Contributions are welcome!

## Snippets

* **class** => class definition
* **constr** => constructor definition
* **for** => for (_initialize_; _max_; _evaluate_) { }
* **foreach** => foreach (_element_ in _collection_)
* **funct** => function _name_(_args_) { }
* **if** => if (_statement_) { }
* **l** => local _variable_
* **p** => print(_args_)


## Installation using Git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/robmerrell/squirrel-tmbundle.git "Squirrel.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


## Credits

Much of the contents of this bundle were gathered and modified from the existing
Javascript, Actionscript and Ruby bundles.


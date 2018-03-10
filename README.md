# towns-widget

## Usage

Options:

selector - Type: string , a css selector containing the whole html needed for the widget  

{ selector: "#widget-container" }



To create new instance:  

```
var townsWidget = new TownsWidget(options);   
```

To initialize events on the new instance:  

```
townsWidget.init();  
```

## For development

use $ in the name of the variable to denote that it is a jQuery object  

keep all of mutated variables in the state object  


## TODO:

1) rewrite in stateless style with a single point for update  

2) rewrite with es6 syntax

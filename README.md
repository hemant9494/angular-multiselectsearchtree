angular-multi-select-tree
=============================

A native Angular multi select tree. No JQuery.
If you use this module you can give it a thumbs up at [http://ngmodules.org/modules/angular-multi-select-tree](http://ngmodules.org/modules/angular-multi-select-tree).

#### Demo Page:

[Demo] (http://htmlpreview.github.io/?)

#### Features:


#### Implementation Details:


#### Design details: Custom element using Angular Directive and Templating

#### Callbacks: This is your onchange :)

##### Usage:

Get this i.

```sh
bower install kjvelarde-angular-multiselectsearchtree --save
```
bower install long name ehhfsaduasdu lol . just kidding use the first one :)
```
Make sure to load the scripts in your html.
```html
<link rel="stylesheet" href="../dist/kjvelarde-multiselect-searchtree-0.8.0.min.css">
<script type="text/javascript" src="../dist/angular-multi-select-tree-0.1.0.js"></script>
<script type="text/javascript" src="../dist/angular-multi-select-tree-0.1.0.tpl.js"></script>

```

And Inject the module as dependency to your angular app.

```
angular.module('[YOURAPPNAMEHERE!]', ['multiselect-searchtree', '....']);
```

###### Html Structure:
                    <multiselect-searchtree data-input-model="data" multi-select="true"
                                            data-output-model="selectedItem2" data-callback="CustomCallback(item, selectedItems)"
                                            data-select-only-leafs="true"></multiselect-searchtree>											

That's what all you have to do.

##### License

MIT, see [LICENSE.md](./LICENSE.md).


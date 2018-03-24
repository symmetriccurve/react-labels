# React-Labels
A simple component to manage(enable/disable or add/delete or apply/remove) permissions/labels/tags

[![N|Solid](https://raw.githubusercontent.com/symmetriccurve/react-labels/master/Label%20Demo.gif)](https://nodesource.com/products/nsolid)


[![N|Solid](https://raw.githubusercontent.com/symmetriccurve/react-labels/master/long%20label%20demo.gif)](https://nodesource.com/products/nsolid)

# Installation

```
$ npm install react-labels
```
# Usage

```
import ReactLabels from 'react-labels'
<ReactLabels allLabels ={['one','two','three']} activeLabels={['one']}/>
```

Props:
  - allLabels - Array of all labels
  - activeLabels - Lables that needs to be active when component loads


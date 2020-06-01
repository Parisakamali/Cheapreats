# Cheapreats
Learning to make folder

var tree_util = require('tree-util')

var items = [{ id : 1 }, { id : 2, parentid : 1 }, { id : 3, parentid : 1 },
             { id : 4, parentid : 1 }, { id : 5, parentid : 3 }];
             
var standardConfig =  { id : 'id', parentid : 'parentid'};

var trees = tree_util.buildTrees(items, standardConfig);

[github](./github)

[src](./src)

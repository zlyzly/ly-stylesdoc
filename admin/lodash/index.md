# Lodsh
## Array
1. _chunk(array, [size=1])
- - - - 
    将一个数组分成多个size长度的块，并返回一个新的数组，如果这个数组不能被平均分，剩余的将作为一个长块。
    参数：1，(array)被处理数组；2，(number),每个快的长度。
    _.chunk(['a', 'b', 'c', 'd'], 2);
    // => [['a', 'b'], ['c', 'd']]

    _.chunk(['a', 'b', 'c', 'd'], 3);
    // => [['a', 'b', 'c'], ['d']]
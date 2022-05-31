## GTExplainer -  a 'Greater Than' SudokuExplainer (SE)

#### Creating 'Greater Than' (GT) sudoku definition

- This GT sudoku was posted [here](http://forum.enjoysudoku.com/greater-than-sudoku-t40038.html).

![GT](https://github.com/1to9only/Downloads/raw/master/greater-than-sudoku.jpg)

- Convert this to text format, using `< > v ^`
```
+---+---+---++---+---+---++---+---+---+
|   <   >   ||   <   >   ||   >   <   |
+-v-+-v-+-^-++-^-+-v-+-^-++-v-+-v-+-^-+
|   <   <   ||   >   >   ||   >   <   |
+-v-+-v-+-v-++-^-+-^-+-v-++-^-+-^-+-v-+
|   >   <   ||   <   >   ||   >   <   |
+---+---+---++---+---+---++---+---+---+
+---+---+---++---+---+---++---+---+---+
|   >   >   ||   >   <   ||   >   <   |
+-v-+-^-+-^-++-v-+-^-+-v-++-v-+-^-+-^-+
|   <   >   ||   <   <   ||   <   <   |
+-^-+-^-+-v-++-^-+-^-+-v-++-^-+-v-+-v-+
|   <   >   ||   <   >   ||   >   >   |
+---+---+---++---+---+---++---+---+---+
+---+---+---++---+---+---++---+---+---+
|   >   <   ||   >   >   ||   >   >   |
+-v-+-v-+-v-++-^-+-^-+-^-++-v-+-v-+-^-+
|   >   >   ||   <   <   ||   <   >   |
+-v-+-^-+-^-++-^-+-v-+-v-++-v-+-^-+-^-+
|   >   <   ||   >   <   ||   <   >   |
+---+---+---++---+---+---++---+---+---+
```

- Extract the `< > v ^` characters
```

<><>><
vv^^v^vv^
<<>>><
vvv^^v^^v
><<>><


>>><><
v^^v^vv^^
<><<<<
^^v^^v^vv
<><>>>


><>>>>
vvv^^^vv^
>><<<>
v^^^vvv^^
><><<>

```

- Merge to obtain 1 line of 108 characters for the GT sudoku definition
```
<><>><vv^^v^vv^<<>>><vvv^^v^^v><<>><>>><><v^^v^vv^^<><<<<^^v^^v^vv<><>>>><>>>>vvv^^^vv^>><<<>v^^^vvv^^><><<>
```



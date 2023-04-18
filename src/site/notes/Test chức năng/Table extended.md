---
{"dg-publish":true,"permalink":"/test-chuc-nang/table-extended/","tags":["gardenEntry"]}
---

Markdown syntax 6 
| Cell1       | Cell2 | Cell3  |
| ----------- | ----- | ------ |
| merge right |       |        |
| merge       |       |        |
| below       | ^     | ^      |
| merge both  |       | value1 |
| ^           |       | value2 |

Noted that GitHub filters out `style` property, so the example uses `align` the obsolete one. However it outputs `style="text-align: ..."` in actual.


-tx-
|             |          Grouping           || 
First Header  | Second Header | Third Header | 
 ------------ | :-----------: | -----------: | 
Content       |          *Long Cell*        || 
Content       |   **Cell**    |         Cell | 
New section   |     More      |         Data | 
And more      | With an escaped '\|'       || 
[Prototype table]


### Rowspan
`^^` indicates cells being merged above.  
Feature contributed by [pmccloghrylaing](https://github.com/pmccloghrylaing).

Stage | Direct Products | ATP Yields
----: | --------------: | ---------:
Glycolysis | 2 ATP ||
^^ | 2 NADH | 3--5 ATP |
Pyruvaye oxidation | 2 NADH | 5 ATP |
Citric acid cycle | 2 ATP ||
^^ | 6 NADH | 15 ATP |
^^ | 2 FADH2 | 3 ATP |
**30--32** ATP |||
[Net ATP yields per hexose]

|--|--|--|--|--|--|--|--|
|♜|  |♝|♛|♚|♝|♞|♜|
|  |♟|♟|♟|  |♟|♟|♟|
|♟|  |♞|  |  |  |  |  |
|  |♗|  |  |♟|  |  |  |
|  |  |  |  |♙|  |  |  |
|  |  |  |  |  |♘|  |  |
|♙|♙|♙|♙|  |♙|♙|♙|
|♖|♘|♗|♕|♔|  |  |♖|


### Multiline

Backslash at end merges with line content below.  
Feature contributed by [Lucas-C](https://github.com/Lucas-C).


|   Markdown   | Rendered HTML |
|--------------|---------------|
|    *Italic*  | *Italic*      | \
|              |               |
|    - Item 1  | - Item 1      | \
|    - Item 2  | - Item 2      |
|    ```python | ```python       \
|    .1 + .2   | .1 + .2         \
|    ```       | ```           |

{{Hello}} 



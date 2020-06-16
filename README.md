# Eimeria_sample_inventory
An inventory of samples for Eimeria projects at the Heitlinger group


The current freezer inventory is number coded in /Eimeria_sample_inventory/Freezers_inventory_022020.csv
Coordinates of 3 numbers (x.x.x) representing 1) freezer, 2) tower within that freezer and 3) a row within that tower.
Tower order is from left to right in a freezer. Therefore when counting a row, skip to beginning of next row at the end,
continuing the numeric count. A "Z" pattern if you will.


1 = Blue -80,
2 = White -80,
NA = Not ours,
Empty = free space.

example: 1.6.8 = Blue -80 freezer, 6th tower, 8th row.

Room 108 -20 freezers: 
3 = first freezer on left,
4 = second freezer on left,

5 = fridge?

For proper organisation projection: 
Rows = samples,
minimum necessary columns = Institute, Freezer, box (sample range or fraction eg. 1/3), project (eg. E7, P3, HZ16, etc.), tissue (or material eg. FEC, CEWE, CEWE cDNA, etc.), sample consumed (probably logical T/F, if sample has been used up). 
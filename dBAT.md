# Wii U DBATs
## 5.5.1, HBL, hello_world elf base.

First few digits of u = Effective address (what you use)
First few digits of l = Physical address

|dBAT|u|i|Notes|
|---|---|---|---|
|0|F40003FF|00000012|MEM1|
|1|E00007FF|14000012|Bucket memory|
|2|FE0000FE|1C000012||
|3|10001FFF|50000012|MEM2|
|4|FA0001FF|1A000013||
|5|008000FF|30800012|HBL code mapping|
|6|00000000|00000000|Empty|
|7|00000000|00000000|Empty|
- ZZ: save and terminate editor(like :wq).
- :w \[FILE NAME\]: save the file using a different name.
- /\[STRING\]: find STRING downwards.
- ?\[STRING\]: find STRING upwards.
- :s/string1/string2/g: replace string1 with string2 in the row at which the cursor is placed.
- :%s/string1/string2/g: replace string1 with string2 in the file.
- :(start row),(end row)s/string1/string2/g: replace string1 with string2 in the range.
- :(start row),(end row)s/string1/string2/gc: let user check if string1 is replaced or not.
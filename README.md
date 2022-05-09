# ASS-1-9-5-22
:write a program to retrieve email id with the name using dictionary.
d = dict([('10:04:14', 1), ('3', 6), ('Thu', 6), ('19:51:21', 1), ('2008',27),  ('From', 27), ('11:35:08', 1), ('5', 1), ('sanju@gmail.com', 3)])

for key in d:
    if "@" in key:
        print(key)
        OUTPUT:
        sanju@gmail.com
      

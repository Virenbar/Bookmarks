# Regex patterns

## Кадастровый номер

[Regex101](https://regex101.com/r/Kb2L0r/2)  

```regexp
\d{2}:\d{2}:\d{6,7}:\d*
```

```text
Valid:
66:77:0066600:0000
66:11:0109003:627
66:44:0101011:725
66:16:2601022:75
Invalid:
  :  :       :
  :  :   
```

## ИНН

```regexp
^(\d{10}|\d{12})$
```

```text
Valid:
1234567890
123456789012
Invalid:
123456789
12345678901234
```

## СНИЛС

```regexp
^\d{3}-\d{3}-\d{3} \d{2}$
```

```text
Valid:
000-000-000 00
```

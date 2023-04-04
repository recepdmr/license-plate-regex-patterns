# License plate regex patterns by country

That repo contains license plate regex patterns for each country.

### TR - Turkiye

```regex
^(0[1-9]|[1-7][0-9]|8[01])((\s?[a-zA-Z]\s?)(\d{4,5})|(\s?[a-zA-Z]{2}\s?)(\d{3,5})|(\s?[a-zA-Z]{3}\s?)(\d{2,3}))$
```

### DE - Germany

```regex
^[A-ZÄÖÜ]{1,3}[ ]{0,1}[A-Z]{0,2}[0-9]{1,4}[H]{0,1}
```

### SY - Syria

```regex
^[A-Z]{1,3}[ ]{0,1}[A-Z]{0,2}[0-9]{1,4}[H]{0,1}
```

### KW - Kuwait

```regex
^[0-9]{1,3}[ ]{0,1}[A-Z]{0,2}[0-9]{1,4}[H]{0,1}
```

### RS - Serbia

```regex
^[0-9]{1,3}[ ]{0,1}[A-Z]{0,2}[0-9]{1,4}[H]{0,1}
```

### Macedonia

```regex
[A-Z]{2}[0-9]{5}[A-Z]{2}
```

# [Advent of Code 2023](https://adventofcode.com/)
 
Testaillaan miten ~~monimutkaisesti~~ elegantisti voi asioita koodailla... sillon kun jaksaa ja ehtii ja osaa.


## Mitä opin?

Välilyönneillä erotettuja taulukoita on helppo lukea pandasilla:
``` python
pandas.read_csv(
    'input.txt', 
    delim_whitespace=True, 
    header=None, # Otsikot pois
    index_col=[0,] # Rivien nimet pois
)
```

Kirjaimia on kätevä vaihtaa translaten avulla:
```python
"Hello team!".translate(str.maketrans('Hetm!', f'Kavsi'))
# > "Kallo vaasi"
```


# Russian names wordlist

## RU

> [!WARNING]
> В вордлистах, содержащих более 1000 строк, могут встречаться погрешности!

### Категории вордлистов

- `a_top` — Топ по мужским и женским фамилиям + именам по всему датасету.
- `f_lastnames_top` — Топ по женским фамилиям.
- `f_names_top` — Топ по женским именам.
- `f_top` — Топ по женским фамилиям + именам по всему датасету.
- `m_lastnames_top` — Топ по мужским фамилиям.
- `m_names_top` — Топ по мужским именам.
- `m_top` — Топ по мужским фамилиям + именам по всему датасету.

### Исходные данные

В качестве исходных данных использовались 100 млн ФИО (объединенные из различных публичных источников). Эти ФИО были разделены по полу с помощью библиотеки [pytrovich](https://github.com/petrovich/pytrovich). Затем были созданы топы по именам и фамилиям, которые впоследствии переведены с кириллицы на латиницу с использованием библиотеки [iuliia](https://iuliia.ru/).

## EN

> [!WARNING]
> Wordlists containing more than 1000 lines may have inaccuracies!

### Wordlist categories

- `a_top` — Top male and female last names + first names across the entire dataset.
- `f_lastnames_top` — Top female last names.
- `f_names_top` — Top female first names.
- `f_top` — Top female last names + first names across the entire dataset.
- `m_lastnames_top` — Top male last names.
- `m_names_top` — Top male first names.
- `m_top` — Top male last names + first names across the entire dataset.

### Source data
The source data consisted of 100 million full names (collected from various public sources). These names were split by gender using the [pytrovich](https://github.com/petrovich/pytrovich) library. Then, top lists were created for first and last names and transliterated from Cyrillic to Latin using the [iuliia](https://iuliia.ru/) library.

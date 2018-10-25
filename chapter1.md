---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Inspecting Data

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

This is an example exercise.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}
import pandas as pd

pd.options.display.max_columns = 10

import matplotlib.pyplot as plt
```

`@sample_code`
```{python}
data = pd.read_csv('http://assets.datacamp.com/production/repositories/3871/datasets/032c54f464befcb66f0243ca2e00c24f8cd58221/online-retail_sample.csv',
                   parse_dates = ['order_date'])				
```

`@solution`
```{python}
data.head()

data.describe()
```

`@sct`
```{python}

```

---

## Inspecting Labels

```yaml
type: NormalExercise
key: 3a62aa3b37
xp: 100
```



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Make Features

```yaml
type: TabExercise
key: 0423fb96d3
xp: 100
```



`@pre_exercise_code`
```{python}
import pandas as pd
pd.options.display.max_columns = 10
```

***

```yaml
type: NormalExercise
key: 62c634b56a
xp: 50
```

`@instructions`


`@hint`


`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

***

```yaml
type: NormalExercise
key: b6a490e9da
xp: 50
```

`@instructions`


`@hint`


`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```

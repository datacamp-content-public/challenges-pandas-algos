---
title: 'Single Column'
output: html_document
description: 'Getting just 1 record based on single column'
---

## [OC] Getting 1 random order by each customer_id

```yaml
type: OutputChallenge
key: d0b64cb12d
```

`@context`


`@code1`
```{python}
df.sample(frac=1).drop_duplicates('customer_id')
```

`@pre_challenge_code`
```{python}
import pandas as pd

df = pd.DataFrame({
  'customer_id': ['C919','C919','C919','C919','C858','C858','C858','C505','C505'],
  'order_number': ['O05656','O15604','O34420','O47968','O83754','O92682','O01353','O35931','O26640'],
  'order_month': ['43831','43831','43862','43891','43831','43862','43862','43862','43862'],
  'order_status': ['CONCLUDED','CANCELLED','CONCLUDED','CONCLUDED','CONCLUDED','CANCELLED','CONCLUDED','CANCELLED','CANCELLED']
})
```

`@variables`
```yaml

```

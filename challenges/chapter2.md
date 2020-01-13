---
title: 'Single Column'
description: 'Getting just 1 record based on single column'
---

## Insert challenge title here

```yaml
type: BlanksChallenge
key: fa5aa97065
```

`@context`
context

`@code1`
```{python}
print(var1)
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
var1:
	- 'c'
```

`@distractors`
```yaml
var1:
	- 'a'
	- 'b'
    - 'c'
```

![Search french cities](https://repository-images.githubusercontent.com/279354946/9952fe80-c5bf-11ea-8796-12a17f6c879e)

# [DATAGOUV] Search French cities

Just a little helper to request the [address api](https://geo.api.gouv.fr/adresse) of the French government open data.

You can retrieve the data for a particular city or the corresponding matching for a partial research like on autocomplete field.

---

## Installation 

You'll need: 
* requests
* urllib3

```bash

  pip3 install -r requirements.txt
```

---

## Example 

```python

  from getCities import GetCities
  cities = GetCities('bordeaux')
  print('cities')
```

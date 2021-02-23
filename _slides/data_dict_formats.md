---

order: 200

---

## Other File Formats

<!--<div class="two-col left">-->
```
temperature: 
    description: The surface temperature on mars
    units: degrees kelvin
    type: integer
    instrument: thermomatic 5000
soil_type:
    description: The soil classification based on the scheme proposed by Bradbury 
    categories: 
        - dust
        - cobble
        - pebble
        - rocky
    type: string

```

```
{
   "temperature": {
      "description": "The surface temperature on mars",
      "units": "degrees kelvin",
      "type": "integer",
      "instrument": "thermomatic 5000"
   },
   "soil_type": {
      "description": "The soil classification based on the scheme proposed by Bradbury",
      "categories": [
         "dust",
         "cobble",
         "pebble",
         "rocky"
      ],
      "type": "string"
   }
}

```








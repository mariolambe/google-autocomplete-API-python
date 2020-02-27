# Google Autocomplete API to extract keywords

Import Libraries

```bash
import requests
import string
import xml.etree.ElementTree as ET
```

Add Keywords 

```bash
list_a = ["hotel berlin", "hotel new york"]
```

Get the Output as a list of keywords
```bash
hotel berlin mitte
hotel berlin berlin
hotel berlin mitte by campanile
hotel berlin alexanderplatz
hotel berlin günstig
hotel berlin spandau
hotel berlin charlottenburg
hotel berlin wedding
hotel berlin hauptbahnhof
hotel berlin friedrichstraße
hotel berlin alexanderplatz
hotel berlin adlershof
hotel new york palace budapest
hotel new york new york
hotel new york brooklyn
hotel new york budapest
hotel new york times square
hotel new york angebote
hotel new york aussicht
hotel new york am central park
.......

## Exercices

1. XML vs JSON

transformer la structure XML en JSON

```XML
<employees>
  <employee>
	  <firstName>John</firstName>
	  <lastName>Doe</lastName>
  </employee>
  <employee>
	  <firstName>Anna</firstName>
	  <lastName>Smith</lastName>
  </employee>
  <employee>
	  <firstName>Peter</firstName>
	  <lastName>Jones</lastName>
  </employee>
</employees>
```

2. JSONPATH

En JSONPATH, l'équivalent de XPATH, récupérer le numéro de téléphone fixe (home)

```JSON
{
"firstName": "John",
"lastName" : "doe",
"age"      : 26,
"address"  : {
  "streetAddress": "naist street",
  "city"         : "Nara",
  "postalCode"   : "630-0192"
},
"phoneNumbers": [
  {
    "type"  : "iPhone",
    "number": "0123-4567-8888"
  },
  {
    "type"  : "home",
    "number": "0123-4567-8910"
  }
]
}
```
3.  XPATH

Pareil avec le XML

```XML
<persons>
	<person>
		<firstName>John</firstName>
		<lastName>doe</lastName>
		<age>26</age>
		<address>
			<streetAddress>naist street</streetAddress>
			<city>Nara</city>
			<postalCode>630-0192</postalCode>
		</address>
		<phoneNumbers>
			<type>iPhone</type>
			<number>0123-4567-8888</number>
		</phoneNumbers>
		<phoneNumbers>
			<type>home</type>
			<number>0123-4567-8910</number>
		</phoneNumbers>
	</person>
</persons>
 ```

4. Convertir le JSON en objet JavaScript

Convertissez le JSON, ...
```JSON
{"mycars" :[
	{"name":"Audi"},
	{"name":"BMW"},
	{"name":"Mercedes"},
	{"name":"Volvo"}
]}
```
 en objet Javascript pour qu'il s'affiche de la manière suivante :
```
Audi
BMW
Mercedes
Volvo
 ```

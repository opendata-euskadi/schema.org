### Iñigo Urkullu (Guía comunicación)

* URL actual: http://gida.irekia.euskadi.eus/es/people/8080
* Archivo: `inigourkullu.json`
* URI recurso (a decidir): 

`"@id":"http://gida.irekia.euskadi.eus/resource/staff/inigo-urkullu-renteria-16068955",`

* URL página (a decidir: como la URI recurso pero `page` en vez de `resource`):

```
  "mainEntityOfPage": {
         "@type": "WebPage",
         "@id": "http://gida.irekia.euskadi.eus/page/staff/inigo-urkullu-renteria-16068955"
      },
```

* URI irekia (a decidir/modificar):

` "sameAs":"http://www.irekia.euskadi.eus/es/politicians/4092",`

* URI Presidencia del Gobierno (a decidir/modificar):

```
  "worksFor":[
    {
      "@type": "GovernmentOrganization", 
      "@id": "http://www.euskadi.eus/gobierno-vasco/lehendakaritza/inicio/",
      "name":"Presidencia del gobierno",
      "description":"Presidente",
```

* URI Comisión Interdepartamental para la Igualdad de Mujeres y Hombres (a decidir/modificar):

```
    {
      "@type": "GovernmentOrganization", 
      "@id":"http://www.emakunde.euskadi.net/u72-20010/es/contenidos/informacion/org_adscritos/es_def/index.shtml#A02",
      "name": "Comisión Interdepartamental para la Igualdad de Mujeres y Hombres",
      "description":"Presidente",
```

* URI Euzko Abertzaleak-Nacionalistas Vascos (EA-NV) (a decidir/modificar):

```
{
      "@type": "GovernmentOrganization", 
      "@id":"http://gida.irekia.euskadi.eus/es/entities/452",
      "name": "Euzko Abertzaleak-Nacionalistas Vascos (EA-NV)",
      "description":"Parlamentario",
```

Las URIs lehendakaritza, igualdad de mujeres y EA-NV deberían seguir el patrón URI/303/URL (ahora la URL y la URI, en el JSON, es la misma).


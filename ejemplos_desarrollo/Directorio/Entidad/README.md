### Estructura y funciones del Departamento de Desarrollo Económico y Competitividad

* URL actual: http://opendata.euskadi.eus/estructura-y-funciones-del-departamento-de-desarrollo-economico-y-competitividad/w79-contdata/es/
* Archivo: `departamentoDesarrollo.json`
* URI recurso (a decidir): 

`"@id":"http://opendata.euskadi.eus/resource/estructura-y-funciones-del-departamento-de-desarrollo-economico-y-competitividad",`

* URL página (a decidir: como la URI recurso pero `page` en vez de `resource`):

```
  "mainEntityOfPage": {
         "@type": "WebPage",
         "@id": "http://opendata.euskadi.eus/estructura-y-funciones-del-departamento-de-desarrollo-economico-y-competitividad/w79-contdata/es/"
      },
```

* URI director (a decidir, es necesario?):

```
  "employee":{
    "@id": "http://gida.irekia.euskadi.eus/resource/staff/MariaAranzazu79054086V",
    "@type":"Person", 
    "givenName": "Maria Aranzazu",
    "familyName":"Tapia Otaegui",
    "gender": "http://schema.org/Female",
    "jobTitle":"Director"
  },
```

* URI suborganizacion (URI Direccion y director a decidir):

```
  "subOrganization":[ 
  {
    "@type":"GovernmentOrganization",
    "name":"Dirección de Servicios", 
    "@id": "http://gida.irekia.euskadi.eus/resource/entity/direccionDeServicios",
    "employee":{
      "@type":"Person", 
      "@id": "http://gida.irekia.euskadi.eus/resource/staff/MariaAmezqueta79054086V",
      "givenName": "María Teresa",
      "familyName":"Amezqueta Alegría",
      "gender": "http://schema.org/Female",
      "jobTitle":"Director"
    }
  }, 
```



### Presidencia del Gobierno (Guía de la comunicación)

* URL actual: http://gida.irekia.euskadi.eus/es/entities/1
* Archivo: `presidenciaDelGobierno.json`
* URI recurso (a decidir): 

`"@id":"http://gida.irekia.euskadi.eus/resource/PreisdenciaDelgobierno",`

* URL página (a decidir: como la URI recurso pero `page` en vez de `resource`):

```
  "mainEntityOfPage": {
         "@type": "WebPage",
         "@id": "http://gida.irekia.euskadi.eus/page/PreisdenciaDelgobierno"
      },
```

También hay que ponber URIs en `"parentOrganization"` y `"subOrganization"`

### Ataun

Ataun es una entidad?

### Evento inteligencia emocional

Un evento es una entidad?

### Noticia Azkuna zentroa

Una noticia es una entidad?
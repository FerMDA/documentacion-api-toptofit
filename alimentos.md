# API ToptoFit - Alimentos

Para emepezar con el api de busqueda de alimentos, necesitaras tener una clave de acceso privada para utilizarla.

[Crear credencial del api!](http://toptofit.tech/home/)

Configuración de cabeceras de autenticación en el API:

```
Content-Type: application/json,
Authorization: 'Token '+yourAPIKEY
```

Ruta de peticción:
https://toptofit.tech/api/v1.0/alimentos/?limit=15&offset=15

Cuerpo de la petición o datos a enviar, en formato json:

```
{
"uid_user": "pqVXrGGDxTMnouf3vwmTK8QW0ae2",
"id_app": 1,
"private_key_app": "yourAppKey",
}
```


Respuesta en formato json

```
{
            "id": 155,
            "region": "MX",
            "calorias": "899",
            "carbohidratos": "12",
            "colesterol": "0",
            "grasas": "16",
            "minerales": "0",
            "name": "aceite de coco",
            "proteinas": "17",
            "porcion": "100g",
            "vitaminas": "0",
            "date_published": "2019-11-09T23:33:59.717261-06:00",
            "date_updated": "2019-11-09T23:33:59.717296-06:00"
        },
        {
            "id": 56,
            "region": "MX",
            "calorias": "899kcal",
            "carbohidratos": "0g",
            "colesterol": "0mg",
            "grasas": "100g",
            "minerales": "0mg",
            "name": "aceite de girasol",
            "proteinas": "0g",
            "porcion": "100g",
            "vitaminas": "vitamina a 4,40ug vitamina e 62,15mg vitamina k 9,40ug",
            "date_published": "2019-11-09T23:33:59.525473-06:00",
            "date_updated": "2019-11-09T23:33:59.525510-06:00"
        },
        {
            "id": 157,
            "region": "MX",
            "calorias": "899kcal",
            "carbohidratos": "0g",
            "colesterol": "0mg",
            "grasas": "100g",
            "minerales": "0mg",
            "name": "aceite de maiz",
            "proteinas": "0g",
            "porcion": "100g",
            "vitaminas": "vitamina e 34mg vitamina k 31ug",
            "date_published": "2019-11-09T23:33:59.721099-06:00",
            "date_updated": "2019-11-09T23:33:59.721136-06:00"
        },
        {
            "id": 35,
            "region": "MX",
            "calorias": "899kcal",
            "carbohidratos": "0g",
            "colesterol": "0mg",
            "grasas": "100g",
            "minerales": "0mg",
            "name": "aceite de oliva",
            "proteinas": "0g",
            "porcion": "100g",
            "vitaminas": "vitamina e 5,10mg vitamina k 49,60ug",
            "date_published": "2019-11-09T23:33:59.483797-06:00",
            "date_updated": "2019-11-09T23:33:59.483834-06:00"
        },
        {
            "id": 217,
            "region": "MX",
            "calorias": "899kcal",
            "carbohidratos": "0g",
            "colesterol": "0mg",
            "grasas": "99,90g",
            "minerales": "0",
            "name": "aceite de palma",
            "proteinas": "0g",
            "porcion": "100g",
            "vitaminas": "vitamina a 9,30ug vitamina k 8ug",
            "date_published": "2019-11-09T23:33:59.835472-06:00",
            "date_updated": "2019-11-09T23:33:59.835511-06:00"
        },
        {
            "id": 1,
            "region": "MX",
            "calorias": "899kcal",
            "carbohidratos": "0g",
            "colesterol": "0mg",
            "grasas": "100g",
            "minerales": "0mg",
            "name": "aceite de soja",
            "proteinas": "0g",
            "porcion": "100g",
            "vitaminas": "vitamina e 16,75mg vitamina k 138ug",
            "date_published": "2019-11-09T23:33:59.414199-06:00",
            "date_updated": "2019-11-09T23:33:59.414282-06:00"
        },
        {
            "id": 168,
            "region": "MX",
            "calorias": "4",
            "carbohidratos": "0,22g",
            "colesterol": "0",
            "grasas": "0,45g",
            "minerales": "0",
            "name": "aceituna",
            "proteinas": "0,04g",
            "porcion": "1 mediana ",
            "vitaminas": "0",
            "date_published": "2019-11-09T23:33:59.742396-06:00",
            "date_updated": "2019-11-09T23:33:59.742429-06:00"
        },
        {
            "id": 103,
            "region": "MX",
            "calorias": "105g",
            "carbohidratos": "0",
            "colesterol": "0",
            "grasas": "0",
            "minerales": "0",
            "name": "aceituna negra",
            "proteinas": "0",
            "porcion": "100 gramos ",
            "vitaminas": "0",
            "date_published": "2019-11-09T23:33:59.617894-06:00",
            "date_updated": "2019-11-09T23:33:59.617929-06:00"
        },
        {
            "id": 83,
            "region": "MX",
            "calorias": "299kcal",
            "carbohidratos": "4g",
            "colesterol": "0mg",
            "grasas": "29,80g",
            "minerales": "hierro 1,50mg calcio 61mg potasio 432mg zinc 0,50mg magnesio 22mg sodio 54mg",
            "name": "aceituna negra con hueso",
            "proteinas": "2g",
            "porcion": "100g",
            "vitaminas": "vitamina a 55ug vitamina b 10,10mg vitamina b2 0,10mg vitamina b3 1mg vitamina b5 0,02gm vitamina b6 0,02mg vitamina b9 11ug vitamina c 20mg vitamina e 1,99mg vitamina k 1,40ug",
            "date_published": "2019-11-09T23:33:59.578286-06:00",
            "date_updated": "2019-11-09T23:33:59.578325-06:00"
        },
        {
            "id": 130,
            "region": "MX",
            "calorias": "299kcal",
            "carbohidratos": "4g",
            "colesterol": "0mg",
            "grasas": "29,80g",
            "minerales": "hierro 1,50mg calcio 61mg potasio 432mg zinc 0,50mg magnesio 22mg sodio 54mg",
            "name": "aceituna negra sin hueso",
            "proteinas": "2g",
            "porcion": "100g",
            "vitaminas": "vitamina A 55ug vitamina B 10,10mg vitamina B2 0,10mg vitamina B 31mg vitamina B 50,02g vitamina B 60,02mg vitamina B 911ug vitamina C 20mg vitamina E 1,99mg vitamina K 1,40ug",
            "date_published": "2019-11-09T23:33:59.669275-06:00",
            "date_updated": "2019-11-09T23:33:59.669317-06:00"
        },
        {
            "id": 209,
            "region": "MX",
            "calorias": "167kcal",
            "carbohidratos": "1g",
            "colesterol": "0mg",
            "grasas": "16,70g",
            "minerales": "hierro 1,77mg calcio 64mg potasio 432mg zinc 0,51mg magnesio 22mg sodio 54mg",
            "name": "aceituna verde con hueso",
            "proteinas": "0,80g",
            "porcion": "100g",
            "vitaminas": "vitamina a 48ug vitamina b 10,03mg vitamina b 20,05mg vitamina b 30,77mg vitamina b 50,56ug vitamina b 60,03mg vitamina b 910,40ug vitamina c 0,07mg vitamina e 1,48mg vitamina k 1,40ug",
            "date_published": "2019-11-09T23:33:59.819947-06:00",
            "date_updated": "2019-11-09T23:33:59.819987-06:00"
        },
        {
            "id": 191,
            "region": "MX",
            "calorias": "167kcal",
            "carbohidratos": "1g",
            "colesterol": "0mg",
            "grasas": "16,70g",
            "minerales": "hierro 1,80mg calcio 64mg potasio 432mg zinc 0,51mg magnesio 22mg sodio 54mg",
            "name": "aceituna verde sin hueso",
            "proteinas": "0,80g",
            "porcion": "100g",
            "vitaminas": "vitamina a 48ug vitamina b 10,03mg vitamina b 20,05mg vitamina b 30,77mg vitamina b 50,56ug vitamina b 60,03mg vitamina b 910,40ug vitamina c 0,07mg vitamina e 1,48mg vitamina k 1,40ug",
            "date_published": "2019-11-09T23:33:59.786049-06:00",
            "date_updated": "2019-11-09T23:33:59.786087-06:00"
        },
        {
            "id": 78,
            "region": "MX",
            "calorias": "19,70kcal",
            "carbohidratos": "2,44g",
            "colesterol": "0mg",
            "grasas": "0,60g",
            "minerales": "hierro 0,40mg calcio 21mg potasio 170mg zinc 0,20mg magnesio 6mg sodio 4,30mg",
            "name": "achicoria",
            "proteinas": "0,50g",
            "porcion": "100g",
            "vitaminas": "vitamina a 20ug vitamina b 10,06mg vitamina b 20,03mg vitamina b 30,30mg vitamina b 50,42ug vitamina b 60,01mg vitamina b 74,80ug vitamina b 914ug vitamina c 5mg vitamina e 0,10mg vitamina k 10ug",
            "date_published": "2019-11-09T23:33:59.568679-06:00",
            "date_updated": "2019-11-09T23:33:59.568716-06:00"
        },
        {
            "id": 7,
            "region": "MX",
            "calorias": "233 Kcal",
            "carbohidratos": "0.4 g",
            "colesterol": "0 mg",
            "grasas": "23.5 g",
            "minerales": "Calcio: 12 mg, Potasio: 487 mg, Yodo: 1 mg, magnesio: 30 mg, Sodio: 4.7 mg",
            "name": "aguacate",
            "proteinas": "1.88 g",
            "porcion": "100 g",
            "vitaminas": "A: 12 ug, B3: 1.43 mg, B7: 10 ug, B9: 30 ug, C: 6 mg",
            "date_published": "2019-11-09T23:33:59.429603-06:00",
            "date_updated": "2019-11-09T23:33:59.429642-06:00"
        },
        {
            "id": 153,
            "region": "MX",
            "calorias": "222kcal",
            "carbohidratos": "0,00g",
            "colesterol": "0mg",
            "grasas": "0g",
            "minerales": "calcio1mg",
            "name": "aguardiente",
            "proteinas": "0,00g",
            "porcion": "100g",
            "vitaminas": "vitamina K 1ug",
            "date_published": "2019-11-09T23:33:59.713023-06:00",
            "date_updated": "2019-11-09T23:33:59.713071-06:00"
        }
    ]
}
```


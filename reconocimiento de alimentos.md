# API ToptoFit - Reconocimiento de Alimentos

Para emepezar con el api de reconocimiento de alimentos, necesitaras tener una clave de acceso privada para utilizarla.

[Crear credencial del api!](http://toptofit.tech/home/)

Configuración de cabeceras de autenticación en el API:

```
Content-Type: application/json,
Authorization: 'Token '+yourAPIKEY
```

Ruta de peticción:
https://toptofit.tech/api/v1.0/predict/

Cuerpo de la petición o datos a enviar, en formato json:

```
{
"uid_user": "pqVXrGGDxTMnouf3vwmTK8QW0ae2",
"id_app": 1,
"private_key_app": "yourAppKey",
"base64": "imageInBase64"

}
```


Respuesta en formato json

```
{
    "foods": [
        {
            "id": "ai_r59dFMqd",
            "name": "juice",
            "value": 0.955967128276825,
            "app_id": "main"
        },
        {
            "id": "ai_2TfRbKFW",
            "name": "apple",
            "value": 0.9315730929374695,
            "app_id": "main"
        },
        {
            "id": "ai_0wh0dJkQ",
            "name": "sweet",
            "value": 0.9084060788154602,
            "app_id": "main"
        },
        {
            "id": "ai_CB8hsS3T",
            "name": "tomato",
            "value": 0.6831430196762085,
            "app_id": "main"
        },
        {
            "id": "ai_P2qDCXHV",
            "name": "lemon",
            "value": 0.5644959211349487,
            "app_id": "main"
        },
        {
            "id": "ai_VV9c9tCP",
            "name": "mango",
            "value": 0.5523394346237183,
            "app_id": "main"
        },
        {
            "id": "ai_4pzSWRHh",
            "name": "peach",
            "value": 0.5441393852233887,
            "app_id": "main"
        },
        {
            "id": "ai_G58V132Z",
            "name": "water",
            "value": 0.5174278616905212,
            "app_id": "main"
        },
        {
            "id": "ai_TtT3b8dX",
            "name": "cherry",
            "value": 0.4638081192970276,
            "app_id": "main"
        },
        {
            "id": "ai_T851HmVS",
            "name": "orange",
            "value": 0.4131726622581482,
            "app_id": "main"
        },
        {
            "id": "ai_NDbbpCv1",
            "name": "vegetable",
            "value": 0.400101900100708,
            "app_id": "main"
        },
        {
            "id": "ai_CFS37srh",
            "name": "tea",
            "value": 0.3882850706577301,
            "app_id": "main"
        },
        {
            "id": "ai_lSK1vzWN",
            "name": "egg",
            "value": 0.37654799222946167,
            "app_id": "main"
        },
        {
            "id": "ai_gF8KLfz3",
            "name": "pear",
            "value": 0.3463618755340576,
            "app_id": "main"
        },
        {
            "id": "ai_s7Sbf40q",
            "name": "nectarine",
            "value": 0.32318776845932007,
            "app_id": "main"
        },
        {
            "id": "ai_CpNjHg1b",
            "name": "plum",
            "value": 0.27958944439888,
            "app_id": "main"
        },
        {
            "id": "ai_RZgNXv7K",
            "name": "aliment",
            "value": 0.26902902126312256,
            "app_id": "main"
        },
        {
            "id": "ai_f1zKlGnc",
            "name": "coffee",
            "value": 0.24869635701179504,
            "app_id": "main"
        },
        {
            "id": "ai_rgNHsKDf",
            "name": "watermelon",
            "value": 0.24644474685192108,
            "app_id": "main"
        },
        {
            "id": "ai_mNsgNJLD",
            "name": "oyster",
            "value": 0.23087935149669647,
            "app_id": "main"
        }
    ]
}

```

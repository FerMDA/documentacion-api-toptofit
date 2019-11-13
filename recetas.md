# API ToptoFit - Recetas

Para empezar con el api de busqueda de recetas, necesitaras tener una clave de acceso privada para utilizarla.

[Crear credencial del api!](http://toptofit.tech/home/)

Configuración de cabeceras de autenticación en el API:

```
Content-Type: application/json,
Authorization: 'Token '+yourAPIKEY
```

Ruta de peticción:
https://toptofit.tech/api/v1.0/recetas/?limit=15&offset=15"

Cuerpo de la petición o datos a enviar, en formato json:

```
{
"id_app": 1,
"private_key_app": "yourAppKey",
}
```


Respuesta en formato json

```
{
            "id": 10,
            "region": "MX",
            "nombre": "Berenjenas rellenas ",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "200 g de carne de cordero picada <br>100 g de espárragos trigueros <br>40 g de parmesano rallado <br>70 g de quesos variados <br>100 g de setas de cardo <br>70 ml de leche entera <br>1 cebolla pequeña <br>50 g de pan rallado <br>50 ml de vino tinto <br>Pimienta negra <br>Aceite de oliva <br>2 berenjenas <br>Pimentón <br>Orégano <br>1 huevo ",
            "instrucciones": "PASO 1\r\n\r\nEn primer lugar, limpia las berenjenas y quítales la punta que las une a la planta y córtalas por la mitad. Haz una incisión siguiendo el perímetro de la hortaliza que quede a medio centímetro de la piel. Realiza cortes longitudinales y transversales en la carne que queden dentro del perímetro que habrás marcado, pero cuidando de no traspasar la hortaliza. Ponlas a cocer en el horno, a 175ºC sobre un papel antiadherente, hasta que la carne del interior esté blanda.\r\nPASO 2\r\n\r\nMientras se cuecen, limpia las setas de cardo, córtalas en tiras finas y ponlos a cocer en una cazuela con aceite. Elimina la parte inferior de los espárragos, que es muy astillosa. Pélalos y córtalos a trozos de 1 cm de grosor aproximadamente. Agrégalos a la cazuela y deja cocer. Añade el Sofrito de Tomate y Cebolla Gallina Blanca. Cuando esté bien cocidos, añade la pastilla de Avecrem Caldo de Pollo desmenuzada y remueve.\r\nPASO 3\r\n\r\nMientras el sofrito se cuece, pon a calentar una sartén a fuego medio con un poco de aceite de oliva. Añádele la carne de cordero picada y rehógala, trabajándola con una cuchara o espátula para que no quede cocida en un bloque. Cuando esté totalmente cocida, moja con el vino y deja que se evapore su alcohol. Decanta la carne en un plato y resérvala. Añade al sofrito un poco de pimentón dulce y el orégano. Con ayuda de una cuchara, saca la carne del interior de las berenjenas. Pícala, mézclala con la carne y el sofrito, dejando cocer el conjunto unos minutos. Saca el relleno del fuego y déjalo templar un poco. Agrega los quesos (excepto el parmesano) al preparado anterior y remueve.\r\nPASO 4\r\n\r\nMézclales el huevo batido, la leche y el pan rallado. Rellena el interior de las berenjenas con la mezcla anterior. Cúbrelas con el parmesano rallado y caliéntalas en el horno a 180ºC durante unos 7-10 minutos antes de servirlas.",
            "image": "https://gbprodcdnimages2.azureedge.net/files/styles/recipe_main_image_670x420/windowsazurestorage/recipes/1540177262cbdba1eceec269dbac94e5e4115dcac2.jpg?itok=7sucvMyA"
        },
        {
            "id": 14,
            "region": "MX",
            "nombre": "Cupcakes De Chocolate Sin Carbohidratos",
            "tipo": "Panes y Productos Horneados Postres Pasa Bocas",
            "porcion": "6 porcion(es)",
            "ingredientes": "<ul> <li>70 g proteína en polvo</li>  <li>3 medianos huevos</li> <li>1 cucharadita canela</li> <li>2 cucharaditas extracto de vainilla</li> <li>2 cucharaditas polvo de hornear</li> </ul>",
            "instrucciones": "<ul>     <li>Precalentar horno a 250 C.</li>     <li>Moler todo en la licuadora hasta que quede uniforme.</li>     <li>Colocar en gorros de cupcakes hasta 3/4 de capacidad.</li>     <li>Hornear por 25 - 30 min.</li> </ul>",
            "image": "https://firebasestorage.googleapis.com/v0/b/caloriefood-4f6eb.appspot.com/o/recipes%2FCupcakes%20de%20Chocolate%20sin%20Carbohidratos.jpg?alt=media&token=3361890f-f801-4488-bf5f-8bd65215d33b"
        },
        {
            "id": 1,
            "region": "MX",
            "nombre": "Ensalada césar ",
            "tipo": "Ensaladas",
            "porcion": "4 personas",
            "ingredientes": "2 yemas de huevo <br>1 diente de ajo <br>10 anchoas <br>50 g de queso rallado <br>4 cdas de aceite de oliva <br>4 rebanadas de pan de molde <br>150 g de panceta ahumada <br>1 lechuga romana <br>4 tomates maduros <br>1 pepino <br>80 g de queso manchego curado ",
            "instrucciones": "PASO 1\r\n\r\nPrepara la salsa César, triturando con una batidora eléctrica, las yemas de huevo, el diente de ajo, las anchoas, el queso rallado, la pastilla de Avecrem Dúo Legumbres Estofadas y el aceite de oliva.\r\n\r\nPASO 2\r\n\r\nCorta el pan de molde sin corteza en triángulos y fríelos en una sartén con una cucharada de aceite de oliva. En la misma sartén fríe la panceta cortada en tiritas gruesas.\r\n\r\nPASO 3\r\n\r\nLimpia las lechugas, escúrrelas y córtalas. Corta también el tomate en gajos y el pepino en tiritas finas. Con un pelador de patatas haz virutas del queso manchego.\r\n\r\nPASO 4\r\n\r\nMonta los platos poniendo de forma decorativa las lechugas, el tomate, el pepino, las tostadas de pan, las virutas de queso y la panceta. Termina sirviendo la ensalada César con la salsa aparte para que cada cual se eche la cantidad que le apetezca.",
            "image": "https://www.comedera.com/wp-content/uploads/2018/03/ensalada-cesar.jpg"
        },
        {
            "id": 12,
            "region": "MX",
            "nombre": "Ensalada de garbanzos con bacalao ",
            "tipo": "Ensaladas ",
            "porcion": "4 personas ",
            "ingredientes": "400 g de garbanzos cocidos <br>200 g de bacalao desalado <br>100 ml de aceite de oliva virgen <br>40 g de aceitunas negras <br>30 ml de vinagre de jerez <br>1 manojo de cebollino <br>2 tomates maduros <br>1 remolacha cocida <br>1 pimiento amarillo <br>1 cebolla morada <br>1 pimiento rojo <br>1 pepino",
            "instrucciones": "PASO 1\r\n\r\nCorta los pimientos, el pepino, los tomates y la cebolla a daditos pequeños. Haz lo mismo con la remolacha cocida y vierte las verduras en un bol.\r\nPASO 2\r\n\r\nCorta el bacalao a tiras finas. Escurre los garbanzos cocidos de su agua.\r\nPASO 3\r\n\r\nMezcla en el bol de las verduras el bacalao, los garbanzos y las aceitunas. Añade la pastilla de Avecrem Dúo Paella de Pescado desmenuzada, mezcla bien y aliña con el vinagre y el aceite de oliva virgen.\r\nPASO 4\r\n\r\nPon en un plato la ensalada y decora con un poco de cebollino cortado a rodajas finas por encima.",
            "image": "https://www.petitchef.es/imgupl/recipe/ensalada-de-garbanzos-y-bacalao--md-53263p67701.jpg"
        },
        {
            "id": 2,
            "region": "MX",
            "nombre": "Fettucini al pesto de brócoli (sin gluten)",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "200 g de harina de trigo sarraceno <br>50 g de harina de maíz <br>1 cucharadita de goma xantana <br>1 huevo <br>agua necesaria <br>1 brócoli pequeño <br>100 ml de aceite de oliva <br>1 cucharada de piñones <br>70 g de queso Parmesano <br>unas hojas de albahaca fresca <br>sal y pimienta negra <br>",
            "instrucciones": "Bate el huevo y viértelo en el vaso medidor. Añade el agua necesaria hasta alcanzar 85 ml.\r\nVierte las harinas y la goma xantana en la máquina de hacer pasta Viva Collection de Philips, coloca el disco de fettucini y selecciona el programa 1.\r\nPon en marcha la máquina y agrega poco a poco el líquido.\r\nCorta la pasta cuando salga.\r\nPara la salsa, lava el brócoli y corta los ramilletes.\r\nTritura el brócoli con el resto de ingredientes hasta tener una mezcla homogénea.\r\nMezcla con la pasta y salpimentar al gusto.",
            "image": "https://img.blogs.es/phillips/wp-content/uploads/2018/05/fettuccine-610x406.jpg"
        },
        {
            "id": 7,
            "region": "MX",
            "nombre": "Guacamole",
            "tipo": "guarnición",
            "porcion": "4 personas",
            "ingredientes": "100 g de Cebolla picada <br>35 g de Cilantro picado <br>20 g de Chile serrano picado <br>500 g de Aguacate <br>15 ml de Jugo de limón <br>20 ml de Aceite de oliva <br>c-n Sal <br>",
            "instrucciones": "Incorporar todos los ingredientes en un molcajete o tazón.\r\nAgregar el aguacate y martajar con un tejolote o un machacador.\r\nSazonar con sal.\r\nReservar en refrigeración.",
            "image": "https://m25m4lmzg5-flywheel.netdna-ssl.com/wp-content/uploads/2018/04/deliciosas-recetas-de-cocina-mexicana-tradicional-4-300x212.jpg"
        },
        {
            "id": 16,
            "region": "MX",
            "nombre": "Mixiotes de pollo ",
            "tipo": "Comida",
            "porcion": "5 personas ",
            "ingredientes": "900 g de Pollo pierna y muslo \\n\r\n40 g de Chile guajillo \\n\r\n15 g de Chile morita \\n\r\n30 g de Manteca de cerdo \\n\r\n300 g de Jitomate guaje asado \\n\r\n20 g de Ajo asado \\n\r\n250 g de Cebolla fileteada \\n\r\n1 g de Comino en polvo \\n\r\n500 ml de Fondo de pollo \\n\r\n1 g de Hoja de aguacate \\n\r\n80 g de Hoja de maguey \\n\r\nCondimentos: \\n\r\nc-n Sal \\n\r\nc-n Pimienta negra molida \\n",
            "instrucciones": "Blanquear los chiles en agua caliente.\r\nLicuar los chiles con el jitomate, ajo, cebolla, comino, sazonar.\r\nFreír en la manteca, rectificar sazón.\r\nMarinar el pollo en la preparación anterior\r\nColocar el pollo sobre una hoja de maguey o papel sulfurizado.\r\nAgregar una hoja de aguacate, salsear y cerrar con un hilo.",
            "image": "https://m25m4lmzg5-flywheel.netdna-ssl.com/wp-content/uploads/2018/04/deliciosas-recetas-de-cocina-mexicana-tradicional-6-300x193.jpg"
        },
        {
            "id": 4,
            "region": "MX",
            "nombre": "Pan básico",
            "tipo": "guarnición",
            "porcion": "4 personas",
            "ingredientes": "300 g de harina de maíz o de trigo sarraceno <br>150 g de harina de arroz integral <br>470 ml de agua <br>100 ml de yogur o de leche <br>1 sobre de levadura de panadería <br>50 g de psyllium <br>25 g de semillas de lino molidas <br>8 g de sal <br>1 cucharadita de azúcar <br>50 ml de aceite de oliva <br>",
            "instrucciones": "En un cuenco mezcla el agua con el yogur, la levadura y las semillas de lino. \\n\r\nEn el recipiente de la amasadora coloca las harinas con la sal, el azúcar, el psyllium y forma un hueco en el centro. \\n \r\nAñade la primera preparación y el aceite de oliva. \\n\r\nMezcla todo un poco con una gran cuchara y después pon en marcha tu amasadora Philips para que trabaje muy bien la masa. \\n\r\nContinúa amasando a velocidad media durante unos 10-15 minutos, hasta que quede elástica. \\n\r\nDeja reposar tapado con un paño durante 30 minutos. \\n\r\nPrepara una bandeja con papel de hornear. \\n\r\nVuelca la masa y dale la forma que más te guste, pinta con aceite y deja reposar otros 30 minutos. \\n\r\nPrecalienta el horno mientras tanto a 240ºC. \\n\r\nEspolvorea el pan con harina de maíz, haz algunos cortes y hornea durante unos 40-45 minutos, hasta que esté bien dorado. \\n\r\nSi se tuesta muy rápido, baja la temperatura a 200ºC cuando hayan pasado 15 minutos. \\n\r\nDeja enfriar por completo sobre una rejilla. ",
            "image": "https://img.blogs.es/phillips/wp-content/uploads/2018/05/pan-singluten8-610x424.jpg"
        },
        {
            "id": 5,
            "region": "MX",
            "nombre": "Pechuga de pollo al limón",
            "tipo": "Comida",
            "porcion": "2 personas ",
            "ingredientes": "3 pechugas de pollo <br>2 limones <br>1 vaso de caldo de pollo <br>1 cucharada de tomillo <br>sal y pimienta <br>aceite de oliva ",
            "instrucciones": "Salpimentamos y doramos las pechugas en una sartén para que mantengan sus jugos\r\nPrimero, limpiamos las pechugas de grasas y cartílagos. Lo condimentamos con el tomillo, la sal y la pimienta. Después, en una sartén amplia a fuego fuerte, ponemos un chorrito de aceite. Cuando esté caliente, ponemos las pechugas y las cocinamos alrededor de unos 2 minutos por cada cara, hasta que queden doradas por todas sus partes. \\n\r\nColocamos las pechugas ya doradas en una olla a presión y añadimos el caldo y el limón\r\nEn una olla, ponemos el caldo, el pollo, el ajo bien picado, un limón partido por la mitad, el jugo del otro limón y lo calentamos todo a fuego medio. Tapamos y dejamos que se cocine durante alrededor de 10 minutos desde que coja presión. Pasado este tiempo, lo retiramos del fuego y dejamos que salga el aire. \\n\r\n\r\nServimos las pechugas cortadas, con su caldo y una guarnición\r\nCuando ya no quede presión, destapamos la olla y sacamos el pollo. Las colocamos en platos, cortadas en rodajas acompañadas con ensalada, patatas fritas o cualquier otra guarnición. \r\nPor encima, echamos una buena cantidad del caldo para darle sabor, y lo servimos en caliente.",
            "image": "https://www.cocinacaserayfacil.net/wp-content/uploads/2019/05/Pechugas-de-pollo-al-limon-1020x574.jpg"
        },
        {
            "id": 9,
            "region": "MX",
            "nombre": "Pechugas de pollo al curry con cebollas ",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "8 filetes de pechuga de pollo <br>20 g de cebollas pequeñas <br>Un chorro de Avecrem Plancha <br> Hierbas Aromáticas <br>Aceite de oliva virgen extra <br>Curry <br>",
            "instrucciones": "PASO 1\r\n\r\nMarina las pechugas de pollo con aceite y curry durante aproximadamente 30 minutos. En un wok, cocina la cebolla con un poco de aceite de oliva, un chorro de Avecrem Plancha Hierbas Aromáticas y una pizca de curry. Después de 15 minutos, retira las cebollas de la sartén y, en el mismo wok, añade el pollo.\r\nPASO 2\r\n\r\nCuece durante 10 minutos más y sirve inmediatamente, acompañando las pechugas de pollo con algunas cebollas.",
            "image": "https://gbprodcdnimages2.azureedge.net/files/styles/trick_664x444/windowsazurestorage/recipes/7efd07f15815cf6faeb9e81b40ac2ded1540183838.jpg?itok=59N_AuZj"
        },
        {
            "id": 13,
            "region": "MX",
            "nombre": "Pechugas de pollo al roquefort ",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "1 Kg. Pechugas de pollo <br>1 Brick 200 ml. Nata líquida <br>300 grs. Queso roquefort <br>",
            "instrucciones": "Poner en una cazuela las pechugas echas filetes a dorar un poco, ir apartándolas conforme vayan dorándose. Cuando estén todas, volcarlas en la misma cacerola y añadir el queso roquefort y la nata liquida y dejar a fuego lento hasta pasados unos 10 minutos.",
            "image": "https://gbprodcdnimages2.azureedge.net/files/styles/recipe_main_image_670x420/windowsazurestorage/recipes/1540140004e1895bc10ced13b9bc7c2a8c0e23c33c.jpg?itok=EBI0JnQy"
        },
        {
            "id": 11,
            "region": "MX",
            "nombre": "Tortitas de anahoria y germen de trigo ",
            "tipo": "Comida ",
            "porcion": "4 personas",
            "ingredientes": "c/s zanahoria <br>12 unds huevos <br>1 bolsa germen de trigo <br>1 pastilla Avecrem Caldo de Verduras-30% de sal <br>c/s nuez moscada <br>c/s cominos <br>",
            "instrucciones": "PASO 1\r\n\r\nTriturar el huevo, añadir la pastilla de Avecrem Caldo de Verduras-30% de sal desmenuzada, la nuez moscada, los cominos molidos, la zanahoria rallada, y el germen de trigo, hacer tortitas y freír en abundante aceite.",
            "image": "https://gbprodcdnimages2.azureedge.net/files/styles/recipe_main_image_mobile/windowsazurestorage/recipes/1540175164bd900ca24c704c9430bf71c5c8bb2918.jpg?itok=9gMNMSS1"
        },
        {
            "id": 15,
            "region": "MX",
            "nombre": "Tortitas de brócoli y zanahoria ",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "1 lámina de pasta quebrada <br>2 cdas. de queso para untar <br>1 pizca de nuez moscada <br>2 cdas. de queso rallado <br>1 pizca de pimienta <br>1 zanahoria rallada <br>1 cda. de mostaza <br>400 g de brócoli <br>100 ml de leche <br>2 huevos <br>",
            "instrucciones": "PASO 1\r\n\r\nForra un molde de tarta redondo con la pasta quebrada. Corta el brócoli en ramilletes y estos por la mitad, para que tengan una base. \r\nPASO 2\r\n\r\nCocina el brócoli en el microondas con un chorrito de agua, 1 pastilla de Avecrem Verduras -30% de Sal desmenuzada y tapado con papel film durante 4 min.\r\nPASO 3\r\n\r\nMezcla el queso para untar, los huevos, un poco de sal, la zanahoria rallada, pimienta y nuez moscada, el queso rallado, la leche y una pizca de mostaza.\r\nPASO 4\r\n\r\nColoca los ramilletes de brócoli encima de la tarta y echa la mezcla por encima. Cuece la tarta en el horno a 180 ºC, hasta que esté cocida y dorada. Enfríala y desmóldala.\r\n",
            "image": "https://gbprodcdnimages2.azureedge.net/files/styles/recipe_main_image_670x420/windowsazurestorage/recipes/154017967077328d5958673e892c7e23ea1f3fc2e8.jpg?itok=ILVXRcLa"
        },
        {
            "id": 3,
            "region": "MX",
            "nombre": "Tortitas de coliflor ",
            "tipo": "Comida ",
            "porcion": "4 personas",
            "ingredientes": "1 kg de coliflor <br>2 huevos <br>150 g harina de trigo <br>Ajo en polvo al gusto <br>Pimienta negra al gusto <br>Aceite de oliva al gusto ",
            "instrucciones": "PASO 1\r\n\r\nPara asegurar que la coliflor queda perfectamente integrada en nuestras tortitas tendrás que hervir la hortaliza. Para hacerlo te proponemos dos maneras. Por un lado, puedes optar por llevar a ebullición una olla con agua y cocer en ella la coliflor. Sino, también puedes usar el microondas durante 15 minutos a máxima potencia.\r\n\r\nPASO 2\r\n\r\nUna vez la tengas cocida, escúrrela muy bien y machácala en un bol grande. Agrega dos huevos a la col cuando ésta esté bien triturada, para que así homegeneizar la mezcla sea más fácil. Tamiza parte de la harina, y reserva una pequeña cantidad; ya que la necesitaremos en próximos pasos. Es importante que tamices la harina con un colador, así evitarás que queden grumos en tu tortitas y sean mucho más suaves. Incorpora muy bien la harina a la mezcla de la coliflor y los huevos. Esto va de mezclar, ya que una vez tengas bien trabajados la harina, los huevos y la colifor, deberás añadir a la mezcla el ajo en polvo, la pimienta negra y volver a integrarlos para terminar sazonando la mezcla con una pastilla de Avecrem Caldo de Verduras. Desmenuza la pastilla e intégralo todo en la masa.\r\n\r\nPASO 3\r\n\r\nY, después de tanto batir, llega la parte divertida. Remángate y comienza a formar las tortitas del tamaño que consideres oportuno. Pásalas por harina, y fríelas en abundante aceite. ¡Y listo!, ya tenemos nuestras tortitas con coliflor listas para hincarles el diente. Pero ojo, ¡que queman!\r\n\r\n",
            "image": "https://okdiario.com/img/recetas/2017/08/30/tortitas-de-coliflor.jpg"
        },
        {
            "id": 8,
            "region": "MX",
            "nombre": "salteado de pollo con soja ",
            "tipo": "Comida",
            "porcion": "4 personas",
            "ingredientes": "2 pechugas de pollo <br>\r\n2 cebollas <br>\r\n300g de brotes de soja en conserva <br>\r\n1/2 vaso de salsa de soja <br>\r\n3 cucharadas de jugo de limón <br>\r\nsal y pimienta <br>\r\naceite de oliva <br>",
            "instrucciones": "Cortamos el pollo en tiras y lo salteamos\r\nCortamos las pechugas en tiras del tamaño aproximado de un dedo y las salpimentamos. En una sartén alta, a fuego fuerte, ponemos un chorro de aceite y lo dejamos calentar. Depués, añadimos las tiras de pollo y las salteamos durante 3-4 minutos. Cuando estén doraditas, las retiramos de la sartén y las reservamos en un plato.\r\nSalteamos la cebolla en juliana y añadimos el resto de ingredientes\r\nEn la misma sartén, ponemos otro chorrito de aceite manteniendo el fuego fuerte. Cuando esté caliente de nuevo, añadimos las cebollas cortadas en tiras finas. Las salteamos hasta que se doren. Hecho esto, devolvemos a la sartén las tiras de pollo y añadimos los brotes de soja bien escurridos.\r\nPara terminar, añadimos la salsa de soja y el jugo de limón\r\nAhora vamos a añadir a la sartén la salsa de soja y las dos cucharadas de jugo de limón, que le dará mucho sabor al plato. Continuamos salteando durante 2-3 de minutos para que se mezclen bien los sabores. Pasado este tiempo, el plato estará listo para servir.",
            "image": "https://www.cocinacaserayfacil.net/wp-content/uploads/2019/05/salteado-de-verduras-con-pollo-1020x573.jpg"
        }
    ]
}
```

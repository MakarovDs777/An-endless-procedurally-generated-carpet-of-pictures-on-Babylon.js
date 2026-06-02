# An-endless-procedurally-generated-carpet-of-pictures-on-Babylon.js

В нулевой версии я сделал бесконечную процедурную генерацию картинок по мере движения камеры в обе стороны -x, и +x в одну полоску.

[Endless procedural image generation (Version 0 - Procedural generation of different pictures along the line) | Babylon.js Playground](https://playground.babylonjs.com/#X5N63U#0)

В первой версии я сделал генерацию по XZ бесконечно процедурно генерируемый ковер из набора выбираются случайные картинки все картинки одинакового размера тык впритык к друг другу.

[Endless procedural image generation (Version 1 - procedural generation of different images based on XZ coordinates) | Babylon.js Playground](https://playground.babylonjs.com/#DXNVN1#0)

Во второй версим я сделал процедурно генерируемого XZ ковера картинок неравномерной.

[Endless procedural image generation (Version 2 - Inconsistent generation by XZ coordinates as the camera moves) | Babylon.js Playground](https://playground.babylonjs.com/#VFZH73#0)

В третей версии есть биомы с наборами из одинаковых картинок, и бесконечно процедурно генерирумый ковер XZ где изображения тык в притык к друг другу одинакового размера. 

[Endless procedural image generation (Version 3 - generated identical images by chunks in XZ coordinates) | Babylon.js Playground](https://playground.babylonjs.com/#V25B02#0)

Что и предыдущий код только LOD ограниченный, и при перемещение камеры не остается след из чанков картинок.

[Endless procedural image generation (Version 4 - General's version within LOD with deletion of previous chunks) | Babylon.js Playground](https://playground.babylonjs.com/#E1CW8N#0)

Изображения одинаквоого размера генерируются впритык друг к другу но когда я перемещаю камеру предыдущий чанки с картинками не удаляются а остаются.

[Endless procedural image generation (Version 5 - Generating different sets of images in different chunks) | Babylon.js Playground](https://playground.babylonjs.com/#QOPFOQ#0)

Изображения разного размера генерируются друг от друга с пустотой между собой.

[Endless procedural image generation (Version 6 - Generating different image sizes sets of images in different chunks) | Babylon.js Playground](https://playground.babylonjs.com/#TPVCEB#0)

В этой версии картинки генерируются в одной полоске тык в притык друг друга но они разного размера.

[Endless procedural image generation (Version 7 - A version with sets of different images in a line of X with different) | Babylon.js Playground](https://playground.babylonjs.com/#WDUTHR#0)

Отлично теперь в разных биомах разные картинки разного размера тык в притык друг другу.

[Endless procedural image generation (Version 8 - A version with different sets of tiles of different image sizes) | Babylon.js Playground](https://playground.babylonjs.com/#T8774W#0)

И наконец в финальной версии в разных биомах разные картинки разного размера тык в притык друг другу но при возвращение камеры в предыдущий чанк картинки те же генерируются по сиду.

[Endless procedural image generation (version 9 - Version with different sets of tiles of different sizes with SEED) | Babylon.js Playground](https://playground.babylonjs.com/#NLB4PI#0)

Теперь мне нужно на одной плоскости генерировать множество разных картинок друг на друга в случайном месте.

[Endless procedural image generation (version 10 - With random overlapping of different images in the same plane) | Babylon.js Playground](https://playground.babylonjs.com/#N2PZTX#1)

Теперь нужно сделать бесконченый процедурно генерируемый ковёр с случайными картинками на этом ковре. 

[Endless procedural image generation (version 11 - Endless carpet with random pictures) | Babylon.js Playground](https://playground.babylonjs.com/#L7JZJ5)

Ну всё теперь осталось лишь сделать заранее установленную генерацию картинок.

[Endless procedural image generation (version 12 - Endless carpet with random pictures preset generation) | Babylon.js Playground](https://playground.babylonjs.com/#PR1SRI)

Тоже что, и предыдущая но без случайного поворота картинок.

[Endless procedural image generation (version 13 - Endless random pictures preset generation without rotating the images) | Babylon.js Playground](https://playground.babylonjs.com/#QCNCCH)

Теперь спресуем генерацию изображений друг к другу.

[Endless procedural image generation (version 14 - Endless carpet of random images in a solid format) | Babylon.js Playground](https://playground.babylonjs.com/#JYDQ4W)

Ну и для пущей эффектности сделаем генерацию не из набора заранее заданых случайных картинок а вообще случайная картинка из множества случайных картинок за основу взят сайт Lorem Picsum но предупреждаю сайт иногда не работает.

[Endless procedural image generation (version 15 - Endless carpet of random Lorem Picsum images in a solid format)](https://playground.babylonjs.com/#3DWRMK#0)

Но мне хотелось бы телепортироваться куда нибудь далеко что-бы найти что-то действительно стоящие.

[Endless procedural image generation (version 16-Endless carpet of random Lorem Picsum images in a solid format+teleport) | Babylon.js Playground](https://playground.babylonjs.com/#VFX2G0)

Короче Lorem Picsum говно постоянно не работет нужно сделать картинки из набора провайдеров для случайных картинок.

[Endless procedural image generation (version 17 - An endless generated carpet of images from a set of providers) | Babylon.js Playground](https://playground.babylonjs.com/#5JGTZX)

Короче нахер, и провайдеры, и Lorem Picsum, и хостинги картинок нужно сделать из массива чисел картинку по три числа RGB то есть тупо вбить молтком в сам скелет кода картинку.

[Endless procedural image generation (version 18 - An endless generated carpet of image but procedural image) | Babylon.js Playground](https://playground.babylonjs.com/#XO390P#2)

Теперь сделаем множество картинок а не одну.

[Endless procedural image generation (version 19 - An endless generated carpet of image but multiply procedural image) | Babylon.js Playground](https://playground.babylonjs.com/#LZYWEI)

Тоже самое что, и 12 версия только с процедурной генерацией картинки случайно повернутойна 360 градусов.

[Endless procedural image generation(version 20-Endless carpet with random images preset generation but procedural image) | Babylon.js Playground](https://playground.babylonjs.com/#ARY9ZD)

Отлично но мне нужно решить проблему обрезки картинок при генерации близь границ чанков.

[Endless procedural image generation (version 21 - An endless carpet of RGB array image without cutting chunks) | Babylon.js Playground](https://playground.babylonjs.com/#AFE40F)

Теперь нужно сделать так что-бы было множество разных картинок где для каждой картинки разная опциональная ширина, и высота.

[Endless procedural image generation (version 22 - An endless carpet of RGB array multuply images without cutting chunks) | Babylon.js Playground](https://playground.babylonjs.com/#P6QF1O)

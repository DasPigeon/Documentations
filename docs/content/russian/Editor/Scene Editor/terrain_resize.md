+++
title = "Изменение размера ландшафта"

[menu.main]
identifier = "terrain_resize"
parent = "core_components"
+++

## Изменение размера ландшафта
При необходимости количество узлов ландшафта можно изменить на панели <b>Resize Terrain</b> в <b>Terrain Inspector</b>.

![](/img/terrain_resize/resize_panel.PNG)

* Есть 4 направления, в которых вы можете добавлять новые узлы или удалять существующие узлы. +X, +Y, -X, -Y (Юг, Восток, Север, Запад соответственно) (Раскраска соответствует Gizmo). \\
* Добавление или удаление узлов автоматически перемещает существующие объекты и флоры на их новые места. Для новых узлов данные о высоте не указаны, и они могут выглядеть несвязанными с остальной частью ландшафта. Художник может (и должен) легко исправить это, используя кисти высоты в редакторе, или может экспортировать карту высот и изменить с помощью внешнего инструмента создания карты высот, а затем импортировать обратно в редактор. \\
* Использование положительных значений на стороне добавит столько новых узлов к этой стороне. Если вы напишете +2 с каждой стороны, ландшафт будет расширяться на 2 узла с каждой стороны. Если вы напишете 3 только для +X и 0 (ноль) для отдыха, ландшафт будет расширяться на 3 узла только в направлении +X. \\
* Если вы напишете отрицательное значение на стороне, это удалит столько узлов с этой стороны. \\
* Если вы напишете 0 (ноль) на боковой стороне, никаких изменений на этой стороне не будет. (значение по умолчанию)

| Добавление | Удаление |
| ------------ | ------------ |
| ![](/img/terrain_resize/append.PNG) | ![](/img/terrain_resize/delete.PNG) |

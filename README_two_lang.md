# Bambu Lab A1 mini Cover Project / Корпус для Bambu Lab A1 mini

## 🐾 Dedicated to my family, patiently tolerating my projects, and to my cat Tyoma, who left for the rainbow far too early.

## 🐾 Посвящается моей семье, терпеливо относящейся к моим проектам, а также моему, преждевременно ушедшему на радугу, котику Тёме.

---

## 📦 Project Summary

A long-held dream of buying a 3D printer finally came true. I had learned some basics of 3D modeling, even made some things for friends, but it was hard to “feel” the result without having my own printer. By the time I bought the Bambu Lab A1 mini, I had already designed a weather station case for an ESP32 with a 2.8” screen.

After printing test boats, calibration prints, and a few cases and trinkets, the question arose: how to cover the printer to protect it from dust and a curious cat? Ready-made enclosures were too expensive and uninspiring. 

![любопытный Тёма](img/cat.JPG)
DIY solutions from the internet didn’t appeal either.

So I decided to build a frame — maybe cover it with film or something later. My constraints: do it as cheaply as possible, from available materials, including parts printed on my new 3D printer.

At that stage, I had no clear idea what the final product would look like. As they say, a samurai has no goal, only the path.

I considered various frame materials: plastic pipes, wooden slats, aluminum angles... and settled on 10×10×1 mm aluminum square tubing. Bare, uncoated tubing with cutting and delivery came out to about \$7 for 6 meters!

### First Attempt

Since the frame seemed sturdy enough, even if just covered with film at first, I figured — why not design a full enclosure suitable for printing with specific materials? I measured the printer’s full motion range and came up with a 450×500×500 mm box.

I designed corner joints with 2.8 mm screw holes for M3 screws. For aesthetics, all holes in the tubes were to be on the same face, so I needed two types of corner elements.
![угловые соединения_картинка](img/inner_corners_dr.JPG)

![угловые соединения](img/inner_corner.JPG)

I printed them and ordered the tubes. Then I 3D-printed a drilling jig to help make centered, consistent holes.

![Кондуктор для труб](img/pipe_drilling_conductor.JPG)

![труба_с_отверстием](img/pipe_hole.JPG)
But once assembled... I was stunned. The thing was huge. Measuring with a tape doesn’t convey the scale.

![большой каркас](img/big_enclouse.JPG)
I decided to downsize. After all, maybe I wouldn’t print inside it anyway. My reasoning:

* Materials like ABS and ASA stink while printing
* The printer is in the bedroom
* The A1 mini is designed as an open printer, and cooling isn't suitable for enclosed operation

So I pivoted: this would be a **storage** cover.

### New Frame

To avoid removing the filament spool each time, I moved it behind the Z-axis using a popular bracket from MakerWorld. After adjusting measurements, I ended up with:

* Width: 434 mm
* Depth: 434 mm
* Height: 477 mm

Corner pieces were already printed. Because they extended the total length by 25 mm at each end, tubes had to be 50 mm shorter than the edge:

* 10 pcs × 384 mm
* 4 pcs × 427 mm

I built the new frame — much better!

Early on I had also designed external corners with slots for wall panels. I assumed 4 mm thick panels, though I didn’t yet know the material. Considered MDF, acrylic, plywood... none felt right. Either too ugly, or (like acrylic) too pricey.

![внешний уголок_картинка](img/outer_corner_dr.JPG)

![внешний уголок](img/outer_corner.JPG)

Eventually settled on twin-wall polycarbonate, 4 mm thick. Since the walls and roof don’t sit directly on the tubes, I used aluminum angles as trim to cover gaps and created printed guides for securing everything.

![направляющая_картинка](img/main_guide_dr.JPG)
![направляющая](img/main_guide.JPG)

![корпус_первоначальный_вид1](img/enclouse1.JPG)
![корпус_первоначальный_вид2](img/enclouse2.JPG)


![кодуктор_для_уголка](img/corner_drilling_conductor_dr.JPG)

### Final Version

Then came the idea of maybe printing inside the box after all. But the 4 mm polycarbonate turned out to be too soft — it wouldn’t even hold the cat’s weight on top.

So I added reinforcement:

* Structural braces
* Sliding top window to allow Bowden/cable movement
* Removable front panel

The top window was made in segments to fit the build plate and mounted to the upper braces. The front panel became a vertical slider. This required tweaking the corner design and adding vertical rail guides.

![верхнее_окно](img/top_window_dr.JPG)

![верхнее_окно](img/top_window.JPG)

![модифицированный_уголок](img/outer_corner_sliding.JPG)

![направляющие_передней_стенки](img/sliding_guide.JPG)
This is the final result!
![финальный_вид1](img/final_enclouse1.JPG)
![финальный_вид2](img/final_enclouse2.JPG)
---

## 🛠️ Features

* Lightweight aluminum frame
* Sliding top window for Bowden tube/cable clearance
* Vertically sliding front panel for easy access
* Polycarbonate walls with printed guides and aluminum trim
* Fully 3D-printed connectors, brackets, and corner elements

---

## 📐 Dimensions

* Width: 434 mm
* Depth: 434 mm
* Height: 477 mm

---

## 📋 Materials List

| №  | Item                                    | Qty    |
| -- | --------------------------------------- | ------ |
| 1  | Aluminum square tube 10×10×1 mm, 384 mm | 10 pcs |
| 2  | Aluminum square tube 10×10×1 mm, 427 mm | 4 pcs  |
| 3  | Aluminum angle 15×15×1 mm, 380 mm       | 4 pcs  |
| 4  | Aluminum angle 15×15×1 mm, 423 mm       | 4 pcs  |
| 5  | Polycarbonate sheet 430×430×4 mm        | 1 pc   |
| 6  | Polycarbonate sheet 430×475×4 mm        | 4 pcs  |
| 7  | M3 screw, 6–8 mm                        | 16 pcs |
| 8  | M3 screw, 16 mm                         | 10 pcs |
| 9  | M3 nut                                  | 4 pcs  |
| 10 | M4 screw, 20 mm                         | 8 pcs  |
| 11 | M4 nut                                  | 8 pcs  |

---

## 💾 Files

STL models for corners, brackets, guides, and other parts are in the [`stl/`](./stl) folder.

---

## 🤝 Support

If you find this project helpful and would like to support its development:

* **PayPal**: [gia@gia.org.ua](mailto:gia@gia.org.ua)
* **Ko-fi**: *(link to be added)*

Your support is greatly appreciated!

---

## ⚖️ License

[MIT License](LICENSE)

---
## Введение (нетерпеливые могут сразу перейти к STL-файлам)

Идея купить 3D-принтер зрела давно. Я уже освоил основы 3D-моделирования, иногда делал заказы для друзей, но всё это было "вслепую": распечатать и подержать в руках результат было негде.

К моменту покупки принтера у меня уже был готовый проект корпуса метеостанции на базе ESP32 с 2.8" экраном, так называемый CYD (Cheap Yellow Display). Информацию по самой метеостанции можно посмотреть [тут](https://github.com/igor-gia/Meteo). Решено: беру! Выбор пал на **Bambu Lab A1 mini** — компактный, шустрый, сразу с автокалибровкой и не требующий шаманства с бубном.

После череды корабликов, тестов зазоров и, конечно же, корпуса той самой метеостанции, встал вопрос: чем прикрыть принтер? От пыли, от лап и любопытсва котика.
![любопытный Тёма](img/cat.JPG)
Готовые решения либо не подходили, либо стоили ощутимо дороже самого принтера. Среди DIY-проектов тоже ничего не зацепило. Решил: делаю **сам**.

## Первый подход: каркас-монстр

Идея была проста: собрать каркас, обтянуть чем придётся, на крайний случай – ПВХ-пленкой, а там видно будет. Главное — дёшево, из доступного, в том числе, распечатанных на моем 3D-принтере.

Что должно получиться в самом конце еще не представлял. **Как говорится, у самурая нет цели - только путь.**

Материалы рассматривал разные: пластиковые водопроводные трубы, деревянные рейки, алюминиевые уголки… Победила квадратная алюминиевая труба **10×10×1 мм**. С порезкой и доставкой получается \~\$7 за 6 метров.
Так как труба довольно жёсткая, решил пойти дальше и спроектировать сразу закрытую камеру. Вдруг пригодится для печати ABS/ASA. Замерил габариты принтера с учётом всех его движений — вышел параллелепипед 450×500×500 мм.
Спроектировал угловые соединения под винты M3. Поскольку хотелось хоть какой-то эстетики, решил, что все отверстия в трубах должны быть на одной грани. Поэтому, угловые элементы нужны двух типов.

![угловые соединения_картинка](img/inner_corners_dr.JPG)

Вот так выглядят распечатанные
![угловые соединения](img/inner_corner.JPG)

Распечатал эти элементы и заказал трубы. В полученных уже нарезанных трубах просверлил по отверстию с каждой стороны. Для этого спроектировал и распечатала кондуктор. Чтоб отверстие было по центру грани и на одинаковом расстоянии от торца. 
![Кондуктор для труб](img/pipe_drilling_conductor.JPG)

Отверстия получились на своих местах
![труба_с_отверстием](img/pipe_hole.JPG)

Собрал каркас… и **офигел**. Он оказался громадным. Рулетка не передаёт масштаб — пока не соберёшь вживую, не поймёшь.
![большой каркас](img/big_enclouse.JPG)
В теории (на рулетке) оно выглядело компактнее. 

Подумал — а может, ну его? Ведь:

* Пластики типа ABS/ASA воняют а принтер стоит в спальне.
* Охлаждение у A1 mini не рассчитано на печать в закрытом объёме и есть риск перегрева электронных компонентов.
* Температура стола не совсем подходит для печати пластиками типа типа ABS/ASA.

Так родилась идея сделать **корпус не для печати, а для хранения**.
## Новый расчёт, новый каркас

В борьбе за компактность, перевесил катушку за ось Z (распечатав один из популярных кронштейнов) и пересчитал габариты корпуса:

* Ширина: **434 мм**
* Глубина: **434 мм**
* Высота: **477 мм**

Почему такие цифры? Уже не вспомню. Но с учётом креплений трубы нужны длиной:

* **384 мм** — 10 шт
* **427 мм** — 4 шт

Снова всё собрал — стало лучше. Принял, что толщина стенок будет **4 мм**. На тот момент материал стенок был под вопросом — думал и про ДВП, и про акрил, и про фанеру. Но всё не нравилось, либо из-за внешнего вида, либо, как в варианте с оргстеклом – из-за цены. Пришел к компромиссному варианту: материал стенок – сотовый поликарбонат толщиной 4мм.
Ещё на раннем этапе спроектировал внешний уголок с пазом под стенки.

![внешний уголок_картинка](img/outer_corner_dr.JPG)

Вот, что получилось
![внешний уголок](img/outer_corner.JPG)

Поскольку стенки и крыша корпуса не лежат непосредственно на трубах (из-за особенности проектирования внешних уголков), то между ними есть зазор, который решил закрыть алюминиевыми уголками 15х15х1 мм. И для лучшей фиксации и прилегания поликарбоната, а также для крепления уголков, спроектировал опоры.
Вот так выглядят опоры поликарбоната, надевающиеся на трубы и которым потом прикручивается алюминевый уголок.

![направляющая_картинка](img/main_guide_dr.JPG)
![направляющая](img/main_guide.JPG)
В сборе с разных ракурсов это выглядит так:
![направляющая](img/main_guide_joint.JPG)
![направляющая](img/main_guide_joint2.JPG)

В результате корпус стал выглядеть так:
![корпус_первоначальный_вид1](img/enclouse1.JPG)
![корпус_первоначальный_вид2](img/enclouse2.JPG)

Для сверления крепежных отверстий в уголках также сделал кондуктор

![кодуктор_для_уголка](img/corner_drilling_conductor_dr.JPG)

## Улучшения и финальная версия

Поликарбонат оказался чересчур гибким — крышку кот просто продавил бы. Да и идея печатать прямо в коробе снова не давала покоя.

Так появилось:

* **окошко в верхней крышке** — чтобы кабели и трубка с филламентом не упирались, а также для отвода тепла;
* **ребра жёсткости** с крепёжными кронштейнами;
* **съёмная передняя стенка**, сдвигающаяся вверх по направляющим.

Рамка окна состоит из частей (в рабочую зону всё не влезало), крепится к верхним рёбрам и между собой.

![верхнее_окно](img/top_window_dr.JPG)

![верхнее_окно](img/top_window.JPG)

С передней стенкой всё оказалось проще: модифицировал уголки, добавил направляющие — работает отлично.
![модифицированный_уголок](img/outer_corner_sliding.JPG)

![направляющие_передней_стенки](img/sliding_guide.JPG)

## Что получилось

![финальный_вид1](img/final_enclouse1.JPG)
![финальный_вид2](img/final_enclouse2.JPG)

---

## 📋 Список материалов

| №  | Материал                                    | Кол-во |
| -- | ------------------------------------------- | ------ |
| 1  | Алюминиевая труба 10×10×1 мм, длина 384 мм  | 10 шт  |
| 2  | Алюминиевая труба 10×10×1 мм, длина 427 мм  | 4 шт   |
| 3  | Алюминиевый уголок 15×15×1 мм, длина 380 мм | 4 шт   |
| 4  | Алюминиевый уголок 15×15×1 мм, длина 423 мм | 4 шт   |
| 5  | Сотовый поликарбонат 430×430×4 мм           | 1 шт   |
| 6  | Сотовый поликарбонат 430×475×4 мм           | 4 шт   |
| 7  | Винт M3, длина 6–8 мм                       | 16 шт  |
| 8  | Винт M3, длина 16 мм                        | 10 шт  |
| 9  | Гайка M3                                    | 4 шт   |
| 10 | Винт M4, длина 20 мм                        | 8 шт   |
| 11 | Гайка M4                                    | 8 шт   |

---

## STL-файлы

Папка `stl/` содержит всё, что я моделировал: углы, направляющие, кондукторы, крепления. Если чего-то не хватает — пишите, добавлю.

---

## Лицензия

Этот проект распространяется по лицензии [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ru).

Вы можете свободно использовать, копировать и модифицировать материалы, но:
- **только не в коммерческих целях**;
- **с обязательным указанием авторства** (Igor Gimelfarb);
- **и с условием**, что производные работы будут распространяться на тех же условиях.

Если хотите показать, что использовали мой проект — буду только рад. Особенно, если это не ради наживы :)

##  Поддержка
Если вы находите этот проект полезным и хотите поддержать его разработку, вы можете сделать пожертвование любым из следующих способов:

- **PayPal**: [gia@gia.org.ua] [Donate via PayPal](https://www.paypal.me)  
- **Ko-fi**: [Donate on Ko-fi](https://ko-fi.com/igorgimelfarb)  


**Ваша поддержка будет очень ценна!**

---

Спасибо за интерес к проекту! / Thank you for your interest in the project!

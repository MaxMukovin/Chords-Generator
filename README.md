# ChordsGenerator

### Цель
Создание веб-приложения для генерации любого аккорда, отображения нот, входящих в данный аккорд и визуализации на клавиатуре фортепиано и грифе гитары (при различных строях).

[Методичка по аккордам](https://github.com/MaxMukovin/ChordsGenerator/edit/main/Methodology.md)

### Задачи ([Issues](https://github.com/MaxMukovin/ChordsGenerator/issues))

- [x] [Описать логику построения всех аккордов](https://github.com/MaxMukovin/ChordsGenerator/issues/2);
- [ ] [Дописать Readme в части заполнения аккордов](https://github.com/MaxMukovin/ChordsGenerator/issues/1)
- [ ] [Создать мокап компонентов в ландшафтном (desktop) и портретном (phone) режимах](https://github.com/MaxMukovin/ChordsGenerator/issues/3)


## Реализация
### Технологии
Веб-приложение должно быть написано с использованием:
1. Мокап UX/UI **Adobe XD**;
2. Языка разметки **HTML**;
3. Параметров форматирования **CSS**;
4. Язык программирования логики приложения - **JS** (JavaScript);
5. Фреймворка **VueJS**.
### UX/UI
Приложение должно быть на русском/английском языке, иметь интуитивно-понятный пользовательский интерфейс.
Расположение элементов управления должно быть удобным, для реализации основных функций приложения должно быть совершено не более 3-х действий (нажатий).
Приложение должно поддерживать дневной/ночной режим с возможностью ручного и автоматического перехода (в соответствии с временем на устройстве Пользователя).

*Пример пользовательского интерфейса*
(in progress...)

### Управление
Приложение должно поддерживать работу на сенсорном экране и с помощью манипуляторов типа: "Мышь" и "Клавиатура".
Должны быть спроектированы и запрограмированы горячие клавиши для выбора любого элемента Функционала приложения.
### Функционал
1. Выбор основного тона аккорда: 
- **C** [До]; 
- **D** [Ре]; 
- **E** [Ми]; 
- **F** [Фа]; 
- **G** [Соль]; 
- **A** [Ля]; 
- **B** [Си];
3. Назначение знаков альтерации: 
- **#** [Диез];
- **b** [Бемоль];
4. Выбор Аккорда;
- М
- 7 
- maj7
- 6
- 6b
- 5# / 5+
- add2 / add9
- add4
- sus2
- sus4
- -5
- add#4
- sus#4
- dim7
- 5
- 9
- maj9
- -9
- 9+
- 11
- 11+
- 13
5. Выбор строя гитары:
- Стандартный (EBGDAE);
- Open-G (DBGDGD);
- Другие (при необходимости).
6. Сохранение всех параметров приложения в файлы Cookie для восстановления работы после перезагрузки/повторного открытия страницы.
7. Просмотр справки по работе с приложением (описание функционала, горячие клавиши, прочая информация).
8. Переключение дневного/ночного режима. Отключение автоматизации. Выбор времени начала/окончания ночного режима.
## Использование приложения
*Раздел будет заполнен после окончания разработки приложения...*

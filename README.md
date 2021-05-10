### Тема диплома:
## «Разработка двухмерного аркадного игрового мобильного приложения “Don't let grab” в среде Unity для ОС Android»

Данные разработки:
1. Среда разработки: Microsoft Visual Studio 2019, Unity 2020.1b  
2. Операционная система: Android 5.1 и выше  
3. Мобильные устройства (для тестирования): Смартфон Leagoo Elite 5, смартфон Vivo V17 Neo  
4. Требования к содержанию мобильного приложения:  
   - функционирование раундов и возрождения объектов врагов в соответствии с действием раундов;
   - функционирование перемещения объектов врагов на игровом поле;
   - функционирование взаимодействия между объектов врагов и объектов защищаемых башен для функции завершения игры;
   - предоставление пользователю управления перемещением и выстрелом снарядами из объектов пушек для уничтожения объектов врагов и защиты объектов башен;
   - функционирование бонусов для снарядов, а также предоставление пользователю возможности сбора бонусов;
   - функционирование игровой статистики, а также предоставление пользователю информации о показателе лучшего результата за всё время игры;
   - функционирование различных видов меню (главное, паузы, завершения).

[Видео работы на Youtube](https://youtu.be/cNT-ODeEbdg)

### Структура папок репозитория:
   - ../Assets - ассеты, которые могут быть использованы проектом на Unity:
      - ./BayatGames - библиотека-ассет для сохранения пользовательских данных;
      - ./GameScene - созданные файлы-ресурсы для функционирования сцен проекта:
         - ./Ammutinion - материалы, изображения иконок, спрайты и префабы объектов ;
         - ./Animation - файлы анимации UI;
         - ./Prefabs - объекты-префабы для функционирования сцен игры;
         - ./Scripts - программный код проекта;
         - ./Textures - текстуры для материалов;
      - ./Scenes - папка с файлами сцен проекта.
   - ../DocImages - изображения снарядов и характеристик снарядов, изображение эскиза проекта, изображение диаграммы классов и диаграммы вариантов использования;
   - ../Library - папка с файлами библиотек (включена для компиляции проекта без установки Unity);
   - ../Packages - дополнительные пакеты проекта;
   - ../ProjectSettings - файлы настроек проекта.

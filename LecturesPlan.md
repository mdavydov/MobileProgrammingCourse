# План лекцій з курсу "Програмне забезпечення мобільних пристроїв"

## Лекції 1-2. Вступне заняття. Операційні системи і апаратне забезпечення мобільних пристроїв

1. Історія розвитку мобільних пристроїв.
1. Типи мобільних пристроїв:  смартфони, планшети, фаблети, розумні годинники, медіа-плеєри, окуляри, ноутбуки, etc.
1. Операційні системи мобільних пристроїв
   - iOS, WatchOS
   - Android, Wear OS
   - Other: Bada/Tizen, BlackBerry OS, MeeGo OS, Palm OS, Symbian OS, webOS, Windows Mobile
1. Апаратне забезпечення мобільних пристроїв:
   - Апаратна архітектура мобільного пристрою
   - Процесори мобільних пристроїв
   - Оперативна пам'ять мобільних пристроїв
   - Графічні процесори мобільних пристроїв
   - Екрани
   - Камери мобільних пристроїв
   - Мережеве обладнання: GSM, EDGE, 3G, 4G, 5G, LTE, Cellular, Wi-Fi, NFC
   - Сенсори мобільних пристроїв: акселерометр, компас, гіроскоп, etc
1. Основні тенденції на ринку мобільних пристроїв: роботи, окуляри, Virtual Reality, Augmented Reality
1. Основні засоби розроблення для мобільних пристроїв: XCode, Android Studio
1. Лабораторні, індивідуальний проект

Презентації:

https://www.slideshare.net/MaksymDavydov/lecture-01-mobile-operating-systems-135081365

https://www.slideshare.net/MaksymDavydov/lecture-02-mobile-hardware

Питання для самоперевірки:

https://create.kahoot.it/share/mobile-os-and-hardware/4fb9752b-66bf-4e29-8169-28d6f4f2f157
   
## Лекції 3-4. Основи розроблення для платформи Android. Мова програмування Java.
1. Архітектура платформи Android
1. Середовище розроблення Android Studio
1. Складові програмного проекту для Android
   - Маніфест програми
   - Ресурси програми
1. Мова програмування Java
   - Базові типи і об'єкти
   - Пакети, класи, методи,
   - інтерфейси, анонімні класи
   - основні бібліотеки
   
   Презентації:
  
   https://www.slideshare.net/MaksymDavydov/android-programming-intro
  
   http://indico.ictp.it/event/a0727/session/7/contribution/4/material/0/1.pdf
   
   https://www.slideshare.net/MaksymDavydov/java-small-tests

## Лекції 5-6. Розроблення для Android: інтерфейсні елементи, анімації, збереження даних, мережева взаємодія, використання  С++.

1. Додаток для Android і його компоненти
   - Додаток
   - Активності
   - Сервіси
   - Приймачі повідомлень
   - Провайдери контенту
1. Основні компоненти інтерфейсу користувача в Android
   - Активності
   - Фрагменти
   - Розміщення та вікна (Views)
   - Віджети та шпалери головного екрану
1. Розроблення інтерфейсу програми
   - Файл розміщення (XML) і основні теги розміщення
   - Засоби розташування елементів
1. Анімація елементів програми і переходи між активностями
   - Анімації в ОС Android
   - Transition Framework
   - Спільні елементи між активностями
   - Анімація елементів в межах однієї активності
   - Анімація векторних малюнків Animate Vector Drawables
1. Засоби збереження даних
1. Засоби мережевої взаємодії
1. Програмування на мові C++ для Android і використання Android NDK

   Презентації:
   
   Програмування інтерфейсу: https://www.slideshare.net/MaksymDavydov/interface-programming-android
   
   Збереження даних: https://www.slideshare.net/MaksymDavydov/android-storage
   
   MVC, виконання операцій у фоні: http://www.di.univr.it/documenti/OccorrenzaIns/matdid/matdid445162.pdf
   
   Мережева взаємодія: https://www.slideshare.net/MaksymDavydov/android-networking-139051053
   
   Анімації в Android: [слайди](https://www.slideshare.net/MaksymDavydov/android-animations-140018946) і [відео](https://youtu.be/P7kNiiPcReo)
   
   Поєднання коду на Java і C++: https://www.slideshare.net/MaksymDavydov/android-mix-java-and-c
   
   Додаткові матеріали:
   
   Використання анотацій для перевірки коду: https://developer.android.com/studio/write/annotations.html#kotlin
   
   Задання обробника події прямо у файлі розміщення: https://www.slideshare.net/MaksymDavydov/handler-declaration-in-layout
   
## Лекції 7-8. Проектування мобільних додатків. Від вимог до інфраструктури.

1. Проектування: визначення вимог
   - Дослідження предметної області.
   - Визначення проблем.
   - Принципи UX.
   - Функціональні і нефункціональні вимоги до мобільних додатків.
   - Аналіз Jobs-to-be-done
   - Аналіз персон
1. Проектування: вибір інфраструктури
   - Засоби і бібліотеки для взаємодії.
   - Основи безпеки й надійності.
   - Хмарні і мобільні сервіси.
   - Основи Google Firebase і Microsoft Mobile Services.
   
   Презентації:
   
   Визначення можливостей: https://www.slideshare.net/MaksymDavydov/mobile-app-design-feature-development
   
   Дизайн мобільних додатків: https://www.slideshare.net/MaksymDavydov/design-of-mobile-apps
   
   Google Play Services: https://www.jumpyjosh.com/topic04-google-services/talk-1-google-1/01.google.plus.pdf
   
   BaaS платформи:
   
   Azure Mobile Services: https://www.slideshare.net/MaksymDavydov/microsoft-mobile-services
   
   Firebase:
   
   - https://www.slideshare.net/MaksymDavydov/firebase-overview-141183795
   - https://www.jumpyjosh.com/topic05-firebase/talk-1-firebase/firebase.pdf
   
   

## Лекції 9-10. Програмування графічних мобільних додатків з використанням OpenGL ES, Metal, Vulkan
1. Історія розвитку OpenGL і Metal.
1. Основні об’єкти.
1. Поняття контексту.
1. Типи шейдерів.
1. Відмінні і спільні риси OpenGL ES і Metal.

Презентації:
  - Малювання у Android View: http://courses.coreservlets.com/Course-Materials/pdf/android/Android-Drawing-1.pdf
  - Програмування OpenGL на Android: https://proglang.informatik.uni-freiburg.de/teaching/androidpracticum/2013/AndroidAndOpenGL.pdf
  - Програмування на JAVA з використанням OpenGL : https://www.cl.cam.ac.uk/teaching//1617/AdvGraph/Printable%20(2016-2017)%20(1-up).pdf
  
Книги:

  - OpenGL для Android: https://doc.lagout.org/programmation/OpenGL/Pro%20OpenGL%20ES%20for%20Android%20%5BSmithwick%20%26%20Verma%202012-01-24%5D.pdf
  
  - OpenGL ES 2.0 для Android: 
  https://doc.lagout.org/programmation/OpenGL/OpenGL%20ES%202%20for%20Android_%20A%20Quick-Start%20Guide%20%5BBrothaler%202013-07-06%5D.pdf

## Лекції 11-12. Засоби кросплатформного програмування.
1. Xamarin
1. JQuery Mobile
1. Unity 3D
1. Проектування Web-сайтів для мобільних пристроїв.

## Лекції 13-14. Розроблення для платформи iOS

1. Основи мов програмування Objective-C і Swift
1. Розроблення засобів користувацького інтерфейсу для iOS.
1. Програмування для iOS: основні фреймфорки і технології

## Лекція 15. Маркетинг мобільних додатків
1. Ідеї та гіпотези.
1. Верифікація гіпотез.
1. Визначення ключового клієнта.
1. Визначення каналів просування.
1. Оцінка доцільності виходу на ринок.

### **README: Android WebView APK для отображения сайта RestroReserve**

---

## **Описание**
Это Android-приложение для отображения сайта [RestroReserve](https://restroreserve.com) с использованием WebView. Приложение создано в Android Studio и позволяет пользователям легко получить доступ к сайту через удобный интерфейс.

---

## **Функционал**
- Открытие сайта [RestroReserve](https://restroreserve.com) внутри приложения.
- Интеграция с WebView для работы с веб-контентом.
- Поддержка JavaScript.
- Обработка загрузки страниц и ошибок подключения.
- Адаптация для портретной и ландшафтной ориентации.

---

## **Технологии**
- **Язык разработки:** Java / Kotlin  
- **Среда разработки:** Android Studio  
- **Минимальная версия Android:** (API Level 31)  

---

## **Установка**

### 1. Клонирование репозитория
```bash
git clone https://github.com/Kudzeri/mobile-restroReserve.git
cd mobile-restroReserve
```

### 2. Открытие проекта
1. Откройте Android Studio.
2. Нажмите **File > Open**.
3. Выберите папку с проектом.

### 3. Настройка
Проверьте и измените базовый URL сайта в файле `MainActivity.java` (или `MainActivity.kt`):  
```java
webView.loadUrl("https://deyvalst.github.io/service/front/");
```

### 4. Сборка и запуск
1. Подключите Android-устройство или эмулятор.
2. Нажмите **Run > Run 'app'** в Android Studio.

---

## **Файловая структура**

```plaintext
.
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/restroreserve/
│   │   │   │   ├── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── values/
│   │   │   │   │   └── strings.xml
├── build.gradle
├── AndroidManifest.xml
```


---

## **Сборка APK**

### 1. Генерация дебаг-APK
В Android Studio:
1. Нажмите **Build > Build APK(s)**.
2. APK будет сохранён в папке `/app/build/outputs/apk/debug`.

### 2. Генерация релиз-APK
1. Нажмите **Build > Generate Signed APK**.
2. Следуйте инструкциям для создания подписанного APK.

---

## **Лицензия**
MIT  

---


ESPHome Project: Smart Fan Control for Recuperator
This project uses ESPHome to control a recuperator fan, including manual speed adjustment with a rotary encoder, a timed boost mode, and a configurable day/night mode. It integrates with Home Assistant via MQTT.

Features
Rotary Encoder Control: Smoothly adjust fan speed from 0 to 50.

Push Button:

Single Click: Turns the fan on/off.

Double Click: Activates a 30-speed boost mode for a configurable duration.

Automated Day/Night Mode: Automatically switches between pre-defined day and night speeds based on the time of day.

MQTT Integration: All controls and statuses are available via MQTT for seamless integration with Home Assistant.

OTA Updates: Allows for over-the-air firmware updates.

Components
ESP8266 (D1 Mini Lite): The microcontroller unit.

Rotary Encoder: For manual fan speed control.

PWM Output (D5): Controls the fan motor speed.

Time Sync: Uses SNTP to get the current time for day/night mode.




ESPHome Проєкт: Розумне керування вентилятором рекуператора
Цей проєкт використовує ESPHome для керування вентилятором рекуператора, включаючи ручне регулювання швидкості за допомогою роторного енкодера, режим прискорення з таймером та налаштовуваний денний/нічний режим. Проєкт інтегрується з Home Assistant через MQTT.

Функції
Керування роторним енкодером: Плавне регулювання швидкості вентилятора від 0 до 50.

Кнопка:

Одинарне натискання: Вмикає/вимикає вентилятор.

Подвійне натискання: Активує режим прискорення на швидкості 30 на налаштований час.

Автоматичний денний/нічний режим: Автоматично перемикає між заздалегідь визначеними денними та нічними швидкостями в залежності від часу доби.

Інтеграція з MQTT: Усі елементи керування та статуси доступні через MQTT для безшовної інтеграції з Home Assistant.

OTA оновлення: Дозволяє оновлювати прошивку по повітрю.

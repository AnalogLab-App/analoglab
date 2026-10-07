# Analog.Lab

Бесплатное приложение для Android для тех, кто сам проявляет плёнку и печатает фотографии: **таймер проявки**, **таймер фотопечати с красным режимом** и **экспонометр**.

Без рекламы, без регистрации и без интернета: у приложения нет разрешения на доступ к сети, все данные остаются на твоём телефоне.

## Что умеет

**Проявка**
- Чёрно-белая плёнка, C-41 и ECN-2. Готовых рецептов в приложении нет: ты сам собираешь пресет из шагов с цифрами из инструкции к своей химии.
- Агитация отрезками: непрерывная, периодическая, один раз (стенд). Подсказки голосом, звуком и вибрацией.
- Таймер работает при погасшем экране и свёрнутом приложении.
- Расчёт объёмов растворов под твой бачок, таблица «температура → время» для цветной химии.
- Журнал проявок, заметки о химии, обмен пресетами файлом.

**Печать**
- Красный режим: чисто красный на чёрном, без белых вспышек и без клавиатуры.
- Экспозиция с отсчётом 3-2-1 и метрономом, тест-полоски (открывая и закрывая), несколько листов в ваннах одновременно, общая промывка.
- Тест на вуаль для экрана телефона.

**Замер**
- Экспонометр по камере телефона, в том числе точечный, и по датчику освещённости (падающий свет).
- Равноценные пары с приоритетом диафрагмы или выдержки, профили твоих камер с их настоящими выдержками и диафрагмами.
- Калибровка по любому эталону, гистограмма, дальномер (на телефонах, где камера это поддерживает).

Интерфейс на русском и английском. Внутри приложения есть подробный гайд и ЧаВо.

## Установка

Нужен Android 8.0 или новее.

1. Открой страницу [Releases](../../releases) и скачай файл `AnalogLab-….apk` из последней версии.
2. Открой скачанный файл. Если телефон спросит разрешение на установку из этого источника (браузера или «Файлов»), разреши его.
3. Если Google Play Protect предупредит о приложении от неизвестного разработчика, выбери «Подробнее» и «Всё равно установить». Такое предупреждение появляется у любого приложения, которого нет в Google Play.

## Обновление

Новые версии ставятся поверх старой, данные сохраняются. Для этого все версии должны быть подписаны одним ключом: так подписаны и сборки отсюда, и сборки из RuStore.

Если у тебя стоит сборка с другой подписью, сначала сохрани копию данных («Настройки» → «Сохранить всё в файл»), удали её, поставь эту и загрузи копию.

## Проверка файла

В описании каждого релиза указана контрольная сумма SHA-256. Если хочешь убедиться, что файл не подменили, посчитай её у скачанного APK и сравни.

На Windows, в PowerShell:

```
Get-FileHash .\AnalogLab-1.1.2.apk -Algorithm SHA256
```

## Конфиденциальность

Приложение ничего не собирает и никуда не отправляет. Камера нужна только для замера света на самом телефоне, кадры не сохраняются. Подробности: [политика конфиденциальности](https://telegra.ph/Politika-konfidencialnosti-AnalogLab-10-07).

## Поддержать автора

Приложение бесплатное и останется таким. Если оно пригодилось и хочется сказать спасибо, можно отправить любую сумму через [CloudTips](https://pay.cloudtips.ru/p/350fcc89). Никакие функции от этого не открываются.

## Вопросы и ошибки

Если что-то работает не так, напиши во вкладке [Issues](../../issues): укажи модель телефона, версию Android и что делал.

---

# Analog.Lab (English)

A free Android app for people who develop their own film and make darkroom prints: a **film development timer**, a **darkroom printing timer with a red mode**, and a **light meter**.

No ads, no sign-up, and no internet: the app has no network permission, and all your data stays on your phone.

- **Develop** — black & white, C-41 and ECN-2. You build your own presets from your chemistry's instructions. Voice, beep and vibration prompts; keeps timing with the screen off.
- **Print** — a pure red-on-black mode, exposure with count-in and metronome, test strips, several sheets in the trays at once.
- **Meter** — camera and incident light metering, equivalent exposures, camera profiles, calibration.
- English and Russian interface, with a built-in guide and FAQ.

**Install:** Android 8.0 or newer. Download the latest `.apk` from [Releases](../../releases), open it, and allow installing from this source if asked. If Google Play Protect warns about an unknown developer, choose "More details" and "Install anyway".

**Privacy:** the app collects and sends nothing. See the [privacy policy](https://telegra.ph/AnalogLab-Privacy-Policy-10-07).

**Support:** the app is free and will stay free. If it is useful to you, you can send any amount via [CloudTips](https://pay.cloudtips.ru/p/350fcc89). Nothing is unlocked by donating.

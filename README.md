# ApexRPC

Лобби            |  В матче
:-------------------------:|:-------------------------:
![](https://cdn.discordapp.com/attachments/694905810077351956/981969285767381053/Screenshot_5.png)  |  ![](https://cdn.discordapp.com/attachments/694905810077351956/981969286136483910/Screenshot_6.png)

## Описание

ApexRPC - это приложение, конфертирующее [Steam Rich Presence](https://partner.steamgames.com/doc/features/enhancedrichpresence) в [Discord Rich Presence](https://discord.com/rich-presence) для Apex Legends, написан на Node.js.

## Использование

- Клонируйте этот репозиторий или загрузите последнюю версию со страницы [релизов](https://github.com/Holfz/ApexRPC/releases)
- Распакуйте zip-файл
- Сделайте копию файла `.env.example`, а затем переименуйте его в `.env`
- Откройте `.env` файл в любом текстовом редакторе,
   - `ВашЛогинСтим` - Вместо этого впишите ваш логин от Steam.
   - `ВашПарольСтим` - Вместо этого впишите ваш пароль от аккаунта Steam (Не волнуйтесь, мы не передаём и не используем ваши данные). 
- Если же вы клонировали этот репозиторий
   - Убедитесь, что [Node.js](https://nodejs.org/en/) установлен
   - Откройте терминал
   - Выполните команду `npm install`
   - Выполните команду `node main.js`
- Если же вы загрузили исполняемый .exe файл
   - Запустите `ApexRPC.exe`
- Приложение запросит ваш код Steam Guard, если он есть
- Запустите Apex Legends

### Всё равно не понятно? Тогда держите детальную инструкцию в видео:

https://user-images.githubusercontent.com/32639831/143059780-29ca2bad-4a13-4b61-9483-290c756a791e.mov

### Параметры (.env)
| Параметр                | Требуется | Описание                                                                                               |
|--------------------------|:--------:|-----------------------------------------------------------------------------------------------------------|
| STEAM_USERNAME           |    ✔     | Ваш логин Steam                                                                                      |
| STEAM_PASSWORD           |    ✔     | Ваш пароль Steam                                                                                      |
| LOG_LEVEL                |    ✕     | Минимальный уровень журнала для создания. Значения `debug`, `info`, `silly`, `warn` и `error`. По умолчанию `info`. |
| LAUNCH_APEX_IF_NESSESARY |    ✕     | Если Steam установлен, то должен ли ApexRPC запустить Apex Legends?. По умолчанию `false`. Используйте `true` для активации параметра                 |

## Важное предупреждение

Никому не отправляйте свой файл `.env`

Мы повторим...

Никому НЕ отправляйте свой файл `.env`, даже своим друзьям.

Повторимся ещё раз...

НИКОМУ НЕ ОТПРАВЛЯЙТЕ СВОЙ ФАЙЛ `.env`, даже своим родителям.

## Примечания
- Все изображения, значки и торговые марки принадлежат их соответствующим владельцам.
- Этот проект не связан с EA / Respawn / EAC или кем-либо из его сотрудников.
- Apex Legends является зарегистрированной торговой маркой EA. Игровые активы, материалы и иконки принадлежат Electronic Arts.
- EA и Respawn не поддерживают этот проект и не несут за него ответственности.
- Разработчик приложения: [Holfz](https://github.com/Holfz)
- Оригинальная страница проекта: [ApexRPC](https://github.com/Holfz/ApexRPC)
- Переводом и локализацией приложения и описания с английского языка на русский язык занимался: [Bayori](https://github.com/Bayori)

## Возможные ошибки
- При игре в режиме "Арены" возможен краш приложения. Обращайтесь к [Holfz](https://github.com/Holfz)
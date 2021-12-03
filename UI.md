# Проектирование интерфейсов (музыкальный бот для дискорд)

### 1. Список интерфейсов
- **Неавторизованный пользователь**:
- [ ] Начальная страница
- [ ] Авторизация
- **Пользователь**:
- [ ] Выбор сервера
- [ ] Плеер (с возможностью добавлять треки в очередь)
- [ ] История запуска треков (на конкретном сервере)
- **Модератор**:
- [ ] Выбор сервера
- [ ] Плеер (с возможностью добавлять треки в очередь, управлять воспроизведением, пропускать и удалять треки из очереди)
- [ ] История запуска треков (на конкретном сервере)
- **Администратор**:
- [ ] Выбор сервера
- [ ] Плеер (с возможностью добавлять треки в очередь, управлять воспроизведением, пропускать и удалять треки из очереди)
- [ ] История запуска треков (на конкретном сервере)
- [ ] Настройки (на конкретном сервере)

### 2. Эскизы интерфейсов
#### Начальная страница:
![ER](https://media.discordapp.net/attachments/755814596383735848/916221273376428082/main.png?width=737&height=553)
#### Авторизация (через формы Discord):
![ER](https://media.discordapp.net/attachments/755814596383735848/916221774075691018/Auth_1.png)
![ER](https://media.discordapp.net/attachments/755814596383735848/916221273162534952/Auth_2.png)

#### Выбор сервера:
![ER](https://media.discordapp.net/attachments/755814596383735848/916235076877029416/server.png)
#### Плеер (для пользователя):
![ER](https://media.discordapp.net/attachments/755814596383735848/916235078143733770/player_user.png)
#### Плеер (для модератора и админа):
![ER](https://media.discordapp.net/attachments/755814596383735848/916235077946597395/player.png)
#### История:
![ER](https://media.discordapp.net/attachments/755814596383735848/916235077468442714/history.png)
#### Настройки:
![ER](https://media.discordapp.net/attachments/755814596383735848/916235077149683732/settings.png)

(У пользователей и модераторов вкладка "Настройки" в меню отображаться не будет)

### 3. Диаграмма пользовательских сценариев

#### Неавторизованный пользователь:
![ER](https://media.discordapp.net/attachments/755814596383735848/916243876031918131/18gYRxVAygmBQMBhEqCLJECAAAECBAgQIECAAAECBAgQIECAAAECBL4EHCZfe2hDgAABAgQIECBAgAABAgQIECBAgAABAgQIBAIOkwBdJAECBAgQIECAAAECBAgQIECAAAECBAgQIPAl4DD52kMbAgQIECBAgAABAgQIECBAgAABAgQIECBAIBBwmAToIgkQIECAAAECBAgQIECAAAECBAgQIECAAIEvAYfJ1x7aECBAgAABAgQIECBAgAABAgQIECBAgAABAoGAwyRAF0mAAAECBAgQIECAAAECBAgQIECAAAECBAh8CThMvvbQhgABAgQIECBAgAABAgQIECBAgAABAgQIEAgEHCYBukgCBAgQIECAAAECBAgQIECAAAECBAgQIEDgS8Bh8rWHNgQIECBAgAABAgQIECBAgAABAgQIECBAgEAgMDkv6PwmJrBQAAAAAElFTkSuQmCC.png?width=462&height=553
)

#### Пользователь/модератор:

![ER](https://media.discordapp.net/attachments/755814596383735848/916243946416513024/7Tzikgx2rAAAAAElFTkSuQmCC.png?width=573&height=553
)

(В плеере у модератора есть дополнительные возможности управлять воспроизведением)


#### Администратор:
![ER](https://media.discordapp.net/attachments/755814596383735848/916245170196983838/zawUAAAAASUVORK5CYII.png?width=629&height=553
)


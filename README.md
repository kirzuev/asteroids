# Asteroids (English desciption)

Game `Asteroids`

You are invited to play for the spaceship with name `Player`. Against you play agressive bots named `Bot`.
Your goal: destroy asteroids, kill bots and collect the bonuses to survive.

How to play: 

`Up`, `Down`, `Left`, `Right` - spaceship control

`Space` - press and hold it for start shooting, release for stop it.

`Tab` - display the game statistics.

`Enter` - restart the game.

Bonuses: reduce/increase spaceship speed (signs of speed limit/speed limit cancellation), change weapon (star blaster),
refueling (canister), remove all asteroids and bonuses from game field (holy grenade), reduce asteroids speed (barrier),
invulnerable protective screen (shield).


![Asteroids.](images/sd.gif)


[![Build Status](https://travis-ci.org/cmc-haskell-2017/project-template.svg?branch=master)](https://travis-ci.org/cmc-haskell-2017/project-template)


## Build and launch

Build the project with [Stack utility](https://www.haskellstack.org):

```
stack setup
stack build
```

Build and launch sigle game with commands:

```
stack build && stack exec asteroids
```

Build and launch multiplayer server with commands: (port number is set as Int number, for example, 8000)

```
stack build && stack exec asteroids-server <port number>
```

Build and launch multiplayer client with commands: (IP-adress is set as String, for example, "192.1.0.0")

```
stack build && stack exec asteroids-client <server IP-adress> <server port number>
```

To launch GHCi interpreter and automatically load all project modules us a command:

```
stack ghci
```


# Asteroids (описание на русском языке)

Игра `Астероиды`

Вам предложено сыграть за корабль с именем `Player`. Против Вас играют агрессивные боты `Bot`. 
Ваша задача: убивать астероиды, убивать ботов, собирать бонусы для того, чтобы выжить.

Как играть: 

`Up`, `Down`, `Left`, `Right` - управление кораблем

`Space` - при нажатии корабль стреляет, при отпускании стрельба прекращается

`Tab` - показать статистику игры

`Enter` - начать игру заново

Действующие бонусы: понижение/повышение скорости корабля (знаки ограничения скорости/снятия ограничений), смена оружия (звездный бластер),
подзаправка топливом (канистра), удаление всех астероидов и бонусов с игрового поля (святая граната), понижение скорости астероидов (барьер),
защитный экран неуязвимости (щит).


![Астероиды.](images/sd.gif)


[![Build Status](https://travis-ci.org/cmc-haskell-2017/project-template.svg?branch=master)](https://travis-ci.org/cmc-haskell-2017/project-template)


## Сборка и запуск

Соберите проект при помощи [утилиты Stack](https://www.haskellstack.org):

```
stack setup
stack build
```

Собрать и запустить одиночную игру можно при помощи команды

```
stack build && stack exec asteroids
```

Собрать и запустить сервер можно при помощи команды (номер порта задается в виде числа типа Int, например, 8000)

```
stack build && stack exec asteroids-server <номер порта>
```

Собрать и запустить клиент можно при помощи команды (IP-адрес задается в виде строки типа String, например, "192.1.0.0")

```
stack build && stack exec asteroids-client <IP-адрес сервера> <номер порта сервера>
```

Чтобы запустить интепретатор GHCi и автоматически подгрузить все модули проекта, используйте команду

```
stack ghci
```


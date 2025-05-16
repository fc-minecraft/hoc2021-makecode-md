### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Первый компьютерный учёный (Отладка)

## Step 1
В приведённом ниже коде есть ошибка. Нажми зелёную кнопку, чтобы запустить его и посмотреть, что произойдёт, а затем отладь его, чтобы увидеть, что не так, и какие изменения нужны, чтобы он заработал.

#### ~ tutorialhint
Используй перемещение агента и поворот агента, чтобы переместить своего Агента к каждому КОРИЧНЕВОМУ блоку. Затем используй разрушение в направлении, в котором ты хочешь разрушить блок, чтобы убрать КОРИЧНЕВЫЙ блок. Повторяй это, пока все КОРИЧНЕВЫЕ блоки не будут разрушены.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(FORWARD, 1)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.turn(LEFT_TURN)
agent.move(FORWARD, 2)
agent.turn(LEFT_TURN)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
agent.move(FORWARD, 2)
agent.destroy(UP)
```
```package
```

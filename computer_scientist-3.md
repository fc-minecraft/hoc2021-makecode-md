### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Первый компьютерный учёный (Решение)

## Step 1
Приведённый ниже код является правильным решением задания. Запусти код, нажав зелёную кнопку, чтобы увидеть его в действии.

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
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 2)
agent.turn(RIGHT_TURN)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
agent.move(FORWARD, 2)
agent.destroy(DOWN)
```
```package
```

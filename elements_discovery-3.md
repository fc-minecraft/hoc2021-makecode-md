### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Элементы открытия (Решение)

## Step 1
Приведённый ниже код является правильным решением задания. Запусти код, нажав зелёную кнопку, чтобы увидеть его в действии.

#### ~ tutorialhint
Используй перемещение агента и поворот агента, чтобы переместить своего Агента к зелёным светящимся книжным шкафам. Используй разрушение в направлении, в котором ты хочешь разрушить блок зелёного светящегося книжного шкафа. Повторяй это, пока 3 блока книжных шкафов не будут разрушены.


```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
agent.move(UP, 1)
agent.move(FORWARD, 4)
agent.destroy(LEFT)
```
```package
```

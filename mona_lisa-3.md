### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Мона Лиза (Решение)

## Шаг 1
Ниже приведён правильный код для решения задачи. Запусти код, нажав зелёную кнопку воспроизведения, чтобы увидеть его в действии.

#### ~ tutorialhint
Используй перемещение агента, чтобы переместить своего агента, затем размещение, чтобы разместить белый глазурованный терракот, который мы дали агенту. Повторяй перемещение агента и размещение, пока не будет размещено правильное количество блоков.


```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(RIGHT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 5; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)
}
agent.turn(RIGHT_TURN)
for (let index = 0; index < 5; index++) {
    agent.move(FORWARD, 1)
    agent.place(DOWN)    	
}
```
```package
```

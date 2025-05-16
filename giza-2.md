### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Великая пирамида в Гизе (Отладка)

## Step 1
В приведённом ниже коде есть ошибка. Нажми зелёную кнопку воспроизведения, чтобы запустить его и посмотреть, что произойдёт, а затем отладь его, чтобы увидеть, что не так, и какие изменения нужны, чтобы он заработал.

#### ~ tutorialhint
Подумай, как Агенту нужно двигаться, чтобы разместить правильное количество блоков для каждого уровня пирамиды. Используй блок перемещения агента, чтобы переместить своего Агента вперёд, и для каждого шага используй размещение, чтобы РАЗМЕСТИТЬ `Гладкий песчаник`, который мы дали Агенту.


```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index=0); index < 3; index++){
agent.move(FORWARD, 1)
agent.place(BACK)
}
agent.move(UP, 1)
agent.turn(LEFT_TURN)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.move(FORWARD, 1)
agent.place(UP)
```
```package
```

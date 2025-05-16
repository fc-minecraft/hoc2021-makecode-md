### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Биг-бэнд джаз (Решение)

## Step 1
Приведённый ниже код является правильным решением задания. Запусти код, нажав зелёную кнопку, чтобы увидеть его в действии.

#### ~ tutorialhint
Перетащи перемещение агента в блок при старте, чтобы дать инструкции своему Агенту, как двигаться. Посчитай, как далеко и в каком направлении Агенту нужно двигаться, и используй блок перемещения агента с направлением (ВВЕРХ, ВНИЗ, ВЛЕВО, ВПРАВО) и расстоянием, чтобы переместиться к трубе. В конце своего кода используй сбор всех, чтобы собрать трубу.

```ghost
    agent.move(FORWARD, 0)
    agent.collectAll()
```
```template
agent.move(FORWARD, 3)
agent.move(UP, 1)
agent.move(FORWARD, 2)
agent.move(DOWN, 2)
agent.move(FORWARD, 2)
agent.move(UP, 2)
agent.move(FORWARD, 1)
agent.collectAll()

```
```package
```

### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Палеонтологическая головоломка (Решение)

## Шаг 1
Ниже приведён правильный код для решения задачи. Запусти код, нажав зелёную кнопку воспроизведения, чтобы увидеть его в действии.
#### ~ tutorialhint
Используй перемещение агента, чтобы переместить своего агента, затем разрушение в направлении, в котором ты хочешь разрушить оранжевые блоки, и размещение, чтобы разместить блок кости, который мы дали агенту. Повторяй это, пока не будет размещено правильное количество блоков.

```ghost
    agent.move(FORWARD, 0)
    agent.destroy(FORWARD)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 4; index++) {
    agent.move(FORWARD, 2)    
    agent.destroy(DOWN)
    agent.place(DOWN)
}
```
```package
```

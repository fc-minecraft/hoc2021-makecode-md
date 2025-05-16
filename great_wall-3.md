### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Великая Китайская стена (Решение)

## Step 1
Приведённый ниже код является правильным решением задания. Запусти код, нажав зелёную кнопку воспроизведения, чтобы увидеть его в действии.

#### ~ tutorialhint
Используй блок перемещения агента, чтобы расположить своего Агента, и размещение, чтобы РАЗМЕСТИТЬ `Бамбук`, который мы дали Агенту.


```ghost
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 5; index++) {
    agent.place(DOWN)
    agent.move(FORWARD, 1)
}
```
```package
```

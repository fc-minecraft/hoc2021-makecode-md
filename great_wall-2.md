### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Великая Китайская стена (Отладка)

## Step 1
В приведённом ниже коде есть ошибка. Нажми зелёную кнопку, чтобы запустить его и посмотреть, что произойдёт, а затем отладь его, чтобы увидеть, что не так, и какие изменения нужны, чтобы он заработал.

#### ~ tutorialhint
Используй блок перемещения агента, чтобы расположить своего Агента, и размещение, чтобы РАЗМЕСТИТЬ `Бамбук`, который мы дали Агенту.


```ghost
    agent.place(FORWARD)
    agent.move(FORWARD, 0)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 3; index++) {
    agent.place(UP)
    agent.move(BACK, 1)
}
```
```package
```

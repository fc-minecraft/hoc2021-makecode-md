### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Первый полёт (Отладка)

## Step 1
В приведённом ниже коде есть ошибка. Нажми зелёную кнопку, чтобы запустить его и посмотреть, что произойдёт, а затем отладь его, чтобы увидеть, что не так, и какие изменения нужны, чтобы он заработал.

#### ~ tutorialhint
Используй перемещение агента, чтобы отправить своего Агента к яме. Заполни каждую яму, используя размещение, чтобы РАЗМЕСТИТЬ блок `Земли`, который мы дали Агенту. Повторяй перемещение агента и размещение, пока все ямы не будут заполнены.

```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 3; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(UP)    	
}
```
```package
```

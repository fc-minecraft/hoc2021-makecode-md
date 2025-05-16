### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Первый полёт (Решение)

## Step 1
Приведённый ниже код является правильным решением задания. Запусти код, нажав зелёную кнопку воспроизведения, чтобы увидеть его в действии.

#### ~ tutorialhint
Используй перемещение агента, чтобы отправить своего Агента к яме. Заполни каждую яму, используя размещение, чтобы РАЗМЕСТИТЬ блок `Земли`, который мы дали Агенту. Повторяй перемещение агента и размещение, пока все ямы не будут заполнены.


```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2)  
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
agent.move(FORWARD, 2)  
agent.move(RIGHT, 2) 
for (let index = 0; index < 2; index++) {
    agent.move(FORWARD, 1)    	
    agent.place(DOWN)    	
}
```
```package
```

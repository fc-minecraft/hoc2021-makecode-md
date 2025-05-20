### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Миссия Луна (Решение)

## Шаг 1
Ниже приведён правильный код для решения задачи. Запусти код, нажав зелёную кнопку воспроизведения, чтобы увидеть его в действии.

#### ~ tutorialhint
Используй блоки перемещения агента и поворота агента внутри блока при старте, чтобы доставить расчёты к космическому модулю. Используй расчёты математика, чтобы определить путь, по которому должен следовать агент. Вперёд 25, вправо 17 и вниз 3.

```ghost
    agent.move(FORWARD, 0)
    agent.turn(RIGHT_TURN)
```
```template
agent.move(FORWARD, 25)
agent.turn(RIGHT_TURN)
agent.move(FORWARD, 17)
agent.turn(RIGHT_TURN)
agent.move(DOWN, 3)
```
```package
```

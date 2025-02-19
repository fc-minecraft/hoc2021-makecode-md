### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Great Pyramid at Giza

## Step 1
ساعد المهندس المعماري في إكمال الشكل  المثلث،  وهو تصميم سيصمد أمام اختبار الزمن. فكر في كيفية إنشاء مثلث. هناك مستويان إضافيان مطلوبان: 3 بلوكات في القاعدة، وبلوك واحد في القمة.

#### ~ tutorialhint  
فكر في كيفية تحرك الروبوت لوضع العدد المناسب من البلوكتن لكل مستوى من مستويات الهرم. استخدم الـ``||agent:وكيل ينقل||`` استخدم المفتاح "ock" لتحريك الروبوت للأمام، وفي كل خطوة استخدم ``||agent:وكيل يضع||`` لوضع الـ `Smooth Sandstone` الذي قدمناه للروبوت.


```ghost
    agent.move(FORWARD, 0)
    agent.place(FORWARD)
    agent.turn(LEFT_TURN)
    for (let index = 0; index < 4; index++) {
    	
    }
```
```template
\\
```
```package
```

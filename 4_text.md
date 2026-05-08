Файл 4 c кодом
------

#Фрагмент кода java


```java
public class HelloWorld {
    public static void main(String args) {
        System.out.println("Hello, World!");
    }
}
``` 

#Текстовая картинка


<code>GameApplication (extends Application)

├── GameModel (данные игры)
│   ├── scoreProperty: IntegerProperty
│   ├── gameActiveProperty: BooleanProperty
│   ├── ballSpeedProperty: IntegerProperty (интервал в мс)
│   └── ballPosition: Point2D.DoubleProperty
│   └── timer: Timer
│   └── gameLogic методы
├── GameView (UI)
│   ├── gamePane: Pane (игровое поле)
│   ├── ball: Circle (Shape компонент)
│   │   ├── fill: RadialGradient (для объема)
│   │   ├── stroke: цвет обводки
│   │   └── centerX/Y: привязка к свойствам модели
│   ├── scoreLabel: Label (привязка к scoreProperty)
│   └── statusLabel: Label (привязка к gameActiveProperty)
└── GameController (логика и обработка)
│   ├── eventHandlers
│   ├── gameModel: GameModel
└── 
</code>
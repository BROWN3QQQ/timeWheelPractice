# timeWheelPractice
时间轮源码练习







timer-java/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── timer/
│   │   │   │   ├── exception/
│   │   │   │   │   └── TimerException.java
│   │   │   │   ├── model/
│   │   │   │   │   ├── MinHeapNode.java
│   │   │   │   │   ├── TimeNode.java
│   │   │   │   │   └── TimeWheelNode.java
│   │   │   │   ├── structure/
│   │   │   │   │   ├── MinHeap.java
│   │   │   │   │   └── TimeWheel.java
│   │   │   │   ├── utils/
│   │   │   │   │   └── TimeUtils.java
│   │   │   │   ├── Timer.java
│   │   │   │   └── TimerFactory.java
│   │   │   └── Main.java   // 用于演示和测试
│   │   └── resources/
│   └── test/
│       ├── java/
│       │   ├── timer/
│       │   │   ├── structure/
│       │   │   │   ├── MinHeapTest.java
│       │   │   │   └── TimeWheelTest.java
│       │   │   └── TimerTest.java
│       └── resources/
└── pom.xml   // Maven配置文件

# HOW TO USE ALL OF COMPONENTS AND SENSORS OF JOY IT ?

![curl screenshot](![image](https://github.com/user-attachments/assets/61fa3ee0-ec86-44a5-83b0-255c72bd1169))


--> In fact, it depends on the type of component that you want to use because there are 2 types : Input and Output components. When we want to use an Input Component, we use **BCM MODE**. However, when we chose Output Component, we use **BOARD MODE**. For example, I would like to use the vibrator sensor as a alarm clock. This sensor is an output sensor and I need to switch off all of the switches excepted the 1 of the right block (ON)
    
```python
GPIO.setmode(GPIO.BCM)

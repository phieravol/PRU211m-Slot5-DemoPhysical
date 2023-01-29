# PRU211m - Slot5 : Demo addForce & Move GameObject by Force

## 1. Environment

 - Unity
 - Asp.net6
 - Visual studio 2022

## 2. Step by Step

 1.  Get gameobject & Rigidbody2d 
 2. 

### 2.1. Get GameObject

  **[#1 [GameObject](https://docs.unity3d.com/ScriptReference/GameObject.html).Find("objectName") ]** 
  

 - Hữu ích khi tự động kết nối với các game object khác tại thời điểm tải, bên trong [MonoBehaviour.Awake](https://docs.unity3d.com/ScriptReference/MonoBehaviour.Awake.html) hoặc [MonoBehaviour.Start](https://docs.unity3d.com/ScriptReference/MonoBehaviour.Start.html).
 - VD:

        private GameObject hand;  
      
        void Start()
        {
            hand = GameObject.Find("/Monster/Arm/Hand");
        }  
      
        void Update()
        {
            hand.transform.Rotate(0, 100 * Time.deltaTime, 0);
        }
 
**[#1 [GameObject](https://docs.unity3d.com/ScriptReference/GameObject.html).Find("objectName") ]** 
 
### 2.2. Get GameObject

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands

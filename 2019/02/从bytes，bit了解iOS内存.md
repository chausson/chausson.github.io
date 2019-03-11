## 从bytes，bit了解iOS内存

bytes是什么
bit是什么


iOS中基础类型的字节知识



``` objective-c
    int a = 3;
    char *aa = (char *)&a;
    char aChar[4] = {0};
    for(int i= 0 ;i < 4 ;i++){
        aChar[i] = *aa;
        aa ++;
    }
```
           
           二进制数据流
           数据流的异或和位移
           图片的二进制流
           16进制和bytes的转换
           bytes的存储
           计算机的组成和原理
                                                 

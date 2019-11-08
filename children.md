Binary: 10110110 <br>
Hex:    b6 <br>

```java
// java code
public byte children = 0xb6;
public byte childA;
public byte childB;
public byte childC;
public byte childD;
public byte childE;
public byte childF;
public byte childG;
public byte childH;

public void set(byte children) {
    childA = (byte) (children & 0x01);
    children >>= 1;
    childB = (byte) (children & 0x01);
    children >>= 1;
    childC = (byte) (children & 0x01);
    children >>= 1;
    childD = (byte) (children & 0x01);
    childE = (byte) (children & 0x01);
    children >>= 1;
    childF = (byte) (children & 0x01);
    children >>= 1;
    childG = (byte) (children & 0x01);
    children >>= 1;
    childH = (byte) (children & 0x01);
}
```

# BaseStrategyGame



## Learn to use

UMP

UI
* Grid Layout Group


delegate
event
general

## Someting New

Edit -> Project Setting -> Script Execution Order 可以調整程式優先度

Ragdoll

ProBuilder

### 程式方面
```csharp
[SerializeField] private LayerMask mousePlaneLayerMask;
```

## 快捷鍵

Ctrl + Shift + F =>  將攝影機 重新定位 到場景攝影機所在的位置
    * 等同於 Gameobject => align with view

## Note

raycast 是看 collider , 如果mesh renderer 關掉 collider依舊開著  Debug.Log(Physics.Raycast(ray)); 會返回true



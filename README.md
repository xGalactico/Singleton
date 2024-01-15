# Singleton
Singleton&lt;T> For Unity3D;

```csharp
public class YourClass : Singleton<YourClass>
{
  public int UltimateFunction(int a, int b)
  {
    return a + b;
  }
}

/*
call
*/
public class AnotherClass : MonoBehaviour
{
    private void Start()
    {
        int result = YourClass.Instance.UltimateFunction(2, 2);
        Debug.Log(result);
    }
}
```

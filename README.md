# Unity Mobile Message

Simple class that pops an iOS alert or an Android toast depending on what platform the code is running.

Usage example:

```csharp

public class Foo : MonoBehaviour
{
    private void Start()
    {
        MobileMessage.ShowAlert("Title","Message");
    }
}

```

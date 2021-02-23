# Unity Mobile Message

Simple class that pops an iOS alert, an Android toast or an editor log, depending on what platform the code is running.

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

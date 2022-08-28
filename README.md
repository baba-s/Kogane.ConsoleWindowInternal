# Kogane Console Window Internal

Console ウィンドウの internal な機能を呼び出せるようにするクラス

## 使用例

```cs
using Kogane;
using UnityEditor;

public class Example
{
    [MenuItem( "Tools/Hoge" )]
    private static void Hoge()
    {
        // Console ウィンドウでログを検索
        ConsoleWindowInternal.SetFilter( "ピカチュウ" );
    }
}
```

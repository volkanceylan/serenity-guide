# Int64Field constructor
**namespace:** *[Serenity.Data](../../README.md#serenity.data-namespace)*   **assembly**: *[Serenity.Net.Entity](../../README.md)*

Initializes a new instance of the [`Int64Field`](../Int64Field.md) class.

```csharp
public Int64Field(ICollection<Field> collection, string name, LocalText caption = null, 
    int size = 0, FieldFlags flags = FieldFlags.Default, Func<IRow, long?> getValue = null, 
    Action<IRow, long?> setValue = null)
```

| parameter | description |
| --- | --- |
| collection | The collection. |
| name | The name. |
| caption | The caption. |
| size | The size. |
| flags | The flags. |
| getValue | The get value. |
| setValue | The set value. |

## See Also

* class [Field](../Field.md)
* class [LocalText](../Serenity.Net.Core/../../Serenity/LocalText.md)
* enum [FieldFlags](../Serenity.Net.Data/../FieldFlags.md)
* interface [IRow](../IRow.md)
* class [Int64Field](../Int64Field.md)
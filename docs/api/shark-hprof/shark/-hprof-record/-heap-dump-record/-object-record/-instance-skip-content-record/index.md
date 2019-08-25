[shark-hprof](../../../../../index.md) / [shark](../../../../index.md) / [HprofRecord](../../../index.md) / [HeapDumpRecord](../../index.md) / [ObjectRecord](../index.md) / [InstanceSkipContentRecord](./index.md)

# InstanceSkipContentRecord

`class InstanceSkipContentRecord : `[`HprofRecord.HeapDumpRecord.ObjectRecord`](../index.md)

This isn't a real record type as found in the heap dump. It's an alternative to
[InstanceDumpRecord](../-instance-dump-record/index.md) for when you don't need the instance content.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `InstanceSkipContentRecord(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, stackTraceSerialNumber: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, classId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`)`<br>This isn't a real record type as found in the heap dump. It's an alternative to [InstanceDumpRecord](../-instance-dump-record/index.md) for when you don't need the instance content. |

### Properties

| Name | Summary |
|---|---|
| [classId](class-id.md) | `val classId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [id](id.md) | `val id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [stackTraceSerialNumber](stack-trace-serial-number.md) | `val stackTraceSerialNumber: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

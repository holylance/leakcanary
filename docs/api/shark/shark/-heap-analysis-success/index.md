[shark](../../index.md) / [shark](../index.md) / [HeapAnalysisSuccess](./index.md)

# HeapAnalysisSuccess

`data class HeapAnalysisSuccess : `[`HeapAnalysis`](../-heap-analysis/index.md)

The result of a successful heap analysis performed by [HeapAnalyzer](../-heap-analyzer/index.md).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `HeapAnalysisSuccess(heapDumpFile: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`, createdAtTimeMillis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, analysisDurationMillis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, applicationLeaks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ApplicationLeak`](../-application-leak/index.md)`>, libraryLeaks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LibraryLeak`](../-library-leak/index.md)`>)`<br>The result of a successful heap analysis performed by [HeapAnalyzer](../-heap-analyzer/index.md). |

### Properties

| Name | Summary |
|---|---|
| [allLeaks](all-leaks.md) | `val allLeaks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Leak`](../-leak/index.md)`>`<br>The list of [Leak](../-leak/index.md) found in the heap dump by [HeapAnalyzer](../-heap-analyzer/index.md), ie all [applicationLeaks](application-leaks.md) and all [libraryLeaks](library-leaks.md) in one list. |
| [analysisDurationMillis](analysis-duration-millis.md) | `val analysisDurationMillis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>Total time spent analyzing the heap. |
| [applicationLeaks](application-leaks.md) | `val applicationLeaks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ApplicationLeak`](../-application-leak/index.md)`>`<br>The list of [ApplicationLeak](../-application-leak/index.md) found in the heap dump by [HeapAnalyzer](../-heap-analyzer/index.md). |
| [createdAtTimeMillis](created-at-time-millis.md) | `val createdAtTimeMillis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>The [System.currentTimeMillis](https://docs.oracle.com/javase/6/docs/api/java/lang/System.html#currentTimeMillis()) when this [HeapAnalysis](../-heap-analysis/index.md) instance was created. |
| [heapDumpFile](heap-dump-file.md) | `val heapDumpFile: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)<br>The hprof file that was analyzed. |
| [libraryLeaks](library-leaks.md) | `val libraryLeaks: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`LibraryLeak`](../-library-leak/index.md)`>`<br>The list of [LibraryLeak](../-library-leak/index.md) found in the heap dump by [HeapAnalyzer](../-heap-analyzer/index.md). |

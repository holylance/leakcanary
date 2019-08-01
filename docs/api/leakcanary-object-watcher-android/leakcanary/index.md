[leakcanary-object-watcher-android](../index.md) / [leakcanary](./index.md)

## Package leakcanary

### Types

| Name | Summary |
|---|---|
| [AppWatcher](-app-watcher/index.md) | `object AppWatcher`<br>The entry point API for using [ObjectWatcher](#) in an Android app. [AppWatcher.objectWatcher](-app-watcher/object-watcher.md) is in charge of detecting retained objects, and [AppWatcher](-app-watcher/index.md) is auto configured on app start to pass it activity and fragment instances. Call [ObjectWatcher.watch](#) on [objectWatcher](-app-watcher/object-watcher.md) to watch any other object that you expect to be unreachable. |

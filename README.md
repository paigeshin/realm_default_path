# realm_default_path

```swift
  let _ = Log.info("REALM PATH: \(String(describing: FileManager.default.urls(for: .documentDirectory, in: .userDomainMask).first?.path))")
```

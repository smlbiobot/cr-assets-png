# cr-csv

Clash Royale CSV files decoded from the APK.

This is created for ease of datamining instead of using the full repo at https://github.com/smlbiobot/cr

It was created using this command:

```
find '/path/to/apk/version/assets' -type f -name '*.png' | cpio -pdm .
```

Tags and releases matches the APK versions.

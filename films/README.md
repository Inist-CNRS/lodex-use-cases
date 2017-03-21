# films

The `data.csv` file is a __comma-separated__ CSV, to load it in LODEX, you need to configure the loader in `lodex`'s `config.json`.

```json
  "loader": {
    "csv": {
      "quote": "\"",
      "delimiter": ","
    }
  }
```

The delimiter is `;` by default, set it to `,`.

The `model.json` was exported on version 6.4.0+.
---
title: Help links from an extension
---

## How it works

A Tallmaker extension can open the reader at the right page from its own Help action. The extension writes a short note in the browser session, then moves to the sheet that holds the reader. The reader reads the note once, removes it and opens the page.

Nothing is written to the app, and the address of the page does not change.

## In the extension

The Help action needs the ID of the sheet that holds the reader. Add it as a setting of the extension, for example **Reader sheet ID**. When the setting is empty, or the host has no sheet navigation, link to the docs on the Tallmaker site instead.

```
const entry = 'tm-docs-reader.open';
sessionStorage.setItem(entry, JSON.stringify({ target: 'tm-heat-grid/colours', at: Date.now() }));
navigation.goToSheet(readerSheetId);
```

The target uses the same form as the **Start page** setting. The note lives for two minutes. A reader that is locked to another product leaves the note for the right reader.

# How to Contribute

See this article: [first-contributions](https://github.com/firstcontributions/first-contributions)

## Where to Start

### 1. Makers Translation

Copy the Chinese name as the key name, and enter the translation as the value.

```JavaScript
{
    "categories": {
        // ... Ignore content above and below
        "收容井": "Securement Silo",
        "传送塔": "Teleporter",
    }
}
```

No need to add anything to **zh-CN.js** file. The translation will fallback to the key name, if Chinese translation is missing.

You can also translate all the item names in the **categories**.

### 2. UI Translation

Not all UI texts are added to the **zh-CN.js** and **en.js** file, you need to create new key name for the missing UI text.

You can use English key name for UI translation.

### 3. Add New Language Translations

Create a new file, copy all the contents of the **en.js** file into it, and you can start translating.

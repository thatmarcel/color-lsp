# Zed Color Highlighting

![Zed Extension](https://img.shields.io/badge/-Zed_Extension-blue?style=flat&logo=zedindustries&logoColor=%23FFFFFF&logoSize=auto&labelColor=%23111111&color=%23084CCF)

Show color previews in your editor based on color-lsp by LSP document colors (forked to enable the extension for more languages).

<img width="1285" alt="Screenshot of a Zed editor window with the extension enabled" src="https://github.com/user-attachments/assets/a1a211d9-dec4-440b-8c74-848d7b03ff52" />

## Usage

After installing the extension via `Install Dev Extension`, add the following to your Zed `settings.json`:

```js
{
    // ...
    // "inlay" adds a box next to the color code,
    // "background" changes the color code's background
    "lsp_document_colors": "inlay",
    // ...
}
```

## License

MIT

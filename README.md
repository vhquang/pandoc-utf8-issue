Demonstration of `streamDecodeUtf8With` when converting markdown to PDF. Issue happens with:

```bash
$ pandoc test.md -o test.pdf
# [WARNING] Missing character: pandoc: Cannot decode byte '\xb9': Data.Text.Internal.Encoding.streamDecodeUtf8With: Invalid UTF-8 stream
```

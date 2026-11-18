---
"emdash": minor
"@emdash-cms/cloudflare": minor
---

Adds `jxl` to the formats `<Image>` accepts. `formats={["jxl", "webp"]}` renders a `<source type="image/jxl">` that browsers without JPEG XL skip. The image endpoint answers a `jxl` request in WebP until middleware or a plugin answers it with JPEG XL.

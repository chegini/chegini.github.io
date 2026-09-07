# Fatemeh photo + favicon patch

Copy these three folders into the root of your existing `hugobricks` project:

- `content`
- `data`
- `static`

Choose Merge/Replace when macOS asks, then run:

    hugo server

This patch:
1. adds Fatemeh's uploaded portrait to the homepage hero;
2. stores it at `static/uploads/photos/myphoto.png`;
3. sets `favicon_image` to a real image path, fixing the `$favicon.Resize` nil-pointer error.

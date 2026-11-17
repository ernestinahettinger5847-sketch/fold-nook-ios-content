# Fold Nook iOS content 1.0.0

Original English content used by Fold Nook 1.0. This snapshot contains the full offline catalog, illustrations, tracing overlays, video, paper textures and brand media. It contains 224 lessons, 989 steps and 225 video files.

Check out the `ios-content-v1.0.0` tag to reproduce this snapshot. From the dataset root, run `shasum -a 256 -c SHA256SUMS` to verify the content files. The manifest lists counts and uncompressed byte sizes.

The app build expects `Content` and `Brand` under `FoldNook/Resources`. Retain the catalog IDs and file paths when updating existing lessons so app references and saved progress can still resolve.

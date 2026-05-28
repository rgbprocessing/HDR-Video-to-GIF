# HDR Video to GIF: BT.2020 Tone-Mapped Conversion

This project explores how to convert an HDR-tagged BT.2020 video into a visually similar GIF.

Default video to GIF conversion produces dull GIFs when generated from an HDR video. We used HDR->SDR tone-mapping before generating the GIF palette to produce GIFs much more closely visually aligned with their original HDR videos.

![Comparison of direct conversion vs tone-mapped conversion](images/comparison.png)

## Batch conversion

We also include code to batch convert every video in a folder into a GIF using the same tone-mapping pipeline.

Compression is the process of reducing the size of data to allow for more efficient storage and faster transmission over networks. Compression can significantly decrease the amount of disk space needed for files and the bandwidth required for transferring them, facilitating more efficient use of resources.

It's a good idea to compress data. In general, the more storage you need, the more expensive it is. Network speed can be metered, meaning you pay for what you use. So compression can save money.

## Lossless

Lossless compression identifies redundant patterns and eliminates them without losing any essential information. This ensures that the decompressed file is an exact replica of the original one, preserving its [[integrity]] and quality. However, compression ratio is usually lower compared to lossy compression.

It uses a type of conversion called run-length encoding (RLE), which is effective for files with consecutive repeated characters or redundant information.

> [!example]
> If you have the following sequence of characters:
> > AAAAAAABBBBBCCCCCCCCCCDDDDDDDDDD
> 
> You can turn it into this:
> > 7A5B9C10D

## Lossy

Lossy compression employs a more aggressive strategy to achieve higher compression ratios. It deletes data, typically minor details that are less noticeable to the human eye or ear, and this type of compression is typically employed on video, sound, or image files.

It uses a type of conversion called transform encoding that has the following steps:

- Build sub-image.
- Forward transform.
- Quantize.
- Encode

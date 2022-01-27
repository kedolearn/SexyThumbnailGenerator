# Sexy Thumbnail Generator

Creates a thumbnail when given a compatible video file. Thumbnail wil be selected based on many criteria.

# Usage & Installation

```bash
pip install SexyThumbnailGenerator
```

```python
import SexyThumbnailGenerator

x = SexyThumbnailGenerator.Generator("./video.mp4")
x.generateSelection()
x.save("./image.png")  # Pass in a path + a file name
```

__Note: The first time you run this package, it will need to download the models, and for this an internet connection is required. The models are downloaded from the first release in this repository named "Checkpoint", and can be manually downloaded and placed inside `/site-packages/SexyThumbnailGenerator/.models`__

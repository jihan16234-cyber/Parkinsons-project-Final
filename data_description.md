# Dataset Description (Update 1)

**Added by:** _Member 3 name_

## What the data is
Hand-drawn images from people drawing on paper. There are two drawing types:

| Type | Task | Image size used in the project |
|------|------|--------------------------------|
| Spiral | Draw a spiral | 128 x 128 pixels |
| Wave | Draw a wave | 256 x 128 pixels |

Each image belongs to one of two classes:
- `healthy`
- `parkinson`

## Folder layout
```
data/
  spiral/
    training/
      healthy/*.png
      parkinson/*.png
    testing/
      healthy/*.png
      parkinson/*.png
  wave/
    training/ ...
    testing/ ...
```

The start of each file name is the subject (person) ID, for example `V01`. This is used later so that drawings from the same person never appear in both training and testing.

## Dataset summary (fill in)
| Type | Split | Healthy images | Parkinson images |
|------|-------|----------------|------------------|
| Spiral | training | 36 | 36 |
| Spiral | testing | 15 | 15 |
| Wave | training | 36 | 36 |
| Wave | testing | 15 | 15 |

**Source of the dataset:** _add the dataset name / link_

## Notes
- The images are in `data.zip`, which is unzipped automatically into `data/` the first time the code runs.
- Total: 204 images (102 spiral, 102 wave).

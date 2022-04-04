# Taperception Dataset

This repository contains the datasets that were used for the research described
in "Predicting and Explaining Mobile UI Tappability with Vision Modeling and
Saliency Analysis" by Eldon Schoop, Xin Zhou, Gang Li, Zhourong Chen, Bjoern
Hartmann and Yang Li, which is to appear in CHI 2022.


BibTex for citation:

```
@InProceedings{taperception,
  title     = "Predicting and Explaining Mobile UI Tappability with Vision Modeling and Saliency Analysis",
  booktitle = "Proceedings of the 2022 {CHI} Conference on Human Factors in
               Computing Systems",
  author    = "Schoop, Eldon and Zhou, Xin and Li, Gang and Chen, Zhourong and
               Hartmann, Bjoern and and Li, Yang",
  publisher = "Association for Computing Machinery",
  pages     = "1--13",
  month     =  may,
  year      =  2022,
  address   = "New Orleans, LA, USA",
  url = {https://doi.org/10.1145/3491102.3502042}
}
```

## Data Format
| Feature Name            | Type   | Content                                  |
| ----------------------- | ------ | ---------------------------------------- |
| img_id                  | string | refer to the original RICO dataset |
| object_id               | string | refer to the original RICO dataset |
| label                   | int    | 0 for tappable and 1 for non-tappable |
| raters_marked_tappable  | int    | in range [0, 5], the number of raters with label "tappable" |
| split                   | string | 'train'/'eval'/'test' | 

This dataset contains 18667 examples.

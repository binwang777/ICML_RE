# ICML_RE

|Dataset|Image |Image caption| Bounding box| Region caption| Hard fine-grained negative sample | 
| --- | --- | --- | --- | --- |--- |
|LAION-2B| 2B| 2B|0|0|0|
|Flickr30k|30K|150K|0|0|0|
|CC3M|3M|3M|0|0|0|
|COCO|330K|330K|1.5M|1.5M|0|
|Ours in stage1|1.6B|1.6B+1.6B|0|0|0|
|Ours in stage2|12M|12M+12M|40M|40M|10M|


| Method        | Backbone    | Top-1  | Top-5  |
|---------------|-------------|--------|--------|
| CLIP | VIT-B-16   | 24.79  | 46.63  |
| EVA|   VIT-B-16  | 14.36 |29.11 |
| FineCLIP | VIT-B-16 |   23.29  |  44.17 |
| FG-CLIP | VIT-B-16 | 28.55  | 52.60  |

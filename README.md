# 关于现有数据集全面核查情况的记录

SubDataset部分：检查part有没有分对

cellAnnotation部分：cellAnnotation-为需要删去的字段；cellAnnotation+为需要添加的字段

UnstructureData部分：uns['metadata']中需要修改或者添加的字段

Notes：其他错误及修改中需要注意的地方

## 2.4.2020更新

| Dataset | SubDataset      | CellAnnotation-                                        | CellAnnotation+                                    | UnstructureData                                        | Notes                |
| ------- | --------------- | ------------------------------------------------------ | -------------------------------------------------- | ------------------------------------------------------ | -------------------- |
| No_376  | 需要分part      | tissue, source Name, Description, Treatment, Geno Type |                                                    | LibPrep为10x                                           |                      |
| No_369  | 不要human的部分 | Description                                            |                                                    |                                                        | 做错，细胞量比文中少 |
| No_368  |                 |                                                        |                                                    |                                                        | 检查无误             |
| No_365  |                 | 格式不整齐                                             |                                                    | 缺少摘要图                                             |                      |
| No_364  |                 | 格式不整齐                                             |                                                    | 缺少摘要图；tissue为notAvailable；LibPrep为C1 Fluidigm |                      |
| No_360  |                 | description, strain, age                               | cellOntologyID填hematopoietic stem cell CL:0000037 | 缺少摘要图                                             |                      |
| No_329  | 不分part        | sampleGroup1，Age1, Description                        |                                                    | 缺少摘要图；tissue填brain                              |                      |
| No_271  |                 |                                                        |                                                    |                                                        | 非单细胞数据集       |
| No_189  |                 |                                                        |                                                    |                                                        | 非单细胞数据集       |


# 关于现有数据集全面核查情况的记录

SubDataset部分：检查part有没有分对

cellAnnotation部分：cellAnnotation-为需要删去的字段；cellAnnotation+为需要添加的字段

UnstructureData部分：uns['metadata']中需要修改或者添加的字段

Notes：其他错误及修改中需要注意的地方

## 2.4.2020更新


| Dataset | SubDataset      | CellAnnotation-                                        | CellAnnotation+                                    | UnstructureData                                        | Notes                | 修改状态 | 人员分配       |
| ------- | --------------- | ------------------------------------------------------ | -------------------------------------------------- | ------------------------------------------------------ | -------------------- | -------- | -------------- |
| No_376  | 需要分part      | tissue, source Name, Description, Treatment, Geno Type |                                                    | LibPrep为10x                                           |                      | 修改中   | 2.3.2020阴佳滢 |
| No_369  | 不要human的部分 | Description                                            |                                                    |                                                        | 做错，细胞量比文中少 | 修改中   | 2.5.2020陈淳   |
| No_368  |                 |                                                        |                                                    |                                                        | 检查无误             | 已完成   |                |
| No_365  |                 | 格式不整齐                                             |                                                    | 缺少摘要图                                             |                      | 未修改   |                |
| No_364  |                 | 格式不整齐                                             |                                                    | 缺少摘要图；tissue为notAvailable；LibPrep为C1 Fluidigm |                      | 未修改   |                |
| No_360  |                 | description, strain, age                               | cellOntologyID填hematopoietic stem cell CL:0000037 | 缺少摘要图                                             |                      | 未修改   |                |
| No_329  | 不分part        | sampleGroup1，Age1, Description                        |                                                    | 缺少摘要图；tissue填brain                              |                      | 修改中   | 2.5.2020赵梦宇 |
| No_271  |                 |                                                        |                                                    |                                                        | 非单细胞数据集       | 待删除   |                |
| No_189  |                 |                                                        |                                                    |                                                        | 非单细胞数据集       | 待删除   |                |

## 2.6.2020更新

| Dataset | SubDataset                    | CellAnnotation-                                             | CellAnnotation+                                              | UnstructureData                 | Notes                       | 修改状态 | 人员分配 |
| ------- | ----------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------- | --------------------------- | -------- | -------- |
| No_316  |                               | Assigned_Subgroup; Scpm Coef                                |                                                              | 缺少摘要图                      |                             | 未修改   |          |
| No_312  |                               | sourceName；gender                                          |                                                              | 缺少摘要图；tissue填brain       |                             | 未修改   |          |
| No_299  |                               | description                                                 | cellOntology填CD8 T细胞的信息，condition_plate，seq_id，batch_bio | 缺少摘要图                      | 细胞数少于文章，重做        | 未修改   |          |
| No_282  |                               | 格式不整齐                                                  |                                                              | 缺少摘要图                      | 混杂了非单细胞数据，重做    | 未修改   |          |
| No_264  |                               | cellID, embryo, description                                 |                                                              | 摘要图不清晰                    | 没有用提供的TPM，重做       | 未修改   |          |
| No_195  | 需要分part，H1和H1 fucci      | passage, treatmen                                           |                                                              | 缺少摘要图                      |                             | 未修改   |          |
| No_98   |                               | description, donor, age, sex; 没有fibrocyte这种cellOntology |                                                              | 摘要图不清晰； Tissue不能填knee | 没有用提供的normalize，重做 | 未修改   |          |
| No_61   | 缺少一个数据集GSE107727的数据 | sorting strategy，strain                                    |                                                              | 缺少摘要图                      |                             | 未修改   |          |


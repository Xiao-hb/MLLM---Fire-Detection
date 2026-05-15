### 论文
  Bowfire: Detection of fire in still images by integrating pixel color and texture analysis

### 下载网址
  https://www.kaggle.com/datasets/malligasenthil/bowfire?select=fire017.png

### 数据集描述
  BoWFire 数据集包含 226 张不同分辨率的图像，其中 119 张图像描绘火灾，107 张图像代表非火灾场景。火灾图像涵盖紧急火灾事件的不同场景，例如建筑火灾、工业火灾、事故和骚乱。非火灾图像包括红色或黄色色调的火状物体和日落场景。此外，还提供了一个由 240 张分辨率为 50 × 50 像素的图像组成的训练集，其中包括 80 张火灾图像和 160 张非火灾图像。

### 标签生成
  1. 使用labelme工具人工标注，只标注火灾图片的检测框

  2. 使用Qwen3-VL-8B生成图片的场景文本描述
    

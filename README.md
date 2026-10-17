# HiddenGallery 语义搜索模型分发

Chinese-CLIP ViT-B/16 fp16 ONNX 双塔（视觉 86M + 文本 RoBERTa-wwm 102M，512 维，224px，context 52）。
由官方 PyTorch 权重转换（opset 16 + onnxsim + ORT transformers fp16），与原始权重余弦相似度 1.000000。
HiddenGallery App 的语义搜索功能从 Releases 匿名下载。
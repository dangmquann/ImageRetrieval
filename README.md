# ImageRetrieval
## Image Retrieval là việc truy xuất các ảnh trong tập dataset để tìm các ảnh tương đồng với query image sử dụng 1 số đo lương :
  - Accuracy
  - cosine similarity
  - correlation coeficient
### Sử dụng Pre-train model : Vision Transformer
 In vision, Attention sẽ được sử dụng cùng với Convolutional network để giảm 1 số thành phần của CNN.
 Khi đưa ảnh vào Transformer encoder, chia ảnh ra thành các chuỗi fixed-size non-overlapping patches. Các token đại diện cho image sẽ được đưa vào model.
  - ViTImageProcess : resize, normalize images
  - ViTImageClassfication



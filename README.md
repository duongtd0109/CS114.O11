# CS114.O11 - Machine Learning

Project: **Optical Character Recognition**

Application: *Bookshelf digitization*

### Members:

*   19521414 - Trịnh Đăng Dương
*   19522553 - Huỳnh Ngọc Hiệp Ý
*   21522123 - Phạm Quang Hưng

### Problem description
---
- **Input**: ảnh bìa sách định dạng .jpg.
- **Output**: thông tin trên bìa sách dạng văn bản bao gồm tiêu đề sách, tác giả, nhà xuất bản, các dòng chữ khác.
- **Ngữ cảnh ứng dụng**: nhập thông tin sách vào cơ sở dữ liệu của thư viện, tra cứu thông tin sách bằng hình ảnh

### Dataset
---
- **Xây dựng bộ dữ liệu**: tự chụp ảnh từ các thư viện, nhà sách gần nơi sinh sống và lấy ảnh bìa sách từ website Amazon.com
- Số lượng và độ đa dạng: bộ dữ liệu có **2000** ảnh bìa sách
- Phân chia (*split*) train / dev / test: 80% train, 10% dev, 10% test

### Feature
---
- Feature là các **pixel** trên ảnh chụp đã được tiền xử lý

### Algorithm
---
- **OCR**, or *Optical Character Recognition*, is a process of recognizing text inside images and converting it into an electronic form. These images could be of handwritten text, printed text like documents, receipts, name cards, etc., or even a natural scene photograph.

### References
- Analytics Vidhya (https://www.analyticsvidhya.com/blog/2020/05/build-your-own-ocr-google-tesseract-opencv/)
- TensorFlow (https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html#configuring-a-training-pipeline)

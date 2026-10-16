Đây là danh sách code dành cho đề tài: MÔ HÌNH HỌC SÂU KHÔNG GIÁM SÁT CHO PHÂN TÍCH ĐỘNG HỌC GIỌNG NÓI ĐỘC LẬP NỘI DUNG NGÔN NGỮ.
Thực hiên bởi sinh viên Phan Nguyên Định mssv 21110423 của trường Đại học Công nghệ Kỹ thuật.

Với mục tiêu tổng quát của là xây dựng và đánh giá một hệ thống học biểu diễn động học giọng nói có khả năng mô hình hóa sự biến đổi trạng thái biểu cảm theo thời gian, thay vì chỉ dự đoán một nhãn cảm xúc rời rạc cho toàn bộ phát ngôn.

Languages / Tools

Python, Jupyter Notebook, GitHub
Deep learning: Transformer, CNN 1D (PyTorch là suy đoán, báo cáo không nêu rõ)
Librosa/audio feature extraction (suy đoán)
Gradio (làm giao diện demo)
UMAP (giảm chiều và visualization)
Scikit-learn: Logistic Regression, Gradient Boosting (làm baseline)

Concepts

Self-supervised learning, representation learning, contrastive learning (CPC)
Xây pipeline tiền xử lý dữ liệu có kiểm soát: chuẩn hóa, VAD, chia tập speaker-disjoint, tránh data leakage
Feature engineering (F0, energy, ZCR, mel-spectrogram)
Đánh giá mô hình: accuracy, F1, confusion matrix, khoảng tin cậy, baseline comparison, retrieval metric
Nhận diện shortcut learning và domain bias
Trực quan hóa kết quả và xây demo ứng dụng, xuất JSON

Danh sách đường dẫn raw data sử dụng để huấn luyện:
- https://www.kaggle.com/datasets/ejlok1/cremad
- https://www.kaggle.com/datasets/samuelsamsudinng/iemocap-emotion-speech-database
- https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio/data

# LSTM Audio Classification

## ***Description***:

### This program:
* Clean audio
* Training model.
* Test model.


### Language: Python

## ***Modules***:

* models: a module that contains LSTM models for training model 
* clean: a functional-based module that contains functions for data preprocessing and save data for training model
* train:  a functional-based module that contains functions for training and save LSTM model
* predict :  a functional-based module that contains functions for testing model
## ***File***
* audio_train : folder include files to training model
* Testpredict : folder include files to testing model
* test.csv : a file include label of files testing to model evaluation
* Pre.csv  : a file include label predict of files testing 
## ***To run this program***

* install library in requirenment.txt
* Run clean.py to data processing.
* then Run train.py to training and save model
* final, run prediction to test model
## ***Tiếng việt***
*Project bao gồm 
-4 modules :
+) models: chứa mô hình LSTM
+) clean : chứa code dùng để xử lý file âm thanh
+) train: chứa code dùng để training mô hình
+) predict : chứa code dùng để test mô hình sau khi train
- các folders:
+) audio_train : chưa file để train mô hình
+) Testpredict : chứa file để test mô hình
+) logs : chưa file dữ liệu train và test
+) models : chưa file model sau khi train
- 2 tiệp Testcsv và Pred.csv có thông tin về label các file trong thư mục Testpredict dùng để đánh giá mô hình

*Cách chạy code project:
-Đầu tiên chạy module clean.py để xử lý dữ liệu. Dữ liệu sau khi xử lý sẽ được lưu vào folder clean
-Tiếp theo chạy module train.py để đào tạo mô hình. Sau khi đào tạo file lstm.h5 được lưu vào folder models
-Cuối cùng chạy module predict.py để test mô hình. Trong quá trình chạy, thông tin về dự đoán sẽ được hiện trên màn hình.
 Và sau khi kết thúc thì dữ liệu dự đoán sẽ được lưu vào file Pred.csv

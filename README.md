# Vietnamese txt classification using DL built on Pyspark.
### Dataset: https://nlp.uit.edu.vn/datasets/#h.p_4Brw8L-cbfTe

## Result
| |  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| **Text**                                                                                                                                                                                 | **prediction** |
| |   |
| "chỉ một câu "" giấc mơ thành đại gia "" ."                                                                                                                                              | negative     |
| "cả năm toàn học vòng lặp "" if "" "" for "" "" while "" đến bữa cuối mới lơ mơ học được struct với tạo file header mà ra đề 5 điểm trong phần đó ."                                     | neutral      |
| "dạy học sinh hỏi thì nói "" tui không biết "" ."                                                                                                                                        | positive     |
| "không nên "" hù dọa "" sinh viên ở phía trước mỗi bài toán mà phải biến nó thành đơn giản để thực thi bài toán giảng viên cần phải làm những bài tập mẫu hơn là cho mấy trăm bài tập ." | negative     |
| "không rõ "" thu được gì "" từ môn học này ."                                                                                                                                            | negative     |
| "khắc phục khuyết điểm "" tôi không có lý do gì để xem bài tập của em cả "" ."                                                                                                           | negative     |
| "lúc cho phép sửa điểm thì không thông báo giờ cụ thể chỉ nói "" buổi tối "" ."                                                                                                          | negative     |
| "quản lý như vậy dẫn đến tình trạng "" cha chung không ai khóc "" ."                                                                                                                     | negative     |
| "rồi trong thời gian sinh viên báo cáo thì không lắng nghe và góp ý , mà hỏi những câu ví dụ như doubledot "" chỉ có vậy thôi hả ? còn gì nữa không ? dotdotdot "" ."                    | negative     |
| "thái độ dạy hời hợt , những buổi giảng viên "" không kẹt xe "" thì sẽ cho lớp nghỉ sớm để giảng viên "" đi họp "" ."                                                                    | negative     |
| "tiếng anh lại không chuẩn mà cứ nói ngập ngừng suốt buổi , không thấy một câu tiếng việt ( ví dụ doubledot "" các em hiểu không ? "" ) ."                                               | negative     |
| 1 chỉ thực hành chỉ còn ý nghĩa tượng trưng .                                                                                                                                            | positive     |
| 1 tín chỉ thực hành 2 tín chỉ học phí .                                                                                                                                                  | negative     |
| 50% giành cho kiến thức chi tiết một loại công nghệ dotnet doubledot có thể giống đồ án cuối kỳ hiện tại .                                                                               | negative     |
| anh văn .                                                                                                                                                                                | neutral      |
| anh wzjwz278 như một người bạn vậy , rất gần gũi , thoải mái khi giao tiếp với sinh viên , kiến thức học được từ anh rất đầy đủ .                                                        | positive     |
| ban đầu thì em có vẻ không hài lòng lắm về giáo viên khi học môn này , nhưng sau một khoảng thời gian thì thấy cũng ổn .                                                                 | negative     |
| biết hai ngôn ngữ sẽ dễ gây ấn tượng với nhà tuyển dụng hơn là một .                                                                                                                     | negative     |
| biết làm bài tập của môn học nhưng không hiểu nó liên quan gì đến thực tế .                                                                                                              | negative     |
| biết tạo điều kiện cho học sinh rèn luyện các kỹ năng , khả năng dẫn dắt truyền đạt tốt .                                                                                                | positive     |
|                                                                                                                                                                                           |  |
only showing top 20 rows                 
### Evaluate
![image](https://github.com/huuquangg/Vietnamese-Students-Feedbacks-Classification-DistributedDL-Spark/assets/98322281/755abe12-057f-4cda-9b05-c2f6f61790f9)


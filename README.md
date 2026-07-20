Đây là source code phát hiện tấn công Anomaly sử dụng học máy. Có thể phát hiện Dos và Bruteforce (các file có trong CIC-IDS-2018)
Sử dụng công cụ CICFlowMeter kết hợp với mô hình XGBoost hoặc Random Forest đã được huấn luyện.
Đã thử nghiệm test và phát hiện thành công DoSSlowLoris.
Để triển khai: 
  - Sử dụng phiên bản Java 8
  - Build với command: bash ./gradlew build
  - Run code với command: bash ./gradlew execute

Sau đó, hãy thử tấn công vào card mạng CICFlowMeter đang lắng nghe và xem kết quả.

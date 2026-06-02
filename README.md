# BÁO CÁO BÀI TẬP LAB 7 - API TESTING VỚI POSTMAN

## 1. Thông tin sinh viên
* **Họ và tên:** Hoàng Như Quỳnh
* **Mã số sinh viên:** 23010027
* **Môn học:** Đánh giá và kiểm định chất lượng phần mềm
* **Môi Trường Kiểm Thử:** Phần mềm Postman
* **Mục Tiêu Kiểm Thử:** Sử dụng Postman để kiểm thử một API thực tế nhằm đánh giá khả năng xử lý dữ liệu và bắt lỗi của hệ thống.
* **Phương Pháp Kiểm Thử:** Kiểm thử tự động và thủ công trên phần mềm Postman.

## 2. Kết quả thực hiện các Kịch bản kiểm thử (Test Scenarios)

### Kịch bản 1: Kiểm thử lấy thông tin tỷ giá các đồng tiền (Thành công)
* **Mục đích:** Kiểm tra khả năng kết nối và lấy dữ liệu tỷ giá tiền tệ thế giới.
* **Phương thức HTTP:** GET
* **URL:** <https://open.er-api.com/v6/latest/USD>
* **Kết quả mong đợi:** Hệ thống trả về mã trạng thái `200 OK` màu xanh và cấu trúc dữ liệu JSON chứa tỷ giá.
* **Kết quả thực tế:** Gửi yêu cầu thành công, hiển thị đầy đủ danh sách tỷ giá (VND, EUR, JPY...).
* **Trạng thái:** ĐẠT (Passed)
* **Kết quả kiểm thử:**
<img width="1920" height="1200" alt="js1" src="https://github.com/user-attachments/assets/8fca333d-33a8-4726-8957-aa68d00badfc" />

#### Kết quả kiểm thử chi tiết:
```text
[
  {
    "result": "success",
    "provider": "https://www.exchangerate-api.com",
    "documentation": "https://www.exchangerate-api.com/docs/free",
    "terms_of_use": "https://www.exchangerate-api.com/terms",
    "time_last_update_unix": 1780358552,
    "time_last_update_utc": "Tue, 02 Jun 2026 00:02:32 +0000",
    "time_next_update_unix": 1780445662,
    "time_next_update_utc": "Wed, 03 Jun 2026 00:14:22 +0000",
    "time_eol_unix": 0,
    "base_code": "USD",
    "rates": {
        "USD": 1,
        "AED": 3.6725,
        "AFN": 63.551194,
        "ALL": 81.905172,
        "AMD": 368.519898,
        "ANG": 1.79,
        "AOA": 924.944166,
        "ARS": 1421.4672,
        "AUD": 1.395746,
        "AWG": 1.79,
        "AZN": 1.700046,
        "BAM": 1.681163,
        "BBD": 2,
        "BDT": 122.74382,
        "BGN": 1.681163,
        "BHD": 0.376,
        "BIF": 2984.298989,
        "BMD": 1,
        "BND": 1.278628,
        "BOB": 6.919451,
        "BRL": 5.02899,
        "BSD": 1,
        "BTN": 95.096561,
        "BWP": 13.78503,
        "BYN": 2.758938,
        "BZD": 2,
        "CAD": 1.38329,
        "CDF": 2264.893628,
        "CHF": 0.786038,
        "CLF": 0.022513,
        "CLP": 889.853551,
        "CNH": 6.764779,
        "CNY": 6.780899,
        "COP": 3692.261877,
        "CRC": 453.665548,
        "CUP": 24,
        "CVE": 94.779918,
        "CZK": 20.860429,
        "DJF": 177.721,
        "DKK": 6.41374,
        "DOP": 58.619839,
        "DZD": 132.692827,
        "EGP": 52.030046,
        "ERN": 15,
        "ETB": 158.019766,
        "EUR": 0.859566,
        "FJD": 2.212563,
        "FKP": 0.74327,
        "FOK": 6.413636,
        "GBP": 0.74327,
        "GEL": 2.664957,
        "GGP": 0.74327,
        "GHS": 11.771695,
        "GIP": 0.74327,
        "GMD": 74.208582,
        "GNF": 8765.059191,
        "GTQ": 7.627733,
        "GYD": 209.197946,
        "HKD": 7.837904,
        "HNL": 26.619698,
        "HRK": 6.476391,
        "HTG": 130.851565,
        "HUF": 305.258877,
        "IDR": 17876.62402,
        "ILS": 2.819146,
        "IMP": 0.74327,
        "INR": 95.097079,
        "IQD": 1310.590187,
        "IRR": 1239166.765907,
        "ISK": 123.405571,
        "JEP": 0.74327,
        "JMD": 157.511613,
        "JOD": 0.709,
        "JPY": 159.601522,
        "KES": 129.491871,
        "KGS": 87.472422,
        "KHR": 4034.610264,
        "KID": 1.395743,
        "KMF": 422.878186,
        "KRW": 1511.047372,
        "KWD": 0.308964,
        "KYD": 0.833333,
        "KZT": 488.090779,
        "LAK": 21964.27398,
        "LBP": 89500,
        "LKR": 330.536763,
        "LRD": 182.125565,
        "LSL": 16.299221,
        "LYD": 6.351337,
        "MAD": 9.185818,
        "MDL": 17.293981,
        "MGA": 4195.638913,
        "MKD": 53.022288,
        "MMK": 2100.459899,
        "MNT": 3599.618209,
        "MOP": 8.073041,
        "MRU": 40.074322,
        "MUR": 47.330914,
        "MVR": 15.440546,
        "MWK": 1742.875588,
        "MXN": 17.356475,
        "MYR": 3.964924,
        "MZN": 63.63082,
        "NAD": 16.299221,
        "NGN": 1371.354653,
        "NIO": 36.802836,
        "NOK": 9.271106,
        "NPR": 152.154497,
        "NZD": 1.684057,
        "OMR": 0.384497,
        "PAB": 1,
        "PEN": 3.403182,
        "PGK": 4.366565,
        "PHP": 61.805265,
        "PKR": 278.756641,
        "PLN": 3.639098,
        "PYG": 6089.799167,
        "QAR": 3.64,
        "RON": 4.509133,
        "RSD": 100.779922,
        "RUB": 71.811965,
        "RWF": 1467.019664,
        "SAR": 3.75,
        "SBD": 7.914496,
        "SCR": 14.752874,
        "SDG": 454.041908,
        "SEK": 9.302891,
        "SGD": 1.278388,
        "SHP": 0.74327,
        "SLE": 24.581085,
        "SLL": 24581.085213,
        "SOS": 571.12679,
        "SRD": 37.164726,
        "SSP": 4700.344354,
        "STN": 21.059339,
        "SYP": 112.382787,
        "SZL": 16.299221,
        "THB": 32.602547,
        "TJS": 9.229273,
        "TMT": 3.499926,
        "TND": 2.907136,
        "TOP": 2.363117,
        "TRY": 45.944326,
        "TTD": 6.763361,
        "TVD": 1.395743,
        "TWD": 31.3679,
        "TZS": 2617.449798,
        "UAH": 44.296748,
        "UGX": 3750.514522,
        "UYU": 40.153563,
        "UZS": 11928.308688,
        "VES": 557.9741,
        "VND": 26178.979791,
        "VUV": 117.531642,
        "WST": 2.680448,
        "XAF": 563.837582,
        "XCD": 2.7,
        "XCG": 1.79,
        "XDR": 0.73005,
        "XOF": 563.837582,
        "XPF": 102.573593,
        "YER": 238.633538,
        "ZAR": 16.295999,
        "ZMW": 18.257271,
        "ZWG": 26.8503,
        "ZWL": 26.8503
      }
    }
  ]
```

### Kịch bản 2: Kiểm thử gọi sai đường dẫn để bắt lỗi hệ thống (Thất bại - Lỗi 404)
* **Mục đích:** Kiểm tra khả năng bắt lỗi và phản hồi của hệ thống khi người dùng nhập sai URL.
* **Phương thức HTTP:** GET
* **URL (Cố tình viết sai):** <https://datausa.io/api/data-sai-duong-dan>
* **Kết quả mong đợi:** Gửi yêu cầu thất bại đúng như thiết kế, hệ thống trả về mã lỗi `404 Not Found` màu đỏ kèm mã HTML báo lỗi trang không tồn tại.
* **Kết quả thực tế:** Postman bắt được mã lỗi `404 Not Found` và hiển thị mã nguồn HTML lỗi của Server.
* **Trạng thái:** ĐẠT (Passed - Bắt lỗi thành công)
* **kết quả kiểm thử:**
<img width="1920" height="1200" alt="js2" src="https://github.com/user-attachments/assets/92b41b1d-65d2-412b-b929-2a8d6c1e37bd" />

#### Kết quả kiểm thử chi tiết:
```text
<!doctype html>
<html dir="ltr" lang="en">
<head>
    <title data-rh="true">Data USA</title>
    <meta data-rh="true" charset="utf-8" />
    <meta data-rh="true" http-equiv="X-UA-Compatible" content="IE=edge" />
</head>
<body>
    <div class="bp3-non-ideal-state notfound">
        <h4 class="bp3-heading">Page Not Found</h4>
        <div>404</div>
    </div>
</body>
</html>
```

### Kịch bản 3: Kiểm thử lấy dữ liệu dự báo thời tiết (Thành công)
* **Mục đích:** Kiểm tra khả năng lấy dữ liệu thời tiết thực tế (nhiệt độ, độ ẩm) theo tọa độ địa lý thông qua các tham số lọc (Params).
* **Phương thức HTTP:** GET
* **URL:** <https://api.open-meteo.com/v1/forecast?latitude=10.82&longitude=106.63&current=temperature_2m,relative_humidity_2m>
* **Kết quả mong đợi:** Hệ thống trả về mã trạng thái `200 OK` màu xanh kèm đoạn mã JSON chứa nhiệt độ và độ ẩm thực tế tại tọa độ đã truyền.
* **Kết quả thực tế:** Nhận dữ liệu thời tiết thành công, hiển thị chính xác cấu trúc JSON.
* **Trạng thái:** ĐẠT (Passed)
* **Kết quả kiểm thử:**
<img width="1920" height="1200" alt="js3" src="https://github.com/user-attachments/assets/33d9ee4f-5b4b-4d88-9852-1968a6a0c2c3" />

#### Kết quả kiểm thử chi tiết:
```text
{
    "latitude": 10.790861,
    "longitude": 106.6313,
    "generationtime_ms": 0.03349781036376953,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 7.0,
    "current_units": {
        "time": "iso8601",
        "interval": "seconds",
        "temperature_2m": "°C",
        "relative_humidity_2m": "%"
    },
    "current": {
        "time": "2026-06-02T09:15",
        "interval": 900,
        "temperature_2m": 26.4,
        "relative_humidity_2m": 93
    }
}
```

## 3. Tóm tắt kết quả kiểm thử (Test Summary)
* **Số lượng kịch bản đã kiểm thử:** 3 kịch bản
* **Số lần thành công (Passed):** 2 kịch bản (Kịch bản 1 và Kịch bản 3)
* **Số lần thất bại (Failed):** 1 kịch bản (Kịch bản 2 - Chủ động thử nghiệm bắt lỗi)
* **Tỉ lệ thành công (Success Rate):** 66.7%

## 4. Nhật ký phát hiện lỗi (Bug Log / Defect Report)
Khi tiến hành kiểm thử, hệ thống đã ghi nhận chi tiết về lỗi phát sinh như sau:

* **ID Lỗi (Status Code):** `404 Not Found`
* **Mô Tả Lỗi:** Trang dữ liệu hoặc địa chỉ URL người dùng đang tìm kiếm không tồn tại trên hệ thống Server. Máy chủ không thể tìm thấy tài nguyên tương ứng với đường dẫn được gửi đi.
* **Mức Độ Ảnh Hưởng (Severity):** Thấp (Low) / Không ảnh hưởng đến vận hành chung (Do đây là lỗi ngoại lệ phát sinh khi tester chủ động nhập sai thông tin địa chỉ URL nhằm kiểm tra khả năng bắt lỗi của hệ thống).
* **Ghi Chú & Đề Xuất (Recommendations):**
  * Người dùng hoặc lập trình viên cần kiểm tra kỹ cấu trúc chuỗi ký tự trên thanh địa chỉ URL.
  * Đảm bảo các tham số truyền vào đúng định dạng và không bị thừa/thiếu các ký tự đặc biệt hoặc dấu gạch chéo `/` trước khi tiến hành gửi Request.

## 5. Kết luận sau bài Lab
* Thành thạo kỹ năng sử dụng công cụ Postman để gửi các request dạng phương thức GET.
* Biết cách phân tích các mã phản hồi tiêu chuẩn của Server trả về (Mã thành công 200 OK và mã lỗi hệ thống 404 Not Found).
* Hiểu cách cấu hình các tham số lọc (Query Params) trực tiếp trên thanh URL và bảng quản lý thuộc tính của Postman.

Đoạn code cũ sử dụng thư viện `requests` để crawl dữ liệu. Tuy nhiên, tôi đã chuyển sang sử dụng `selenium` như thầy yêu cầu. 

Đầu tiên, hãy tải **chromedriver.exe** tương ứng với phiên bản Chrome bạn đang sử dụng [tại đây](https://chromedriver.chromium.org/downloads). 

Sau đó, chỉnh sửa tên đội ở dòng 17 trong code và sửa đường dẫn trong hàm main.

Ngoài ra, hãy điều chỉnh tham số ở dòng 44 theo từng giải đấu:

- Ngoại hạng Anh: `//*[@id="stats_standard_9"]/tbody`
- La Liga: `//*[@id="stats_standard_12"]/tbody`
- Serie A: `//*[@id="stats_standard_11"]/tbody`
- Bundesliga: `//*[@id="stats_standard_20"]/tbody`
- Ligue 1: `//*[@id="stats_standard_13"]/tbody`
- Giải Mexico (Liga MX): `//*[@id="stats_standard_31"]/tbody`
- Giải Bồ Đào Nha (Primeira Liga): `//*[@id="stats_standard_32"]/tbody`
- Hà Lan (Eredivisie): `//*[@id="stats_standard_23"]/tbody`
- Brazil (Série A): `//*[@id="stats_standard_24"]/tbody`
- Bỉ (Belgian Pro League): `//*[@id="stats_standard_37"]/tbody`

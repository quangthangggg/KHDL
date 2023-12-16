 Do code cũ họ dùng request để crawl nên t đổi qua selenium (thầy bảo không dùng request)\\
 Ae vào web này tải **chromedriver.exe** đúng với phiên bản chrome mà ae đang xài : https://chromedriver.chromium.org/downloads\\
 Code thì ae chỉnh sửa tên đội (dòng 17 trong code), và sửa path ở trong hàm main nhé\\
 Ngoài ra chỉnh tham số ở dòng 44 theo từng giải đấu:\\
 Ngoại hạng anh: //*[@id="stats_standard_9"]/tbody\\
Laliga: //*[@id="stats_standard_12"]/tbody\\
SerieA: //*[@id="stats_standard_11"]/tbody\\
Bundes: //*[@id="stats_standard_20"]/tbody\\
Ligue1: //*[@id="stats_standard_13"]/tbody\\
Giải mexico(Liga MX): //*[@id="stats_standard_31"]/tbody\\
Giải bồ (Primeira Liga): //*[@id="stats_standard_32"]/tbody\\
Hà lan (Eredivisie): //*[@id="stats_standard_23"]/tbody\\
Brazil (Série A): //*[@id="stats_standard_24"]/tbody\\
Bỉ (Belgian Pro League): //*[@id="stats_standard_37"]/tbody\\

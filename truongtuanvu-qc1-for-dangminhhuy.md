# Phiếu QC 1 — Road v1.0

Lô được kiểm (học viên): Đặng Minh Huy        Người kiểm (học viên): Trương Tuấn Vũ  
Ngày: 22/11/2026                          Phiên bản guideline: Road v1.0  
File được kiểm (tên + `revision` trong manifest): DangMinhHuy-front.zip, DangMinhHuy-fisheye.zip; revision: chưa được cung cấp.  
Số ảnh kiểm: 6 (+ 0 ảnh thêm, ghi riêng)   Số nhãn đã kiểm (shape + tag): 84  

## Tổng hợp theo mã

| Mã | Loại lỗi | Số mục kiểm | Số lỗi | Mức |
| --- | --- | ---: | ---: | --- |
| QC1-01 tag camera | sai thuộc tính / bỏ sót | 24 | 3 | nhẹ |
| QC1-02 đủ L1, R1 | bỏ sót | 10 | 0 | nặng |
| QC1-03 position | sai thuộc tính / thừa | 13 | 2 | nặng |
| QC1-04 tâm vạch, chiều, điểm dừng | sai phạm vi / bỏ sót | 13 | 1 | chính |
| QC1-05 vạch đứt, che | sai phạm vi / sai thuộc tính | 13 | 0 | chính |
| QC1-06 style, color, kind | sai thuộc tính | 13 | 0 | chính |
| QC1-07 vùng lái | sai phạm vi / bỏ sót / thừa | 24 | 5 | chính |
| QC1-08 đèn, màu | bỏ sót / sai phạm vi / sai thuộc tính | 15 | 2 | chính |
| QC1-09 facing, type, group, biển phụ | sai thuộc tính | 23 | 16 | chính |
| QC1-10 hình in, đủ biển | bỏ sót / sai phạm vi | 6 | 1 | chính |
| QC1-11 fisheye | sai phạm vi / sai thuộc tính | 19 | 0 | chính |
| QC1-12 file | lỗi file | 2 | 0 | nhẹ / nặng |

## Danh sách lỗi (mỗi lỗi một dòng)

| # | Mã | Ảnh | Nhãn (label, id) | Mức | Mô tả ngắn |
| --- | --- | --- | --- | --- | --- |
| 1 | QC1-03 | A04 | lane, XML #5 @(1280,525) | nặng | Vạch bên phải R1 gán L2; đúng: R2. |
| 2 | QC1-03 | B03 | lane, XML #1 @(303,618) | nặng | Gán vùng tối/biên gần thân xe thành lane, không có vệt sơn tương ứng. |
| 3 | QC1-07 | A04 | drivable, XML #1 @(730,534) | chính | Vùng làn bên phải R1 gán direct; đúng: alternative. |
| 4 | QC1-09 | A04 | traffic_light, XML #3 @(551,271) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 5 | QC1-07 | A08 | drivable, XML #4 @(646,306) | chính | Làn bên phải ở xa gán direct; đúng: alternative. |
| 6 | QC1-07 | A08 | road_curb, XML #11 @(258,424) | chính | road_curb đi chéo giữa mặt đường, không có lề/vỉa hè tương ứng. |
| 7 | QC1-09 | A08 | traffic_light, XML #8 @(198,98) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 8 | QC1-09 | A08 | traffic_light, XML #9 @(360,79) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 9 | QC1-09 | A08 | traffic_light, XML #10 @(519,176) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 10 | QC1-09 | A08 | traffic_light, XML #12 @(290,135) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 11 | QC1-09 | A08 | traffic_light, XML #13 @(668,146) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 12 | QC1-09 | A08 | traffic_light, XML #14 @(760,159) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 13 | QC1-09 | A08 | traffic_light, XML #15 @(868,140) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 14 | QC1-09 | A08 | traffic_light, XML #16 @(649,212) | chính | Đèn cho xe gán type=beacon; đúng: vehicle. |
| 15 | QC1-10 | A08 | traffic_sign bị thiếu, khoảng (987,185)–(1015,249) | chính | Thiếu biển cấm đỗ/dừng bên phải, cao trên 8 px. |
| 16 | QC1-09 | A10 | traffic_sign, XML #3 @(44,47) | chính | Biển NO PARKING/NO STANDING gán supplementary; đúng: prohibitory. |
| 17 | QC1-07 | A10 | drivable, XML #9 @(453,602) | chính | Làn xe mình gán alternative; đúng: direct. Polygon khoét sát đuôi/bánh xe khác. |
| 18 | QC1-09 | A10 | traffic_light, XML #6 @(743,180) | chính | type=beacon sai; đúng: vehicle. |
| 19 | QC1-09 | A10 | traffic_light, XML #7 @(479,254) | chính | type=beacon sai; đúng: pedestrian. |
| 20 | QC1-09 | A10 | traffic_light, XML #8 @(557,194) | chính | type=beacon sai; đúng: vehicle. |
| 21 | QC1-08 | B02 | traffic_light, XML #0 @(1061,13) | chính | Box gộp nhiều cụm đèn và cả nền/đầu người. |
| 22 | QC1-09 | B02 | traffic_light, XML #0 @(1061,13) | chính | Gộp mặt trước/sau, type=beacon và facing=front áp chung sai. |
| 23 | QC1-08 | B02 | traffic_light, XML #1 @(53,73) | chính | Box gộp nhiều cụm đèn trước/sau và nền. |
| 24 | QC1-09 | B02 | traffic_light, XML #1 @(53,73) | chính | Gộp mặt trước/sau, type=beacon và facing=front áp chung sai. |
| 25 | QC1-04 | B03 | lane, XML #0 @(1009,602) | chính | Điểm gần xe (1009,602) lệch sang phải vệt sơn trắng hàng chục pixel. |
| 26 | QC1-09 | B03 | traffic_sign, XML #6 @(1124,362) | chính | Biển tròn xanh mũi tên gán information; đúng: mandatory. |
| 27 | QC1-07 | B06 | drivable, XML #0 @(833,467) | chính | Polygon lấn thân xe tại khoảng (1119,875), (1117,837). |
| 28 | QC1-01 | A04 | tag weather | nhẹ | weather=clear; đúng: overcast. |
| 29 | QC1-01 | A08 | tag weather | nhẹ | weather=clear; đúng: overcast. |
| 30 | QC1-01 | A10 | tag weather | nhẹ | weather=clear; đúng: rain. |

## Ca mơ hồ

| Ảnh | Câu hỏi cho lead | Lời đáp (nếu có) |
| --- | --- | --- |
| A08 | Vạch trái qua giao lộ có phải L1 nhìn thấy rõ không? | Chưa có |
| A08 | Hai box #16/#22 tại (649,212) thuộc hai cụm riêng hay nhãn trùng sai màu? | Chưa có |
| A10 | Màu thật của các đèn nhỏ bị chói là đỏ hay vàng? | Chưa có |
| B02, B03 | Polyline 2–3 điểm có bám cung và đạt ngưỡng 5 px không? | Chưa có |
| B06 | Polyline curb chạy vòng có bám đúng các mép phân cách không? | Chưa có |

## Quyết định

Lỗi nặng: 2   Lỗi chính: 25 / 84 nhãn = 29,76 %   Lỗi nhẹ: 3   Ca chờ lead: 5  
Quyết định (Release / Hold / Rework): Rework  
Lý do (theo luật của phiếu): có 2 lỗi nặng; tỉ lệ lỗi chính 29,76 % vượt ngưỡng 5 %.  

Loại lỗi: bỏ sót = thiếu nhãn phải có; thừa = gán cái không phải đối tượng; sai phạm vi = hình lệch, sai chiều, dừng sai chỗ, tràn vùng. Ba loại này theo cách chia lỗi gán nhãn của ISO/IEC 5259-4 (mục 8.4.2); "sai thuộc tính" và "lỗi file" là khóa học thêm. Cách xếp mức: [thang mức lỗi](../docs/qc_severity_road_v1.0.md).

http://arduino.vn/tutorial/1423-avr-dieu-khien-dong-co-servo-sieu-chuan-voi-bien-do-goc-cuc-nho
( đọc từ phần 1 đến 4 )

http://arduino.vn/tutorial/1416-avr-xuat-xung-voi-tan-so-va-do-rong-theo-y-muon
( đọc phần 2 và phần 4 )

File code:
	Giá trị ICR1 có thể thay đổi nhưng k nên, giá trị 65535 sẽ tối ưu hóa độ phân giải,
		giúp xuất xung chuẩn hơn.
	Giá trị OCR1A phụ thuộc vào set up TCCR1B ( set up prescaller ).

Lập bảng excel ghi lại và so sánh theo prescaller, chế độ counter, chế độ so sánh tương ứng.


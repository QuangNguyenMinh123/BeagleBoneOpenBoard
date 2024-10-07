# BeagleBoneOpenBoard
BeagleBone Open Board
Mạch hỗ trợ học linux bằng beagle bone black.
Mạch hỗ trợ:
	- GPIO, interrupt: nút nhấn và led
	- I2c: SSD1306
	- SPI: ILI9341, Nokia5110
Muốn debug thì vẫn bắt buộc phải hàn vào các pin hoặc cắm trên broadboard
File project: Altium
File schematic: check file Schematic.pdf
File gerber:  Project Outputs for BeagleBoneOpenBoard.rar
Thông số mạch: 2 lớp, độ rộng via và trace mặc định, mạch ghép
Đặt mạch tại cxt.vn, giá thành: 180k/10 mạch

# Linh kiện
Toàn bộ các linh kiện sẽ sử dụng là linh kiện cắm, giá tối ưu nhất có thể. Đối với header cái thì đành phải dùng kèm/kéo để cắt ra cho vừa

https://banlinhkien.com/nut-nhan-4-chan-4.5x4.5x5mm-dip-10-chiec-p22290982.html         1       5,000
https://banlinhkien.com/jump-don-cai-2.54mm-1x10p-thang-5-chiec-p23527300.html          1       7,500
https://banlinhkien.com/tro-vach-14w-5-3.3k-50c-p6652002.html                           1       2,500
https://banlinhkien.com/led-3mm-phu-do-10c-p6651437.html                                1       1,500
PCB                                                                                     1       18.000
=> 35k/mạch, k tính tiền ship, k tính công hàn
# Note
Giá trị điện trở có thể thay đổi từ 1k-4.7k, nhưng không nên dùng nhiều hơn 1 giá trị điện trở trong mạch
Đối với ILI9341 và Nokia5110, chân LED có thể switch từ 3v3 hoặc GPIO, check J5 schematic để rõ hơn, hoặc xem ảnh "J5 Header"
Contact: nguyenminhquangcn1@gmail.com hoặc zalo: 0965 891 270

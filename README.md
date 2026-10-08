# LED-button
Điều khiển LED ngoài kết nối với board **ESP32 DevKit V1** sử dụng nút nhấn thông qua thư viện **OneButton** để điều khiển trạng thái đèn LED
---

# Tính năng

- **Nhấn đơn :** Bật hoặc Tắt LED.
- **Nhấn kép :** Bật chế độ nhấp nháy LED với chu kỳ 250ms.
---

# Phần cứng
1. **ESP32 DevKit V1** (1 board)
2. **Button 4 pins** (1 cái)
3. **LED 5mm** (1 cái)
4. **Điện trở 1kΩ** (1 cái)
5. **Breadboard & Dây cắm**

---

Sơ đồ kết nối
D21 - Button - GND
D4 - led(-) - led(+) - R(1k) - 3.3v

# Thư mục dự án

```text
One_button/
├── .vscode/
├── include/
│   └── LED.h          
├── src/
│   └── main.cpp      
├── .gitignore
├── platformio.ini     
└── README.md         

# Mission Planner

Docs tại đây: https://ardupilot.org/planner/index.html#

# Tổng quan Misstion Planner 

Mission Planner là một ứng dụng trạm mặt đất với đầy đủ chức năng cho dự án điều khiển tự động mã nguồn mở ArduPilot.

## Mission Planner là gì?

Mission Planner là phần mềm điều khiển mặt đất cho Plane, Copter và Rover. Phần mềm chỉ tương thích với Window. Dưới đây là một số chức năng của Mission Planner
- Tải firmware vào mạch của thiết bị bay không người lái.
- Cài đặt, cấu hình, và tinh chỉnh thiết bị bay đạt hiệu suất tối ưu.
- Lên chiến thuật bay, lưu và tải vào thiết bị bay.
- Tải và phân tích mission logs được tạo bởi thiết bị bay.

# Tải Firmware

## Kết nối autopilot với máy tính

Kết nối với autopilot sử dụng cáp micro USB. Sử dụng trực tiếp cổng USB từ máy tính của bạn. Window sẽ tự động nhận diện và cài đặt đúng phần mềm driver.

<p align="center"><img src="https://ardupilot.org/planner/_images/pixhawk_usb_connection.jpg"></p>

## Chọn cổng COM

Cài đặt như trong hình

<p align="center"><img src="https://ardupilot.org/planner/_images/Pixhawk_ConnectWithMP.png"></p>

## Cài đặt firmware

Chọn icon ứng với thiết bị bay của bạn.

<p align="center"><img src="https://ardupilot.org/planner/_images/Pixhawk_InstallFirmware.jpg"></p>

Tiếp theo, phần mềm sẽ nhận diện bạn đang sử dụng mạch nào trong autopilot và nó có thể yêu cầu bạn rút phích cắm của bo mạch, nhấn OK và cắm lại để phát hiện loại bo mạch.

# Kết nối Mission Planner với Autopilot

## Cài đặt kết nối

Để thiết lập kêt nối, bạn phải chọn cách thức/ kênh giao tiếp. Sau đó set up phần cứng và Window device drivers. Ta không thể kết nối PC với autopilot bằng cap USB, Bluetooth, kết nối IP.

<p align="center"><img src="https://ardupilot.org/planner/_images/pixhawk_usb_connection.jpg"></p>
_Pixhawk USB Connection_
<p align="center"><img src="https://ardupilot.org/planner/_images/new-radio-laptop.jpg"></p>
_Connection using SiK Radio_


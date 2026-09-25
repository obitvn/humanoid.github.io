# So Sánh Pin Robot Humanoid — Humanoid Battery Comparison

Bảng so sánh trực quan về **pin và cấu hình của 94 robot humanoid** trên thị trường (16 quốc gia), phục vụ nghiên cứu thiết kế pin/BMS.

Live: **https://obitvn.github.io/humanoid.github.io/** (`index.html` — dashboard)
Nguồn cập nhật dữ liệu: sửa `robots-data.js` → commit & push.

## Nội dung

- **94 robot** — Unitree, Tesla Optimus, Figure, Atlas, Digit, Apollo, NEO, UBTECH Walker/U1, Fourier GR/N1, Booster, AgiBot A2/A3/G2/X2, EngineAI, XPENG IRON, Kepler, Galbot, Dobot, Pudu, DEEP Robotics, LimX, NEURA 4NE-1, TALOS, iCub, NAO, Kaleido, Kapex 01 (LG-KIST), Tiangong Ultra, Honor Lightning, **VinMotion Motion 2 & VinRobotics VR-H3 (VN)**…
- **12 cột pin**: loại pin (Li-ion / LiFePO4 / semi-solid / solid-state), dung lượng Wh & Ah, điện áp, cấu hình S/P, khối lượng pack, dòng xả, form factor, connector, giờ sạc, hot-swap, tính năng đặc biệt
- **Cột thông số robot**: năm, quốc gia, chiều cao, khối lượng, DoF, tốc độ, payload, runtime, giá
- **Mở rộng** (click hàng): CPU/GPU, camera, LLM, OS, kết nối, motor/gear tech, vật liệu, an toàn, nguồn tham khảo
- **Dashboard**: 6 stat tiles, 4 biểu đồ (dung lượng Wh, runtime, scatter Wh vs kg theo loại pin, phân bố điện áp theo dải S), section phân tích hot-swap 43 robot theo 4 cơ chế
- Search, filter (quốc gia / loại pin / hot-swap), sort mọi cột, xuất CSV

## Cập nhật dữ liệu

Mọi dữ liệu nằm trong mảng `ROBOTS` ở **`robots-data.js`** — thêm/sửa robot bằng cách thêm 1 object theo mẫu có sẵn trong file, commit & push, trang tự cập nhật.

## Nguồn dữ liệu (09/2026)

- [humanoid.guide](https://humanoid.guide/humanoid-robots-database/)
- [humanoid-robots.io](https://www.humanoid-robots.io/robots)
- [blog.robozaps.com](https://blog.robozaps.com/b/best-humanoid-robots)
- [jk4e/list-ai-humanoid-robots](https://github.com/jk4e/list-ai-humanoid-robots)
- Trang thông số chính hãng (unitree.com, figure.ai, bostondynamics.com, pal-robotics.com, robotis.us, fftai.com, engineai.com.cn…)

Giá trị thiếu đánh dấu N/A — NSX chưa công bố. Số liệu tham khảo thiết kế, hãy đối chiếu datasheet chính thức trước khi quyết định kỹ thuật.

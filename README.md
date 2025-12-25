

# 🎄 Grand Luxury Tree

[![Contributors](https://img.shields.io/github/contributors/electronicminer/gesture-Christmas_tree-3d_with_photo?color=dark-green)](https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors)

Xin chào! Đây là một dự án nhỏ mình viết để chào mừng Giáng Sinh. ✨

Ban đầu chỉ định vẽ một cây thông 3D bình thường, nhưng thấy chưa đủ “ngầu”, nên mình thêm **nhận diện cử chỉ tay** và **hiệu ứng hạt**. Giờ bạn có thể điều khiển cây thông này “từ xa” qua webcam, và còn treo ảnh yêu thích của mình lên nữa.

Dù chỉ vài trăm dòng code, nhưng hiệu ứng hình ảnh cực kỳ mãn nhãn (nhất là trên màn hình lớn).

Nhấn vào link bên dưới để trải nghiệm trực tiếp (hỗ trợ đa nền tảng):
https://electronicminer.github.io/gesture-Christmas_tree-3d_with_photo/christmas_tree_touch&gesture.html

<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf" />


## 🤔 Đây là gì? (Giới thiệu)

Đây không phải là một tấm thiệp web tĩnh. Đây là một cây thông động được tạo nên từ **hàng ngàn hạt nhỏ**.
Mình tích hợp Google MediaPipe, nên nó có thể “hiểu” cử chỉ tay của bạn.

* **Hiệu ứng hạt**: Cây sẽ “thở”, xoay, và có thể nổ tung thành dải sao.
* **Điều khiển không chạm**: Không cần chuột, chỉ cần vẫy tay trước webcam là điều khiển được (cảm giác như Doctor Strange).
* **Treo kỷ niệm**: Nhấn nút góc phải trên để tải ảnh lên, ảnh sẽ thành khung polaroid viền vàng lơ lửng quanh cây.
* **Thẩm mỹ tối giản**: Chỉ có hai màu đen-vàng, không trang trí lòe loẹt, chủ yếu là “chất sang”.
<img width="2557" height="1291" alt="image" src="https://github.com/user-attachments/assets/d7d31b4c-bf4d-49b2-b922-79813bbddba5" />

<img width="2559" height="1294" alt="image" src="https://github.com/user-attachments/assets/d7e4e982-3042-449d-8898-105048aeac1d" />


## 🛠️ Công nghệ sử dụng (Tech)

Toàn bộ là “phép thuật” frontend, không dùng framework phức tạp:
* **Three.js** - Xử lý 3D và hệ thống hạt.
* **MediaPipe** - Nhận diện cử chỉ tay (cực mạnh).
* **JS thuần (ES Modules)** - Tự code logic lõi.

## 🎮 Cách chơi? (Điều khiển)

Lần đầu chơi nên bật loa (dù chưa có nhạc nền, bạn có thể tự mở Jingle Bells 🎵).

### 🖐️ Chế độ cử chỉ (quan trọng!)
Hãy đảm bảo trình duyệt cho phép dùng webcam, sau đó:
1.  **Xòe bàn tay (🖐️)**: Đây là “chế độ nổ tung”! Cây sẽ bung ra thành dải sao, bạn có thể xoay góc nhìn.
2.  **Nắm chặt tay (✊)**: Thu lại! Các hạt sẽ tụ lại thành cây thông.
3.  **Bóp hai ngón (🤏)**: Như động tác bóp, sẽ ngẫu nhiên chọn một ảnh và phóng to cho bạn xem.

### 🖱️ Dành cho “team chuột”
* Kéo chuột trái để xoay, cuộn để phóng to/thu nhỏ.
* **Phím H**: Ẩn toàn bộ giao diện, tiện chụp màn hình/làm wallpaper.

## 🚀 Chạy thế nào? (How to Run)

⚠️ **Lưu ý:** Vì dùng ES Modules và webcam, **tuyệt đối không mở file `index.html` trực tiếp** (sẽ bị lỗi CORS). Bạn cần chạy server local.

**Nếu dùng VS Code (khuyên dùng):**
Cài extension `Live Server`, chuột phải vào `index.html` -> "Open with Live Server". Xong!

**Nếu bạn rành Python:**
Mở terminal tại thư mục này:
```bash
python -m http.server 8000
````

Sau đó truy cập trình duyệt: `localhost:8000`.

**Nếu quen Node.js:**

```bash
npx http-server .
```



**Merry Christmas\! 🎅**
Nếu bạn thấy dự án thú vị, hãy Star hoặc Fork đổi màu theo ý thích!

Đã bổ sung hỗ trợ giao diện di động
## Contributors ✨

Cảm ơn tất cả các lập trình viên đã đóng góp cho dự án này:

<a href="https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=electronicminer/gesture-Christmas_tree-3d_with_photo" />
</a>

## 📊 Lịch sử Star

[![Star History Chart](https://api.star-history.com/svg?repos=electronicminer/gesture-Christmas_tree-3d_with_photo&type=Date)](https://star-history.com/#electronicminer/gesture-Christmas_tree-3d_with_photo&Date)

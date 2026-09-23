# Typography Readability Pass

Bản này không cộng cứng `+10px` cho mọi chữ vì sẽ làm vỡ bố cục mobile. Thay vào đó, các cỡ chữ nhỏ được tăng mạnh hơn, chữ lớn tăng vừa phải.

## Một số thay đổi chính

- Màn mở thiệp: tên 34–40px mobile, 48px tablet/desktop; ngày / lời mời 20–21px.
- Tiêu đề section: 21px mobile, 28px tablet/desktop.
- Tên bố mẹ: 16–17px; địa chỉ: 14–15px.
- Tên cô dâu / chú rể phần lễ: 32–42px mobile, tối đa 52px desktop.
- Nội dung lễ cưới / giờ / ngày: 15–18px; số ngày 36–40px.
- Countdown: số 22–23px; nhãn 12px.
- Lịch: thứ 12–13px; ngày 14px.
- Địa điểm / timeline: 17–18px.
- Guestbook: input 17px; comment 16px.
- RSVP: label 15–16px; input 16–17px; option 16–17px; mô tả 13–14px.
- QR / ngân hàng: thông tin 14–15px; nút `Lưu QR` 14–15px.
- Footer: 16–17px.

## Cache busting

`index.html` được cập nhật query version:

```html
styles.css?v=20260923-typography1
config.js?v=20260923-typography1
app.js?v=20260923-typography1
```

để GitHub Pages / trình duyệt không giữ CSS/JS cũ.

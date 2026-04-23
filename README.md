# learning-nuclear-reactor-visualizer
Một trang web dashboard mô phỏng PWR (thường đc dùng cho điện hạt nhân) phục vụ cho việc học tập và tìm hiểu về điện hạt nhân
Tính năng chính
Mô phỏng lõi lò: fuel rods, neutron, moderator, control rods
State machine: normal → warning → transient → prompt_critical → meltdown
Decay heat sau shutdown (không “nguội ngay”)
3D specter mode với X-ray để quan sát bên trong
Tooltip theo ngữ cảnh + chế độ “giải thích từng bước”
Dashboard turbine (vòng thứ cấp)
Kiến trúc
Core Engine: neutron, k_eff, thermal/decay heat
Reactor Modules: PWR (hiện tại), có thể mở rộng SMR
UI Layer: 2D/3D, tooltip, learning flow
Cách chạy

Mở index.html trực tiếp hoặc deploy qua GitHub Pages.

Demo (QR)

Quét QR để mở bản online (sẽ cập nhật sau khi deploy).

Định hướng
Thêm SMR mode (integral PWR, passive cooling)
Tối ưu LOD & hiệu năng mobile
Nâng độ chính xác thermal/neutron model

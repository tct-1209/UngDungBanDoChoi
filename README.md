# Toy Shop - Ứng dụng bán đồ chơi Flutter

Ứng dụng bán đồ chơi hiện đại với giao diện thanh lịch, được xây dựng bằng Flutter/Dart.

## Tính năng

- 🎨 Giao diện hiện đại với gradient pastel
- 🧸 Danh sách sản phẩm đồ chơi đa dạng
- 🔍 Lọc theo danh mục
- 📱 Responsive design
- 🛒 Giỏ hàng (đang phát triển)
- ⭐ Đánh giá sản phẩm
- 🎯 Chi tiết sản phẩm với Hero animation

## Cài đặt

1. Clone repository
2. Chạy `flutter pub get` để cài đặt dependencies
3. Chạy `flutter run` để khởi động ứng dụng

## Cấu trúc dự án

\`\`\`
lib/
├── main.dart                 # Entry point
├── models/                   # Data models
│   ├── toy.dart
│   └── cart_item.dart
├── screens/                  # Màn hình chính
│   ├── home_screen.dart
│   ├── toy_detail_screen.dart
│   └── cart_screen.dart
├── widgets/                  # Components tái sử dụng
│   ├── toy_card.dart
│   ├── category_chip.dart
│   └── custom_button.dart
├── providers/                # State management
│   └── cart_provider.dart
└── data/                     # Sample data
    └── toy_data.dart
\`\`\`

## Công nghệ sử dụng

- Flutter SDK
- Google Fonts (Poppins)
- Material Design 3
- Provider (state management)

## Màu sắc

- Primary: #FF6B9D (Hồng)
- Secondary: #4ECDC4 (Xanh mint)
- Tertiary: #FFC857 (Vàng)
- Surface: #FAFAFA (Xám nhạt)

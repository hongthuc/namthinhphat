<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT | namthinhphat.com</title>
    <meta name="description" content="CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT - Chuyên Tư vấn, Thiết kế Kiến trúc, Thi công Xây dựng trọn gói và Nội thất uy tín tại Đà Nẵng. Hotline: 0905.005.003.">

    <!-- Open Graph / Thumbnail chia sẻ link trang web sử dụng Logo Nam Thịnh Phát -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="NAM THỊNH PHÁT">
    <meta property="og:url" content="https://namthinhphat.com/">
    <meta property="og:title" content="CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT">
    <meta property="og:description" content="Thiết kế Kiến trúc - Thi công Xây dựng trọn gói - Nội thất chuyên nghiệp tại Đà Nẵng. Hotline: 0905.005.003.">
    <meta property="og:image" content="https://namthinhphat.com/wp-content/uploads/logo-nam-thinh-phat-og.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Dịch Vụ - Tư Vấn Thiết Kế Nam Thịnh Phát">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT">
    <meta name="twitter:description" content="Thiết kế Kiến trúc - Thi công Xây dựng - Nội thất tại Đà Nẵng. Hotline: 0905.005.003.">
    <meta name="twitter:image" content="https://namthinhphat.com/wp-content/uploads/logo-nam-thinh-phat-og.png">

    <!-- Favicon sử dụng Logo Vector Nam Thịnh Phát -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2C59'/%3E%3Cpath d='M12 46V24L32 11L52 24V46H44V28L32 20L20 28V46H12Z' fill='%23D49A2A'/%3E%3Cpath d='M25 46V31H39V46H34V36H30V46H25Z' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình màu sắc chủ đạo đồng bộ theo Logo Nam Thịnh Phát -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        ntpNavy: {
                            DEFAULT: '#0F2C59',
                            dark: '#091D3D',
                            light: '#1B427E',
                            soft: '#EEF3FA'
                        },
                        ntpGold: {
                            DEFAULT: '#C9932C',
                            light: '#E2B04B',
                            dark: '#A4741D',
                            soft: '#FBF5E8'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* =========================================================
           THIẾT LẬP CƠ BẢN & CHỐNG TRÀN VIỀN / LỆCH PHẢI
           ========================================================= */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chuẩn Flatsome: Chiều ngang bằng 95% màn hình máy tính, không tràn viền */
        .ntp-container {
            width: 94%;
            max-width: 94%;
            margin-left: auto;
            margin-right: auto;
        }

        @media (min-width: 1024px) {
            .ntp-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UXBuilder */
        .flatsome-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .flatsome-heading::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background-color: #C9932C;
            border-radius: 2px;
        }
        .flatsome-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Dropdown Menu Flatsome mượt mà */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown,
        .nav-item:focus-within .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner Slider 2 ảnh bằng kích thước tuyệt đối */
        .banner-grid-stage {
            display: grid;
            grid-template-columns: 1fr;
            width: 100%;
        }
        .banner-slide {
            grid-area: 1 / 1 / 2 / 2;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
            pointer-events: none;
            z-index: 1;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
            z-index: 2;
        }

        /* Hiệu ứng nhịp nhẹ cho nút Hotline nổi */
        @keyframes ntpPulse {
            0% {
                box-shadow: 0 0 0 0 rgba(201, 147, 44, 0.55);
            }
            70% {
                box-shadow: 0 0 0 12px rgba(201, 147, 44, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(201, 147, 44, 0);
            }
        }
        .ntp-pulse {
            animation: ntpPulse 2s infinite;
        }

        /* Ảnh sản phẩm tỷ lệ chuẩn, mượt khi hover */
        .card-img-wrap {
            overflow: hidden;
            aspect-ratio: 4 / 3;
            background-color: #EEF3FA;
        }
        .card-img-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
            display: block;
        }
        .project-card:hover .card-img-wrap img {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- =========================================================
         TOP BAR THÔNG TIN NHANH (CHUẨN FLATSOME)
         ========================================================= -->
    <div class="bg-ntpNavy text-white text-xs border-b border-ntpNavy-light/40">
        <div class="ntp-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="font-medium text-white/95">CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT</span>
                <span class="hidden md:inline text-white/40">|</span>
                <span class="hidden md:inline text-white/85">Tổ 2, Thanh Quýt 2, Phường An Thắng, TP Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-3">
                <a href="tel:0905005003" class="hover:text-ntpGold-light transition-colors font-semibold">Hotline: 0905.005.003</a>
                <span class="text-white/40">|</span>
                <a href="mailto:lienhe@namthinhphat.com" class="hover:text-ntpGold-light transition-colors hidden sm:inline">lienhe@namthinhphat.com</a>
            </div>
        </div>
    </div>

    <!-- =========================================================
         HEADER CHÍNH (LOGO GỌN NHỎ + MENU 1 HÀNG KHÔNG NÚT GỌI NGAY)
         ========================================================= -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="ntp-container h-16 lg:h-[72px] flex items-center justify-between gap-3">
            <!-- Logo Công ty Nam Thịnh Phát thiết kế gọn nhỏ, chuyên nghiệp -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="Nam Thịnh Phát Trang chủ">
                <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Nam Thịnh Phát">
                    <rect width="64" height="64" rx="10" fill="#0F2C59"/>
                    <path d="M11 47V24.5L32 11L53 24.5V47H45.5V28.5L32 19.8L18.5 28.5V47H11Z" fill="#C9932C"/>
                    <path d="M23.5 47V31.5H40.5V47H35.2V36.5H28.8V47H23.5Z" fill="#FFFFFF"/>
                    <rect x="11" y="50" width="42" height="3.2" rx="1.6" fill="#C9932C"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm lg:text-[15px] font-extrabold tracking-tight text-ntpNavy group-hover:text-ntpGold transition-colors whitespace-nowrap">
                        NAM THỊNH PHÁT
                    </div>
                    <div class="text-[9.5px] lg:text-[10px] font-semibold tracking-wider text-ntpGold uppercase whitespace-nowrap">
                        Tư Vấn - Thiết Kế - Xây Dựng
                    </div>
                </div>
            </a>

            <!-- Menu Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng, không nút gọi ngay -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-5" aria-label="Menu chính">
                <a href="#trang-chu" class="text-[12.5px] xl:text-[13px] font-semibold text-ntpNavy hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                    Giới thiệu
                </a>

                <!-- Dropdown: Công trình thực tế (giống mẫu tintruongthinh.com) -->
                <div class="relative nav-item">
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                        Công trình thực tế
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                            <a href="#cong-trinh-thuc-te" onclick="selectCategory('khach-san')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectCategory('biet-thu')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectCategory('nha-pho')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectCategory('van-phong')" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="relative nav-item">
                    <a href="#dich-vu-tieu-bieu" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                        Lĩnh vực hoạt động
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                            <a href="#dich-vu-tieu-bieu" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#dich-vu-tieu-bieu" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Thi công phần thô</a>
                            <a href="#dich-vu-tieu-bieu" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Thi công hoàn thiện</a>
                            <a href="#dich-vu-tieu-bieu" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Mẫu thiết kế -->
                <div class="relative nav-item">
                    <a href="#du-an-da-nang" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                        Dự án Đà Nẵng
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Mẫu thiết kế nhà phố</a>
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Mẫu thiết kế nội thất</a>
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Dự án thi công Đà Nẵng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Báo giá -->
                <div class="relative nav-item">
                    <a href="#bao-gia" class="inline-flex items-center gap-1 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                        Báo giá
                        <svg class="w-3.5 h-3.5 text-slate-400" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full pt-1 w-60 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-ntpNavy-soft hover:text-ntpNavy font-medium">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#tin-tuc" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                    Tin tức
                </a>
                <a href="#lien-he" class="text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-ntpGold transition-colors whitespace-nowrap py-2">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút Menu Mobile -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-ntpNavy hover:bg-ntpNavy-soft transition-colors" aria-label="Mở menu điều hướng">
                <svg id="iconMenuOpen" class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
                <svg id="iconMenuClose" class="w-6 h-6 hidden" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/>
                </svg>
            </button>
        </div>

        <!-- Menu Mobile thả xuống chuẩn Flatsome -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="ntp-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-3 text-ntpNavy">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-3 hover:text-ntpGold">Giới thiệu</a>
                <div class="py-2">
                    <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="block py-1.5 text-ntpNavy">Công trình thực tế</a>
                    <div class="pl-4 flex flex-col gap-1 text-[13px] font-medium text-slate-600 pb-1">
                        <a href="#cong-trinh-thuc-te" onclick="selectCategory('khach-san'); closeMobileMenu();" class="py-1.5 hover:text-ntpGold">• Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh-thuc-te" onclick="selectCategory('biet-thu'); closeMobileMenu();" class="py-1.5 hover:text-ntpGold">• Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="selectCategory('nha-pho'); closeMobileMenu();" class="py-1.5 hover:text-ntpGold">• Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="selectCategory('van-phong'); closeMobileMenu();" class="py-1.5 hover:text-ntpGold">• Văn phòng</a>
                    </div>
                </div>
                <div class="py-2">
                    <a href="#dich-vu-tieu-bieu" onclick="closeMobileMenu()" class="block py-1.5 text-ntpNavy">Lĩnh vực hoạt động</a>
                    <div class="pl-4 flex flex-col gap-1 text-[13px] font-medium text-slate-600 pb-1">
                        <a href="#dich-vu-tieu-bieu" onclick="closeMobileMenu()" class="py-1.5 hover:text-ntpGold">• Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#dich-vu-tieu-bieu" onclick="closeMobileMenu()" class="py-1.5 hover:text-ntpGold">• Thi công phần thô & Hoàn thiện</a>
                        <a href="#dich-vu-tieu-bieu" onclick="closeMobileMenu()" class="py-1.5 hover:text-ntpGold">• Thi công nội thất trọn gói</a>
                    </div>
                </div>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-3 hover:text-ntpGold">Dự án tại Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-3 hover:text-ntpGold">Báo giá thi công</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-3 hover:text-ntpGold">Tin tức & Kiến thức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-3 hover:text-ntpGold">Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================
         HERO BANNER SLIDER: 2 ẢNH TỰ TRƯỢT BẰNG NHAU, CHỮ NẰM GỌN TRONG BANNER
         ========================================================= -->
    <section id="trang-chu" class="w-full bg-ntpNavy-dark py-4 sm:py-6">
        <div class="ntp-container">
            <div id="heroSlider" class="relative rounded-xl overflow-hidden shadow-xl border border-white/10">
                <div class="banner-grid-stage">

                    <!-- BANNER 1: THIẾT KẾ & THI CÔNG XÂY DỰNG TRỌN GÓI -->
                    <div class="banner-slide active relative w-full bg-ntpNavy-dark">
                        <!-- Ảnh nền công trình thực tế với lớp phủ đảm bảo chữ nổi bật -->
                        <img
                            src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                            data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                            data-fallback="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1600&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Thi công xây dựng trọn gói Nam Thịnh Phát"
                            class="absolute inset-0 w-full h-full object-cover opacity-35"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-ntpNavy-dark/95 via-ntpNavy/85 to-ntpNavy-dark/70"></div>

                        <!-- Vùng chữ cách xa viền ảnh banner (px-8 sm:px-14 md:px-20 py-10 sm:py-14 lg:py-16), đảm bảo không thiếu chữ trên mọi màn hình -->
                        <div class="relative z-10 px-8 sm:px-14 md:px-20 py-10 sm:py-14 lg:py-16 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-ntpGold-light">
                                    CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT
                                </p>
                                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                    Thiết Kế Kiến Trúc & Thi Công Xây Dựng Trọn Gói Tại Đà Nẵng
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-[15px] text-slate-200 leading-relaxed max-w-2xl">
                                    Kiến tạo không gian sống đẳng cấp với tiêu chuẩn kỹ thuật nghiêm ngặt: An Toàn – Chất Lượng – Đúng Tiến Độ – Tối Ưu Chi Phí cho Nhà phố, Biệt thự, Khách sạn và Căn hộ.
                                </p>
                                <div class="pt-2 flex flex-wrap items-center gap-3">
                                    <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-ntpGold hover:bg-ntpGold-light text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
                                        Nhận Báo Giá Miễn Phí
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition-colors">
                                        Xem Công Trình Thực Tế
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh công trình nằm gọn trong banner -->
                            <div class="hidden lg:block lg:col-span-5">
                                <div class="rounded-xl overflow-hidden border-2 border-ntpGold/60 shadow-2xl aspect-[16/10] bg-ntpNavy">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                                        data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                        data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1000&q=80"
                                        onerror="handleDriveImgError(this)"
                                        alt="Công trình kiến trúc Nam Thịnh Phát"
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2: TƯ VẤN THIẾT KẾ CHUYÊN SÂU & THI CÔNG NỘI THẤT -->
                    <div class="banner-slide relative w-full bg-ntpNavy-dark">
                        <img
                            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                            data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                            data-fallback="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1600&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Dự án tiêu biểu tại Đà Nẵng Nam Thịnh Phát"
                            class="absolute inset-0 w-full h-full object-cover opacity-35"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-ntpNavy-dark/95 via-ntpNavy/85 to-ntpNavy-dark/70"></div>

                        <!-- Vùng chữ cách xa viền ảnh banner giống hệt Banner 1 để kích thước 2 banner bằng nhau 100% -->
                        <div class="relative z-10 px-8 sm:px-14 md:px-20 py-10 sm:py-14 lg:py-16 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs font-bold uppercase tracking-[0.18em] text-ntpGold-light">
                                    NAMTHINHPHAT.COM • NHÀ THẦU XÂY DỰNG UY TÍN ĐÀ NẴNG
                                </p>
                                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                    Giải Pháp Thiết Kế Hiện Đại – Thi Công Bền Vững & Bảo Hành Dài Lâu
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-[15px] text-slate-200 leading-relaxed max-w-2xl">
                                    Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm đồng hành từ khâu xin phép xây dựng, thiết kế 3D, thi công phần thô đến hoàn thiện chìa khóa trao tay không phát sinh chi phí.
                                </p>
                                <div class="pt-2 flex flex-wrap items-center gap-3">
                                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-ntpGold hover:bg-ntpGold-light text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
                                        Khám Phá Dự Án Đà Nẵng
                                    </a>
                                    <a href="tel:0905005003" class="inline-flex items-center justify-center px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition-colors">
                                        Tư Vấn Trực Tiếp: 0905.005.003
                                    </a>
                                </div>
                            </div>

                            <div class="hidden lg:block lg:col-span-5">
                                <div class="rounded-xl overflow-hidden border-2 border-ntpGold/60 shadow-2xl aspect-[16/10] bg-ntpNavy">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                                        data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                        data-fallback="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1000&q=80"
                                        onerror="handleDriveImgError(this)"
                                        alt="Thi công hoàn thiện nội ngoại thất Đà Nẵng"
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng 2 bên banner gọn gàng -->
                <button id="prevBannerBtn" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-ntpGold text-white flex items-center justify-center transition-colors">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button id="nextBannerBtn" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-ntpGold text-white flex items-center justify-center transition-colors">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Dấu chấm chuyển slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" class="banner-dot w-7 h-2 rounded-full bg-ntpGold transition-all" data-slide="0" aria-label="Chọn banner 1"></button>
                    <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-slide="1" aria-label="Chọn banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         DỊCH VỤ TIÊU BIỂU (CHUẨN BỐ CỤC TINTRUONGTHINH.COM - FLATSOME)
         ========================================================= -->
    <section id="dich-vu-tieu-bieu" class="py-10 sm:py-14 bg-white">
        <div class="ntp-container">
            <div class="text-center mb-8 sm:mb-10">
                <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-ntpNavy uppercase tracking-tight">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ Tư vấn thiết kế kiến trúc, Thi công xây dựng phần thô đến Hoàn thiện nội thất trọn gói.
                </p>
            </div>

            <!-- 3 Cột dịch vụ cốt lõi (dễ dựng lại bằng 3 Cols Image Box trong Flatsome UXBuilder) -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-5 lg:gap-7">
                <!-- Dịch vụ 1: Thiết kế -->
                <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-shadow flex flex-col">
                    <div class="card-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w900"
                            data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                            data-fallback="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=900&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Thiết kế kiến trúc và nội thất"
                        >
                    </div>
                    <div class="p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-ntpNavy uppercase group-hover:text-ntpGold transition-colors">
                                THIẾT KẾ KIẾN TRÚC
                            </h3>
                            <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Tư vấn thiết kế nhà phố, biệt thự, khách sạn, căn hộ và văn phòng tối ưu công năng, phong thủy và thẩm mỹ hiện đại.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-4 inline-block text-xs sm:text-sm font-bold text-ntpGold hover:text-ntpNavy transition-colors">
                            Nhận báo giá thiết kế →
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2: Thi công -->
                <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-shadow flex flex-col">
                    <div class="card-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                            data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                            data-fallback="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=900&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Thi công xây dựng phần thô và trọn gói"
                        >
                    </div>
                    <div class="p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-ntpNavy uppercase group-hover:text-ntpGold transition-colors">
                                THI CÔNG XÂY DỰNG
                            </h3>
                            <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay, cam kết vật tư chuẩn và đúng tiến độ.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-4 inline-block text-xs sm:text-sm font-bold text-ntpGold hover:text-ntpNavy transition-colors">
                            Nhận báo giá thi công →
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3: Nội thất -->
                <div class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-shadow flex flex-col">
                    <div class="card-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900"
                            data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                            data-fallback="https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=900&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Thi công nội thất hoàn thiện"
                        >
                    </div>
                    <div class="p-5 text-center flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-base sm:text-lg font-extrabold text-ntpNavy uppercase group-hover:text-ntpGold transition-colors">
                                THI CÔNG NỘI THẤT
                            </h3>
                            <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Thiết kế và lắp đặt nội thất gỗ cao cấp cho phòng khách, bếp, phòng ngủ, căn hộ và văn phòng sang trọng, bền đẹp.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-4 inline-block text-xs sm:text-sm font-bold text-ntpGold hover:text-ntpNavy transition-colors">
                            Nhận báo giá nội thất →
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI
         ========================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-slate-50 border-y border-slate-200/80">
        <div class="ntp-container">
            <!-- Hàng 1: Giới thiệu công ty (2 cột Flatsome) -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-7 lg:gap-10 items-center mb-12">
                <div class="lg:col-span-6 space-y-4">
                    <h2 class="flatsome-heading flatsome-heading-left text-lg sm:text-2xl font-extrabold text-ntpNavy uppercase leading-snug">
                        CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        <strong>NAM THỊNH PHÁT</strong> chuyên Tư vấn – Thiết kế – Thi công Xây dựng & Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng và Nhà phố tại khu vực <strong>TP. Đà Nẵng</strong> và miền Trung.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Với phương châm <strong>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</strong>, chúng tôi đặt chữ <strong>“TÂM”</strong> trong từng hạng mục thi công để mỗi dự án bàn giao luôn đạt chuẩn <strong>An Toàn – Chất Lượng – Tiến Độ – Sự Hài Lòng Của Khách Hàng</strong>.
                    </p>
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-ntpGold">10+</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Năm kinh nghiệm</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-ntpNavy">150+</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Công trình bàn giao</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-ntpGold">100%</div>
                            <div class="text-[11px] sm:text-xs font-medium text-slate-600 mt-0.5">Cam kết bảo hành</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-6">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 aspect-[16/10] bg-ntpNavy-soft">
                        <img
                            src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1200"
                            data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                            data-fallback="https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&w=1200&q=80"
                            onerror="handleDriveImgError(this)"
                            alt="Đội ngũ thi công công trình Nam Thịnh Phát"
                            class="w-full h-full object-cover"
                        >
                    </div>
                </div>
            </div>

            <!-- Hàng 2: 6 Thế mạnh của chúng tôi (Flatsome Icon Box Grid) -->
            <div class="text-center mb-8">
                <h3 class="flatsome-heading text-lg sm:text-xl lg:text-2xl font-extrabold text-ntpNavy uppercase">
                    Thế Mạnh Của Chúng Tôi
                </h3>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpNavy-soft text-ntpNavy flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Đội ngũ KTS & kỹ sư chuyên nghiệp</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư hiện trường và thợ lành nghề nhiều năm kinh nghiệm.</p>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpGold-soft text-ntpGold flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Cập nhật xu hướng hiện đại</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Ứng dụng vật liệu mới, giải pháp không gian thông minh và quy trình thi công tối ưu nhất.</p>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpNavy-soft text-ntpNavy flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Giám sát tiến độ chuẩn xác</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Báo cáo tiến độ thi công định kỳ minh bạch, đảm bảo bàn giao đúng thời gian cam kết.</p>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpGold-soft text-ntpGold flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Bảo hành công trình lâu dài</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Chế độ hậu mãi rõ ràng, bảo hành kết cấu dài hạn và hỗ trợ bảo trì nhanh chóng khi cần.</p>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpNavy-soft text-ntpNavy flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Chi phí hợp lý, minh bạch</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục ngay từ đầu, tối ưu ngân sách và cam kết không phát sinh.</p>
                    </div>
                </div>

                <div class="bg-white p-5 rounded-xl border border-slate-200 flex items-start gap-4 hover:border-ntpGold transition-colors">
                    <div class="w-11 h-11 rounded-lg bg-ntpGold-soft text-ntpGold flex items-center justify-center shrink-0">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    </div>
                    <div>
                        <h4 class="text-sm sm:text-[15px] font-bold text-ntpNavy">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="mt-1 text-xs sm:text-[13px] text-slate-600 leading-relaxed">Luôn sẵn sàng lắng nghe, khảo sát thực tế và tư vấn phương án phù hợp nhất cho gia chủ.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         CÔNG TRÌNH THỰC TẾ (9 ẢNH GOOGLE DRIVE THI CÔNG XÂY DỰNG)
         - Danh mục nhỏ gọn, viết liền không xuống dòng tên danh mục
         - Chia 2 cột trên điện thoại, KHÔNG nhãn dán, KHÔNG tràn chữ
         ========================================================= -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
        <div class="ntp-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-ntpNavy uppercase tracking-tight">
                    Công Trình Thi Công Thực Tế
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500 max-w-2xl mx-auto">
                    Hình ảnh thực tế các hạng mục thiết kế và thi công xây dựng do Nam Thịnh Phát trực tiếp triển khai.
                </p>
            </div>

            <!-- Thanh Danh Mục Sản Phẩm / Công Trình: Chữ nhỏ gọn, từng tên danh mục viết liền trên 1 hàng -->
            <div id="categoryFilterBar" class="flex flex-wrap items-center justify-center gap-2 sm:gap-2.5 mb-7 sm:mb-9">
                <button type="button" data-cat="all" class="cat-tab active px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap border transition-colors bg-ntpNavy text-white border-ntpNavy">
                    Tất cả
                </button>
                <button type="button" data-cat="nha-pho" class="cat-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap border transition-colors bg-white text-slate-700 border-slate-200 hover:border-ntpNavy hover:text-ntpNavy">
                    Nhà phố
                </button>
                <button type="button" data-cat="biet-thu" class="cat-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap border transition-colors bg-white text-slate-700 border-slate-200 hover:border-ntpNavy hover:text-ntpNavy">
                    Biệt thự
                </button>
                <button type="button" data-cat="khach-san" class="cat-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap border transition-colors bg-white text-slate-700 border-slate-200 hover:border-ntpNavy hover:text-ntpNavy">
                    Khách sạn – Căn hộ
                </button>
                <button type="button" data-cat="van-phong" class="cat-tab px-3.5 py-1.5 sm:px-4 sm:py-2 rounded-lg text-xs sm:text-[13px] font-semibold whitespace-nowrap border transition-colors bg-white text-slate-700 border-slate-200 hover:border-ntpNavy hover:text-ntpNavy">
                    Văn phòng
                </button>
            </div>

            <!-- Lưới 9 Công Trình Thi Công Thực Tế (2 cột trên mobile, 3 cột trên desktop, sạch đẹp không nhãn dán) -->
            <div id="constructionGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3.5 sm:gap-5 lg:gap-6">
                <!-- Render tự động bằng JavaScript từ 9 link Google Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH GOOGLE DRIVE DỰ ÁN)
         - Chia 2 cột trên điện thoại, 5 cột trên máy tính (2 hàng 5 ảnh cân đối)
         - Không nhãn dán, tên sản phẩm đầy đủ rõ nét
         ========================================================= -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-ntpNavy-soft/50 border-y border-slate-200/80">
        <div class="ntp-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-ntpNavy uppercase tracking-tight">
                    Các Dự Án Tại Đà Nẵng
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500 max-w-2xl mx-auto">
                    Những công trình nhà ở, biệt thự, căn hộ và văn phòng nổi bật được Nam Thịnh Phát thiết kế và thi công tại TP. Đà Nẵng.
                </p>
            </div>

            <!-- Lưới 10 Dự Án Đà Nẵng: 2 cột trên điện thoại, 5 cột trên desktop -->
            <div id="danangProjectsGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3.5 sm:gap-5">
                <!-- Render tự động bằng JavaScript từ 10 link Google Drive dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (CHUẨN TINTRUONGTHINH.COM)
         ========================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-ntpNavy text-white">
        <div class="ntp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center">
                <!-- Cột trái: Bảng thông tin báo giá nhanh -->
                <div class="lg:col-span-5 space-y-5">
                    <div>
                        <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl font-extrabold text-white uppercase">
                            Đăng Ký Tư Vấn & Báo Giá
                        </h2>
                        <p class="mt-3 text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Để lại thông tin công trình dự kiến của bạn, kỹ sư Nam Thịnh Phát sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết hoàn toàn miễn phí trong vòng 30 phút.
                        </p>
                    </div>

                    <div class="space-y-3">
                        <div class="p-3.5 rounded-lg bg-white/10 border border-white/15 flex items-center justify-between gap-3">
                            <span class="text-xs sm:text-sm font-semibold">Thiết kế Kiến trúc – Nội thất</span>
                            <span class="text-xs sm:text-sm font-bold text-ntpGold-light whitespace-nowrap">Báo giá theo m²</span>
                        </div>
                        <div class="p-3.5 rounded-lg bg-white/10 border border-white/15 flex items-center justify-between gap-3">
                            <span class="text-xs sm:text-sm font-semibold">Thi công phần thô & nhân công</span>
                            <span class="text-xs sm:text-sm font-bold text-ntpGold-light whitespace-nowrap">Tối ưu chi phí</span>
                        </div>
                        <div class="p-3.5 rounded-lg bg-white/10 border border-white/15 flex items-center justify-between gap-3">
                            <span class="text-xs sm:text-sm font-semibold">Thi công xây nhà trọn gói</span>
                            <span class="text-xs sm:text-sm font-bold text-ntpGold-light whitespace-nowrap">Miễn phí hồ sơ XPXD</span>
                        </div>
                    </div>

                    <div class="pt-1 text-xs sm:text-sm text-slate-200 space-y-1.5">
                        <p><strong class="text-ntpGold-light">Hotline hỗ trợ 24/7:</strong> <a href="tel:0905005003" class="underline hover:text-white">0905.005.003</a></p>
                        <p><strong class="text-ntpGold-light">Địa chỉ:</strong> Tổ 2, Thanh Quýt 2, Phường An Thắng, TP Đà Nẵng</p>
                    </div>
                </div>

                <!-- Cột phải: Form yêu cầu và báo giá -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
                        <h3 class="text-base sm:text-lg font-extrabold text-ntpNavy uppercase border-b border-slate-100 pb-3">
                            Miễn Phí Tư Vấn & Khái Toán Chi Phí
                        </h3>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                <input id="qName" name="name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại *</label>
                                <input id="qPhone" name="phone" type="tel" required placeholder="Nhập số điện thoại / Zalo" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                <select id="qType" name="type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn - Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa & Nội thất</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" name="budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email (không bắt buộc)</label>
                            <input id="qEmail" name="email" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15">
                        </div>

                        <div>
                            <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu cụ thể (Diện tích, số tầng, địa điểm xây dựng...)</label>
                            <textarea id="qNote" name="note" rows="3" placeholder="Ví dụ: Đất 5x20m tại Hòa Xuân, Đà Nẵng, dự kiến xây nhà 3 tầng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-ntpNavy focus:ring-2 focus:ring-ntpNavy/15"></textarea>
                        </div>

                        <!-- Thông báo phản hồi trực tiếp (không dùng alert) -->
                        <div id="quoteFeedback" class="hidden p-3.5 rounded-lg text-xs sm:text-sm font-medium"></div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-ntpGold hover:bg-ntpGold-dark text-white font-bold text-sm uppercase tracking-wide shadow-md transition-colors">
                            Gửi Yêu Cầu Nhận Báo Giá Ngay
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         TIN TỨC & KIẾN THỨC XÂY DỰNG TRANG CHỦ
         ========================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
        <div class="ntp-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-ntpNavy uppercase tracking-tight">
                    Tin Tức & Cẩm Nang Xây Dựng
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500 max-w-2xl mx-auto">
                    Chia sẻ kinh nghiệm thiết kế kiến trúc, kỹ thuật thi công và dự toán xây dựng hữu ích cho chủ đầu tư.
                </p>
            </div>

            <!-- Lưới 4 bài viết trang chủ (2 cột trên điện thoại, 4 cột trên desktop) -->
            <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3.5 sm:gap-5">
                <!-- Render tự động bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         ĐỐI TÁC TIÊU BIỂU
         ========================================================= -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-slate-50 border-t border-slate-200/80">
        <div class="ntp-container">
            <div class="text-center mb-7">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold text-ntpNavy uppercase tracking-tight">
                    Đối Tác Đồng Hành
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500">
                    Hợp tác cùng các thương hiệu vật liệu xây dựng & nội thất hàng đầu đảm bảo chất lượng công trình bền vững.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3 sm:gap-4">
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">AN CƯỜNG</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gỗ Nội Thất</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn Cao Cấp</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">JOTUN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn Bảo Vệ</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">XINGFA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Nhôm Kính</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">TOTO</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">PANASONIC</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị Điện</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col items-center justify-center text-center hover:border-ntpGold transition-colors min-h-[76px]">
                    <span class="text-sm font-extrabold text-ntpNavy tracking-tight">VIGLACERA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Gạch Ốp Lát</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         ========================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white border-t border-slate-200/80">
        <div class="ntp-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-ntpNavy uppercase tracking-tight">
                    Vị Trí Công Ty & Kết Nối Fanpage
                </h2>
                <p class="mt-3 text-xs sm:text-sm text-slate-500">
                    Trụ sở: Tổ 2, Thanh Quýt 2, Phường An Thắng, TP Đà Nẵng • Hotline: 0905.005.003
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Trái (7 cột): Google Map nhúng trực tiếp -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 bg-ntpNavy text-white flex items-center justify-between gap-2">
                        <span class="text-xs sm:text-sm font-bold">Bản Đồ Chỉ Đường – Nam Thịnh Phát Đà Nẵng</span>
                        <a href="https://www.google.com/maps/search/?api=1&query=Thanh+Qu%C3%BDt+2,+An+Th%E1%BA%AFng,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-ntpGold-light hover:underline whitespace-nowrap">
                            Mở Google Maps ↗
                        </a>
                    </div>
                    <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty TNHH Dịch Vụ - Tư Vấn Thiết Kế Nam Thịnh Phát"
                            src="https://maps.google.com/maps?q=Thanh+Qu%C3%BDt+2,+An+Th%E1%BA%AFng,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Cột Phải (5 cột): Khung Fanpage Facebook ngay ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
                            <span class="text-xs sm:text-sm font-bold flex items-center gap-2">
                                <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                                Fanpage Facebook Chính Thức
                            </span>
                            <span class="text-[11px] text-white/85">Trực tuyến</span>
                        </div>

                        <!-- Ảnh bìa Fanpage & Avatar Logo -->
                        <div class="relative h-36 bg-ntpNavy overflow-hidden">
                            <img
                                src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800"
                                data-drive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                                data-fallback="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80"
                                onerror="handleDriveImgError(this)"
                                alt="Ảnh bìa Fanpage Nam Thịnh Phát"
                                class="w-full h-full object-cover opacity-55"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                            <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                <div class="w-12 h-12 rounded-lg bg-white p-1 shadow-md shrink-0">
                                    <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="64" height="64" rx="8" fill="#0F2C59"/>
                                        <path d="M11 47V24.5L32 11L53 24.5V47H45.5V28.5L32 19.8L18.5 28.5V47H11Z" fill="#C9932C"/>
                                        <path d="M23.5 47V31.5H40.5V47H35.2V36.5H28.8V47H23.5Z" fill="#FFFFFF"/>
                                    </svg>
                                </div>
                                <div class="text-white min-w-0">
                                    <div class="text-sm font-bold leading-tight">Nam Thịnh Phát – Tư Vấn Thiết Kế & Xây Dựng</div>
                                    <div class="text-[11px] text-white/85 mt-0.5">namthinhphat.com • TP. Đà Nẵng</div>
                                </div>
                            </div>
                        </div>

                        <!-- Nội dung cập nhật mới trên Fanpage -->
                        <div class="p-4 space-y-3">
                            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
                                Theo dõi Fanpage <strong>Nam Thịnh Phát</strong> để cập nhật hình ảnh thi công thực tế mỗi ngày, mẫu thiết kế nhà đẹp tại Đà Nẵng và bảng giá xây dựng mới nhất.
                            </p>
                            <div class="grid grid-cols-3 gap-2">
                                <div class="aspect-square rounded-lg overflow-hidden bg-slate-100">
                                    <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w400" data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k" data-fallback="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=400&q=80" onerror="handleDriveImgError(this)" alt="Ảnh công trình 1" class="w-full h-full object-cover">
                                </div>
                                <div class="aspect-square rounded-lg overflow-hidden bg-slate-100">
                                    <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w400" data-drive-id="1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N" data-fallback="https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=400&q=80" onerror="handleDriveImgError(this)" alt="Ảnh công trình 2" class="w-full h-full object-cover">
                                </div>
                                <div class="aspect-square rounded-lg overflow-hidden bg-slate-100">
                                    <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w400" data-drive-id="1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML" data-fallback="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=400&q=80" onerror="handleDriveImgError(this)" alt="Ảnh công trình 3" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="px-4 pb-4 grid grid-cols-2 gap-2.5">
                        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white text-xs font-bold text-center transition-colors">
                            Thích Trang Facebook
                        </a>
                        <a href="https://zalo.me/0905005003" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-ntpNavy hover:bg-ntpNavy-light text-white text-xs font-bold text-center transition-colors">
                            Nhắn Tin Tư Vấn
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FOOTER CHUYÊN NGHIỆP (CHUẨN BỐ CỤC FLATSOME)
         ========================================================= -->
    <footer class="bg-ntpNavy-dark text-slate-300 pt-10 pb-6 border-t-4 border-ntpGold">
        <div class="ntp-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin pháp lý công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="10" fill="#1B427E"/>
                            <path d="M11 47V24.5L32 11L53 24.5V47H45.5V28.5L32 19.8L18.5 28.5V47H11Z" fill="#C9932C"/>
                            <path d="M23.5 47V31.5H40.5V47H35.2V36.5H28.8V47H23.5Z" fill="#FFFFFF"/>
                        </svg>
                        <div>
                            <div class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT</div>
                            <div class="text-[11px] text-ntpGold-light font-semibold">Website: namthinhphat.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-[13px] leading-relaxed pt-1">
                        <li><strong class="text-white">Mã số thuế:</strong> 4001320419</li>
                        <li><strong class="text-white">Trụ sở chính:</strong> Tổ 2, Thanh Quýt 2, Phường An Thắng, TP Đà Nẵng</li>
                        <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0905005003" class="text-ntpGold-light font-semibold hover:underline">0905.005.003</a></li>
                        <li><strong class="text-white">Email:</strong> lienhe@namthinhphat.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider border-b border-ntpGold/50 pb-2 inline-block">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#dich-vu-tieu-bieu" class="hover:text-ntpGold-light transition-colors">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#dich-vu-tieu-bieu" class="hover:text-ntpGold-light transition-colors">• Thi công phần thô chuyên nghiệp</a></li>
                        <li><a href="#dich-vu-tieu-bieu" class="hover:text-ntpGold-light transition-colors">• Thi công hoàn thiện công trình</a></li>
                        <li><a href="#dich-vu-tieu-bieu" class="hover:text-ntpGold-light transition-colors">• Thi công xây dựng trọn gói Đà Nẵng</a></li>
                        <li><a href="#dich-vu-tieu-bieu" class="hover:text-ntpGold-light transition-colors">• Cải tạo & sửa chữa nhà ở, văn phòng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wider border-b border-ntpGold/50 pb-2 inline-block">
                        Liên Kết Nhanh
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-[13px]">
                        <li><a href="#gioi-thieu" class="hover:text-ntpGold-light transition-colors">• Giới thiệu công ty</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-ntpGold-light transition-colors">• Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-ntpGold-light transition-colors">• Các dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-ntpGold-light transition-colors">• Bảng báo giá xây dựng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-ntpGold-light transition-colors">• Tin tức & Kiến thức</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] sm:text-xs text-slate-400">
                <p>Copyright 2026 © <strong class="text-white">CÔNG TY TNHH DỊCH VỤ - TƯ VẤN THIẾT KẾ NAM THỊNH PHÁT</strong>.</p>
                <p>namthinhphat.com • TP. Đà Nẵng</p>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích hoàn hảo trên máy tính và điện thoại
         ========================================================= -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905005003" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Zalo 0905.005.003" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0056D6] text-white pl-3 pr-3 sm:pl-3.5 sm:pr-4 py-2.5 rounded-full shadow-lg transition-all hover:scale-105">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Nam Thịnh Phát" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1261C9] text-white pl-3 pr-3 sm:pl-3.5 sm:pr-4 py-2.5 rounded-full shadow-lg transition-all hover:scale-105">
            <svg class="w-6 h-6 fill-current shrink-0" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905005003" aria-label="Gọi Hotline 0905.005.003" class="ntp-pulse flex items-center gap-2 bg-ntpGold hover:bg-ntpGold-dark text-white px-3.5 sm:px-4 py-2.5 rounded-full shadow-xl transition-all hover:scale-105">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="text-xs sm:text-sm font-extrabold whitespace-nowrap">0905.005.003</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT
         ========================================================= -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/70 p-4 backdrop-blur-xs">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-100 flex items-center justify-between gap-3 z-10">
                <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-ntpNavy leading-snug"></h3>
                <button id="closeModalBtn" type="button" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100 hover:text-ntpNavy" aria-label="Đóng cửa sổ">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-5 space-y-4">
                <div id="modalImageBox" class="rounded-lg overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img id="modalImage" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div id="modalMeta" class="text-xs text-ntpGold font-semibold"></div>
                <div id="modalDesc" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2"></div>
                <div class="pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-3">
                    <a href="tel:0905005003" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-ntpNavy hover:bg-ntpNavy-light text-white text-xs sm:text-sm font-bold">
                        Gọi tư vấn: 0905.005.003
                    </a>
                    <a href="#bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-lg bg-ntpGold hover:bg-ntpGold-dark text-white text-xs sm:text-sm font-bold">
                        Yêu cầu báo giá công trình tương tự
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT: XỬ LÝ ẢNH GOOGLE DRIVE, SLIDER, LỌC DANH MỤC, FORM
         ========================================================= -->
    <script>
        /**
         * Cơ chế tải ảnh Google Drive an toàn nhiều tầng:
         * 1. Thử drive.google.com/thumbnail?id=...&sz=w1000
         * 2. Thử lh3.googleusercontent.com/d/...=w1000
         * 3. Thử drive.google.com/uc?export=view&id=...
         * 4. Nếu file Drive bị giới hạn quyền truy cập, tự động dùng ảnh dự phòng sắc nét
         */
        function handleDriveImgError(img) {
            const driveId = img.getAttribute('data-drive-id');
            const fallback = img.getAttribute('data-fallback');
            const step = parseInt(img.getAttribute('data-retry') || '0', 10);

            if (driveId && step === 0) {
                img.setAttribute('data-retry', '1');
                img.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
            } else if (driveId && step === 1) {
                img.setAttribute('data-retry', '2');
                img.src = `https://drive.google.com/uc?export=view&id=${driveId}`;
            } else if (fallback && step === 2) {
                img.setAttribute('data-retry', '3');
                img.src = fallback;
            } else if (step < 4) {
                img.setAttribute('data-retry', '4');
                img.src = 'https://placehold.co/800x600/0F2C59/C9932C?text=Nam+Thinh+Phat';
            }
        }

        function getDriveThumbUrl(driveId) {
            return `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
        }

        /**
         * DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
         */
        const constructionWorks = [
            {
                id: 'ct-1',
                driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng',
                location: 'TP. Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng được Nam Thịnh Phát thiết kế kiến trúc và thi công xây dựng trọn gói. Kết cấu móng băng vững chắc, tối ưu lấy sáng tự nhiên và không gian sinh hoạt hiện đại.',
                fallback: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-2',
                driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Thi Công Phần Thô Kết Cấu Bê Tông Cốt Thép',
                location: 'An Thắng – TP. Đà Nẵng',
                desc: 'Hạng mục thi công phần thô công trình dân dụng tuân thủ nghiêm ngặt quy trình lắp dựng cốt thép, cốp pha và đổ bê tông thương phẩm đúng mác thiết kế.',
                fallback: 'https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-3',
                driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Thiết Kế & Thi Công Biệt Thự Sân Vườn Cao Cấp',
                location: 'Ngũ Hành Sơn – Đà Nẵng',
                desc: 'Biệt thự vườn phong cách hiện đại với mặt tiền sang trọng, hệ cửa kính cường lực thoáng rộng và quy trình hoàn thiện ngoại thất tỉ mỉ.',
                fallback: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-4',
                driveId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                category: 'khach-san',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Thi Công Xây Dựng Khách Sạn & Căn Hộ Cho Thuê',
                location: 'Sơn Trà – Đà Nẵng',
                desc: 'Công trình căn hộ dịch vụ và khách sạn tối ưu công năng khai thác, đảm bảo hệ thống PCCC, cấp thoát nước và hoàn thiện thẩm mỹ cao.',
                fallback: 'https://images.unsplash.com/photo-1582268611958-ebfd161ef9cf?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-5',
                driveId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                title: 'Thi Công Hoàn Thiện Trụ Sở Văn Phòng Doanh Nghiệp',
                location: 'Hải Châu – Đà Nẵng',
                desc: 'Giải pháp thi công hoàn thiện kiến trúc và nội thất văn phòng làm việc hiện đại, tối ưu ánh sáng, âm học và tiến độ bàn giao nhanh chóng.',
                fallback: 'https://images.unsplash.com/photo-1497366216548-37526070297c?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-6',
                driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                title: 'Thi Công Biệt Thự 2 Mặt Tiền Phong Cách Tân Cổ Điển',
                location: 'Cẩm Lệ – Đà Nẵng',
                desc: 'Công trình biệt thự 2 mặt tiền nổi bật với đường nét phào chỉ tinh tế, sơn ngoại thất chống thấm cao cấp phù hợp khí hậu miền Trung.',
                fallback: 'https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-7',
                driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                category: 'khach-san',
                categoryLabel: 'Khách sạn – Căn hộ',
                title: 'Hoàn Thiện Nội Thất Căn Hộ Dịch Vụ Cao Cấp',
                location: 'Sơn Trà – Đà Nẵng',
                desc: 'Hạng mục sản xuất và lắp đặt nội thất gỗ công nghiệp chống ẩm, thiết bị vệ sinh và ánh sáng trang trí đồng bộ cho căn hộ cho thuê.',
                fallback: 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-8',
                driveId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                title: 'Xây Dựng Nhà Phố Kết Hợp Kinh Doanh 4 Tầng',
                location: 'Thanh Khê – Đà Nẵng',
                desc: 'Thiết kế thông minh kết hợp không gian kinh doanh tầng trệt và khu vực sinh hoạt gia đình tiện nghi các tầng trên.',
                fallback: 'https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=900&q=80'
            },
            {
                id: 'ct-9',
                driveId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                title: 'Tư Vấn Giám Sát & Thi Công Cải Tạo Công Trình',
                location: 'TP. Đà Nẵng',
                desc: 'Dịch vụ khảo sát hiện trạng, cải tạo nâng tầng, chống thấm và nâng cấp kết cấu công trình nhà phố, văn phòng an toàn và tiết kiệm.',
                fallback: 'https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=900&q=80'
            }
        ];

        /**
         * DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE
         */
        const danangProjects = [
            {
                driveId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại Khu Đô Thị Hòa Xuân – Cẩm Lệ',
                location: 'Hòa Xuân, Đà Nẵng',
                desc: 'Dự án thiết kế và thi công trọn gói nhà phố 3 tầng hiện đại tại Khu đô thị sinh thái Hòa Xuân, Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1600585154526-990dced4db0d?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Phố Khu Nam Việt Á – Ngũ Hành Sơn',
                location: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Thiết kế kiến trúc biệt thự kết hợp sân vườn xanh mát và hồ cá Koi tại khu Nam Việt Á, Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1600566753376-12c8ab7fb75b?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Căn Hộ Cho Thuê Ven Biển – Quận Sơn Trà',
                location: 'Sơn Trà, Đà Nẵng',
                desc: 'Thi công trọn gói tòa nhà căn hộ dịch vụ 5 tầng gần biển Mỹ Khê, tối ưu số phòng khai thác và tiện ích.',
                fallback: 'https://images.unsplash.com/photo-1560448204-e02f11c3d0e2?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Khách Sạn Boutique Trung Tâm – Quận Hải Châu',
                location: 'Hải Châu, Đà Nẵng',
                desc: 'Tư vấn thiết kế và thi công hoàn thiện khách sạn boutique trung tâm thành phố Đà Nẵng theo tiêu chuẩn 3 sao.',
                fallback: 'https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Nhà Phố 3 Tầng Khu Đô Thị Phước Lý',
                location: 'Liên Chiểu – Cẩm Lệ, Đà Nẵng',
                desc: 'Công trình nhà ở gia đình 3 tầng hiện đại với mặt tiền lam chắn nắng và không gian thông tầng thoáng đãng.',
                fallback: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Thiết Kế & Thi Công Văn Phòng Đường 2 Tháng 9',
                location: 'Hải Châu, Đà Nẵng',
                desc: 'Thi công cải tạo và hoàn thiện nội thất văn phòng đại diện doanh nghiệp trên trục đường 2/9, Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1497366811353-6870744d04b2?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Nhà Ở Gia Đình Trọn Gói Phường An Thắng',
                location: 'An Thắng, TP. Đà Nẵng',
                desc: 'Công trình nhà phố mái Nhật kết hợp sân trước rộng rãi được thi công trọn gói tại Phường An Thắng, TP. Đà Nẵng.',
                fallback: 'https://images.unsplash.com/photo-1600047509807-ba8f99d2cdde?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Biệt Thự Ven Sông Cổ Cò – TP. Đà Nẵng',
                location: 'Ven Sông Cổ Cò, Đà Nẵng',
                desc: 'Biệt thự nghỉ dưỡng cao cấp sở hữu tầm nhìn thoáng rộng, thiết kế mở hòa hợp cùng thiên nhiên.',
                fallback: 'https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Căn Hộ Dịch Vụ Trục Đường Nguyễn Tất Thành',
                location: 'Thanh Khê – Liên Chiểu, Đà Nẵng',
                desc: 'Dự án căn hộ cho thuê hiện đại gần vịnh Đà Nẵng, thi công phần thô và hoàn thiện nội thất chìa khóa trao tay.',
                fallback: 'https://images.unsplash.com/photo-1512917774080-9991f1c4c750?auto=format&fit=crop&w=800&q=80'
            },
            {
                driveId: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Nhà Phố 2 Mặt Tiền Khu Đô Thị Tây Bắc',
                location: 'Liên Chiểu, Đà Nẵng',
                desc: 'Thi công trọn gói nhà phố 2 mặt tiền tối ưu ánh sáng tự nhiên, thông gió đối lưu và công năng kinh doanh.',
                fallback: 'https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=800&q=80'
            }
        ];

        /**
         * DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ (TƯƠNG ĐỒNG WEB MẪU TINTRUONGTHINH.COM)
         */
        const homeArticles = [
            {
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Sau Khi Đổ',
                date: '15/11/2026',
                driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                fallback: 'https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=800&q=80',
                excerpt: 'Bảo dưỡng bê tông móng đúng quy trình giúp kết cấu đạt cường độ tối đa, chống nứt chân chim và tăng tuổi thọ công trình.',
                content: 'Trong quá trình thi công phần thô, bê tông móng đóng vai trò nền tảng chịu toàn bộ tải trọng công trình. Sau khi đổ bê tông từ 4–6 giờ, cần giữ ẩm liên tục trong 7 ngày đầu bằng cách tưới nước phun sương nhẹ, che phủ bạt hoặc bao tải ẩm tránh nắng gắt trực tiếp làm mất nước đột ngột.'
            },
            {
                title: '03 Nỗi Lo Lớn Nhất Khi Xây Nhà Trọn Gói & Cách Phòng Tránh',
                date: '08/11/2026',
                driveId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                fallback: 'https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=800&q=80',
                excerpt: 'Phát sinh chi phí, chậm tiến độ và vật tư không đúng cam kết là 3 vấn đề chủ đầu tư cần kiểm soát chặt bằng hợp đồng minh bạch.',
                content: 'Để xây nhà an tâm không phát sinh, gia chủ nên hoàn thiện hồ sơ thiết kế kỹ thuật 2D/3D đầy đủ trước khi khởi công, ký hợp đồng ghi rõ chủng loại vật tư phần thô & hoàn thiện, đồng thời lựa chọn đơn vị nhà thầu uy tín tại Đà Nẵng có cam kết tiến độ và bảo hành rõ ràng.'
            },
            {
                title: 'Thiết Kế Nội Thất Là Gì? Tầm Quan Trọng Của Không Gian Sống',
                date: '28/10/2026',
                driveId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                fallback: 'https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?auto=format&fit=crop&w=800&q=80',
                excerpt: 'Thiết kế nội thất khoa học giúp tối ưu diện tích, cân bằng ánh sáng và nâng cao chất lượng sinh hoạt cho mọi thành viên.',
                content: 'Thiết kế nội thất không chỉ là việc sắp xếp bàn ghế hay tủ kệ mà là nghệ thuật tổ chức công năng, màu sắc, vật liệu và ánh sáng hài hòa với thói quen sống của gia chủ. Một bản vẽ 3D chuẩn giúp bạn kiểm soát ngân sách và tránh lãng phí khi thi công thực tế.'
            },
            {
                title: 'Kinh Nghiệm Chọn Đơn Vị Tư Vấn Thiết Kế & Thi Công Tại Đà Nẵng',
                date: '19/10/2026',
                driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                fallback: 'https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=800&q=80',
                excerpt: 'Những tiêu chí quan trọng giúp chủ đầu tư đánh giá năng lực pháp lý, đội ngũ kỹ sư và các công trình thực tế của nhà thầu.',
                content: 'Khi chọn nhà thầu xây dựng tại Đà Nẵng, chủ đầu tư nên kiểm tra giấy phép kinh doanh, tham quan trực tiếp các công trình đang thi công, đối chiếu bảng báo giá chi tiết từng hạng mục và tìm hiểu chính sách bảo hành kết cấu cũng như chống thấm sau bàn giao.'
            }
        ];

        /**
         * RENDER 9 CÔNG TRÌNH THI CÔNG THỰC TẾ (KHÔNG NHÃN DÁN, 2 CỘT TRÊN MOBILE)
         */
        function renderConstructionWorks(filterCat = 'all') {
            const grid = document.getElementById('constructionGrid');
            if (!grid) return;

            const list = filterCat === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.category === filterCat);

            grid.innerHTML = list.map((item) => `
                <article
                    onclick="openWorkModal('${item.id}')"
                    class="project-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-ntpGold/70 transition-all flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumbUrl(item.driveId)}"
                            data-drive-id="${item.driveId}"
                            data-fallback="${item.fallback}"
                            onerror="handleDriveImgError(this)"
                            alt="${item.title}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-ntpNavy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500">
                            ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /**
         * RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (KHÔNG NHÃN DÁN, 2 CỘT MOBILE / 5 CỘT DESKTOP)
         */
        function renderDanangProjects() {
            const grid = document.getElementById('danangProjectsGrid');
            if (!grid) return;

            grid.innerHTML = danangProjects.map((item, idx) => `
                <article
                    onclick="openDanangModal(${idx})"
                    class="project-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-ntpGold/70 transition-all flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumbUrl(item.driveId)}"
                            data-drive-id="${item.driveId}"
                            data-fallback="${item.fallback}"
                            onerror="handleDriveImgError(this)"
                            alt="${item.title}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-ntpNavy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="mt-1.5 text-[11px] text-slate-500">
                            ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /**
         * RENDER BÀI VIẾT TRANG CHỦ (2 CỘT MOBILE / 4 CỘT DESKTOP)
         */
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            if (!grid) return;

            grid.innerHTML = homeArticles.map((art, idx) => `
                <article
                    onclick="openArticleModal(${idx})"
                    class="project-card cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-ntpGold/70 transition-all flex flex-col"
                >
                    <div class="card-img-wrap">
                        <img
                            src="${getDriveThumbUrl(art.driveId)}"
                            data-drive-id="${art.driveId}"
                            data-fallback="${art.fallback}"
                            onerror="handleDriveImgError(this)"
                            alt="${art.title}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-ntpGold font-semibold mb-1">${art.date}</div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-ntpNavy leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="mt-1.5 text-[11.5px] sm:text-xs text-slate-600 leading-relaxed hidden sm:block">
                                ${art.excerpt}
                            </p>
                        </div>
                        <span class="mt-2.5 inline-block text-[11px] sm:text-xs font-bold text-ntpNavy hover:text-ntpGold">
                            Đọc chi tiết →
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /**
         * LỌC DANH MỤC CÔNG TRÌNH THỰC TẾ
         */
        function selectCategory(cat) {
            const tabs = document.querySelectorAll('.cat-tab');
            tabs.forEach(btn => {
                const isMatch = btn.getAttribute('data-cat') === cat;
                if (isMatch) {
                    btn.classList.add('bg-ntpNavy', 'text-white', 'border-ntpNavy');
                    btn.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
                } else {
                    btn.classList.remove('bg-ntpNavy', 'text-white', 'border-ntpNavy');
                    btn.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
                }
            });
            renderConstructionWorks(cat);
        }

        /**
         * XỬ LÝ MODAL CHI TIẾT
         */
        function showDetailModal({ title, driveId, fallback, meta, desc }) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalMeta').textContent = meta;
            document.getElementById('modalDesc').textContent = desc;

            img.removeAttribute('data-retry');
            img.setAttribute('data-drive-id', driveId);
            img.setAttribute('data-fallback', fallback);
            img.onerror = function () { handleDriveImgError(this); };
            img.src = getDriveThumbUrl(driveId);
            img.alt = title;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function openWorkModal(id) {
            const item = constructionWorks.find(w => w.id === id);
            if (!item) return;
            showDetailModal({
                title: item.title,
                driveId: item.driveId,
                fallback: item.fallback,
                meta: `Hạng mục: ${item.categoryLabel} • Địa điểm: ${item.location}`,
                desc: item.desc
            });
        }

        function openDanangModal(index) {
            const item = danangProjects[index];
            if (!item) return;
            showDetailModal({
                title: item.title,
                driveId: item.driveId,
                fallback: item.fallback,
                meta: `Dự án Đà Nẵng • Khu vực: ${item.location}`,
                desc: item.desc
            });
        }

        function openArticleModal(index) {
            const art = homeArticles[index];
            if (!art) return;
            showDetailModal({
                title: art.title,
                driveId: art.driveId,
                fallback: art.fallback,
                meta: `Cẩm nang xây dựng • Ngày đăng: ${art.date}`,
                desc: `${art.excerpt} ${art.content}`
            });
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        /**
         * BANNER SLIDER TỰ TRƯỢT (2 ẢNH BẰNG NHAU + HỖ TRỢ VUỐT CẢM ỨNG)
         */
        let currentSlide = 0;
        let slideTimer = null;

        function goToSlide(index) {
            const slides = document.querySelectorAll('.banner-slide');
            const dots = document.querySelectorAll('.banner-dot');
            if (!slides.length) return;

            currentSlide = (index + slides.length) % slides.length;

            slides.forEach((s, i) => {
                s.classList.toggle('active', i === currentSlide);
            });

            dots.forEach((d, i) => {
                if (i === currentSlide) {
                    d.classList.add('w-7', 'bg-ntpGold');
                    d.classList.remove('w-2.5', 'bg-white/50');
                } else {
                    d.classList.remove('w-7', 'bg-ntpGold');
                    d.classList.add('w-2.5', 'bg-white/50');
                }
            });
        }

        function startAutoSlide() {
            clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                goToSlide(currentSlide + 1);
            }, 5000);
        }

        /**
         * MENU MOBILE
         */
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            const openIcon = document.getElementById('iconMenuOpen');
            const closeIcon = document.getElementById('iconMenuClose');
            const isHidden = menu.classList.contains('hidden');
            menu.classList.toggle('hidden', !isHidden);
            openIcon.classList.toggle('hidden', isHidden);
            closeIcon.classList.toggle('hidden', !isHidden);
        }

        function closeMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            const openIcon = document.getElementById('iconMenuOpen');
            const closeIcon = document.getElementById('iconMenuClose');
            menu.classList.add('hidden');
            openIcon.classList.remove('hidden');
            closeIcon.classList.add('hidden');
        }

        /**
         * KHỞI TẠO TOÀN BỘ SỰ KIỆN KHI TẢI TRANG
         */
        document.addEventListener('DOMContentLoaded', () => {
            try {
                // 1. Render dữ liệu trang chủ
                renderConstructionWorks('all');
                renderDanangProjects();
                renderArticles();

                // 2. Sự kiện lọc danh mục
                document.querySelectorAll('.cat-tab').forEach(btn => {
                    btn.addEventListener('click', () => {
                        selectCategory(btn.getAttribute('data-cat'));
                    });
                });

                // 3. Sự kiện Banner Slider + Vuốt trên điện thoại
                document.getElementById('prevBannerBtn')?.addEventListener('click', () => {
                    goToSlide(currentSlide - 1);
                    startAutoSlide();
                });
                document.getElementById('nextBannerBtn')?.addEventListener('click', () => {
                    goToSlide(currentSlide + 1);
                    startAutoSlide();
                });
                document.querySelectorAll('.banner-dot').forEach(dot => {
                    dot.addEventListener('click', () => {
                        goToSlide(parseInt(dot.getAttribute('data-slide'), 10));
                        startAutoSlide();
                    });
                });

                const heroSlider = document.getElementById('heroSlider');
                let touchStartX = 0;
                heroSlider?.addEventListener('touchstart', (e) => {
                    touchStartX = e.changedTouches[0].screenX;
                }, { passive: true });
                heroSlider?.addEventListener('touchend', (e) => {
                    const diff = e.changedTouches[0].screenX - touchStartX;
                    if (Math.abs(diff) > 40) {
                        goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                        startAutoSlide();
                    }
                }, { passive: true });

                startAutoSlide();

                // 4. Sự kiện Menu Mobile
                document.getElementById('mobileMenuBtn')?.addEventListener('click', toggleMobileMenu);

                // 5. Sự kiện Modal chi tiết
                document.getElementById('closeModalBtn')?.addEventListener('click', closeDetailModal);
                document.getElementById('detailModal')?.addEventListener('click', (e) => {
                    if (e.target.id === 'detailModal') closeDetailModal();
                });
                document.addEventListener('keydown', (e) => {
                    if (e.key === 'Escape') closeDetailModal();
                });

                // 6. Xử lý gửi Form Báo Giá (hiển thị thông báo trực tiếp, không dùng alert)
                const quoteForm = document.getElementById('quoteForm');
                const feedback = document.getElementById('quoteFeedback');
                quoteForm?.addEventListener('submit', (e) => {
                    e.preventDefault();
                    const name = document.getElementById('qName').value.trim();
                    const phone = document.getElementById('qPhone').value.trim();
                    const type = document.getElementById('qType').value;

                    if (!name || !phone) {
                        feedback.className = 'p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                        feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Nam Thịnh Phát liên hệ báo giá.';
                        feedback.classList.remove('hidden');
                        return;
                    }

                    feedback.className = 'p-3.5 rounded-lg text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                    feedback.textContent = `Cảm ơn ${name}! Yêu cầu báo giá hạng mục "${type}" của bạn đã được ghi nhận. Kỹ sư Nam Thịnh Phát sẽ liên hệ qua số ${phone} trong thời gian sớm nhất.`;
                    feedback.classList.remove('hidden');
                    quoteForm.reset();
                });
            } catch (err) {
                console.error('Lỗi khởi tạo giao diện Nam Thịnh Phát:', err);
            }
        });
    </script>
</body>
</html>

<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>Gốm Nhật Nhà Chanh - Tinh Hoa Gốm Sứ Nhật Bản Tại Đà Nẵng | gomnhatnhachanh.com</title>
    <meta name="description" content="Gốm Nhật Nhà Chanh (gomnhatnhachanh.com) - Chuyên cung cấp gốm sứ Nhật Bản chính hãng, Trà cụ, Ấm Tetsubin, Gốm Bizen, Gốm Mino, Kutani, Satsuma, Đĩa cảnh & Đồ Decor tại 242 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng. Hotline: 0708.885.288">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://gomnhatnhachanh.com/">
    <meta property="og:title" content="Gốm Nhật Nhà Chanh - Gốm Sứ Nhật Bản Tuyển Chọn | gomnhatnhachanh.com">
    <meta property="og:description" content="Chuyên sỉ & lẻ Gốm sứ Nhật Bản, Trà cụ, Bình hoa, Đĩa cảnh trang trí, Bộ bàn ăn Nhật tại 242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP. Đà Nẵng. ĐT: 0708.885.288">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w800">
    <meta property="og:image:alt" content="Logo Gốm Nhật Nhà Chanh">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w800">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w200">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w200">

    <!-- Google Fonts: Inter & Noto Serif Display -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Noto+Serif:ital,wght@0,600;0,700;1,400&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        chanh: {
                            50: '#f9fbe7',
                            100: '#f0f4c3',
                            500: '#689f38',
                            600: '#558b2f',
                            700: '#33691e',
                            800: '#254d15',
                            900: '#1b3b0e',
                        },
                        gom: {
                            light: '#fdfbf7',
                            cream: '#f6f1e7',
                            gold: '#d49a2a',
                            brown: '#4a3525',
                            dark: '#2b1e16',
                            sale: '#d32f2f'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Noto Serif', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền và chống lệch sang phải tuyệt đối */
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
            background-color: #fdfbf7;
            color: #2b1e16;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 15px;
            padding-right: 15px;
        }

        /* Thanh danh mục trên máy tính: bắt buộc nằm trên 1 hàng, không xuống dòng */
        .desktop-nav-list {
            display: flex;
            flex-wrap: nowrap;
            align-items: center;
            justify-content: space-between;
            width: 100%;
            margin: 0;
            padding: 0;
            list-style: none;
        }
        .desktop-nav-item {
            position: relative;
            white-space: nowrap;
            flex-shrink: 0;
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            padding: 11px 8px;
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            color: #ffffff;
            white-space: nowrap;
            letter-spacing: 0.01em;
            transition: all 0.2s ease;
        }
        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 12.5px;
                padding: 12px 11px;
            }
        }
        @media (min-width: 1440px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 12px 13px;
            }
        }
        .desktop-nav-link:hover, .desktop-nav-item.active .desktop-nav-link {
            background-color: rgba(255, 255, 255, 0.16);
            color: #f0f4c3;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border: 1px solid #e5e0d5;
            box-shadow: 0 10px 25px rgba(0,0,0,0.12);
            border-radius: 0 0 6px 6px;
            padding: 8px 0;
            z-index: 100;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .desktop-nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .nav-dropdown a {
            display: block;
            padding: 8px 16px;
            font-size: 13px;
            color: #3d2c1e;
            font-weight: 500;
            white-space: nowrap;
            transition: background 0.15s ease;
        }
        .nav-dropdown a:hover {
            background-color: #f9fbe7;
            color: #33691e;
            padding-left: 20px;
        }

        /* Tiêu đề Section kiểu Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 20px;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e6dfd3;
            padding-bottom: 8px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .section-title-main {
            font-size: 17px;
            font-weight: 700;
            text-transform: uppercase;
            color: #254d15;
            position: relative;
            padding-bottom: 8px;
            margin-bottom: -10px;
            border-bottom: 3px solid #558b2f;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 20px;
            }
        }

        /* Banner Slider: 2 ảnh banner kích thước bằng nhau tuyệt đối */
        .banner-slider-wrapper {
            position: relative;
            width: 100%;
            height: 310px;
            overflow: hidden;
            border-radius: 10px;
            background-color: #2b1e16;
        }
        @media (min-width: 640px) {
            .banner-slider-wrapper {
                height: 360px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slider-wrapper {
                height: 460px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Khống chế chữ trong Banner luôn nằm gọn bên trong, không bị CSS ngoài làm phóng to hay tràn khung */
        .banner-content-box {
            max-height: calc(100% - 20px);
            overflow: hidden;
            box-sizing: border-box;
        }
        .banner-sub {
            font-size: 10px !important;
            line-height: 1.3 !important;
            margin: 0 0 4px 0 !important;
            padding: 0 !important;
        }
        .banner-title {
            font-family: 'Noto Serif', serif !important;
            font-size: 14px !important;
            line-height: 1.32 !important;
            font-weight: 700 !important;
            color: #ffffff !important;
            margin: 0 0 6px 0 !important;
            padding: 0 !important;
            border: none !important;
            word-wrap: break-word !important;
        }
        .banner-desc {
            font-size: 11px !important;
            line-height: 1.38 !important;
            color: #e7e5e4 !important;
            margin: 0 0 6px 0 !important;
            padding: 0 !important;
        }
        .banner-meta {
            font-size: 10.5px !important;
            line-height: 1.35 !important;
            margin: 0 0 8px 0 !important;
            padding: 0 !important;
        }
        .banner-btn {
            font-size: 11px !important;
            line-height: 1.2 !important;
            padding: 6px 10px !important;
            text-decoration: none !important;
        }
        @media (min-width: 640px) {
            .banner-sub {
                font-size: 12px !important;
                margin-bottom: 6px !important;
            }
            .banner-title {
                font-size: 20px !important;
                line-height: 1.3 !important;
                margin-bottom: 8px !important;
            }
            .banner-desc {
                font-size: 13px !important;
                line-height: 1.45 !important;
                margin-bottom: 10px !important;
            }
            .banner-meta {
                font-size: 12px !important;
                margin-bottom: 12px !important;
            }
            .banner-btn {
                font-size: 12.5px !important;
                padding: 8px 14px !important;
            }
        }
        @media (min-width: 1024px) {
            .banner-title {
                font-size: 28px !important;
                line-height: 1.28 !important;
                margin-bottom: 10px !important;
            }
            .banner-desc {
                font-size: 14.5px !important;
                margin-bottom: 12px !important;
            }
            .banner-meta {
                font-size: 13.5px !important;
                margin-bottom: 14px !important;
            }
            .banner-btn {
                font-size: 13.5px !important;
                padding: 9px 16px !important;
            }
        }

        /* Badge giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-badge-sale {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 20;
            background-color: #d32f2f;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            width: 42px;
            height: 42px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.22);
            line-height: 1;
            pointer-events: none;
        }
        @media (max-width: 640px) {
            .flatsome-badge-sale {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 7px;
                left: 7px;
            }
        }

        /* Card sản phẩm chuẩn Flatsome - Tên sản phẩm đầy đủ không bị cắt hay tràn chữ */
        .product-small-box {
            background: #ffffff;
            border: 1px solid #ece6da;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: transform 0.22s ease, box-shadow 0.22s ease;
        }
        .product-small-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(43, 30, 22, 0.09);
            border-color: #c5d6a7;
        }
        .product-box-image {
            position: relative;
            width: 100%;
            aspect-ratio: 1 / 1;
            background-color: #f7f4ee;
            overflow: hidden;
        }
        .product-box-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s ease;
        }
        .product-small-box:hover .product-box-image img {
            transform: scale(1.05);
        }
        .product-box-text {
            padding: 10px 10px 12px;
            display: flex;
            flex-direction: column;
            flex-grow: 1;
            justify-content: space-between;
        }
        @media (min-width: 768px) {
            .product-box-text {
                padding: 12px 14px 14px;
            }
        }
        .product-title {
            font-size: 13px;
            line-height: 1.42;
            font-weight: 600;
            color: #2b1e16;
            margin-bottom: 6px;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            display: block;
        }
        @media (min-width: 768px) {
            .product-title {
                font-size: 14px;
            }
        }
        .product-title:hover {
            color: #33691e;
        }

        /* Nút liên hệ nổi góc dưới */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(211, 47, 47, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(211, 47, 47, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(211, 47, 47, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-gom-light text-gom-dark antialiased selection:bg-chanh-600 selection:text-white">

    <!-- Script hỗ trợ tự động chuyển đổi link ảnh Google Drive nếu 1 endpoint bị chậm -->
    <script>
        function handleDriveImgError(img, fileId, fallbackLabel) {
            const step = parseInt(img.getAttribute('data-retry-step') || '0', 10);
            if (step === 0) {
                img.setAttribute('data-retry-step', '1');
                img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (step === 1) {
                img.setAttribute('data-retry-step', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                const cleanText = encodeURIComponent(fallbackLabel || 'Gom Nhat Nha Chanh');
                img.src = 'https://placehold.co/600x600/f6f1e7/33691e?text=' + cleanText;
            }
        }
    </script>

    <!-- ==========================================
         HEADER WRAPPER (CHUẨN FLATSOME - KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header id="header" class="header-wrapper w-full bg-white shadow-sm sticky top-0 z-40">

        <!-- TOP BAR (Đơn giản, không hiển thị tùy chọn UX Builder) -->
        <div class="top-bar bg-gom-brown text-stone-100 text-xs py-1.5 border-b border-stone-700">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <span class="inline-flex items-center gap-1.5 font-medium text-chanh-100">
                        <i class="fa-solid fa-Store"></i> GỐM NHẬT NHÀ CHANH – TINH HOA GỐM SỨ NHẬT BẢN
                    </span>
                    <span class="hidden md:inline text-stone-400">|</span>
                    <span class="hidden md:inline text-stone-200">
                        <i class="fa-solid fa-location-dot text-gom-gold mr-1"></i>242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, Tp.Đà Nẵng
                    </span>
                </div>
                <div class="hidden sm:flex items-center gap-4 text-xs">
                    <a href="#ve-chung-toi" class="hover:text-chanh-100 transition">Giới thiệu</a>
                    <span class="text-stone-500">|</span>
                    <a href="#form-bao-gia" class="hover:text-chanh-100 transition">Bán sỉ & Báo giá</a>
                    <span class="text-stone-500">|</span>
                    <a href="#ban-do-shop" class="hover:text-chanh-100 transition">Chỉ đường tới Shop</a>
                </div>
            </div>
        </div>

        <!-- HEADER MAIN (Logo, Tìm kiếm, Địa chỉ & Giỏ hàng - Không để nút Gọi ngay) -->
        <div class="header-main py-2.5 md:py-3.5 bg-white">
            <div class="flatsome-container flex items-center justify-between gap-3 md:gap-6">

                <!-- Nút mở Menu danh mục trên Điện thoại -->
                <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-stone-200 text-chanh-800 hover:bg-chanh-50 flex-shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo Gốm Nhật Nhà Chanh -->
                <a href="#" class="flex items-center gap-2.5 md:gap-3 flex-shrink-0 group">
                    <div class="w-12 h-12 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-chanh-600 shadow-sm flex-shrink-0 bg-gom-cream">
                        <img src="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w400"
                             onerror="handleDriveImgError(this, '13tIvCCqErET29mp8YMggaz7T1ghScj5e', 'Logo Nha Chanh')"
                             alt="Logo Gốm Nhật Nhà Chanh"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="flex flex-col">
                        <span class="font-serif font-bold text-base sm:text-lg md:text-2xl text-chanh-800 tracking-tight leading-tight group-hover:text-chanh-600 transition">
                            GỐM NHẬT NHÀ CHANH
                        </span>
                        <span class="text-[11px] md:text-xs text-stone-500 font-medium">
                            gomnhatnhachanh.com • Đà Nẵng
                        </span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-2">
                    <form onsubmit="handleSearch(event)" class="w-full flex items-center border-2 border-chanh-600 rounded-full overflow-hidden bg-stone-50 focus-within:bg-white focus-within:ring-2 focus-within:ring-chanh-100">
                        <input id="desktopSearchInput" type="text" placeholder="Tìm kiếm ấm trà Bizen, bình hoa, đĩa cảnh, chén dĩa Nhật..."
                               class="w-full px-4 py-2 text-sm bg-transparent focus:outline-none text-stone-800">
                        <button type="submit" class="bg-chanh-700 hover:bg-chanh-800 text-white px-5 py-2.5 text-sm font-semibold transition flex items-center gap-1.5 flex-shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                            <span>Tìm</span>
                        </button>
                    </form>
                </div>

                <!-- Thông tin địa chỉ & Giỏ hàng (Tuyệt đối không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-2.5 md:gap-4 flex-shrink-0">
                    <div class="hidden xl:flex items-center gap-2.5 text-left border-r border-stone-200 pr-4">
                        <div class="w-9 h-9 rounded-full bg-chanh-50 text-chanh-700 flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div class="text-xs leading-tight">
                            <p class="font-bold text-stone-800">242 Xô Viết Nghệ Tĩnh</p>
                            <p class="text-stone-500">P. Cẩm Lệ, TP. Đà Nẵng</p>
                        </div>
                    </div>

                    <button type="button" onclick="openCartModal()" class="relative inline-flex items-center gap-2 px-3 py-2 rounded-lg border border-chanh-600/30 bg-chanh-50/70 hover:bg-chanh-100/70 text-chanh-800 text-xs md:text-sm font-semibold transition">
                        <i class="fa-solid fa-basket-shopping text-base text-chanh-700"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="inline-flex items-center justify-center w-5 h-5 text-[11px] font-bold bg-gom-sale text-white rounded-full">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên Điện thoại (Gọn trong container, không tràn viền) -->
            <div class="flatsome-container md:hidden mt-2">
                <form onsubmit="handleMobileSearch(event)" class="w-full flex items-center border border-chanh-600 rounded-lg overflow-hidden bg-stone-50">
                    <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm gốm Nhật Nhà Chanh..."
                           class="w-full px-3 py-1.5 text-xs bg-transparent focus:outline-none text-stone-800">
                    <button type="submit" class="bg-chanh-700 text-white px-3.5 py-1.5 text-xs font-semibold flex-shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- HEADER BOTTOM: THANH DANH MỤC TRÊN MÁY TÍNH (NẰM TRÊN CÙNG 1 HÀNG, KHÔNG XUỐNG DÒNG) -->
        <nav class="header-bottom hidden lg:block bg-chanh-700 border-t border-chanh-800 shadow-sm">
            <div class="flatsome-container">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item active">
                        <a href="#" onclick="filterCategory('all'); return false;" class="desktop-nav-link">
                            <i class="fa-solid fa-house"></i> TRANG CHỦ
                        </a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('decor')" class="desktop-nav-link">
                            ĐỒ DECOR TỔNG HỢP <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('decor')">Tượng Decor Gốm Nhật</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('decor')">Chuông Chánh Niệm – Mindfulness Bell</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('decor')">Bình Hoa Gốm Nhật Tuyển Chọn</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('decor')">Chậu Cây Bonsai Mini</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('bizen')" class="desktop-nav-link">
                            GỐM SỨ BIZEN <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('bizen')">Bình Gốm Bizen</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('bizen')">Bình Trà Bizen</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('bizen')">Đĩa Gốm Bizen</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('bizen')">Ly Gốm Bizen</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('mino')" class="desktop-nav-link">
                            GỐM MINO <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('mino')">Gốm Kiseto</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('mino')">Gốm Oribe</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('mino')">Gốm Setoguro</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('mino')">Gốm Akashino & Eshino</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('mino')">Gốm Nezumishino</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('tracu')" class="desktop-nav-link">
                            TRÀ CỤ – ẤM TETSUBIN <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('tracu')">Ấm Tetsubin – Kamafuro</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('tracu')">Chawan – Phụ Kiện Trà Đạo</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('tracu')">Bộ Trà Nhật Bản</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('tracu')">Bộ Ly Uống Trà & Chén Tống</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('miniset')" class="desktop-nav-link">
                            MINI SET & BÀN ĂN <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('miniset')">Mini Set Trà & Bánh</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('miniset')">Bộ Chén Đĩa Gia Đình Nhật</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('miniset')">Tô Bát Sành Sứ Vẽ Tay</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('diacanh')" class="desktop-nav-link">
                            ĐĨA CẢNH TRANG TRÍ <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('diacanh')">Đĩa Cảnh Phong Thủy</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('diacanh')">Kệ Kê Đĩa – Chân Kê Đĩa</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('diacanh')">Móc Treo Đĩa Lên Tường</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterCategory('gomkhac')" class="desktop-nav-link">
                            DÒNG GỐM KHÁC <i class="fa-solid fa-chevron-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="nav-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterCategory('gomkhac')">Gốm Kutani</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('gomkhac')">Gốm Satsuma</a>
                            <a href="#danh-muc-san-pham" onclick="filterCategory('gomkhac')">Gốm Arita & Tokoname</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bai-viet-trang-chu" class="desktop-nav-link">
                            CHIA SẺ KIẾN THỨC
                        </a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#ban-do-shop" class="desktop-nav-link">
                            CHỈ ĐƯỜNG TỚI SHOP
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI (Thiết kế đẹp, rõ ràng, dễ bấm) -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[290px] max-w-[85vw] bg-white z-50 transform -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-4 bg-chanh-700 text-white flex items-center justify-between">
            <div class="flex items-center gap-2.5">
                <img src="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w200"
                     onerror="handleDriveImgError(this, '13tIvCCqErET29mp8YMggaz7T1ghScj5e', 'Logo')"
                     alt="Logo" class="w-9 h-9 rounded-full bg-white object-cover">
                <div>
                    <p class="font-bold text-sm leading-tight">GỐM NHẬT NHÀ CHANH</p>
                    <p class="text-[11px] text-chanh-100">Danh mục sản phẩm</p>
                </div>
            </div>
            <button type="button" onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <div class="overflow-y-auto flex-1 divide-y divide-stone-100 text-sm">
            <a href="#" onclick="filterCategory('all'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-semibold text-chanh-800 bg-chanh-50/50">
                <span><i class="fa-solid fa-house mr-2 text-chanh-600"></i>Trang chủ</span>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('decor'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-fan mr-2 text-chanh-600"></i>Đồ Decor Tổng Hợp</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('bizen'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-fire-flame-curved mr-2 text-chanh-600"></i>Gốm Sứ Bizen</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('mino'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-bowl-rice mr-2 text-chanh-600"></i>Gốm Mino (Kiseto, Oribe, Shino)</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('tracu'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-mug-hot mr-2 text-chanh-600"></i>Trà Cụ – Ấm Tetsubin</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('miniset'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-utensils mr-2 text-chanh-600"></i>Mini Set & Bộ Bàn Ăn</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('diacanh'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-compact-disc mr-2 text-chanh-600"></i>Đĩa Cảnh Trang Trí</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterCategory('gomkhac'); toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-vase mr-2 text-chanh-600"></i>Các Dòng Gốm Khác (Kutani, Satsuma)</span>
                <i class="fa-solid fa-angle-right text-xs text-stone-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-file-signature mr-2 text-chanh-600"></i>Yêu Cầu Tư Vấn & Báo Giá</span>
            </a>
            <a href="#bai-viet-trang-chu" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-book-open mr-2 text-chanh-600"></i>Tìm Hiểu – Chia Sẻ Kiến Thức</span>
            </a>
            <a href="#ban-do-shop" onclick="toggleMobileMenu();" class="flex items-center justify-between px-4 py-3 font-medium text-stone-700 hover:bg-stone-50">
                <span><i class="fa-solid fa-map-location-dot mr-2 text-chanh-600"></i>Chỉ Đường Tới Shop</span>
            </a>
        </div>

        <div class="p-4 bg-stone-50 border-t border-stone-200 text-xs text-stone-600 space-y-1">
            <p class="font-bold text-stone-800">GỐM NHẬT NHÀ CHANH</p>
            <p><i class="fa-solid fa-location-dot text-chanh-700 mr-1.5"></i>242 Xô Viết Nghệ Tĩnh, P. Cẩm Lệ, Đà Nẵng</p>
            <p><i class="fa-solid fa-phone text-chanh-700 mr-1.5"></i>Hotline: <strong class="text-gom-sale">0708.885.288</strong></p>
        </div>
    </aside>

    <!-- ==========================================
         MAIN CONTENT (CHUẨN UX BUILDER FLATSOME)
         ========================================== -->
    <main id="main" class="w-full">

        <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU DỰA VÀO 4 ẢNH CỬA HÀNG -->
        <section class="section py-3 md:py-5">
            <div class="flatsome-container">
                <div class="banner-slider-wrapper shadow-md" id="heroSlider">

                    <!-- SLIDE BANNER 1 (Kết hợp 2 ảnh cửa hàng thực tế: 1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad & 1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ) -->
                    <div class="banner-slide active" data-slide="0">
                        <div class="w-full h-full grid grid-cols-1 md:grid-cols-12 relative">
                            <!-- Ảnh nền cửa hàng -->
                            <div class="col-span-1 md:col-span-7 h-full relative overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad=w1400"
                                     onerror="handleDriveImgError(this, '1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad', 'Cua Hang Gom Nhat Nha Chanh 1')"
                                     alt="Không gian Gốm Nhật Nhà Chanh 242 Xô Viết Nghệ Tĩnh"
                                     class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-gradient-to-r from-black/75 via-black/45 to-black/20 md:via-black/25 md:to-transparent"></div>
                            </div>
                            <div class="hidden md:block md:col-span-5 h-full relative overflow-hidden border-l-4 border-gom-gold/70">
                                <img src="https://lh3.googleusercontent.com/d/1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ=w1000"
                                     onerror="handleDriveImgError(this, '1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ', 'Cua Hang Gom Nhat Nha Chanh 2')"
                                     alt="Kệ trưng bày Gốm Nhật Nhà Chanh"
                                     class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-black/25"></div>
                            </div>

                            <!-- Nội dung chữ trên Banner 1 (Tối ưu trên điện thoại nằm gọn bên trong không tràn viền) -->
                            <div class="absolute inset-0 flex items-center justify-start px-9 sm:px-12 md:px-14 py-2.5">
                                <div class="w-full max-w-full md:max-w-2xl">
                                    <div class="banner-content-box bg-black/60 backdrop-blur-sm border-l-4 border-gom-gold p-3 sm:p-5 md:p-6 rounded-r-xl text-white w-full">
                                        <p class="banner-sub uppercase tracking-wider text-chanh-100 font-semibold">
                                            gomnhatnhachanh.com • Showroom Gốm Nhật Đà Nẵng
                                        </p>
                                        <div class="banner-title">
                                            GỐM NHẬT NHÀ CHANH – TINH HOA GỐM SỨ NHẬT BẢN
                                        </div>
                                        <p class="banner-desc">
                                            Chuyên Trà cụ, Ấm Tetsubin, Gốm Bizen, Kutani, Satsuma, Bình hoa, Đĩa cảnh & Bộ bàn ăn Nhật tuyển chọn.
                                        </p>
                                        <div class="banner-meta flex flex-col sm:flex-row sm:flex-wrap sm:items-center gap-0.5 sm:gap-2 text-amber-200 font-medium">
                                            <span><i class="fa-solid fa-location-dot mr-1"></i>242 Xô Viết Nghệ Tĩnh, P. Cẩm Lệ, TP. Đà Nẵng</span>
                                            <span class="hidden sm:inline">•</span>
                                            <span><i class="fa-solid fa-phone-volume mr-1"></i>0708.885.288</span>
                                        </div>
                                        <div class="flex flex-wrap items-center gap-1.5 sm:gap-2">
                                            <a href="#khu-vuc-san-pham" class="banner-btn inline-flex items-center gap-1.5 bg-chanh-600 hover:bg-chanh-500 text-white font-semibold rounded-lg shadow transition">
                                                <span>Khám phá sản phẩm</span>
                                                <i class="fa-solid fa-arrow-right text-[10px]"></i>
                                            </a>
                                            <a href="#form-bao-gia" class="banner-btn inline-flex items-center gap-1.5 bg-white/95 hover:bg-white text-gom-brown font-semibold rounded-lg transition">
                                                <span>Nhận báo giá sỉ & lẻ</span>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE BANNER 2 (Kết hợp 2 ảnh cửa hàng thực tế: 1f0Kgshqqde3SBpUGlOiM6uN3RKO68UCj & 1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A) -->
                    <div class="banner-slide" data-slide="1">
                        <div class="w-full h-full grid grid-cols-1 md:grid-cols-12 relative">
                            <div class="col-span-1 md:col-span-7 h-full relative overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1f0Kgshqqde3SBpUGlOiM6uN3RKO68UCj=w1400"
                                     onerror="handleDriveImgError(this, '1f0Kgshqqde3SBpUGlOiM6uN3RKO68UCj', 'Khong Gian Cua Hang Nha Chanh 3')"
                                     alt="Kho Gốm Nhật Nhà Chanh Đà Nẵng"
                                     class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-gradient-to-r from-black/75 via-black/45 to-black/20 md:via-black/25 md:to-transparent"></div>
                            </div>
                            <div class="hidden md:block md:col-span-5 h-full relative overflow-hidden border-l-4 border-chanh-500">
                                <img src="https://lh3.googleusercontent.com/d/1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A=w1000"
                                     onerror="handleDriveImgError(this, '1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A', 'Khong Gian Cua Hang Nha Chanh 4')"
                                     alt="Gốm sứ Nhật Bản tại cửa hàng Nhà Chanh"
                                     class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-black/25"></div>
                            </div>

                            <!-- Nội dung chữ trên Banner 2 (Tối ưu trên điện thoại nằm gọn bên trong không tràn viền) -->
                            <div class="absolute inset-0 flex items-center justify-start px-9 sm:px-12 md:px-14 py-2.5">
                                <div class="w-full max-w-full md:max-w-2xl">
                                    <div class="banner-content-box bg-black/60 backdrop-blur-sm border-l-4 border-chanh-500 p-3 sm:p-5 md:p-6 rounded-r-xl text-white w-full">
                                        <p class="banner-sub uppercase tracking-wider text-amber-200 font-semibold">
                                            Hàng Tuyển Chọn Chuẩn Nhật • Cập Nhật Mỗi Ngày
                                        </p>
                                        <div class="banner-title">
                                            TRÀ CỤ, ĐĨA CẢNH, BÌNH HOA & ĐỒ BẾP GỐM NHẬT
                                        </div>
                                        <p class="banner-desc">
                                            Ưu đãi hấp dẫn trực tiếp tại cửa hàng 242 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng. Đóng gói an toàn, giao hàng toàn quốc.
                                        </p>
                                        <div class="banner-meta flex flex-col sm:flex-row sm:flex-wrap sm:items-center gap-0.5 sm:gap-2 text-chanh-100 font-medium">
                                            <span><i class="fa-solid fa-clock mr-1"></i>Mở cửa: 09:00 – 21:30</span>
                                            <span class="hidden sm:inline">•</span>
                                            <span><i class="fa-solid fa-truck-fast mr-1"></i>Ship COD Toàn Quốc</span>
                                        </div>
                                        <div class="flex flex-wrap items-center gap-1.5 sm:gap-2">
                                            <a href="#ban-do-shop" class="banner-btn inline-flex items-center gap-1.5 bg-gom-gold hover:bg-amber-600 text-white font-semibold rounded-lg shadow transition">
                                                <i class="fa-solid fa-map-pin"></i>
                                                <span>Xem bản đồ cửa hàng</span>
                                            </a>
                                            <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener" class="banner-btn inline-flex items-center gap-1.5 bg-white/95 hover:bg-white text-gom-brown font-semibold rounded-lg transition">
                                                <i class="fa-brands fa-facebook text-blue-600"></i>
                                                <span>Ghé Fanpage Nhà Chanh</span>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng 2 Banner -->
                    <button type="button" onclick="prevBanner()" aria-label="Banner trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/45 hover:bg-black/70 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
                    </button>
                    <button type="button" onclick="nextBanner()" aria-label="Banner tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/45 hover:bg-black/70 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
                    </button>

                    <!-- Dots chỉ báo slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" onclick="goToBanner(0)" id="bannerDot0" class="w-6 h-2 rounded-full bg-white transition-all"></button>
                        <button type="button" onclick="goToBanner(1)" id="bannerDot1" class="w-2.5 h-2 rounded-full bg-white/50 transition-all"></button>
                    </div>
                </div>

                <!-- 4 Ô Hình Không Gian Thực Tế Tại Cửa Hàng (Dễ dàng quản lý trong UX Builder) -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 md:gap-4 mt-3">
                    <div class="bg-white p-1.5 rounded-lg border border-stone-200 flex items-center gap-2.5 shadow-sm">
                        <img src="https://lh3.googleusercontent.com/d/1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad=w300"
                             onerror="handleDriveImgError(this, '1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad', 'Cua hang 1')"
                             alt="Góc trưng bày 1" class="w-12 h-12 md:w-14 md:h-14 rounded object-cover flex-shrink-0">
                        <div class="min-w-0">
                            <p class="font-bold text-xs md:text-sm text-chanh-800 leading-tight">Chuẩn Gốm Nhật</p>
                            <p class="text-[11px] text-stone-500 leading-tight mt-0.5">Tuyển chọn từng món độc bản</p>
                        </div>
                    </div>
                    <div class="bg-white p-1.5 rounded-lg border border-stone-200 flex items-center gap-2.5 shadow-sm">
                        <img src="https://lh3.googleusercontent.com/d/1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ=w300"
                             onerror="handleDriveImgError(this, '1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ', 'Cua hang 2')"
                             alt="Góc trưng bày 2" class="w-12 h-12 md:w-14 md:h-14 rounded object-cover flex-shrink-0">
                        <div class="min-w-0">
                            <p class="font-bold text-xs md:text-sm text-chanh-800 leading-tight">Kho Hàng Sẵn Có</p>
                            <p class="text-[11px] text-stone-500 leading-tight mt-0.5">Đa dạng bình, đĩa, trà cụ</p>
                        </div>
                    </div>
                    <div class="bg-white p-1.5 rounded-lg border border-stone-200 flex items-center gap-2.5 shadow-sm">
                        <img src="https://lh3.googleusercontent.com/d/1f0Kgshqqde3SBpUGlOiM6uN3RKO68UCj=w300"
                             onerror="handleDriveImgError(this, '1f0Kgshqqde3SBpUGlOiM6uN3RKO68UCj', 'Cua hang 3')"
                             alt="Góc trưng bày 3" class="w-12 h-12 md:w-14 md:h-14 rounded object-cover flex-shrink-0">
                        <div class="min-w-0">
                            <p class="font-bold text-xs md:text-sm text-chanh-800 leading-tight">Bán Sỉ & Bán Lẻ</p>
                            <p class="text-[11px] text-stone-500 leading-tight mt-0.5">Chiết khấu tốt cho nhà hàng, cafe</p>
                        </div>
                    </div>
                    <div class="bg-white p-1.5 rounded-lg border border-stone-200 flex items-center gap-2.5 shadow-sm">
                        <img src="https://lh3.googleusercontent.com/d/1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A=w300"
                             onerror="handleDriveImgError(this, '1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A', 'Cua hang 4')"
                             alt="Góc trưng bày 4" class="w-12 h-12 md:w-14 md:h-14 rounded object-cover flex-shrink-0">
                        <div class="min-w-0">
                            <p class="font-bold text-xs md:text-sm text-chanh-800 leading-tight">Đóng Gói Bảo Đảm</p>
                            <p class="text-[11px] text-stone-500 leading-tight mt-0.5">Cam kết an toàn khi vận chuyển</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ nhỏ gọn, đẹp trên cả máy tính & điện thoại, lấy theo shopgomnhat.com) -->
        <section id="danh-muc-san-pham" class="section py-4 md:py-6">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main">
                            <i class="fa-solid fa-layer-group text-chanh-600"></i>
                            <span>DANH MỤC SẢN PHẨM</span>
                        </h2>
                        <span class="text-xs text-stone-500">Chọn danh mục để lọc nhanh sản phẩm thực tế</span>
                    </div>
                </div>

                <!-- Grid Danh Mục Trang Chủ: Máy tính 8 cột nằm gọn 1 hàng chữ nhỏ gọn, Điện thoại 2 cột gọn đẹp -->
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 md:gap-3">
                    <!-- Danh mục 1 -->
                    <button type="button" onclick="filterCategory('all')" data-cat-btn="all" class="cat-home-card group bg-white hover:bg-chanh-50 border-2 border-chanh-600 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-chanh-500">
                            <img src="https://lh3.googleusercontent.com/d/13B6aZbel_KYvpqqADXbuBOsw65cRXB0e=w300"
                                 onerror="handleDriveImgError(this, '13B6aZbel_KYvpqqADXbuBOsw65cRXB0e', 'Tat Ca')"
                                 alt="Tất cả sản phẩm" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-chanh-800 leading-tight block">Tất Cả Sản Phẩm</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">16 mẫu thực tế</span>
                    </button>

                    <!-- Danh mục 2 -->
                    <button type="button" onclick="filterCategory('tracu')" data-cat-btn="tracu" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/134vHjy5Vt4rq2XDnoKLy3FjIZdnBp7p3=w300"
                                 onerror="handleDriveImgError(this, '134vHjy5Vt4rq2XDnoKLy3FjIZdnBp7p3', 'Tra Cu')"
                                 alt="Trà cụ Nhật Bản" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Trà Cụ – Tetsubin</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Ấm trà & Phụ kiện</span>
                    </button>

                    <!-- Danh mục 3 -->
                    <button type="button" onclick="filterCategory('bizen')" data-cat-btn="bizen" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1j1PU-nSFXw5uQa52Hm83l6gMmMMfbLTm=w300"
                                 onerror="handleDriveImgError(this, '1j1PU-nSFXw5uQa52Hm83l6gMmMMfbLTm', 'Gom Bizen')"
                                 alt="Gốm Sứ Bizen" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Gốm Sứ Bizen</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Bình, Ấm, Đĩa, Ly</span>
                    </button>

                    <!-- Danh mục 4 -->
                    <button type="button" onclick="filterCategory('mino')" data-cat-btn="mino" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/10j2rpu78Rqi4T_pLJDMVbZbm71BP1rD9=w300"
                                 onerror="handleDriveImgError(this, '10j2rpu78Rqi4T_pLJDMVbZbm71BP1rD9', 'Gom Mino')"
                                 alt="Gốm Mino" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Gốm Mino</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Oribe, Shino, Kiseto</span>
                    </button>

                    <!-- Danh mục 5 -->
                    <button type="button" onclick="filterCategory('decor')" data-cat-btn="decor" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1TxrFnUwHCcHVo1i9jTL_ifwDQw7c4CzC=w300"
                                 onerror="handleDriveImgError(this, '1TxrFnUwHCcHVo1i9jTL_ifwDQw7c4CzC', 'Do Decor')"
                                 alt="Đồ Decor Tổng Hợp" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Đồ Decor Tổng Hợp</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Bình hoa & Tượng</span>
                    </button>

                    <!-- Danh mục 6 -->
                    <button type="button" onclick="filterCategory('diacanh')" data-cat-btn="diacanh" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1hMDDej-X6RXbAxnQKeBLGeIc1j1JU6Jg=w300"
                                 onerror="handleDriveImgError(this, '1hMDDej-X6RXbAxnQKeBLGeIc1j1JU6Jg', 'Dia Canh')"
                                 alt="Đĩa Cảnh Trang Trí" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Đĩa Cảnh Trang Trí</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Đĩa vẽ tay & Kệ kê</span>
                    </button>

                    <!-- Danh mục 7 -->
                    <button type="button" onclick="filterCategory('miniset')" data-cat-btn="miniset" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/11mBdlQNWr_pO4yhykgvJewoDXwNOGOeu=w300"
                                 onerror="handleDriveImgError(this, '11mBdlQNWr_pO4yhykgvJewoDXwNOGOeu', 'Mini Set')"
                                 alt="Mini Set & Bàn Ăn" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Mini Set & Bàn Ăn</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Tô, bát, chén, dĩa</span>
                    </button>

                    <!-- Danh mục 8 -->
                    <button type="button" onclick="filterCategory('gomkhac')" data-cat-btn="gomkhac" class="cat-home-card group bg-white hover:bg-chanh-50 border border-stone-200 rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center justify-center">
                        <div class="w-11 h-11 rounded-full overflow-hidden mb-1.5 border border-stone-200">
                            <img src="https://lh3.googleusercontent.com/d/1r84ANE9lsM8krDGAHyn6zetspm2JsCoq=w300"
                                 onerror="handleDriveImgError(this, '1r84ANE9lsM8krDGAHyn6zetspm2JsCoq', 'Kutani Satsuma')"
                                 alt="Kutani & Satsuma" class="w-full h-full object-cover group-hover:scale-110 transition">
                        </div>
                        <span class="text-[11.5px] font-bold text-stone-800 group-hover:text-chanh-800 leading-tight block">Kutani & Satsuma</span>
                        <span class="text-[10px] text-stone-500 mt-0.5">Dòng gốm cổ điển</span>
                    </button>
                </div>
            </div>
        </section>

        <!-- SECTION 3: KHU VỰC SẢN PHẨM THỰC TẾ THEO DANH MỤC (16 ẢNH THỰC TẾ, 2 CỘT TRÊN MOBILE, 4 CỘT TRÊN PC, BADGE % GIẢM GIÁ GÓC TRÊN BÊN TRÁI CHUẨN FLATSOME, KHÔNG NHÃN DÁN PHỤ) -->
        <section id="khu-vuc-san-pham" class="section py-4 md:py-6">
            <div class="flatsome-container">

                <!-- KHỐI 1: SẢN PHẨM NỔI BẬT / BỘ SƯU TẬP THỰC TẾ NHÀ CHANH -->
                <div class="mb-10">
                    <div class="section-title-container">
                        <div class="section-title-normal">
                            <h2 id="activeCategoryHeading" class="section-title-main">
                                <i class="fa-solid fa-star text-gom-gold"></i>
                                <span>SẢN PHẨM NỔI BẬT TẠI NHÀ CHANH</span>
                            </h2>
                            <div class="flex items-center gap-2 text-xs">
                                <span id="productCountText" class="text-stone-600 font-medium">Hiển thị 16 sản phẩm thực tế</span>
                                <button type="button" onclick="filterCategory('all')" class="text-chanh-700 hover:underline font-semibold">Xem tất cả</button>
                            </div>
                        </div>
                    </div>

                    <!-- Lưới sản phẩm: Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 4 cột (lg:grid-cols-4) -->
                    <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">
                        <!-- Sản phẩm được render tự động từ 16 file ảnh thực tế bằng JS bên dưới -->
                    </div>
                </div>

                <!-- KHỐI 2: TRÀ CỤ & ẤM TRÀ NHẬT BẢN (Giống bố cục shopgomnhat.com) -->
                <div class="mb-10">
                    <div class="section-title-container">
                        <div class="section-title-normal">
                            <h2 class="section-title-main">
                                <i class="fa-solid fa-mug-hot text-chanh-600"></i>
                                <span>TRÀ CỤ & BỘ ẤM TRÀ NHẬT BẢN</span>
                            </h2>
                            <a href="#khu-vuc-san-pham" onclick="filterCategory('tracu')" class="text-xs font-semibold text-chanh-700 hover:text-chanh-800">
                                Xem thêm Trà cụ <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
                    </div>
                    <div id="teaProductGrid" class="grid grid-cols-2 md:grid-cols-4 gap-3 md:gap-5"></div>
                </div>

                <!-- KHỐI 3: CÁC DÒNG GỐM NHẬT - BIZEN, MINO, KUTANI, SATSUMA & ĐĨA CẢNH DECOR -->
                <div class="mb-6">
                    <div class="section-title-container">
                        <div class="section-title-normal">
                            <h2 class="section-title-main">
                                <i class="fa-solid fa-vase text-chanh-600"></i>
                                <span>CÁC DÒNG GỐM NHẬT – BÌNH HOA, ĐĨA CẢNH & BỘ BÀN ĂN</span>
                            </h2>
                            <a href="#khu-vuc-san-pham" onclick="filterCategory('decor')" class="text-xs font-semibold text-chanh-700 hover:text-chanh-800">
                                Xem toàn bộ <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
                    </div>
                    <div id="ceramicProductGrid" class="grid grid-cols-2 md:grid-cols-4 gap-3 md:gap-5"></div>
                </div>

            </div>
        </section>

        <!-- SECTION 4: FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ + FANPAGE NGOÀI TRANG CHỦ -->
        <section id="form-bao-gia" class="section py-6 md:py-10 bg-gom-cream/70 border-y border-stone-200">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 md:gap-8 items-start">

                    <!-- CỘT TRÁI (7 CỘT): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-stone-200 p-4 sm:p-6 md:p-7 shadow-sm">
                        <div class="section-title-container mb-4">
                            <div class="section-title-normal">
                                <h2 class="section-title-main">
                                    <i class="fa-solid fa-file-invoice-dollar text-chanh-600"></i>
                                    <span>ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ SỈ / LẺ</span>
                                </h2>
                            </div>
                        </div>
                        <p class="text-xs sm:text-sm text-stone-600 mb-5 leading-relaxed">
                            Quý khách cần tìm mẫu gốm Nhật theo yêu cầu, đặt bộ quà tặng tân gia, đối tác hoặc nhận báo giá sỉ cho quán trà, nhà hàng, quán cafe? Hãy để lại thông tin, <strong>Gốm Nhật Nhà Chanh (0708.885.288)</strong> sẽ gửi hình thực tế và báo giá chi tiết ngay!
                        </p>

                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold uppercase text-stone-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="quoteName" required placeholder="Nhập họ và tên..."
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-stone-300 focus:border-chanh-600 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold uppercase text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="quotePhone" required placeholder="Ví dụ: 0905xxxxxx"
                                           class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-stone-300 focus:border-chanh-600 focus:outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold uppercase text-stone-700 mb-1">Danh mục sản phẩm quan tâm</label>
                                    <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-stone-300 focus:border-chanh-600 focus:outline-none bg-white">
                                        <option value="Trà cụ - Ấm trà Nhật Bản">Trà cụ – Ấm Tetsubin – Bộ ấm trà Nhật</option>
                                        <option value="Gốm Sứ Bizen / Mino / Kutani / Satsuma">Gốm Sứ Bizen / Mino / Kutani / Satsuma</option>
                                        <option value="Bình hoa & Đồ Decor tổng hợp">Bình hoa gốm Nhật & Đồ Decor tổng hợp</option>
                                        <option value="Đĩa cảnh trang trí & Kệ kê đĩa">Đĩa cảnh trang trí & Phụ kiện kê đĩa</option>
                                        <option value="Bộ chén đĩa bàn ăn gia đình / Nhà hàng">Bộ chén dĩa bàn ăn gia đình / Nhà hàng</option>
                                        <option value="Báo giá sỉ số lượng lớn">Nhập sỉ gốm Nhật theo kiện / Số lượng lớn</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold uppercase text-stone-700 mb-1">Hình thức mua hàng</label>
                                    <select id="quoteType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-stone-300 focus:border-chanh-600 focus:outline-none bg-white">
                                        <option value="Mua lẻ giao tận nơi">Mua lẻ – Giao hàng tận nơi (Ship COD)</option>
                                        <option value="Ghé trực tiếp cửa hàng 242 Xô Viết Nghệ Tĩnh">Ghé lựa trực tiếp tại 242 Xô Viết Nghệ Tĩnh</option>
                                        <option value="Đặt làm quà biếu / Quà tặng">Đặt set quà tặng kèm hộp sang trọng</option>
                                        <option value="Báo giá sỉ đại lý / Nhà hàng">Nhận bảng giá sỉ cho Đại lý / Nhà hàng</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold uppercase text-stone-700 mb-1">Nội dung yêu cầu & Ghi chú báo giá</label>
                                <textarea id="quoteNote" rows="3" placeholder="Mô tả mẫu gốm, kích thước, tầm giá hoặc mã sản phẩm bạn đang quan tâm..."
                                          class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-stone-300 focus:border-chanh-600 focus:outline-none"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="bg-chanh-700 hover:bg-chanh-800 text-white font-bold text-sm px-6 py-3 rounded-lg shadow transition inline-flex items-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY</span>
                                </button>
                                <span class="text-xs text-stone-500">
                                    Hoặc liên hệ trực tiếp Zalo/SĐT: <strong class="text-gom-sale">0708.885.288</strong>
                                </span>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quoteSuccessBox" class="hidden p-3.5 rounded-lg bg-chanh-50 border border-chanh-500 text-chanh-900 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>

                    <!-- CỘT PHẢI (5 CỘT): ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-stone-200 p-4 sm:p-6 shadow-sm">
                        <div class="section-title-container mb-4">
                            <div class="section-title-normal">
                                <h2 class="section-title-main">
                                    <i class="fa-brands fa-facebook text-blue-600"></i>
                                    <span>FANPAGE GỐM NHẬT NHÀ CHANH</span>
                                </h2>
                            </div>
                        </div>

                        <!-- Thẻ Fanpage trực quan kết hợp khung nhúng Facebook chính thức -->
                        <div class="rounded-xl overflow-hidden border border-stone-200 bg-stone-50">
                            <!-- Ảnh bìa thực tế của cửa hàng -->
                            <div class="relative h-36 sm:h-40 w-full overflow-hidden">
                                <img src="https://lh3.googleusercontent.com/d/1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad=w900"
                                     onerror="handleDriveImgError(this, '1xSqQflx8lRn2pWxNTAgz9SfCcDviLIad', 'Fanpage Gom Nhat Nha Chanh')"
                                     alt="Bìa Fanpage Gốm Nhật Nhà Chanh" class="w-full h-full object-cover">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/35 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w300"
                                         onerror="handleDriveImgError(this, '13tIvCCqErET29mp8YMggaz7T1ghScj5e', 'Logo')"
                                         alt="Avatar Fanpage" class="w-14 h-14 rounded-full border-2 border-white shadow-md bg-white object-cover flex-shrink-0">
                                    <div class="text-white min-w-0">
                                        <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener" class="font-bold text-base hover:underline block truncate">
                                            Gốm Nhật Nhà Chanh <i class="fa-solid fa-circle-check text-blue-400 text-xs ml-0.5"></i>
                                        </a>
                                        <p class="text-xs text-stone-200 truncate">@GomNhatNhaChanhMienTrung • Cửa hàng gốm sứ</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Thông tin Fanpage & Nút tương tác -->
                            <div class="p-3.5 space-y-3">
                                <p class="text-xs text-stone-600 leading-relaxed">
                                    Cập nhật video khui kiện gốm Nhật mới về mỗi tuần, livestream báo giá chi tiết từng mẫu đĩa cảnh, ấm trà, bình hoa tại <strong>242 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng</strong>.
                                </p>
                                <div class="flex flex-wrap gap-2">
                                    <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener"
                                       class="flex-1 inline-flex items-center justify-center gap-1.5 bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-3 rounded-lg transition">
                                        <i class="fa-brands fa-facebook-f"></i>
                                        <span>Theo Dõi Fanpage</span>
                                    </a>
                                    <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener"
                                       class="flex-1 inline-flex items-center justify-center gap-1.5 bg-stone-200 hover:bg-stone-300 text-stone-800 text-xs font-bold py-2.5 px-3 rounded-lg transition">
                                        <i class="fa-brands fa-facebook-messenger text-blue-600"></i>
                                        <span>Nhắn Tin Cho Shop</span>
                                    </a>
                                </div>

                                <!-- Facebook Iframe Page Plugin -->
                                <div class="w-full overflow-hidden rounded-lg border border-stone-200 bg-white flex justify-center">
                                    <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FGomNhatNhaChanhMienTrung&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                            width="340" height="180" style="border:none;overflow:hidden;max-width:100%;" scrolling="no" frameborder="0" allowfullscreen="true"
                                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                            title="Fanpage Gốm Nhật Nhà Chanh Miền Trung"></iframe>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECTION 5: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TÌM HIỂU – CHIA SẺ KIẾN THỨC GỐM NHẬT GIỐNG WEB MẪU) -->
        <section id="bai-viet-trang-chu" class="section py-6 md:py-10">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main">
                            <i class="fa-solid fa-book-open-reader text-chanh-600"></i>
                            <span>BÀI VIẾT – TIN TỨC & KIẾN THỨC GỐM NHẬT</span>
                        </h2>
                        <span class="text-xs text-stone-500">Chuyên mục văn hóa Trà đạo & Gốm sứ Nhật Bản</span>
                    </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 md:gap-6">
                    <!-- Bài viết 1 -->
                    <article onclick="openArticleModal(0)" class="cursor-pointer bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="relative aspect-[16/10] bg-stone-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1j1PU-nSFXw5uQa52Hm83l6gMmMMfbLTm=w600"
                                 onerror="handleDriveImgError(this, '1j1PU-nSFXw5uQa52Hm83l6gMmMMfbLTm', '7 Dong Gom Nhat')"
                                 alt="7 dòng gốm lâu đời nhất Nhật Bản" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-chanh-700 font-semibold uppercase mb-1">Kiến thức gốm Nhật</p>
                                <h3 class="font-bold text-sm md:text-base text-stone-800 hover:text-chanh-700 leading-snug mb-2">
                                    7 dòng gốm lâu đời và danh tiếng nhất Nhật Bản bạn nên biết
                                </h3>
                                <p class="text-xs text-stone-600 leading-relaxed">
                                    Nhật Bản là quốc gia có lịch sử gốm sứ lâu đời với các dòng gốm trứ danh như Bizen, Mino, Kutani, Satsuma, Arita, Shigaraki và Tokoname...
                                </p>
                            </div>
                            <span class="inline-flex items-center gap-1 text-xs font-bold text-chanh-700 mt-3">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </span>
                        </div>
                    </article>

                    <!-- Bài viết 2 -->
                    <article onclick="openArticleModal(1)" class="cursor-pointer bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="relative aspect-[16/10] bg-stone-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1TxrFnUwHCcHVo1i9jTL_ifwDQw7c4CzC=w600"
                                 onerror="handleDriveImgError(this, '1TxrFnUwHCcHVo1i9jTL_ifwDQw7c4CzC', 'Cam Hoa Ikebana')"
                                 alt="Phong cách cắm hoa Ikebana Nhật Bản" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-chanh-700 font-semibold uppercase mb-1">Nghệ thuật Decor</p>
                                <h3 class="font-bold text-sm md:text-base text-stone-800 hover:text-chanh-700 leading-snug mb-2">
                                    Phong cách cắm hoa Ikebana Nhật Bản cùng bình gốm mộc Nhà Chanh
                                </h3>
                                <p class="text-xs text-stone-600 leading-relaxed">
                                    Ikebana không chỉ là cắm hoa mà là nghệ thuật sắp đặt không gian tĩnh lặng, tôn vinh vẻ đẹp tự nhiên của cành lá và dáng bình gốm...
                                </p>
                            </div>
                            <span class="inline-flex items-center gap-1 text-xs font-bold text-chanh-700 mt-3">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </span>
                        </div>
                    </article>

                    <!-- Bài viết 3 -->
                    <article onclick="openArticleModal(2)" class="cursor-pointer bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="relative aspect-[16/10] bg-stone-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/134vHjy5Vt4rq2XDnoKLy3FjIZdnBp7p3=w600"
                                 onerror="handleDriveImgError(this, '134vHjy5Vt4rq2XDnoKLy3FjIZdnBp7p3', 'Tra Dao Nhat Ban')"
                                 alt="Tìm hiểu về Trà cụ Nhật Bản" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-chanh-700 font-semibold uppercase mb-1">Trà Đạo Nhật Bản</p>
                                <h3 class="font-bold text-sm md:text-base text-stone-800 hover:text-chanh-700 leading-snug mb-2">
                                    Cách chọn ấm trà Kyusu, Bizen và chén Chawan chuẩn vị Trà đạo
                                </h3>
                                <p class="text-xs text-stone-600 leading-relaxed">
                                    Chất đất giàu khoáng chất của ấm trà Nhật giúp làm mềm nước, giữ trọn hương thơm thanh khiết và hậu ngọt sâu của lá trà...
                                </p>
                            </div>
                            <span class="inline-flex items-center gap-1 text-xs font-bold text-chanh-700 mt-3">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </span>
                        </div>
                    </article>

                    <!-- Bài viết 4 -->
                    <article onclick="openArticleModal(3)" class="cursor-pointer bg-white rounded-xl border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="relative aspect-[16/10] bg-stone-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1r84ANE9lsM8krDGAHyn6zetspm2JsCoq=w600"
                                 onerror="handleDriveImgError(this, '1r84ANE9lsM8krDGAHyn6zetspm2JsCoq', 'Gom Kutani Satsuma')"
                                 alt="Gốm sứ truyền thống Nhật Bản Kutani và Satsuma" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <p class="text-[11px] text-chanh-700 font-semibold uppercase mb-1">Sưu tầm Gốm cổ</p>
                                <h3 class="font-bold text-sm md:text-base text-stone-800 hover:text-chanh-700 leading-snug mb-2">
                                    Tìm hiểu vẻ đẹp men vàng vương giả của Gốm Kutani & Satsuma
                                </h3>
                                <p class="text-xs text-stone-600 leading-relaxed">
                                    Nổi bật với nét vẽ tay tỉ mỉ phủ vàng kim lộng lẫy, đĩa cảnh và bình gốm Kutani – Satsuma luôn là tâm điểm sang trọng cho phòng khách...
                                </p>
                            </div>
                            <span class="inline-flex items-center gap-1 text-xs font-bold text-chanh-700 mt-3">
                                Đọc chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                            </span>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- SECTION 6: ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ (242 XÔ VIẾT NGHỆ TĨNH, CẨM LỆ, ĐÀ NẴNG) -->
        <section id="ban-do-shop" class="section py-6 md:py-10 bg-white border-t border-stone-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main">
                            <i class="fa-solid fa-map-location-dot text-chanh-600"></i>
                            <span>BẢN ĐỒ CHỈ ĐƯỜNG TỚI GỐM NHẬT NHÀ CHANH</span>
                        </h2>
                        <a href="https://maps.app.goo.gl/HtcJR3SvxsnVqr55A" target="_blank" rel="noopener" class="text-xs font-bold text-chanh-700 hover:underline">
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở ứng dụng Google Maps
                        </a>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                    <!-- Thông tin cửa hàng & Ảnh thực tế cửa hàng -->
                    <div id="ve-chung-toi" class="lg:col-span-5 bg-gom-light rounded-xl border border-stone-200 p-4 sm:p-6 flex flex-col justify-between">
                        <div>
                            <div class="flex items-center gap-3 mb-4">
                                <img src="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w200"
                                     onerror="handleDriveImgError(this, '13tIvCCqErET29mp8YMggaz7T1ghScj5e', 'Logo')"
                                     alt="Logo Nhà Chanh" class="w-12 h-12 rounded-full border border-chanh-600 object-cover">
                                <div>
                                    <h3 class="font-serif font-bold text-lg text-chanh-800">GỐM NHẬT NHÀ CHANH</h3>
                                    <p class="text-xs text-stone-500">Website chính thức: gomnhatnhachanh.com</p>
                                </div>
                            </div>

                            <ul class="space-y-2.5 text-xs sm:text-sm text-stone-700 mb-4">
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-location-dot text-gom-sale mt-1 w-4 text-center flex-shrink-0"></i>
                                    <span><strong>Địa chỉ:</strong> 242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, Tp.Đà Nẵng</span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-phone-volume text-chanh-700 mt-1 w-4 text-center flex-shrink-0"></i>
                                    <span><strong>Số điện thoại / Zalo:</strong> <a href="tel:0708885288" class="font-bold text-gom-sale hover:underline">0708.885.288</a></span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-brands fa-facebook text-blue-600 mt-1 w-4 text-center flex-shrink-0"></i>
                                    <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener" class="text-blue-700 hover:underline break-all">fb.com/GomNhatNhaChanhMienTrung</a></span>
                                </li>
                                <li class="flex items-start gap-2.5">
                                    <i class="fa-solid fa-clock text-amber-600 mt-1 w-4 text-center flex-shrink-0"></i>
                                    <span><strong>Giờ mở cửa:</strong> 09:00 – 21:30 (Tất cả các ngày trong tuần)</span>
                                </li>
                            </ul>

                            <!-- 2 Ảnh thực tế mặt tiền / kệ gốm tại 242 Xô Viết Nghệ Tĩnh -->
                            <div class="grid grid-cols-2 gap-2.5 mb-4">
                                <div class="rounded-lg overflow-hidden border border-stone-200 h-28">
                                    <img src="https://lh3.googleusercontent.com/d/1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ=w500"
                                         onerror="handleDriveImgError(this, '1lMlUwd7-eFCoVszTNZQgqdgVqZBfFXlZ', 'Cua hang 242 XVNT')"
                                         alt="Cửa hàng 242 Xô Viết Nghệ Tĩnh" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border border-stone-200 h-28">
                                    <img src="https://lh3.googleusercontent.com/d/1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A=w500"
                                         onerror="handleDriveImgError(this, '1HR1-XuUl8c25uarAfZa6_EiyzDVIC84A', 'Ke Gom Nha Chanh')"
                                         alt="Kệ gốm Nhà Chanh" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>

                        <a href="https://maps.app.goo.gl/HtcJR3SvxsnVqr55A" target="_blank" rel="noopener"
                           class="w-full inline-flex items-center justify-center gap-2 bg-chanh-700 hover:bg-chanh-800 text-white font-bold text-xs sm:text-sm py-3 px-4 rounded-lg shadow transition">
                            <i class="fa-solid fa-route"></i>
                            <span>MỞ BẢN ĐỒ GOOGLE MAPS CHỈ ĐƯỜNG TỚI SHOP</span>
                        </a>
                    </div>

                    <!-- Khung Bản Đồ Google Maps Trực Tiếp Ngoài Trang Chủ -->
                    <div class="lg:col-span-7 rounded-xl overflow-hidden border border-stone-200 shadow-sm bg-stone-100 flex flex-col min-h-[320px] sm:min-h-[380px]">
                        <iframe
                            src="https://maps.google.com/maps?q=G%E1%BB%91m%20Nh%E1%BA%ADt%20nh%C3%A0%20Chanh%20242%20X%C3%B4%20Vi%E1%BA%BFt%20Ngh%E1%BB%87%20T%C4%A9nh,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            width="100%"
                            height="100%"
                            style="border:0; min-height: 330px; flex: 1;"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            title="Google Map Gốm Nhật Nhà Chanh 242 Xô Viết Nghệ Tĩnh">
                        </iframe>
                        <div class="bg-stone-50 px-4 py-2.5 border-t border-stone-200 flex flex-wrap items-center justify-between gap-2 text-xs">
                            <span class="font-medium text-stone-700">
                                <i class="fa-solid fa-location-crosshairs text-chanh-700 mr-1"></i>Định vị: <strong>Gốm Nhật Nhà Chanh – 242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, Tp.Đà Nẵng</strong>
                            </span>
                            <a href="https://maps.app.goo.gl/HtcJR3SvxsnVqr55A" target="_blank" rel="noopener" class="text-blue-600 font-bold hover:underline">
                                Xem trên Google Maps <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 7: CAM KẾT CHÍNH SÁCH CHUẨN SHOPGOMNHAT.COM -->
        <section class="section py-6 bg-gom-cream border-t border-stone-200">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div class="bg-white p-4 rounded-xl border border-stone-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-full bg-chanh-50 text-chanh-700 flex items-center justify-center text-lg flex-shrink-0">
                            <i class="fa-solid fa-truck-fast"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-stone-800 uppercase mb-1">Giao Hàng Toàn Quốc</h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Đóng gói xốp chống sốc nhiều lớp chuyên nghiệp. Hỗ trợ giao nhanh nội thành Đà Nẵng và Ship COD toàn quốc.
                            </p>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-xl border border-stone-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-full bg-chanh-50 text-chanh-700 flex items-center justify-center text-lg flex-shrink-0">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-stone-800 uppercase mb-1">Đổi Trả Hàng Miễn Phí</h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Gốm Nhật Nhà Chanh bảo hành bể vỡ 100% trong quá trình vận chuyển và hỗ trợ đổi trả nếu giao sai mẫu đã chốt.
                            </p>
                        </div>
                    </div>
                    <div class="bg-white p-4 rounded-xl border border-stone-200 flex items-start gap-3.5">
                        <div class="w-11 h-11 rounded-full bg-chanh-50 text-chanh-700 flex items-center justify-center text-lg flex-shrink-0">
                            <i class="fa-solid fa-headset"></i>
                        </div>
                        <div>
                            <h3 class="font-bold text-sm text-stone-800 uppercase mb-1">Tư Vấn Tận Tâm 24/7</h3>
                            <p class="text-xs text-stone-600 leading-relaxed">
                                Chụp ảnh và quay video thực tế từng sản phẩm qua Zalo/Facebook trước khi gửi. Hotline: <strong>0708.885.288</strong>.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- ==========================================
         FOOTER (CHUẨN FLATSOME & SHOPGOMNHAT.COM)
         ========================================== -->
    <footer class="footer-wrapper bg-gom-brown text-stone-200 pt-10 pb-20 md:pb-8 text-xs sm:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-stone-700">

                <!-- Cột 1: Về chúng tôi -->
                <div>
                    <div class="flex items-center gap-3 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/13tIvCCqErET29mp8YMggaz7T1ghScj5e=w200"
                             onerror="handleDriveImgError(this, '13tIvCCqErET29mp8YMggaz7T1ghScj5e', 'Logo')"
                             alt="Logo Gốm Nhật Nhà Chanh" class="w-11 h-11 rounded-full bg-white object-cover">
                        <div>
                            <h4 class="font-bold text-white text-base">GỐM NHẬT NHÀ CHANH</h4>
                            <p class="text-xs text-chanh-100">gomnhatnhachanh.com</p>
                        </div>
                    </div>
                    <p class="text-stone-300 text-xs leading-relaxed mb-3">
                        Chuyên cung cấp sỉ & lẻ Gốm Sứ Nhật Bản chính hãng: Trà cụ, Ấm Tetsubin, Gốm Bizen, Gốm Mino, Kutani, Satsuma, Bình hoa, Đĩa cảnh trang trí & Bộ bàn ăn gia đình.
                    </p>
                    <ul class="space-y-1.5 text-xs text-stone-300">
                        <li><i class="fa-solid fa-location-dot text-gom-gold mr-2"></i>242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-gom-gold mr-2"></i>Hotline / Zalo: <strong>0708.885.288</strong></li>
                        <li><i class="fa-solid fa-globe text-gom-gold mr-2"></i>Website: gomnhatnhachanh.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-stone-600 inline-block">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('decor')" class="hover:text-chanh-100">• Đồ Decor Tổng Hợp & Bình Hoa</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('bizen')" class="hover:text-chanh-100">• Gốm Sứ Bizen Nhật Bản</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('mino')" class="hover:text-chanh-100">• Gốm Mino (Kiseto, Oribe, Shino)</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('tracu')" class="hover:text-chanh-100">• Trà Cụ & Ấm Tetsubin – Kamafuro</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('miniset')" class="hover:text-chanh-100">• Mini Set & Bộ Bàn Ăn Nhật</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('diacanh')" class="hover:text-chanh-100">• Đĩa Cảnh Trang Trí & Phụ Kiện Kê</a></li>
                        <li><a href="#khu-vuc-san-pham" onclick="filterCategory('gomkhac')" class="hover:text-chanh-100">• Gốm Kutani & Gốm Satsuma</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hướng dẫn & Chính sách -->
                <div>
                    <h4 class="font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-stone-600 inline-block">Hướng Dẫn & Chính Sách</h4>
                    <ul class="space-y-2 text-xs text-stone-300">
                        <li><a href="#form-bao-gia" class="hover:text-chanh-100">• Hướng dẫn đặt hàng & Báo giá</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-chanh-100">• Chính sách bán sỉ & Chiết khấu đại lý</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-chanh-100">• Chính sách bảo hành bể vỡ khi ship</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-chanh-100">• Dịch vụ vận chuyển SHIP COD toàn quốc</a></li>
                        <li><a href="#ban-do-shop" class="hover:text-chanh-100">• Chỉ đường tới cửa hàng tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối với Nhà Chanh -->
                <div>
                    <h4 class="font-bold text-white uppercase text-sm mb-3 pb-1.5 border-b border-stone-600 inline-block">Kết Nối Cùng Nhà Chanh</h4>
                    <p class="text-xs text-stone-300 mb-3 leading-relaxed">
                        Theo dõi Fanpage chính thức hoặc nhắn Zalo để xem video khui kiện gốm Nhật mới mỗi ngày.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-4">
                        <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener"
                           class="inline-flex items-center gap-1.5 bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold px-3 py-2 rounded-lg">
                            <i class="fa-brands fa-facebook-f"></i> Fanpage
                        </a>
                        <a href="https://zalo.me/0708885288" target="_blank" rel="noopener"
                           class="inline-flex items-center gap-1.5 bg-sky-500 hover:bg-sky-600 text-white text-xs font-semibold px-3 py-2 rounded-lg">
                            <i class="fa-solid fa-comment-dots"></i> Zalo 0708.885.288
                        </a>
                        <a href="https://maps.app.goo.gl/HtcJR3SvxsnVqr55A" target="_blank" rel="noopener"
                           class="inline-flex items-center gap-1.5 bg-chanh-600 hover:bg-chanh-500 text-white text-xs font-semibold px-3 py-2 rounded-lg">
                            <i class="fa-solid fa-location-dot"></i> Bản Đồ
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-stone-400">
                <p>Copyright © 2026 <strong class="text-white">Gốm Nhật Nhà Chanh (gomnhatnhachanh.com)</strong> – 242 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng.</p>
                <p>Thiết kế chuẩn giao diện UX Builder Flatsome</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         ========================================== -->
    <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0708885288" target="_blank" rel="noopener"
           class="group flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:-translate-x-1">
            <span class="w-8 h-8 rounded-full bg-white text-sky-600 font-extrabold text-xs flex items-center justify-center flex-shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/GomNhatNhaChanhMienTrung" target="_blank" rel="noopener"
           class="group flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:-translate-x-1">
            <span class="w-8 h-8 rounded-full bg-white text-blue-600 flex items-center justify-center flex-shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0708885288"
           class="floating-pulse flex items-center gap-2 bg-gom-sale hover:bg-red-700 text-white pl-3 pr-4 py-2 rounded-full shadow-xl transition">
            <span class="w-8 h-8 rounded-full bg-white text-gom-sale flex items-center justify-center flex-shrink-0">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <div class="leading-tight text-left">
                <span class="block text-[10px] uppercase text-red-100 font-medium">Hotline 24/7</span>
                <span class="block text-xs font-extrabold whitespace-nowrap">0708.885.288</span>
            </div>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH
         ========================================== -->
    <div id="productModal" class="fixed inset-0 bg-black/65 z-50 hidden items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-chanh-700 text-white flex items-center justify-between">
                <h3 id="modalProductTitleHeader" class="font-bold text-sm sm:text-base truncate pr-3">Chi tiết sản phẩm</h3>
                <button type="button" onclick="closeProductModal()" class="w-8 h-8 rounded-full bg-white/15 hover:bg-white/25 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-6 overflow-y-auto grid grid-cols-1 sm:grid-cols-12 gap-5 items-start">
                <div class="sm:col-span-6 relative rounded-xl overflow-hidden border border-stone-200 bg-stone-50 aspect-square">
                    <span id="modalProductDiscount" class="flatsome-badge-sale">-20%</span>
                    <img id="modalProductImage" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div class="sm:col-span-6 space-y-3">
                    <p id="modalProductCat" class="text-xs font-bold uppercase text-chanh-700"></p>
                    <h4 id="modalProductName" class="font-bold text-base sm:text-lg text-stone-800 leading-snug"></h4>
                    <div class="flex items-baseline gap-2.5 py-1">
                        <del id="modalProductOldPrice" class="text-sm text-stone-400"></del>
                        <span id="modalProductNewPrice" class="text-xl font-extrabold text-gom-sale"></span>
                    </div>
                    <p id="modalProductDesc" class="text-xs sm:text-sm text-stone-600 leading-relaxed"></p>
                    <div class="p-3 rounded-lg bg-stone-50 border border-stone-200 text-xs space-y-1 text-stone-700">
                        <p><i class="fa-solid fa-check text-chanh-700 mr-1.5"></i>Ảnh chụp thực tế tại Gốm Nhật Nhà Chanh</p>
                        <p><i class="fa-solid fa-location-dot text-chanh-700 mr-1.5"></i>242 Xô Viết Nghệ Tĩnh, Cẩm Lệ, Đà Nẵng</p>
                        <p><i class="fa-solid fa-phone text-chanh-700 mr-1.5"></i>Tư vấn & Chốt đơn: <strong>0708.885.288</strong></p>
                    </div>
                    <div class="flex flex-col gap-2 pt-2">
                        <button id="modalAddToCartBtn" type="button" class="w-full bg-chanh-700 hover:bg-chanh-800 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg shadow transition">
                            <i class="fa-solid fa-cart-plus mr-1.5"></i> THÊM VÀO GIỎ HÀNG
                        </button>
                        <a href="https://zalo.me/0708885288" target="_blank" rel="noopener" class="w-full text-center bg-sky-500 hover:bg-sky-600 text-white font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg transition">
                            <i class="fa-solid fa-comment-dots mr-1.5"></i> NHẮN ZALO XEM VIDEO MẪU NÀY
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         MODAL GIỎ HÀNG & ĐẶT HÀNG
         ========================================== -->
    <div id="cartModal" class="fixed inset-0 bg-black/65 z-50 hidden items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-chanh-700 text-white flex items-center justify-between">
                <h3 class="font-bold text-sm sm:text-base"><i class="fa-solid fa-basket-shopping mr-2"></i>Giỏ Hàng Gốm Nhật Nhà Chanh</h3>
                <button type="button" onclick="closeCartModal()" class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5 overflow-y-auto flex-1 space-y-4">
                <div id="cartItemsContainer" class="divide-y divide-stone-200 text-xs sm:text-sm"></div>
                <div id="cartTotalSection" class="pt-3 border-t border-stone-200 flex items-center justify-between font-bold text-sm sm:text-base">
                    <span>Tổng tạm tính:</span>
                    <span id="cartTotalPrice" class="text-gom-sale text-lg">0₫</span>
                </div>
                <form onsubmit="submitOrderCart(event)" class="space-y-3 pt-2 border-t border-stone-200">
                    <p class="text-xs font-bold uppercase text-stone-700">Thông tin nhận hàng:</p>
                    <input type="text" id="orderCustomerName" required placeholder="Họ và tên người nhận *" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded-lg">
                    <input type="tel" id="orderCustomerPhone" required placeholder="Số điện thoại liên hệ *" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded-lg">
                    <input type="text" id="orderCustomerAddress" required placeholder="Địa chỉ nhận hàng (hoặc nhận tại 242 Xô Viết Nghệ Tĩnh)" class="w-full px-3 py-2 text-xs sm:text-sm border border-stone-300 rounded-lg">
                    <button type="submit" class="w-full bg-gom-sale hover:bg-red-700 text-white font-bold text-xs sm:text-sm py-2.5 rounded-lg shadow transition">
                        HOÀN TẤT ĐẶT HÀNG (HOTLINE: 0708.885.288)
                    </button>
                    <div id="cartOrderSuccess" class="hidden p-3 rounded-lg bg-chanh-50 border border-chanh-600 text-chanh-900 text-xs font-medium"></div>
                </form>
            </div>
        </div>
    </div>

    <!-- ==========================================
         MODAL ĐỌC BÀI VIẾT KIẾN THỨC GỐM NHẬT
         ========================================== -->
    <div id="articleModal" class="fixed inset-0 bg-black/65 z-50 hidden items-center justify-center p-3 sm:p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full overflow-hidden shadow-2xl border border-stone-200 max-h-[90vh] flex flex-col">
            <div class="px-4 py-3 bg-chanh-700 text-white flex items-center justify-between">
                <h3 id="articleModalTitle" class="font-bold text-sm sm:text-base truncate pr-3">Kiến thức Gốm Nhật</h3>
                <button type="button" onclick="closeArticleModal()" class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="articleModalBody" class="p-4 sm:p-6 overflow-y-auto text-xs sm:text-sm text-stone-700 space-y-3 leading-relaxed"></div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT: DỮ LIỆU 16 ẢNH SẢN PHẨM THỰC TẾ, SLIDER, BỘ LỌC & GIỎ HÀNG
         ========================================== -->
    <script>
        // Danh sách 16 sản phẩm thực tế từ đúng 16 link Google Drive của Gốm Nhật Nhà Chanh
        const productsData = [
            {
                id: 1,
                fileId: '13B6aZbel_KYvpqqADXbuBOsw65cRXB0e',
                name: 'Bộ Trà Gốm Nhật Tuyển Chọn Nhà Chanh – Men Cổ Điển Tinh Tế (Mã NC01)',
                category: 'tracu',
                categoryName: 'Trà Cụ – Bộ Trà Nhật',
                oldPrice: 650000,
                price: 520000,
                discount: 20,
                desc: 'Bộ ấm chén trà gốm Nhật Bản tuyển chọn tại Gốm Nhật Nhà Chanh, nước men sâu ấm áp, giữ nhiệt tốt và tôn hương vị trà đạo.'
            },
            {
                id: 2,
                fileId: '134vHjy5Vt4rq2XDnoKLy3FjIZdnBp7p3',
                name: 'Ấm Trà & Trà Cụ Gốm Sứ Nhật Bản Chế Tác Thủ Công (Mã NC02)',
                category: 'tracu',
                categoryName: 'Trà Cụ – Ấm Tetsubin',
                oldPrice: 780000,
                price: 620000,
                discount: 21,
                desc: 'Trà cụ gốm sứ Nhật Bản chuẩn mộc, lọc trà êm, dòng nước rót tròn đều, thích hợp thưởng trà đạo hoặc làm quà biếu sang trọng.'
            },
            {
                id: 3,
                fileId: '1j1PU-nSFXw5uQa52Hm83l6gMmMMfbLTm',
                name: 'Tác Phẩm Gốm Sứ Bizen Nhật Bản Hỏa Biến Tự Nhiên (Mã NC03)',
                category: 'bizen',
                categoryName: 'Gốm Sứ Bizen',
                oldPrice: 850000,
                price: 680000,
                discount: 20,
                desc: 'Gốm Bizen trứ danh Nhật Bản nung củi truyền thống tạo vết hỏa biến tự nhiên độc bản, càng dùng lâu chất gốm càng bóng đẹp.'
            },
            {
                id: 4,
                fileId: '10j2rpu78Rqi4T_pLJDMVbZbm71BP1rD9',
                name: 'Gốm Mino Nhật Bản – Vẻ Đẹp Men Truyền Thống Tuyển Chọn (Mã NC04)',
                category: 'mino',
                categoryName: 'Gốm Mino',
                oldPrice: 520000,
                price: 420000,
                discount: 19,
                desc: 'Sản phẩm thuộc dòng gốm Mino truyền thống Nhật Bản với sắc men mộc mạc, hài hòa cho bàn trà và không gian sống.'
            },
            {
                id: 5,
                fileId: '1TxrFnUwHCcHVo1i9jTL_ifwDQw7c4CzC',
                name: 'Bình Hoa Gốm Nhật Nghệ Thuật Cắm Hoa Ikebana Nhà Chanh (Mã NC05)',
                category: 'decor',
                categoryName: 'Đồ Decor Tổng Hợp',
                oldPrice: 590000,
                price: 450000,
                discount: 24,
                desc: 'Bình gốm Nhật dáng chuẩn cắm hoa Ikebana hoặc trưng bày kệ gỗ phòng khách, hoa văn tinh xảo tạo điểm nhấn thanh lịch.'
            },
            {
                id: 6,
                fileId: '13_IK_X14FD1wkjRxgCo1FjDWPQeudyUe',
                name: 'Bình Gốm Sứ Nhật Bản Vẽ Tay Trang Trí Phòng Khách (Mã NC06)',
                category: 'decor',
                categoryName: 'Đồ Decor Tổng Hợp',
                oldPrice: 680000,
                price: 550000,
                discount: 19,
                desc: 'Bình gốm trang trí tuyển chọn trực tiếp tại Gốm Nhật Nhà Chanh 242 Xô Viết Nghệ Tĩnh, Đà Nẵng.'
            },
            {
                id: 7,
                fileId: '1hMDDej-X6RXbAxnQKeBLGeIc1j1JU6Jg',
                name: 'Đĩa Cảnh Trang Trí Gốm Sứ Nhật Bản Hoa Văn Sắc Nét (Mã NC07)',
                category: 'diacanh',
                categoryName: 'Đĩa Cảnh Trang Trí',
                oldPrice: 480000,
                price: 380000,
                discount: 21,
                desc: 'Đĩa cảnh gốm sứ Nhật Bản họa tiết truyền thống nổi bật, tặng kèm tư vấn chọn chân kê đĩa trưng bày tủ kệ.'
            },
            {
                id: 8,
                fileId: '1K8kobfNUWkLdcqkHOF8hUpO-Bq-sYHl_',
                name: 'Đĩa Gốm Nhật Vẽ Tay Nghệ Thuật Trưng Bày & Bàn Tiệc (Mã NC08)',
                category: 'diacanh',
                categoryName: 'Đĩa Cảnh Trang Trí',
                oldPrice: 420000,
                price: 340000,
                discount: 19,
                desc: 'Đĩa gốm Nhật Bản nước men bóng sáng, họa tiết vẽ tay tỉ mỉ vừa dùng bày biện món ăn vừa làm đĩa cảnh decor.'
            },
            {
                id: 9,
                fileId: '11mBdlQNWr_pO4yhykgvJewoDXwNOGOeu',
                name: 'Bộ Chén Đĩa Bàn Ăn Gốm Sứ Nhật Bản Cao Cấp (Mã NC09)',
                category: 'miniset',
                categoryName: 'Mini Set & Bàn Ăn',
                oldPrice: 550000,
                price: 440000,
                discount: 20,
                desc: 'Set chén đĩa gốm Nhật làm bừng sáng căn bếp gia đình, chất sứ dày dặn, an toàn sức khỏe.'
            },
            {
                id: 10,
                fileId: '1PTeCvPqARqzM6dNWBNGTrjpdx3tdfNaQ',
                name: 'Mini Set Tô Bát Đĩa Gốm Nhật Họa Tiết Lam Cổ Điển (Mã NC10)',
                category: 'miniset',
                categoryName: 'Mini Set & Bàn Ăn',
                oldPrice: 460000,
                price: 370000,
                discount: 20,
                desc: 'Bộ tô bát chén gốm Nhật Bản phong cách truyền thống, rất được ưa chuộng tại các gia đình và nhà hàng Nhật.'
            },
            {
                id: 11,
                fileId: '1K-20jw3ng-Fhfjg_fD5IqNngp6YyxSHe',
                name: 'Chawan & Ly Gốm Thưởng Trà Đạo Nhật Bản Độc Bản (Mã NC11)',
                category: 'tracu',
                categoryName: 'Trà Cụ – Chawan',
                oldPrice: 390000,
                price: 310000,
                discount: 21,
                desc: 'Chén trà Chawan và ly gốm Nhật cầm đầm tay, giữ nhiệt lâu, tôn màu nước trà xanh matcha và sencha.'
            },
            {
                id: 12,
                fileId: '1MVZZYDoL5g0YWH8iIlfuctFjVeNcyiDB',
                name: 'Bình Trà & Ấm Gốm Bizen Hidasuki Tuyển Chọn (Mã NC12)',
                category: 'bizen',
                categoryName: 'Gốm Sứ Bizen',
                oldPrice: 750000,
                price: 600000,
                discount: 20,
                desc: 'Tác phẩm gốm Bizen mang sắc đất nung ấm áp đặc trưng của nghệ nhân Nhật Bản.'
            },
            {
                id: 13,
                fileId: '1r84ANE9lsM8krDGAHyn6zetspm2JsCoq',
                name: 'Gốm Kutani Nhật Bản Vẽ Vàng Thủ Công Sang Trọng (Mã NC13)',
                category: 'gomkhac',
                categoryName: 'Gốm Kutani & Satsuma',
                oldPrice: 890000,
                price: 720000,
                discount: 19,
                desc: 'Dòng gốm Kutani nổi danh với bảng màu rực rỡ và đường viền nhũ vàng quý phái, thích hợp sưu tầm và biếu tặng.'
            },
            {
                id: 14,
                fileId: '1rEgparZdR43D7ONSEw-PS-BgryeeAcbF',
                name: 'Gốm Satsuma & Arita Nhật Bản Hoa Văn Cổ Truyền (Mã NC14)',
                category: 'gomkhac',
                categoryName: 'Gốm Kutani & Satsuma',
                oldPrice: 820000,
                price: 660000,
                discount: 20,
                desc: 'Tuyệt tác gốm Satsuma / Arita Nhật Bản với lớp men rạn nhẹ cổ kính và nét vẽ thủ công sống động.'
            },
            {
                id: 15,
                fileId: '1w_DIp5VU1Uem7N3vjyWjtiuZBJRAC3OS',
                name: 'Set Gốm Mino Oribe & Shino Phong Cách Mộc Trà Đạo (Mã NC15)',
                category: 'mino',
                categoryName: 'Gốm Mino',
                oldPrice: 610000,
                price: 490000,
                discount: 20,
                desc: 'Sự kết hợp hài hòa giữa men xanh Oribe và men trắng sữa Shino đặc trưng của vùng gốm Mino Nhật Bản.'
            },
            {
                id: 16,
                fileId: '1534rcy2Bly8R9cBKt_9Uf7XY_kEO9v5e',
                name: 'Vật Phẩm Decor & Chậu Gốm Bonsai Mini Nhà Chanh (Mã NC16)',
                category: 'decor',
                categoryName: 'Đồ Decor Tổng Hợp',
                oldPrice: 450000,
                price: 350000,
                discount: 22,
                desc: 'Vật phẩm trang trí bàn trà, kệ sách và chậu gốm mini mang đậm hơi thở thiền tịnh Nhật Bản.'
            }
        ];

        function formatVND(amount) {
            return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + '₫';
        }

        // Tạo HTML cho 1 thẻ sản phẩm chuẩn Flatsome (Chỉ có cục % giảm giá góc trên bên trái, không có nhãn dán phụ, tên sản phẩm đầy đủ không cắt chữ)
        function createProductCardHTML(product) {
            const imgUrl = `https://lh3.googleusercontent.com/d/${product.fileId}=w700`;
            return `
                <div class="product-small-box group">
                    <div class="product-box-image cursor-pointer" onclick="openProductModal(${product.id})">
                        <span class="flatsome-badge-sale">-${product.discount}%</span>
                        <img src="${imgUrl}"
                             onerror="handleDriveImgError(this, '${product.fileId}', 'Gom Nhat NC${product.id}')"
                             alt="${product.name}"
                             loading="lazy">
                    </div>
                    <div class="product-box-text">
                        <div>
                            <p class="text-[10.5px] uppercase tracking-wide text-stone-400 font-semibold mb-1">${product.categoryName}</p>
                            <a href="#khu-vuc-san-pham" onclick="openProductModal(${product.id}); return false;" class="product-title">
                                ${product.name}
                            </a>
                        </div>
                        <div class="pt-2 mt-1 border-t border-stone-100">
                            <div class="price-wrapper flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] sm:text-xs text-stone-400 font-normal">${formatVND(product.oldPrice)}</del>
                                <ins class="text-sm sm:text-base font-extrabold text-gom-sale no-underline">${formatVND(product.price)}</ins>
                            </div>
                            <button type="button" onclick="addToCart(${product.id})"
                                    class="w-full py-1.5 px-2.5 rounded bg-chanh-700 hover:bg-chanh-800 text-white font-semibold text-xs transition flex items-center justify-center gap-1.5">
                                <i class="fa-solid fa-cart-plus text-[11px]"></i>
                                <span>Thêm vào giỏ</span>
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        // Render các lưới sản phẩm ngoài trang chủ
        function renderInitialGrids() {
            const mainGrid = document.getElementById('mainProductGrid');
            const teaGrid = document.getElementById('teaProductGrid');
            const ceramicGrid = document.getElementById('ceramicProductGrid');

            mainGrid.innerHTML = productsData.map(createProductCardHTML).join('');

            const teaProducts = productsData.filter(p => p.category === 'tracu' || p.category === 'bizen').slice(0, 4);
            teaGrid.innerHTML = teaProducts.map(createProductCardHTML).join('');

            const ceramicProducts = productsData.filter(p => ['decor', 'diacanh', 'miniset', 'gomkhac', 'mino'].includes(p.category)).slice(0, 8);
            ceramicGrid.innerHTML = ceramicProducts.map(createProductCardHTML).join('');
        }

        // Lọc theo danh mục
        const categoryTitles = {
            all: 'TẤT CẢ SẢN PHẨM THỰC TẾ TẠI NHÀ CHANH',
            tracu: 'DANH MỤC: TRÀ CỤ & ẤM TETSUBIN NHẬT BẢN',
            bizen: 'DANH MỤC: GỐM SỨ BIZEN NHẬT BẢN',
            mino: 'DANH MỤC: GỐM MINO (ORIBE, SHINO, KISETO)',
            decor: 'DANH MỤC: ĐỒ DECOR TỔNG HỢP & BÌNH HOA',
            diacanh: 'DANH MỤC: ĐĨA CẢNH TRANG TRÍ',
            miniset: 'DANH MỤC: MINI SET & BỘ BÀN ĂN NHẬT',
            gomkhac: 'DANH MỤC: GỐM KUTANI & GỐM SATSUMA'
        };

        function filterCategory(catKey) {
            const filtered = catKey === 'all'
                ? productsData
                : productsData.filter(p => p.category === catKey);

            const mainGrid = document.getElementById('mainProductGrid');
            const heading = document.getElementById('activeCategoryHeading');
            const countText = document.getElementById('productCountText');

            heading.innerHTML = `<i class="fa-solid fa-star text-gom-gold"></i> <span>${categoryTitles[catKey] || categoryTitles.all}</span>`;
            countText.textContent = `Hiển thị ${filtered.length} sản phẩm thực tế`;
            mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');

            // Highlight thẻ danh mục trang chủ
            document.querySelectorAll('[data-cat-btn]').forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === catKey) {
                    btn.classList.add('border-2', 'border-chanh-600', 'bg-chanh-50/40');
                    btn.classList.remove('border-stone-200');
                } else {
                    btn.classList.remove('border-2', 'border-chanh-600', 'bg-chanh-50/40');
                    btn.classList.add('border', 'border-stone-200');
                }
            });

            const productSection = document.getElementById('khu-vuc-san-pham');
            if (productSection && catKey !== 'all') {
                productSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        // Tìm kiếm sản phẩm
        function runSearchQuery(keyword) {
            const q = keyword.trim().toLowerCase();
            const filtered = !q
                ? productsData
                : productsData.filter(p =>
                    p.name.toLowerCase().includes(q) ||
                    p.categoryName.toLowerCase().includes(q) ||
                    p.desc.toLowerCase().includes(q)
                );

            const mainGrid = document.getElementById('mainProductGrid');
            const heading = document.getElementById('activeCategoryHeading');
            const countText = document.getElementById('productCountText');

            heading.innerHTML = `<i class="fa-solid fa-magnifying-glass text-chanh-600"></i> <span>KẾT QUẢ TÌM KIẾM: "${keyword}"</span>`;
            countText.textContent = `Tìm thấy ${filtered.length} sản phẩm`;

            if (filtered.length === 0) {
                mainGrid.innerHTML = `
                    <div class="col-span-full bg-white p-6 rounded-xl border border-stone-200 text-center">
                        <p class="text-sm text-stone-600 mb-3">Không tìm thấy mẫu trùng khớp với từ khóa "<strong>${keyword}</strong>".</p>
                        <button type="button" onclick="filterCategory('all')" class="bg-chanh-700 text-white text-xs font-bold px-4 py-2 rounded-lg">Xem tất cả 16 sản phẩm</button>
                    </div>
                `;
            } else {
                mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');
            }
            document.getElementById('khu-vuc-san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        function handleSearch(e) {
            e.preventDefault();
            const val = document.getElementById('desktopSearchInput').value;
            runSearchQuery(val);
        }

        function handleMobileSearch(e) {
            e.preventDefault();
            const val = document.getElementById('mobileSearchInput').value;
            runSearchQuery(val);
        }

        // Slider 2 Banner tự trượt chuyên nghiệp
        let currentBannerIdx = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            const slides = document.querySelectorAll('.banner-slide');
            slides.forEach((slide, idx) => {
                if (idx === currentBannerIdx) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');
            if (currentBannerIdx === 0) {
                dot0.className = 'w-6 h-2 rounded-full bg-white transition-all';
                dot1.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
            } else {
                dot0.className = 'w-2.5 h-2 rounded-full bg-white/50 transition-all';
                dot1.className = 'w-6 h-2 rounded-full bg-white transition-all';
            }
        }

        function nextBanner() {
            currentBannerIdx = (currentBannerIdx + 1) % totalBanners;
            updateBannerUI();
            resetBannerTimer();
        }

        function prevBanner() {
            currentBannerIdx = (currentBannerIdx - 1 + totalBanners) % totalBanners;
            updateBannerUI();
            resetBannerTimer();
        }

        function goToBanner(idx) {
            currentBannerIdx = idx;
            updateBannerUI();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentBannerIdx = (currentBannerIdx + 1) % totalBanners;
                updateBannerUI();
            }, 5000);
        }

        // Mobile Drawer Menu
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            const drawer = document.getElementById('mobileMenuDrawer');
            const isHidden = overlay.classList.contains('hidden');
            if (isHidden) {
                overlay.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            } else {
                overlay.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            }
        }

        // Modal Chi tiết sản phẩm
        function openProductModal(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;

            document.getElementById('modalProductTitleHeader').textContent = product.name;
            document.getElementById('modalProductCat').textContent = product.categoryName;
            document.getElementById('modalProductName').textContent = product.name;
            document.getElementById('modalProductOldPrice').textContent = formatVND(product.oldPrice);
            document.getElementById('modalProductNewPrice').textContent = formatVND(product.price);
            document.getElementById('modalProductDiscount').textContent = `-${product.discount}%`;
            document.getElementById('modalProductDesc').textContent = product.desc;

            const imgEl = document.getElementById('modalProductImage');
            imgEl.setAttribute('data-retry-step', '0');
            imgEl.onerror = function() { handleDriveImgError(this, product.fileId, product.name); };
            imgEl.src = `https://lh3.googleusercontent.com/d/${product.fileId}=w900`;

            const addBtn = document.getElementById('modalAddToCartBtn');
            addBtn.onclick = function() {
                addToCart(product.id);
                closeProductModal();
                openCartModal();
            };

            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Giỏ hàng
        let cart = [];

        function addToCart(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            const existing = cart.find(item => item.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartUI();
        }

        function removeFromCart(productId) {
            cart = cart.filter(item => item.id !== productId);
            updateCartUI();
        }

        function updateCartUI() {
            const totalQty = cart.reduce((sum, item) => sum + item.qty, 0);
            document.getElementById('cartCountBadge').textContent = totalQty;

            const container = document.getElementById('cartItemsContainer');
            const totalPriceEl = document.getElementById('cartTotalPrice');

            if (cart.length === 0) {
                container.innerHTML = `<p class="py-6 text-center text-stone-500">Chưa có sản phẩm nào trong giỏ hàng.</p>`;
                totalPriceEl.textContent = '0₫';
                return;
            }

            let total = 0;
            container.innerHTML = cart.map(item => {
                const sub = item.price * item.qty;
                total += sub;
                return `
                    <div class="py-2.5 flex items-center justify-between gap-3">
                        <div class="flex items-center gap-2.5 min-w-0">
                            <img src="https://lh3.googleusercontent.com/d/${item.fileId}=w200"
                                 onerror="handleDriveImgError(this, '${item.fileId}', 'SP')"
                                 alt="${item.name}" class="w-12 h-12 rounded object-cover border border-stone-200 flex-shrink-0">
                            <div class="min-w-0">
                                <p class="font-semibold text-stone-800 text-xs leading-snug">${item.name}</p>
                                <p class="text-xs text-gom-sale font-bold mt-0.5">${formatVND(item.price)} x ${item.qty}</p>
                            </div>
                        </div>
                        <button type="button" onclick="removeFromCart(${item.id})" class="text-stone-400 hover:text-red-600 p-1">
                            <i class="fa-solid fa-trash-can"></i>
                        </button>
                    </div>
                `;
            }).join('');
            totalPriceEl.textContent = formatVND(total);
        }

        function openCartModal() {
            updateCartUI();
            const modal = document.getElementById('cartModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeCartModal() {
            const modal = document.getElementById('cartModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function submitOrderCart(e) {
            e.preventDefault();
            const name = document.getElementById('orderCustomerName').value;
            const phone = document.getElementById('orderCustomerPhone').value;
            const box = document.getElementById('cartOrderSuccess');
            box.classList.remove('hidden');
            box.innerHTML = `<i class="fa-solid fa-circle-check text-chanh-700 mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Đơn hàng của quý khách đã được ghi nhận. Gốm Nhật Nhà Chanh (<strong>0708.885.288</strong>) sẽ liên hệ xác nhận ngay.`;
            cart = [];
            updateCartUI();
        }

        // Xử lý gửi Form Yêu Cầu & Báo Giá ngoài trang chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('quoteName').value;
            const phone = document.getElementById('quotePhone').value;
            const cat = document.getElementById('quoteCategory').value;
            const box = document.getElementById('quoteSuccessBox');

            box.classList.remove('hidden');
            box.innerHTML = `
                <i class="fa-solid fa-circle-check text-chanh-700 mr-1.5"></i>
                Đã gửi yêu cầu báo giá thành công! Cảm ơn anh/chị <strong>${name}</strong> (${phone}) đã quan tâm danh mục <strong>${cat}</strong>. Bộ phận CSKH Gốm Nhật Nhà Chanh (<strong>0708.885.288</strong>) sẽ liên hệ qua Zalo/SĐT trong ít phút.
            `;
            document.getElementById('quoteRequestForm').reset();
        }

        // Dữ liệu chi tiết các bài viết trang chủ
        const articlesContent = [
            {
                title: '7 dòng gốm lâu đời và danh tiếng nhất Nhật Bản',
                body: `
                    <p><strong>1. Gốm Bizen (Bizen-yaki):</strong> Một trong Lục cổ vô danh tiếng nhất Nhật Bản, hoàn toàn không phủ men mà nung bằng củi thông suốt nhiều ngày ở nhiệt độ cao, tạo nên những vệt hỏa biến tự nhiên độc nhất vô nhị.</p>
                    <p><strong>2. Gốm Mino (Mino-yaki):</strong> Bao gồm các dòng gốm trứ danh như Oribe (men xanh đồng), Shino (men trắng sữa dày), Kiseto (men vàng cổ) và Setoguro (men đen huyền).</p>
                    <p><strong>3. Gốm Kutani & Satsuma:</strong> Nổi bật với nghệ thuật vẽ tay phủ men màu rực rỡ điểm xuyết vàng kim vương giả, thường xuất hiện trên các mẫu đĩa cảnh, bình hoa và bộ trà cao cấp.</p>
                    <p>Tại <strong>Gốm Nhật Nhà Chanh (242 Xô Viết Nghệ Tĩnh, Phường Cẩm Lệ, TP. Đà Nẵng)</strong>, quý khách có thể trực tiếp chiêm ngưỡng và lựa chọn các tác phẩm thuộc những dòng gốm truyền thống này.</p>
                `
            },
            {
                title: 'Phong cách cắm hoa Ikebana Nhật Bản cùng bình gốm mộc Nhà Chanh',
                body: `
                    <p><strong>Ikebana (Hoa đạo)</strong> là nghệ thuật cắm hoa truyền thống của người Nhật, đề cao sự tối giản, bất đối xứng và vẻ đẹp tự nhiên của từng nhánh cây, ngọn cỏ.</p>
                    <p>Khi kết hợp cùng những mẫu bình gốm Bizen, Shigaraki hay bình gốm men mộc tại <strong>Gốm Nhật Nhà Chanh</strong>, chỉ cần một nhành mai, cành thông hay vài bông cúc nhỏ cũng đủ biến góc bàn trà, phòng khách trở nên tĩnh tại và sang trọng.</p>
                `
            },
            {
                title: 'Cách chọn ấm trà Kyusu, Bizen và chén Chawan chuẩn vị Trà đạo',
                body: `
                    <p>Một chiếc ấm trà Nhật tốt không chỉ đẹp ở dáng vẻ mà còn nằm ở độ khít của nắp ấm, lưới lọc tổ ong tinh xảo và chất đất giàu khoáng chất.</p>
                    <p>Ấm Tetsubin dùng để đun nước giúp bổ sung vi lượng sắt tự nhiên làm nước ngọt dịu, trong khi ấm Bizen và Tokoname giúp giảm vị đắng chát của trà xanh, giữ trọn hậu vị ngọt thanh.</p>
                `
            },
            {
                title: 'Tìm hiểu vẻ đẹp men vàng vương giả của Gốm Kutani & Satsuma',
                body: `
                    <p>Gốm Kutani và Satsuma từ lâu đã được giới sưu tầm gốm sứ trên toàn thế giới săn đón bởi kỹ thuật vẽ vàng nổi (Kinrande) cực kỳ công phu trên nền men rạn mịn.</p>
                    <p>Mỗi chiếc đĩa cảnh hay bình gốm Kutani – Satsuma trưng bày trên kệ gỗ trong phòng khách không chỉ mang giá trị nghệ thuật mà còn mang ý nghĩa phong thủy cát tường, thịnh vượng.</p>
                `
            }
        ];

        function openArticleModal(idx) {
            const art = articlesContent[idx];
            if (!art) return;
            document.getElementById('articleModalTitle').textContent = art.title;
            document.getElementById('articleModalBody').innerHTML = art.body;
            const modal = document.getElementById('articleModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeArticleModal() {
            const modal = document.getElementById('articleModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Khởi chạy khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderInitialGrids();
            resetBannerTimer();
        });
    </script>
</body>
</html>

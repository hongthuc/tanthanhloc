<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TÂN THANH LỘC - Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói Đà Nẵng | tanthanhloc.com</title>
    <meta name="description" content="CÔNG TY TNHH TÂN THANH LỘC (tanthanhloc.com) - Chuyên phân phối Gạch lát nền, Gạch ốp tường, Gạch giả gỗ, Gạch sân vườn, Thiết bị vệ sinh trọn gói uy tín tại 417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng.">

    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tanthanhloc.com/">
    <meta property="og:title" content="CÔNG TY TNHH TÂN THANH LỘC - Gạch Ốp Lát & Thiết Bị Vệ Sinh Đà Nẵng">
    <meta property="og:description" content="Showroom Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói tại 417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng. Hotline: 0914.704.046 - 0932.564.550">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds&sz=w800">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds&sz=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#b91c1c', // Màu đỏ gốm sứ chủ đạo theo logo & web mẫu
                            dark: '#881313',
                            light: '#fef2f2',
                            gold: '#d97706',
                            navy: '#1e293b'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 10px;
            padding-right: 10px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Chuẩn tiêu đề Section của Flatsome UX Builder */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 0.5rem;
            gap: 0.75rem;
            flex-wrap: wrap;
        }
        .section-title-main {
            font-weight: 800;
            text-transform: uppercase;
            color: #b91c1c;
            border-bottom: 3px solid #b91c1c;
            margin-bottom: -0.62rem;
            padding-bottom: 0.5rem;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
        }

        /* Tên danh mục viết liền trên 1 hàng, không bao giờ xuống dòng giữa chừng */
        .nav-cat-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-discount-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #b91c1c;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 5px 7px;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.18);
        }

        /* Khung sản phẩm Flatsome đơn giản, tên sản phẩm hiển thị đầy đủ không bị cắt chữ */
        .product-small.box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .product-small.box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -5px rgba(0, 0, 0, 0.08);
            border-color: #cbd5e1;
        }
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(185, 28, 28, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(185, 28, 28, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==================== HEADER FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40 w-full">
        <!-- Topbar thông tin công ty gọn gàng -->
        <div class="bg-brand text-white text-xs py-1.5 w-full">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-amber-300 shrink-0"></i>
                    <span class="truncate">417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng | Web: <strong>tanthanhloc.com</strong></span>
                </div>
                <div class="hidden md:flex items-center gap-4 shrink-0">
                    <a href="#ve-chung-toi" class="hover:text-amber-200 transition">Hồ sơ năng lực</a>
                    <span>|</span>
                    <a href="#tin-tuc" class="hover:text-amber-200 transition">Kiến thức xây dựng</a>
                    <span>|</span>
                    <a href="#bao-gia" class="hover:text-amber-200 transition">Báo giá sỉ & lẻ</a>
                    <span>|</span>
                    <a href="#lien-he" class="hover:text-amber-200 transition">Liên hệ Showroom</a>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm + Giỏ báo giá -->
        <div class="py-2.5 border-b border-slate-100 w-full bg-white">
            <div class="flatsome-container flex items-center justify-between gap-3">
                <!-- Nút mở menu trên điện thoại -->
                <button id="mobile-menu-btn" type="button" aria-label="Menu danh mục" class="lg:hidden p-2 rounded-md text-slate-700 hover:bg-slate-100 shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <img
                        src="https://drive.google.com/thumbnail?id=1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds&sz=w400"
                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds=w400';"
                        alt="Logo Công Ty TNHH Tân Thanh Lộc"
                        class="h-9 sm:h-11 w-auto object-contain rounded"
                    >
                    <div class="leading-tight">
                        <span class="block font-extrabold text-brand text-xs sm:text-sm md:text-base tracking-tight">TÂN THANH LỘC CERAMIC</span>
                        <span class="block text-[10px] sm:text-xs text-slate-500 font-medium">Gạch Ốp Lát & TBVS Trọn Gói</span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <form id="desktop-search-form" class="w-full flex rounded-lg overflow-hidden border border-slate-300 focus-within:border-brand">
                        <input
                            id="search-input"
                            type="text"
                            placeholder="Tìm gạch lát nền 60x60, 80x80, gạch ốp tường, gạch giả gỗ, thiết bị vệ sinh..."
                            class="w-full px-3.5 py-2 text-xs sm:text-sm focus:outline-none"
                        >
                        <button type="submit" class="bg-brand hover:bg-brand-dark text-white px-4 text-xs sm:text-sm font-semibold shrink-0 transition">
                            <i class="fa-solid fa-magnifying-glass mr-1"></i> Tìm kiếm
                        </button>
                    </form>
                </div>

                <!-- Liên kết nhanh gọn (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-2 shrink-0">
                    <a href="#bao-gia" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-brand hover:text-white text-slate-700 text-xs font-semibold px-3 py-2 rounded-lg transition whitespace-nowrap">
                        <i class="fa-solid fa-file-invoice"></i>
                        <span class="hidden sm:inline">Nhận báo giá</span>
                    </a>
                    <a href="#bando-showroom" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-brand hover:text-white text-slate-700 text-xs font-semibold px-3 py-2 rounded-lg transition whitespace-nowrap">
                        <i class="fa-solid fa-map-location-dot"></i>
                        <span class="hidden sm:inline">Chỉ đường</span>
                    </a>
                </div>
            </div>

            <!-- Ô tìm kiếm trên điện thoại -->
            <div class="flatsome-container mt-2 md:hidden">
                <form id="mobile-search-form" class="w-full flex rounded-lg overflow-hidden border border-slate-300">
                    <input
                        id="mobile-search-input"
                        type="text"
                        placeholder="Tìm kiếm mẫu gạch, thiết bị vệ sinh..."
                        class="w-full px-3 py-1.5 text-xs focus:outline-none"
                    >
                    <button type="submit" class="bg-brand text-white px-3 text-xs font-semibold shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- Thanh Danh Mục Trên Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, tuyệt đối không xuống dòng trong tên danh mục -->
        <nav class="hidden lg:block bg-slate-900 text-white w-full border-b border-slate-800">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-1 py-1.5 text-[12.5px] font-semibold">
                    <li>
                        <a href="#trang-chu" class="nav-cat-link px-2.5 py-1.5 rounded bg-brand text-white">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang chủ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-lat-nen" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch lát nền
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-op-tuong" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch ốp tường
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-gia-go" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch giả gỗ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-gia-go" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch lát sân vườn
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-op-tuong" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch nhập khẩu
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-gia-go" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Gạch trang trí
                        </a>
                    </li>
                    <li>
                        <a href="#sec-thiet-bi-ve-sinh" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Thiết bị vệ sinh
                        </a>
                    </li>
                    <li>
                        <a href="#sec-thiet-bi-ve-sinh" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Sản phẩm khác
                        </a>
                    </li>
                    <li>
                        <a href="#ve-chung-toi" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Dự án
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-lat-nen" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Khuyến mãi
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Tin tức
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he" class="nav-cat-link px-2.5 py-1.5 rounded hover:bg-slate-800 hover:text-amber-300">
                            Liên hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh Mục Thu Gọn Mở Rộng Trên Điện Thoại -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg w-full">
            <div class="flatsome-container py-3">
                <div class="text-xs font-bold uppercase text-slate-400 mb-2">Danh mục sản phẩm & dịch vụ</div>
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-2 text-xs font-semibold">
                    <a href="#sec-gach-lat-nen" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch lát nền</a>
                    <a href="#sec-gach-op-tuong" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch ốp tường</a>
                    <a href="#sec-gach-gia-go" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch giả gỗ</a>
                    <a href="#sec-gach-gia-go" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch lát sân vườn</a>
                    <a href="#sec-gach-op-tuong" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch nhập khẩu</a>
                    <a href="#sec-gach-gia-go" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Gạch trang trí</a>
                    <a href="#sec-thiet-bi-ve-sinh" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Thiết bị vệ sinh</a>
                    <a href="#sec-thiet-bi-ve-sinh" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Sản phẩm khác</a>
                    <a href="#ve-chung-toi" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Dự án & Showroom</a>
                    <a href="#tin-tuc" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Tin tức xây dựng</a>
                    <a href="#bao-gia" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Báo giá trọn gói</a>
                    <a href="#lien-he" class="mobile-nav-item nav-cat-link px-3 py-2 rounded bg-slate-100 hover:bg-brand hover:text-white">Liên hệ & Bản đồ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE) ==================== -->
    <main id="trang-chu" class="w-full py-4 space-y-8">

        <!-- 1. SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU, HÌNH ẢNH & CHỮ NẰM TRONG HẾT BANNER, CÁCH XA VIỀN -->
        <section class="w-full">
            <div class="flatsome-container">
                <div class="relative w-full h-[250px] sm:h-[320px] md:h-[400px] lg:h-[440px] rounded-xl overflow-hidden shadow-md bg-slate-900">

                    <!-- SLIDE 1 -->
                    <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                        <!-- Ảnh nền showroom cửa hàng thực tế kết hợp lớp phủ sang trọng -->
                        <img
                            src="https://drive.google.com/thumbnail?id=1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx&sz=w1400"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx=w1400';"
                            alt="Showroom Công Ty TNHH Tân Thanh Lộc"
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-slate-950/90 via-slate-900/75 to-slate-900/40"></div>

                        <!-- Nội dung chữ & hình ảnh phụ nằm hoàn toàn bên trong, cách xa viền ảnh banner -->
                        <div class="absolute inset-0 flex items-center justify-between px-7 sm:px-12 md:px-16 lg:px-24 py-6 sm:py-10">
                            <div class="max-w-xl text-white space-y-2 sm:space-y-3.5">
                                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-amber-400">
                                    CÔNG TY TNHH TÂN THANH LỘC • TANTHANHLOC.COM
                                </p>
                                <h1 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                    TỔNG KHO GẠCH ỐP LÁT & THIẾT BỊ VỆ SINH TRỌN GÓI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed">
                                    Chuyên phân phối sỉ & lẻ gạch lát nền, gạch ốp tường, gạch vân gỗ, gạch sân vườn và thiết bị vệ sinh cao cấp. Chiết khấu cao cho nhà thầu và công trình.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                                    <a href="#sec-gach-lat-nen" class="bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg transition shadow">
                                        Xem mẫu gạch mới
                                    </a>
                                    <a href="#bao-gia" class="bg-white/15 hover:bg-white/25 backdrop-blur text-white border border-white/30 text-xs sm:text-sm font-semibold px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg transition">
                                        Nhận báo giá ngay
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh sản phẩm thực tế nằm gọn bên trong banner trên máy tính -->
                            <div class="hidden lg:grid grid-cols-2 gap-3 w-72 shrink-0 p-3 bg-white/10 backdrop-blur-md rounded-xl border border-white/20">
                                <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w400" alt="Gạch ốp lát Tân Thanh Lộc" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w400" alt="Gạch lát nền cao cấp" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w400" alt="Gạch nhập khẩu" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=1X31hmhpLVVORV-tmMSZYzBO-qtpyusry&sz=w400" alt="Thiết bị vệ sinh" class="w-full h-28 object-cover rounded-lg">
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 (Kích thước bằng nhau 100%) -->
                    <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                        <img
                            src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w1400"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w1400';"
                            alt="Không gian Gạch Ốp Lát & Thiết Bị Vệ Sinh Tân Thanh Lộc"
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-slate-900/80 to-slate-900/50"></div>

                        <!-- Nội dung chữ & hình ảnh phụ nằm hoàn toàn bên trong, cách xa viền ảnh banner -->
                        <div class="absolute inset-0 flex items-center justify-between px-7 sm:px-12 md:px-16 lg:px-24 py-6 sm:py-10">
                            <div class="max-w-xl text-white space-y-2 sm:space-y-3.5">
                                <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-amber-300">
                                    SHOWROOM: 417-419 Đ. 29 THÁNG 3, HÒA XUÂN, ĐÀ NẴNG
                                </p>
                                <h2 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                    KIẾN TẠO KHÔNG GIAN SỐNG ĐẲNG CẤP & BỀN VỮNG
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed">
                                    Đa dạng kích thước 30x60, 60x60, 80x80, 60x120, 100x100 và combo phòng tắm hiện đại. Giao hàng tận chân công trình nhanh chóng, uy tín.
                                </p>
                                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                                    <a href="#sec-thiet-bi-ve-sinh" class="bg-amber-500 hover:bg-amber-600 text-slate-950 text-xs sm:text-sm font-bold px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg transition shadow">
                                        Combo Thiết Bị Vệ Sinh
                                    </a>
                                    <a href="#bando-showroom" class="bg-white/15 hover:bg-white/25 backdrop-blur text-white border border-white/30 text-xs sm:text-sm font-semibold px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg transition">
                                        Xem bản đồ Showroom
                                    </a>
                                </div>
                            </div>

                            <!-- Khung ảnh sản phẩm thực tế nằm gọn bên trong banner trên máy tính -->
                            <div class="hidden lg:grid grid-cols-2 gap-3 w-72 shrink-0 p-3 bg-white/10 backdrop-blur-md rounded-xl border border-white/20">
                                <img src="https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w400" alt="Gạch vân đá" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w400" alt="Gạch khổ lớn" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54&sz=w400" alt="Gạch giả gỗ" class="w-full h-28 object-cover rounded-lg">
                                <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w400" alt="Gạch trang trí" class="w-full h-28 object-cover rounded-lg">
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng trái / phải nằm gọn bên trong banner -->
                    <button id="prev-slide" type="button" aria-label="Slide trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button id="next-slide" type="button" aria-label="Slide tiếp" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Chấm chỉ báo slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button type="button" data-slide="0" class="slide-dot w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                        <button type="button" data-slide="1" class="slide-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- 2. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ DANH MỤC NHỎ GỌN, TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI) -->
        <section class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            <i class="fa-solid fa-layer-group"></i> DANH MỤC SẢN PHẨM
                        </h2>
                        <span class="text-xs text-slate-500">Chọn nhanh danh mục theo mẫu Quang Hưng Ceramic</span>
                    </div>
                </div>

                <!-- Grid Danh Mục: 2 cột trên màn hình nhỏ, 4 cột trên tablet, 8 cột trên máy tính, chữ nhỏ gọn trên 1 dòng -->
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                    <a href="#sec-gach-lat-nen" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w400" alt="Gạch lát nền" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch lát nền</span>
                    </a>

                    <a href="#sec-gach-op-tuong" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w400" alt="Gạch ốp tường" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch ốp tường</span>
                    </a>

                    <a href="#sec-gach-gia-go" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w400" alt="Gạch giả gỗ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch giả gỗ</span>
                    </a>

                    <a href="#sec-gach-gia-go" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP&sz=w400" alt="Gạch lát sân vườn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch lát sân vườn</span>
                    </a>

                    <a href="#sec-gach-op-tuong" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w400" alt="Gạch nhập khẩu" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch nhập khẩu</span>
                    </a>

                    <a href="#sec-gach-gia-go" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-&sz=w400" alt="Gạch trang trí" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Gạch trang trí</span>
                    </a>

                    <a href="#sec-thiet-bi-ve-sinh" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w400" alt="Thiết bị vệ sinh" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Thiết bị vệ sinh</span>
                    </a>

                    <a href="#sec-thiet-bi-ve-sinh" class="group bg-white border border-slate-200 hover:border-brand rounded-lg p-2.5 text-center transition shadow-sm flex flex-col items-center">
                        <div class="w-full h-20 sm:h-24 rounded overflow-hidden mb-2 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w400" alt="Sản phẩm khác" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <span class="text-xs font-bold text-slate-800 group-hover:text-brand whitespace-nowrap">Sản phẩm khác</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- 3. DANH MỤC 1: GẠCH LÁT NỀN (5 ẢNH THỰC TẾ, 2 CỘT TRÊN ĐIỆN THOẠI, % GIẢM GIÁ GÓC TRÊN BÊN TRÁI) -->
        <section id="sec-gach-lat-nen" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            GẠCH LÁT NỀN CAO CẤP
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5 text-xs">
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 60x60</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 80x80</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 100x100</span>
                            <a href="#bao-gia" class="text-brand font-bold ml-1 whitespace-nowrap hover:underline">Xem báo giá <i class="fa-solid fa-angle-right"></i></a>
                        </div>
                    </div>
                </div>

                <!-- Grid sản phẩm: 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính -->
                <div id="grid-lat-nen" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
            </div>
        </section>

        <!-- 4. DANH MỤC 2: GẠCH ỐP TƯỜNG & GẠCH NHẬP KHẨU KHỔ LỚN (5 ẢNH THỰC TẾ) -->
        <section id="sec-gach-op-tuong" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            GẠCH ỐP TƯỜNG & GẠCH NHẬP KHẨU
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5 text-xs">
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 30x60</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 60x120</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Kích thước 90x180</span>
                            <a href="#bao-gia" class="text-brand font-bold ml-1 whitespace-nowrap hover:underline">Xem báo giá <i class="fa-solid fa-angle-right"></i></a>
                        </div>
                    </div>
                </div>

                <div id="grid-op-tuong" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
            </div>
        </section>

        <!-- 5. DANH MỤC 3: GẠCH GIẢ GỖ, GẠCH LÁT SÂN VƯỜN & GẠCH TRANG TRÍ (4 ẢNH THỰC TẾ) -->
        <section id="sec-gach-gia-go" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            GẠCH GIẢ GỖ • SÂN VƯỜN • TRANG TRÍ
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5 text-xs">
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Gạch vân gỗ 15x90</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Gạch sân vườn chống trơn</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Gạch trang trí</span>
                        </div>
                    </div>
                </div>

                <div id="grid-gia-go" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
            </div>
        </section>

        <!-- 6. DANH MỤC 4: THIẾT BỊ VỆ SINH & SẢN PHẨM KHÁC (5 ẢNH THỰC TẾ) -->
        <section id="sec-thiet-bi-ve-sinh" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            THIẾT BỊ VỆ SINH & PHÒNG TẮM TRỌN GÓI
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5 text-xs">
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Bồn cầu 1 khối</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Tủ chậu Lavabo</span>
                            <span class="px-2 py-1 bg-slate-200/80 rounded text-slate-700 whitespace-nowrap">Sen cây tắm nóng lạnh</span>
                        </div>
                    </div>
                </div>

                <div id="grid-tbvs" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
            </div>
        </section>

        <!-- 7. GIỚI THIỆU CỬA HÀNG TÂN THANH LỘC (LẤY ẢNH CỬA HÀNG THỰC TẾ TRONG FILE GOOGLE DRIVE) -->
        <section id="ve-chung-toi" class="w-full">
            <div class="flatsome-container">
                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <!-- Ảnh cửa hàng thực tế -->
                        <div class="lg:col-span-6">
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx&sz=w1200"
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx=w1200';"
                                    alt="Showroom Cửa Hàng Công Ty TNHH Tân Thanh Lộc - 417-419 Đường 29 Tháng 3, Hòa Xuân, Đà Nẵng"
                                    class="w-full h-64 sm:h-80 md:h-96 object-cover"
                                >
                            </div>
                        </div>

                        <!-- Nội dung giới thiệu Công ty TNHH Tân Thanh Lộc -->
                        <div class="lg:col-span-6 space-y-3.5">
                            <span class="text-xs font-bold uppercase tracking-wider text-brand">HỒ SƠ NĂNG LỰC & SHOWROOM TRƯNG BÀY</span>
                            <h2 class="text-lg sm:text-2xl font-extrabold text-slate-900 leading-snug">
                                CÔNG TY TNHH TÂN THANH LỘC - UY TÍN TẠO NÊN THƯƠNG HIỆU
                            </h2>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                Tọa lạc tại <strong>417-419 Đường 29 Tháng 3, Phường Hòa Xuân, TP. Đà Nẵng</strong>, <strong>CÔNG TY TNHH TÂN THANH LỘC</strong> tự hào là nhà phân phối uy tín hàng đầu chuyên cung cấp các dòng gạch ốp lát Porcelain, Granite, Ceramic, gạch khổ lớn nhập khẩu và thiết bị vệ sinh chính hãng cho hàng ngàn công trình nhà phố, biệt thự, khách sạn và dự án tại Đà Nẵng – Miền Trung.
                            </p>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs sm:text-sm">
                                <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-slate-50 border border-slate-100">
                                    <i class="fa-solid fa-circle-check text-brand mt-0.5"></i>
                                    <div>
                                        <strong class="block text-slate-800">Hàng chính hãng loại 1 (A1)</strong>
                                        <span class="text-xs text-slate-500">Đầy đủ chứng chỉ chất lượng, xuất xứ rõ ràng.</span>
                                    </div>
                                </div>
                                <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-slate-50 border border-slate-100">
                                    <i class="fa-solid fa-truck-fast text-brand mt-0.5"></i>
                                    <div>
                                        <strong class="block text-slate-800">Giao hàng tận công trình</strong>
                                        <span class="text-xs text-slate-500">Vận chuyển nhanh chóng tại Đà Nẵng & các tỉnh.</span>
                                    </div>
                                </div>
                                <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-slate-50 border border-slate-100">
                                    <i class="fa-solid fa-percent text-brand mt-0.5"></i>
                                    <div>
                                        <strong class="block text-slate-800">Chiết khấu sỉ & lẻ tốt nhất</strong>
                                        <span class="text-xs text-slate-500">Chính sách giá ưu đãi đặc biệt cho thầu thợ, chủ nhà.</span>
                                    </div>
                                </div>
                                <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-slate-50 border border-slate-100">
                                    <i class="fa-solid fa-rotate text-brand mt-0.5"></i>
                                    <div>
                                        <strong class="block text-slate-800">Hỗ trợ đổi trả linh hoạt</strong>
                                        <span class="text-xs text-slate-500">Thoải mái kiểm tra hàng trước khi thanh toán.</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ + FANPAGE NGOÀI TRANG CHỦ -->
        <section id="bao-gia" class="w-full">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">

                    <!-- Cột trái (7 cột): Form Yêu Cầu & Báo Giá Trang Chủ -->
                    <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm">
                        <div class="section-title-container">
                            <div class="section-title-normal">
                                <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                                    <i class="fa-solid fa-file-signature"></i> ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ
                                </h2>
                            </div>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 mb-4">
                            Quý khách hàng, đối tác, nhà thầu cần nhận bảng báo giá gạch ốp lát & thiết bị vệ sinh chiết khấu tốt nhất từ <strong>CÔNG TY TNHH TÂN THANH LỘC</strong>, vui lòng để lại thông tin bên dưới:
                        </p>

                        <form id="quote-request-form" class="space-y-3.5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                                    <input type="text" id="q-name" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="q-phone" required placeholder="Nhập số điện thoại nhận báo giá" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục cần báo giá *</label>
                                    <select id="q-category" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand bg-white">
                                        <option value="Trọn gói Gạch ốp lát & Thiết bị vệ sinh">Trọn gói Gạch ốp lát & Thiết bị vệ sinh</option>
                                        <option value="Gạch lát nền (60x60, 80x80, 100x100)">Gạch lát nền (60x60, 80x80, 100x100)</option>
                                        <option value="Gạch ốp tường & Gạch nhập khẩu">Gạch ốp tường & Gạch nhập khẩu</option>
                                        <option value="Gạch giả gỗ & Gạch lát sân vườn">Gạch giả gỗ & Gạch lát sân vườn</option>
                                        <option value="Thiết bị vệ sinh phòng tắm">Thiết bị vệ sinh phòng tắm</option>
                                        <option value="Báo giá đại lý / Nhà thầu xây dựng">Báo giá đại lý / Nhà thầu xây dựng</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình</label>
                                    <input type="text" id="q-address" placeholder="VD: Hòa Xuân, Cẩm Lệ, Đà Nẵng" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu (Mã sản phẩm, diện tích m², số lượng...)</label>
                                <textarea id="q-note" rows="3" placeholder="Nhập mã sản phẩm bạn đang quan tâm hoặc diện tích cần tư vấn..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="bg-brand hover:bg-brand-dark text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded-lg shadow transition">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                                </button>
                                <div class="text-xs text-slate-500">
                                    Hotline tư vấn trực tiếp: <strong class="text-brand">0914.704.046 - 0932.564.550</strong>
                                </div>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quote-success-msg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>

                    <!-- Cột phải (5 cột): Đưa Fanpage Facebook ra ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="section-title-container">
                                <div class="section-title-normal">
                                    <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                                        <i class="fa-brands fa-facebook text-blue-600"></i> FANPAGE TÂN THANH LỘC CERAMIC
                                    </h2>
                                </div>
                            </div>

                            <!-- Thẻ Fanpage trực quan kết hợp khung nhúng Facebook Plugin -->
                            <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 mb-3">
                                <div class="relative h-28 bg-slate-900">
                                    <img src="https://drive.google.com/thumbnail?id=1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx&sz=w800" alt="Fanpage Tân Thanh Lộc Ceramic" class="w-full h-full object-cover opacity-75">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <img src="https://drive.google.com/thumbnail?id=1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds&sz=w200" alt="Logo Tân Thanh Lộc" class="w-12 h-12 rounded-lg bg-white p-1 object-contain shadow">
                                        <div class="text-white min-w-0">
                                            <a href="https://www.facebook.com/tanthanhlocceramic?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="font-bold text-sm hover:underline block truncate">
                                                Tân Thanh Lộc Ceramic
                                            </a>
                                            <span class="text-[11px] text-slate-200 block">Gạch Ốp Lát & Thiết Bị Vệ Sinh Đà Nẵng</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3 space-y-2 text-xs">
                                    <p class="text-slate-600">
                                        Cập nhật mẫu gạch ốp lát mới về kho mỗi ngày, hình ảnh bàn giao thực tế tại công trình và các chương trình khuyến mãi tại Fanpage chính thức.
                                    </p>
                                    <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                                        <iframe
                                            title="Facebook Fanpage Tân Thanh Lộc Ceramic"
                                            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Ftanthanhlocceramic&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                            width="340"
                                            height="180"
                                            style="border:none;overflow:hidden;max-width:100%;"
                                            scrolling="no"
                                            frameborder="0"
                                            allowfullscreen="true"
                                            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                        </iframe>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="flex flex-wrap items-center gap-2 pt-1">
                            <a href="https://www.facebook.com/tanthanhlocceramic?locale=vi_VN" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold py-2.5 px-3 rounded-lg transition">
                                <i class="fa-brands fa-facebook-f mr-1"></i> Truy cập Fanpage
                            </a>
                            <a href="https://zalo.me/0914704046" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-sky-500 hover:bg-sky-600 text-white text-xs font-bold py-2.5 px-3 rounded-lg transition">
                                <i class="fa-solid fa-comment-dots mr-1"></i> Chat Zalo Báo Giá
                            </a>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- 9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KIẾN THỨC XÂY DỰNG GIỐNG QUANG HƯNG CERAMIC) -->
        <section id="tin-tuc" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            <i class="fa-solid fa-newspaper"></i> DANH MỤC BÀI VIẾT & KIẾN THỨC XÂY DỰNG
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5 text-xs">
                            <button type="button" data-blog-cat="all" class="blog-tab-btn px-2.5 py-1 rounded bg-brand text-white font-semibold whitespace-nowrap">Tất cả bài viết</button>
                            <button type="button" data-blog-cat="kinh-nghiem" class="blog-tab-btn px-2.5 py-1 rounded bg-slate-200 text-slate-700 font-semibold whitespace-nowrap">Kinh nghiệm chọn gạch</button>
                            <button type="button" data-blog-cat="xu-huong" class="blog-tab-btn px-2.5 py-1 rounded bg-slate-200 text-slate-700 font-semibold whitespace-nowrap">Xu hướng nội thất</button>
                            <button type="button" data-blog-cat="du-an" class="blog-tab-btn px-2.5 py-1 rounded bg-slate-200 text-slate-700 font-semibold whitespace-nowrap">Bàn giao công trình</button>
                        </div>
                    </div>
                </div>

                <div id="blog-posts-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4"></div>
            </div>
        </section>

        <!-- 10. DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI -->
        <section id="doi-tac" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            <i class="fa-solid fa-handshake"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG
                        </h2>
                        <span class="text-xs text-slate-500">Hợp tác trực tiếp cùng các nhà máy gạch & thiết bị vệ sinh hàng đầu</span>
                    </div>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3">
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-brand tracking-wider">VIGLACERA</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát & Sứ vệ sinh</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-slate-800 tracking-wider">PRIME GROUP</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch men & Granite cao cấp</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-brand tracking-wider">ĐỒNG TÂM</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch Porcelain & Ngói màu</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-slate-800 tracking-wider">Á MỸ CERAMIC</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát xuất khẩu</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-brand tracking-wider">INAX / TOTO</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh Nhật Bản</div>
                    </div>
                    <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center hover:border-brand transition shadow-sm">
                        <div class="text-sm sm:text-base font-extrabold text-slate-800 tracking-wider">TAICERA & CMC</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Gạch đồng chất & Khổ lớn</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 11. ĐƯA GOOGLE MAP RA NGOÀI TRANG CHỦ (417-419 Đ. 29 THÁNG 3, HÒA XUÂN, ĐÀ NẴNG) -->
        <section id="bando-showroom" class="w-full">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                            <i class="fa-solid fa-map-location-dot"></i> BẢN ĐỒ ĐƯỜNG ĐI ĐẾN SHOWROOM TÂN THANH LỘC
                        </h2>
                        <a href="https://share.google/CTPcylLj5jgBh0JF0" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-brand hover:underline whitespace-nowrap">
                            <i class="fa-solid fa-up-right-from-square mr-1"></i> Mở trên ứng dụng Google Maps
                        </a>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                    <div class="grid grid-cols-1 lg:grid-cols-12">
                        <!-- Thông tin liên hệ trực tiếp -->
                        <div class="lg:col-span-4 p-4 sm:p-6 bg-slate-900 text-white flex flex-col justify-between space-y-4">
                            <div class="space-y-3">
                                <div class="inline-flex items-center gap-2 bg-brand px-3 py-1 rounded text-xs font-bold">
                                    SHOWROOM CHÍNH ĐÀ NẴNG
                                </div>
                                <h3 class="text-base sm:text-lg font-extrabold leading-snug">
                                    CÔNG TY TNHH TÂN THANH LỘC
                                </h3>
                                <div class="space-y-2.5 text-xs sm:text-sm text-slate-200 pt-1">
                                    <p class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
                                        <span><strong>Địa chỉ:</strong> 417-419 Đ. 29 Tháng 3, Hòa Xuân, Cẩm Lệ, Đà Nẵng</span>
                                    </p>
                                    <div class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-phone-volume text-amber-400 mt-1 shrink-0"></i>
                                        <div class="space-y-1">
                                            <strong class="block text-white">Hệ thống Hotline / Zalo:</strong>
                                            <a href="tel:0914704046" class="block hover:text-amber-300">• 0914.704.046</a>
                                            <a href="tel:0932564550" class="block hover:text-amber-300">• 0932.564.550</a>
                                            <a href="tel:0945575221" class="block hover:text-amber-300">• 0945.575.221</a>
                                            <a href="tel:0905278468" class="block hover:text-amber-300">• 0905.278.468</a>
                                        </div>
                                    </div>
                                    <p class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-globe text-amber-400 mt-1 shrink-0"></i>
                                        <span><strong>Website:</strong> tanthanhloc.com</span>
                                    </p>
                                    <p class="flex items-start gap-2.5">
                                        <i class="fa-solid fa-clock text-amber-400 mt-1 shrink-0"></i>
                                        <span><strong>Giờ mở cửa:</strong> 07:00 – 17:30 (Thứ 2 – Chủ Nhật)</span>
                                    </p>
                                </div>
                            </div>

                            <div class="pt-2 flex flex-col sm:flex-row lg:flex-col gap-2">
                                <a href="https://share.google/CTPcylLj5jgBh0JF0" target="_blank" rel="noopener noreferrer" class="w-full text-center bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm py-2.5 px-4 rounded-lg transition">
                                    <i class="fa-solid fa-diamond-turn-right mr-1.5"></i> Chỉ đường Google Maps
                                </a>
                            </div>
                        </div>

                        <!-- Bản đồ Google Map nhúng trực tiếp ngoài trang chủ -->
                        <div class="lg:col-span-8 h-72 sm:h-80 lg:h-auto min-h-[320px] bg-slate-100 relative">
                            <iframe
                                title="Bản đồ Công Ty TNHH Tân Thanh Lộc 417-419 Đường 29 Tháng 3 Hòa Xuân Đà Nẵng"
                                src="https://maps.google.com/maps?q=417-419%20%C4%90.%2029%20Th%C3%A1ng%203,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer id="lien-he" class="bg-slate-950 text-slate-300 pt-10 pb-6 border-t-4 border-brand w-full">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-slate-800">

                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <img
                            src="https://drive.google.com/thumbnail?id=1TG0WbzdO4rFFnScc6vddgZe3cYQDv5ds&sz=w300"
                            alt="Logo Tân Thanh Lộc"
                            class="h-11 w-auto bg-white p-1 rounded object-contain"
                        >
                        <div>
                            <h3 class="text-white font-extrabold text-sm sm:text-base">CÔNG TY TNHH TÂN THANH LỘC</h3>
                            <p class="text-xs text-amber-400 font-medium">Website: tanthanhloc.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-400 leading-relaxed">
                        Chuyên phân phối sỉ & lẻ Gạch ốp lát nội ngoại thất, Gạch lát nền, Gạch ốp tường, Gạch giả gỗ, Gạch sân vườn và Thiết bị vệ sinh trọn gói uy tín tại TP. Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-brand mr-2"></i><strong>Địa chỉ:</strong> 417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-brand mr-2"></i><strong>Điện thoại:</strong> 0914704046 - 0932564550 - 0945575221 - 0905278468</li>
                        <li><i class="fa-brands fa-facebook text-brand mr-2"></i><strong>Fanpage:</strong> fb.com/tanthanhlocceramic</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-white font-bold text-xs sm:text-sm uppercase tracking-wider border-b border-slate-800 pb-2">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#sec-gach-lat-nen" class="hover:text-amber-400 transition">• Gạch lát nền (60x60, 80x80, 100x100)</a></li>
                        <li><a href="#sec-gach-op-tuong" class="hover:text-amber-400 transition">• Gạch ốp tường (30x60, 40x80)</a></li>
                        <li><a href="#sec-gach-gia-go" class="hover:text-amber-400 transition">• Gạch giả gỗ cao cấp</a></li>
                        <li><a href="#sec-gach-gia-go" class="hover:text-amber-400 transition">• Gạch lát sân vườn chống trơn</a></li>
                        <li><a href="#sec-gach-op-tuong" class="hover:text-amber-400 transition">• Gạch nhập khẩu khổ lớn</a></li>
                        <li><a href="#sec-thiet-bi-ve-sinh" class="hover:text-amber-400 transition">• Thiết bị vệ sinh trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="text-white font-bold text-xs sm:text-sm uppercase tracking-wider border-b border-slate-800 pb-2">
                        CHÍNH SÁCH & ĐIỀU KHOẢN
                    </h4>
                    <ul class="space-y-1.5 text-xs">
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition">• Chính sách báo giá & chiết khấu công trình</a></li>
                        <li><a href="#ve-chung-toi" class="hover:text-amber-400 transition">• Chính sách vận chuyển & giao nhận tận nơi</a></li>
                        <li><a href="#ve-chung-toi" class="hover:text-amber-400 transition">• Chính sách bảo hành chính hãng</a></li>
                        <li><a href="#ve-chung-toi" class="hover:text-amber-400 transition">• Chính sách đổi trả hàng linh hoạt</a></li>
                        <li><a href="https://share.google/CTPcylLj5jgBh0JF0" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 transition">• Xem vị trí Showroom trên Google Maps</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-500">
                <p>© Bản quyền thuộc về <strong class="text-slate-300">CÔNG TY TNHH TÂN THANH LỘC (tanthanhloc.com)</strong>.</p>
                <p>417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng</p>
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a
            href="https://www.facebook.com/tanthanhlocceramic?locale=vi_VN"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Facebook Fanpage Tân Thanh Lộc"
            class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        >
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center font-bold text-sm shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a
            href="https://zalo.me/0914704046"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Chat Zalo Tân Thanh Lộc"
            class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:scale-105"
        >
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 flex items-center justify-center font-extrabold text-[11px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Hotline (Bấm mở danh sách 4 số điện thoại hoặc gọi ngay) -->
        <button
            id="floating-hotline-btn"
            type="button"
            aria-label="Gọi Hotline Tân Thanh Lộc"
            class="floating-pulse flex items-center gap-2 bg-brand hover:bg-brand-dark text-white pl-3 pr-4 py-2.5 rounded-full shadow-xl transition"
        >
            <span class="w-7 h-7 rounded-full bg-white text-brand flex items-center justify-center text-sm shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold whitespace-nowrap">0914.704.046</span>
        </button>
    </div>

    <!-- ==================== MODAL CHỌN SỐ HOTLINE / CHI TIẾT SẢN PHẨM / BÀI VIẾT ==================== -->
    <div id="app-modal" class="fixed inset-0 bg-slate-950/70 backdrop-blur-xs z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 py-3 bg-brand text-white">
                <h3 id="modal-title" class="font-bold text-sm sm:text-base">Thông tin chi tiết</h3>
                <button id="close-modal-btn" type="button" class="w-7 h-7 rounded-full bg-white/20 hover:bg-white/30 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modal-body" class="p-4 sm:p-5 text-xs sm:text-sm text-slate-700 max-h-[80vh] overflow-y-auto"></div>
        </div>
    </div>

    <!-- ==================== JAVASCRIPT QUẢN LÝ DỮ LIỆU 19 ẢNH SẢN PHẨM THỰC TẾ, SLIDER & TƯƠNG TÁC ==================== -->
    <script>
        // Hàm tạo link ảnh Google Drive có cơ chế dự phòng tự động
        function driveImg(fileId) {
            return `https://drive.google.com/thumbnail?id=${fileId}&sz=w800`;
        }
        function driveBackup(fileId) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w800`;
        }

        // Toàn bộ 19 ảnh sản phẩm thực tế từ Google Drive được phân vào đúng 4 nhóm danh mục chuẩn Quang Hưng Ceramic
        const productsData = [
            // --- NHÓM 1: GẠCH LÁT NỀN CAO CẤP (5 sản phẩm) ---
            {
                id: 'TTL-LN01',
                section: 'grid-lat-nen',
                category: 'Gạch lát nền',
                name: 'Gạch lát nền Porcelain vân đá Marble 80x80 TTL-8801 Men Bóng Kiếng',
                fileId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                oldPrice: '310.000₫/m²',
                price: '248.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-LN02',
                section: 'grid-lat-nen',
                category: 'Gạch lát nền',
                name: 'Gạch lát nền Granite vân mây xám khói 80x80 TTL-8802 Chống Trầy Xước',
                fileId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
                oldPrice: '295.000₫/m²',
                price: '239.000₫/m²',
                discount: '-19%'
            },
            {
                id: 'TTL-LN03',
                section: 'grid-lat-nen',
                category: 'Gạch lát nền',
                name: 'Gạch lát nền bóng kiếng toàn phần 60x60 TTL-6603 Vân Đá Tự Nhiên',
                fileId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
                oldPrice: '235.000₫/m²',
                price: '188.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-LN04',
                section: 'grid-lat-nen',
                category: 'Gạch lát nền',
                name: 'Gạch lát nền khổ lớn 100x100 TTL-1010 Vân Đá Hoàng Gia Cao Cấp',
                fileId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
                oldPrice: '450.000₫/m²',
                price: '369.000₫/m²',
                discount: '-18%'
            },
            {
                id: 'TTL-LN05',
                section: 'grid-lat-nen',
                category: 'Gạch lát nền',
                name: 'Gạch lát nền phòng khách 80x80 TTL-8805 Men Matt Mịn Hiện Đại',
                fileId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
                oldPrice: '320.000₫/m²',
                price: '256.000₫/m²',
                discount: '-20%'
            },

            // --- NHÓM 2: GẠCH ỐP TƯỜNG & GẠCH NHẬP KHẨU (5 sản phẩm) ---
            {
                id: 'TTL-OT01',
                section: 'grid-op-tuong',
                category: 'Gạch ốp tường',
                name: 'Gạch ốp tường 30x60 TTL-3601 Vân Đá Sáng Bóng Dễ Vệ Sinh',
                fileId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                oldPrice: '215.000₫/m²',
                price: '168.000₫/m²',
                discount: '-22%'
            },
            {
                id: 'TTL-OT02',
                section: 'grid-op-tuong',
                category: 'Gạch nhập khẩu',
                name: 'Gạch ốp lát nhập khẩu khổ lớn 60x120 TTL-6120 Vân Đá Liên Mạch',
                fileId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                oldPrice: '420.000₫/m²',
                price: '336.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-OT03',
                section: 'grid-op-tuong',
                category: 'Gạch ốp tường',
                name: 'Bộ gạch ốp tường phòng tắm & phòng bếp 30x60 TTL-3608 Cao Cấp',
                fileId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
                oldPrice: '225.000₫/m²',
                price: '179.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-OT04',
                section: 'grid-op-tuong',
                category: 'Gạch nhập khẩu',
                name: 'Gạch nhập khẩu 90x180 TTL-9180 Vân Đá Cẩm Thạch Sang Trọng',
                fileId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
                oldPrice: '650.000₫/m²',
                price: '520.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-OT05',
                section: 'grid-op-tuong',
                category: 'Gạch ốp tường',
                name: 'Gạch ốp tường ngoại thất & mặt tiền 40x80 TTL-4802 Chống Thấm',
                fileId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
                oldPrice: '280.000₫/m²',
                price: '224.000₫/m²',
                discount: '-20%'
            },

            // --- NHÓM 3: GẠCH GIẢ GỖ, SÂN VƯỜN & TRANG TRÍ (4 sản phẩm) ---
            {
                id: 'TTL-GG01',
                section: 'grid-gia-go',
                category: 'Gạch giả gỗ',
                name: 'Gạch thanh giả gỗ tự nhiên 15x90 TTL-G1590 Chống Ẩm Mốc & Mối Mọt',
                fileId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                oldPrice: '265.000₫/m²',
                price: '212.000₫/m²',
                discount: '-20%'
            },
            {
                id: 'TTL-GG02',
                section: 'grid-gia-go',
                category: 'Gạch giả gỗ',
                name: 'Sàn gạch vân gỗ sồi Bắc Âu 20x120 TTL-G2012 Bề Mặt Matt Chống Trơn',
                fileId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                oldPrice: '310.000₫/m²',
                price: '245.000₫/m²',
                discount: '-21%'
            },
            {
                id: 'TTL-SV01',
                section: 'grid-gia-go',
                category: 'Gạch lát sân vườn',
                name: 'Gạch lát sân vườn định hình chống trơn 50x50 TTL-SV505 Độ Bền Cao',
                fileId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                oldPrice: '195.000₫/m²',
                price: '155.000₫/m²',
                discount: '-21%'
            },
            {
                id: 'TTL-TT01',
                section: 'grid-gia-go',
                category: 'Gạch trang trí',
                name: 'Gạch bông & gạch thẻ trang trí điểm nhấn kiến trúc TTL-TT202',
                fileId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                oldPrice: '290.000₫/m²',
                price: '229.000₫/m²',
                discount: '-21%'
            },

            // --- NHÓM 4: THIẾT BỊ VỆ SINH & PHÒNG TẮM TRỌN GÓI (5 sản phẩm) ---
            {
                id: 'TTL-VS01',
                section: 'grid-tbvs',
                category: 'Thiết bị vệ sinh',
                name: 'Bồn cầu 1 khối men Nano kháng khuẩn xả xoáy siêu êm TTL-BC01',
                fileId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                oldPrice: '4.850.000₫',
                price: '3.650.000₫',
                discount: '-25%'
            },
            {
                id: 'TTL-VS02',
                section: 'grid-tbvs',
                category: 'Thiết bị vệ sinh',
                name: 'Bộ tủ chậu rửa mặt Lavabo kèm gương LED cảm ứng hiện đại TTL-LV02',
                fileId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                oldPrice: '5.400.000₫',
                price: '4.150.000₫',
                discount: '-23%'
            },
            {
                id: 'TTL-VS03',
                section: 'grid-tbvs',
                category: 'Thiết bị vệ sinh',
                name: 'Sen cây tắm đứng nóng lạnh Inox 304 mạ PVD cao cấp TTL-SC03',
                fileId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                oldPrice: '3.200.000₫',
                price: '2.450.000₫',
                discount: '-23%'
            },
            {
                id: 'TTL-VS04',
                section: 'grid-tbvs',
                category: 'Thiết bị vệ sinh',
                name: 'Chậu rửa mặt Lavabo đặt bàn sứ trắng men tuyết chống bám bẩn TTL-LV04',
                fileId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                oldPrice: '1.650.000₫',
                price: '1.250.000₫',
                discount: '-24%'
            },
            {
                id: 'TTL-VS05',
                section: 'grid-tbvs',
                category: 'Sản phẩm khác',
                name: 'Combo trọn bộ thiết bị phòng tắm & phụ kiện cao cấp Tân Thanh Lộc TTL-CB05',
                fileId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                oldPrice: '11.500.000₫',
                price: '8.850.000₫',
                discount: '-23%'
            }
        ];

        // Dữ liệu các bài viết trang chủ
        const blogPosts = [
            {
                id: 1,
                cat: 'kinh-nghiem',
                day: '12',
                month: 'Th11',
                title: 'Kinh nghiệm chọn gạch lát nền 80x80 và 60x120 cho nhà phố hiện đại tại Đà Nẵng',
                image: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                excerpt: 'Hướng dẫn cách phối màu gạch lát nền men bóng và men Matt giúp không gian phòng khách rộng rãi, sang trọng và bền đẹp theo thời gian.',
                content: 'Khi lựa chọn gạch lát nền cho nhà phố hoặc biệt thự tại Đà Nẵng, các khổ gạch 80x80 và 60x120 xương đá Porcelain đang là xu hướng hàng đầu nhờ đường ron ít, độ hút nước dưới 0.5% và khả năng chịu lực vượt trội. Tại Showroom Công ty TNHH Tân Thanh Lộc (417-419 Đ. 29 Tháng 3, Hòa Xuân), quý khách có thể trực tiếp trải nghiệm hàng trăm mẫu vân đá tự nhiên mới nhất.'
            },
            {
                id: 2,
                cat: 'xu-huong',
                day: '08',
                month: 'Th11',
                title: 'Vì sao gạch giả gỗ chống trơn được ưa chuộng cho phòng ngủ và sân thượng?',
                image: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                excerpt: 'Gạch vân gỗ khắc phục hoàn toàn nhược điểm cong vênh, mối mọt của sàn gỗ tự nhiên trong điều kiện khí hậu nhiệt đới ẩm tại miền Trung.',
                content: 'Gạch giả gỗ kích thước 15x80, 15x90 và 20x120 mang lại vẻ đẹp ấm cúng như gỗ thật nhưng có độ bền vĩnh cửu, chống thấm nước 100% và dễ dàng lau chùi.'
            },
            {
                id: 3,
                cat: 'du-an',
                day: '03',
                month: 'Th11',
                title: 'Tân Thanh Lộc Ceramic bàn giao trọn gói gạch ốp lát & TBVS biệt thự Hòa Xuân',
                image: '1Sj5iJqJsqzhzCBiDStKdrLeQyUPpX7Cx',
                excerpt: 'Hình ảnh thực tế cung cấp gạch khổ lớn và thiết bị vệ sinh phòng tắm cao cấp cho các công trình dân dụng và khách sạn tại Hòa Xuân, Cẩm Lệ.',
                content: 'Cảm ơn quý khách hàng và các nhà thầu tại khu đô thị sinh thái Hòa Xuân đã luôn tin tưởng lựa chọn Công ty TNHH Tân Thanh Lộc làm đơn vị cung ứng vật liệu hoàn thiện trọn gói.'
            },
            {
                id: 4,
                cat: 'kinh-nghiem',
                day: '27',
                month: 'Th10',
                title: 'Bí quyết chọn trọn bộ thiết bị vệ sinh phòng tắm tiết kiệm chi phí mà vẫn đẳng cấp',
                image: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                excerpt: 'Gợi ý cách chọn bồn cầu 1 khối, tủ chậu Lavabo và sen cây tắm nóng lạnh đồng bộ giúp tối ưu diện tích phòng tắm gia đình.',
                content: 'Việc mua theo gói Combo thiết bị vệ sinh tại Tân Thanh Lộc Ceramic giúp gia chủ tiết kiệm từ 20% - 25% chi phí so với mua lẻ từng món, đồng thời đảm bảo tính thẩm mỹ đồng bộ cho phòng tắm.'
            }
        ];

        // Hàm tạo thẻ HTML sản phẩm chuẩn Flatsome (Góc trên bên trái có % giảm giá, tên sản phẩm đầy đủ không cắt chữ, không nhãn dán thừa)
        function createProductCardHTML(p) {
            return `
                <div class="product-small box">
                    <div class="relative w-full aspect-square bg-slate-100 overflow-hidden">
                        <span class="flatsome-discount-badge">${p.discount}</span>
                        <img
                            src="${driveImg(p.fileId)}"
                            onerror="this.onerror=null;this.src='${driveBackup(p.fileId)}';"
                            alt="${p.name}"
                            loading="lazy"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300 cursor-pointer"
                            onclick="openProductModal('${p.id}')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-semibold text-slate-800 hover:text-brand cursor-pointer" onclick="openProductModal('${p.id}')">
                                ${p.name}
                            </h3>
                        </div>
                        <div class="pt-2 mt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <del class="text-[11px] sm:text-xs text-slate-400">${p.oldPrice}</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-brand no-underline">${p.price}</ins>
                            </div>
                            <button
                                type="button"
                                onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}')"
                                class="mt-2 w-full py-1.5 px-2 rounded bg-slate-100 hover:bg-brand hover:text-white text-slate-700 font-semibold text-[11px] sm:text-xs transition"
                            >
                                Nhận báo giá
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        // Render toàn bộ sản phẩm vào 4 section trên trang chủ
        function renderAllProducts(filterKeyword = '') {
            const sections = ['grid-lat-nen', 'grid-op-tuong', 'grid-gia-go', 'grid-tbvs'];
            const kw = filterKeyword.trim().toLowerCase();

            sections.forEach(secId => {
                const container = document.getElementById(secId);
                if (!container) return;
                const list = productsData.filter(item => {
                    const matchSec = item.section === secId;
                    const matchKw = !kw || item.name.toLowerCase().includes(kw) || item.category.toLowerCase().includes(kw);
                    return matchSec && matchKw;
                });

                if (list.length === 0) {
                    container.innerHTML = `<div class="col-span-full text-xs text-slate-500 py-4">Không tìm thấy sản phẩm khớp từ khóa trong mục này.</div>`;
                } else {
                    container.innerHTML = list.map(createProductCardHTML).join('');
                }
            });
        }

        // Render danh sách bài viết trang chủ
        function renderBlogs(category = 'all') {
            const grid = document.getElementById('blog-posts-grid');
            if (!grid) return;
            const filtered = category === 'all' ? blogPosts : blogPosts.filter(b => b.cat === category);

            grid.innerHTML = filtered.map(post => `
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-44 bg-slate-100 overflow-hidden">
                            <img
                                src="${driveImg(post.image)}"
                                onerror="this.onerror=null;this.src='${driveBackup(post.image)}';"
                                alt="${post.title}"
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                            <div class="absolute top-2.5 left-2.5 bg-white/95 text-brand border border-brand/20 rounded px-2 py-1 text-center leading-tight shadow">
                                <span class="block text-xs font-extrabold">${post.day}</span>
                                <span class="block text-[10px] font-semibold uppercase">${post.month}</span>
                            </div>
                        </div>
                        <div class="p-3.5">
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-slate-900 hover:text-brand cursor-pointer mb-1.5" onclick="openBlogModal(${post.id})">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button type="button" onclick="openBlogModal(${post.id})" class="text-xs font-bold text-brand hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        // Mở Modal xem chi tiết sản phẩm
        function openProductModal(productId) {
            const p = productsData.find(item => item.id === productId);
            if (!p) return;
            const modal = document.getElementById('app-modal');
            document.getElementById('modal-title').textContent = p.category + ' - ' + p.id;
            document.getElementById('modal-body').innerHTML = `
                <div class="space-y-3">
                    <div class="relative rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                        <span class="flatsome-discount-badge">${p.discount}</span>
                        <img src="${driveImg(p.fileId)}" onerror="this.onerror=null;this.src='${driveBackup(p.fileId)}';" alt="${p.name}" class="w-full max-h-72 object-cover">
                    </div>
                    <h4 class="font-bold text-sm sm:text-base text-slate-900">${p.name}</h4>
                    <div class="flex items-center gap-3">
                        <del class="text-xs text-slate-400">${p.oldPrice}</del>
                        <span class="text-base font-extrabold text-brand">${p.price}</span>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Sản phẩm được trưng bày trực tiếp tại Showroom <strong>CÔNG TY TNHH TÂN THANH LỘC</strong>: 417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng. Cam kết hàng chính hãng loại 1, chiết khấu cao cho công trình.
                    </p>
                    <div class="pt-2 flex flex-wrap gap-2">
                        <button type="button" onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}'); closeModal();" class="flex-1 bg-brand hover:bg-brand-dark text-white font-bold text-xs py-2.5 px-4 rounded-lg">
                            Đăng ký nhận báo giá mẫu này
                        </button>
                        <a href="tel:0914704046" class="flex-1 text-center bg-slate-800 hover:bg-slate-900 text-white font-bold text-xs py-2.5 px-4 rounded-lg">
                            Gọi 0914.704.046
                        </a>
                    </div>
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        // Mở Modal đọc bài viết
        function openBlogModal(blogId) {
            const post = blogPosts.find(item => item.id === blogId);
            if (!post) return;
            const modal = document.getElementById('app-modal');
            document.getElementById('modal-title').textContent = 'Tin tức & Kiến thức xây dựng';
            document.getElementById('modal-body').innerHTML = `
                <div class="space-y-3">
                    <img src="${driveImg(post.image)}" onerror="this.onerror=null;this.src='${driveBackup(post.image)}';" alt="${post.title}" class="w-full h-56 object-cover rounded-lg">
                    <h4 class="font-bold text-sm sm:text-base text-slate-900">${post.title}</h4>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${post.content}</p>
                    <div class="p-3 rounded-lg bg-slate-100 text-xs text-slate-700">
                        <strong>CÔNG TY TNHH TÂN THANH LỘC</strong><br>
                        Địa chỉ: 417-419 Đ. 29 Tháng 3, Hòa Xuân, Đà Nẵng<br>
                        Hotline: 0914704046 - 0932564550 - 0945575221 - 0905278468
                    </div>
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('app-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Điền nhanh sản phẩm vào Form Báo Giá
        function selectProductForQuote(productName) {
            const noteEl = document.getElementById('q-note');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn & báo giá mẫu: ${productName}`;
            }
            const formSec = document.getElementById('bao-gia');
            if (formSec) {
                formSec.scrollIntoView({ behavior: 'smooth' });
            }
        }

        window.onload = function () {
            renderAllProducts();
            renderBlogs('all');

            // 1. Điều khiển Slider 2 Banner tự trượt chuyên nghiệp
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.slide-dot');
            let currentSlide = 0;

            function showSlide(index) {
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach((sl, idx) => {
                    if (idx === currentSlide) {
                        sl.classList.remove('opacity-0', 'z-0');
                        sl.classList.add('opacity-100', 'z-10');
                    } else {
                        sl.classList.remove('opacity-100', 'z-10');
                        sl.classList.add('opacity-0', 'z-0');
                    }
                });
                dots.forEach((dot, idx) => {
                    if (idx === currentSlide) {
                        dot.className = 'slide-dot w-6 h-2 rounded-full bg-amber-400 transition-all';
                    } else {
                        dot.className = 'slide-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                    }
                });
            }

            let slideTimer = setInterval(() => showSlide(currentSlide + 1), 4500);

            document.getElementById('prev-slide').addEventListener('click', () => {
                clearInterval(slideTimer);
                showSlide(currentSlide - 1);
                slideTimer = setInterval(() => showSlide(currentSlide + 1), 4500);
            });

            document.getElementById('next-slide').addEventListener('click', () => {
                clearInterval(slideTimer);
                showSlide(currentSlide + 1);
                slideTimer = setInterval(() => showSlide(currentSlide + 1), 4500);
            });

            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    clearInterval(slideTimer);
                    showSlide(parseInt(dot.getAttribute('data-slide'), 10));
                    slideTimer = setInterval(() => showSlide(currentSlide + 1), 4500);
                });
            });

            // 2. Menu trên điện thoại
            const mobileBtn = document.getElementById('mobile-menu-btn');
            const mobileDrawer = document.getElementById('mobile-menu-drawer');
            mobileBtn.addEventListener('click', () => {
                mobileDrawer.classList.toggle('hidden');
            });
            document.querySelectorAll('.mobile-nav-item').forEach(link => {
                link.addEventListener('click', () => mobileDrawer.classList.add('hidden'));
            });

            // 3. Tìm kiếm sản phẩm
            const desktopSearch = document.getElementById('desktop-search-form');
            const mobileSearch = document.getElementById('mobile-search-form');
            desktopSearch.addEventListener('submit', (e) => {
                e.preventDefault();
                const val = document.getElementById('search-input').value;
                renderAllProducts(val);
                document.getElementById('sec-gach-lat-nen').scrollIntoView({ behavior: 'smooth' });
            });
            mobileSearch.addEventListener('submit', (e) => {
                e.preventDefault();
                const val = document.getElementById('mobile-search-input').value;
                renderAllProducts(val);
                document.getElementById('sec-gach-lat-nen').scrollIntoView({ behavior: 'smooth' });
            });

            // 4. Lọc danh mục bài viết
            document.querySelectorAll('.blog-tab-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.blog-tab-btn').forEach(b => {
                        b.className = 'blog-tab-btn px-2.5 py-1 rounded bg-slate-200 text-slate-700 font-semibold whitespace-nowrap';
                    });
                    btn.className = 'blog-tab-btn px-2.5 py-1 rounded bg-brand text-white font-semibold whitespace-nowrap';
                    renderBlogs(btn.getAttribute('data-blog-cat'));
                });
            });

            // 5. Xử lý gửi Form Yêu cầu & Báo giá trang chủ
            document.getElementById('quote-request-form').addEventListener('submit', (e) => {
                e.preventDefault();
                const name = document.getElementById('q-name').value;
                const phone = document.getElementById('q-phone').value;
                const category = document.getElementById('q-category').value;
                const msgBox = document.getElementById('quote-success-msg');
                msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${category}</strong> đã được ghi nhận. Bộ phận kinh doanh CÔNG TY TNHH TÂN THANH LỘC sẽ liên hệ lại ngay!`;
                msgBox.classList.remove('hidden');
                e.target.reset();
            });

            // 6. Nút Hotline nổi bật (Hiển thị đầy đủ 4 số điện thoại để bấm gọi ngay)
            document.getElementById('floating-hotline-btn').addEventListener('click', () => {
                const modal = document.getElementById('app-modal');
                document.getElementById('modal-title').textContent = 'Gọi Hotline Tư Vấn & Báo Giá Ngay';
                document.getElementById('modal-body').innerHTML = `
                    <div class="space-y-2.5">
                        <p class="text-xs text-slate-600 mb-2">Chọn số Hotline của <strong>CÔNG TY TNHH TÂN THANH LỘC</strong> để kết nối trực tiếp:</p>
                        <a href="tel:0914704046" class="flex items-center justify-between p-3 rounded-lg bg-slate-100 hover:bg-brand hover:text-white font-bold transition">
                            <span><i class="fa-solid fa-phone mr-2"></i> Hotline 1: 0914.704.046</span>
                            <span class="text-xs underline">Gọi ngay</span>
                        </a>
                        <a href="tel:0932564550" class="flex items-center justify-between p-3 rounded-lg bg-slate-100 hover:bg-brand hover:text-white font-bold transition">
                            <span><i class="fa-solid fa-phone mr-2"></i> Hotline 2: 0932.564.550</span>
                            <span class="text-xs underline">Gọi ngay</span>
                        </a>
                        <a href="tel:0945575221" class="flex items-center justify-between p-3 rounded-lg bg-slate-100 hover:bg-brand hover:text-white font-bold transition">
                            <span><i class="fa-solid fa-phone mr-2"></i> Hotline 3: 0945.575.221</span>
                            <span class="text-xs underline">Gọi ngay</span>
                        </a>
                        <a href="tel:0905278468" class="flex items-center justify-between p-3 rounded-lg bg-slate-100 hover:bg-brand hover:text-white font-bold transition">
                            <span><i class="fa-solid fa-phone mr-2"></i> Hotline 4: 0905.278.468</span>
                            <span class="text-xs underline">Gọi ngay</span>
                        </a>
                    </div>
                `;
                modal.classList.remove('hidden');
                modal.classList.add('flex');
            });

            document.getElementById('close-modal-btn').addEventListener('click', closeModal);
            document.getElementById('app-modal').addEventListener('click', (e) => {
                if (e.target.id === 'app-modal') closeModal();
            });
        };
    </script>
</body>
</html>

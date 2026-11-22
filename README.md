<html lang="vi">
<head>
    <!-- Thiết lập mã hóa & khung nhìn chuẩn cho điện thoại và máy tính -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM | Xây Dựng, Chống Thấm & Sửa Chữa Nhà Ở Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM - Chuyên xây dựng, xử lý chống thấm & sửa chữa nhà ở tại Đà Nẵng. Bền đẹp vững theo thời gian, giá trị trường tồn. Hotline: 0905.701.059">
    <meta name="keywords" content="xây dựng tân nam, xaydungtannam.com, sửa nhà trọn gói đà nẵng, chống thấm đà nẵng, sơn sửa nhà ở, thi công xây dựng đà nẵng">

    <!-- Thẻ Open Graph & Twitter Card: Sử dụng ảnh Logo làm ảnh Thumbnail khi chia sẻ link website -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="xaydungtannam.com">
    <meta property="og:url" content="https://xaydungtannam.com/">
    <meta property="og:title" content="CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM | House Repair / Paint / Waterproof">
    <meta property="og:description" content="Chuyên xây dựng, xử lý chống thấm & sửa chữa nhà ở tại Đà Nẵng. Bền đẹp vững theo thời gian, giá trị trường tồn. Hotline: 0905.701.059">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w1000">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w1000">
    <meta property="og:image:alt" content="Logo Công ty TNHH Bảo Trì Xây Dựng Tân Nam">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM">
    <meta name="twitter:description" content="Chuyên xây dựng, xử lý chống thấm & sửa chữa nhà ở Đà Nẵng. Hotline: 0905.701.059">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w1000">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w256">

    <!-- Font Inter hỗ trợ tiếng Việt sắc nét -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        /* Cấu hình bảng màu nhận diện thương hiệu Tân Nam & phong cách Flatsome */
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2E5A',      /* Xanh navy đậm vững chắc */
                            blue: '#1B4B8A',      /* Xanh thương hiệu xây dựng */
                            accent: '#D97706',    /* Vàng cam xây dựng nổi bật */
                            accentHover: '#B45309',
                            light: '#F4F7FB',     /* Nền xám xanh nhạt chuẩn Flatsome */
                            border: '#E2E8F0'
                        }
                    }
                }
            }
        };
    </script>

    <style>
        /* Thiết lập chống tràn viền ngang và căn chuẩn cho mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            scroll-behavior: smooth;
            color: #1E293B;
            background-color: #FFFFFF;
        }

        /* Khung nội dung chính: Chiều ngang máy tính đúng 95% kích thước màn hình, căn giữa tuyệt đối */
        .tn-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }

        /* Phong cách Flatsome Dropdown Menu mượt mà trên máy tính */
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

        /* Đường gạch chân tiêu đề mục chuẩn UX Builder Flatsome */
        .section-divider {
            width: 56px;
            height: 3px;
            background-color: #D97706;
            margin: 10px auto 0;
            border-radius: 9999px;
        }

        /* Hệ thống Banner trượt 2 ảnh kích thước bằng nhau tuyệt đối, chữ nằm gọn an toàn bên trong */
        .banner-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
        }
        .banner-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        .banner-slide {
            width: 50%;
            flex: 0 0 50%;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        /* Hiệu ứng sóng lan tỏa cho nút Hotline nổi */
        @keyframes hotlinePulse {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .hotline-pulse {
            animation: hotlinePulse 2s infinite;
        }

        /* Tùy chỉnh thanh cuộn danh mục lọc gọn gàng trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ===================================================================== -->
    <!-- THANH THÔNG TIN ĐẦU TRANG (TOP BAR PHONG CÁCH FLATSOME - KHÔNG CÓ UX BUILDER) -->
    <!-- ===================================================================== -->
    <div class="bg-brand-navy text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="tn-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
                <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                </svg>
                <span class="truncate">86 Lưu Quang Vũ, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-4 shrink-0 text-slate-200">
                <span>House Repair / Paint / Waterproof</span>
                <span class="text-white/30">|</span>
                <span class="font-semibold text-amber-300">xaydungtannam.com</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- HEADER CHÍNH: LOGO GỌN NHỎ + DANH MỤC 1 HÀNG TRÊN MÁY TÍNH (KHÔNG CÓ NÚT GỌI NGAY) -->
    <!-- ===================================================================== -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="tn-container flex items-center justify-between h-16 md:h-[70px] gap-3">
            <!-- Logo thương hiệu gọn nhỏ, cân đối -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 focus:outline-none">
                <img
                    src="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w400"
                    data-drive-id="1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ"
                    onerror="handleDriveImageError(this, 'LOGO TAN NAM')"
                    alt="Logo Công Ty TNHH Bảo Trì Xây Dựng Tân Nam"
                    class="h-10 sm:h-11 w-auto max-w-[110px] object-contain rounded-lg"
                >
                <div class="leading-tight">
                    <div class="text-xs sm:text-[13px] lg:text-sm font-extrabold text-brand-navy tracking-tight whitespace-nowrap">XÂY DỰNG TÂN NAM</div>
                    <div class="text-[10px] text-slate-500 font-medium whitespace-nowrap">House Repair • Paint • Waterproof</div>
                </div>
            </a>

            <!-- Menu Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng duy nhất, không xuống dòng -->
            <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end gap-2 xl:gap-4 min-w-0">
                <a href="#trang-chu" class="text-[11.5px] xl:text-[12.5px] font-bold text-brand-navy hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                    TRANG CHỦ
                </a>

                <!-- Dropdown Báo Giá (theo web mẫu trinhtiendana.com) -->
                <div class="relative nav-item">
                    <a href="#bao-gia" class="inline-flex items-center gap-1 text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                        <span>BÁO GIÁ</span>
                        <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2 text-xs font-medium text-slate-700">
                            <a href="#bao-gia" onclick="selectQuoteCategory('Báo giá Thi công trọn gói')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Báo giá Thi công</a>
                            <a href="#bao-gia" onclick="selectQuoteCategory('Báo giá Sửa chữa nhà')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Báo giá Sửa chữa</a>
                            <a href="#bao-gia" onclick="selectQuoteCategory('Báo giá Chống thấm')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Báo giá Chống thấm</a>
                            <a href="#bao-gia" onclick="selectQuoteCategory('Báo giá Thiết kế')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Báo giá Thiết kế</a>
                            <a href="#bao-gia" onclick="selectQuoteCategory('Báo giá Hoàn thiện & Sơn nhà')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Báo giá Hoàn thiện</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Thi Công -->
                <div class="relative nav-item">
                    <a href="#dich-vu" onclick="filterServices('thi-cong')" class="inline-flex items-center gap-1 text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                        <span>THI CÔNG</span>
                        <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2 text-xs font-medium text-slate-700">
                            <a href="#dich-vu" onclick="filterServices('thi-cong')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thi công Trọn gói</a>
                            <a href="#dich-vu" onclick="filterServices('thi-cong')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thi công Phần thô</a>
                            <a href="#dich-vu" onclick="filterServices('thi-cong')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thi công Hoàn thiện</a>
                            <a href="#dich-vu" onclick="filterServices('thi-cong')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thi công Nhân công</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Sửa Nhà Trọn Gói -->
                <div class="relative nav-item">
                    <a href="#dich-vu" onclick="filterServices('sua-nha')" class="inline-flex items-center gap-1 text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                        <span>SỬA NHÀ TRỌN GÓI</span>
                        <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2 text-xs font-medium text-slate-700">
                            <a href="#dich-vu" onclick="filterServices('sua-nha')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Sửa chữa nhà trọn gói</a>
                            <a href="#dich-vu" onclick="filterServices('sua-nha')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Cải tạo nâng tầng nhà phố</a>
                            <a href="#dich-vu" onclick="filterServices('sua-nha')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Sơn mới & bảo trì nhà ở</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Chống Thấm -->
                <div class="relative nav-item">
                    <a href="#dich-vu" onclick="filterServices('chong-tham')" class="inline-flex items-center gap-1 text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                        <span>CHỐNG THẤM</span>
                        <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2 text-xs font-medium text-slate-700">
                            <a href="#dich-vu" onclick="filterServices('chong-tham')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Chống thấm tường ngoài</a>
                            <a href="#dich-vu" onclick="filterServices('chong-tham')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Chống thấm ngược</a>
                            <a href="#dich-vu" onclick="filterServices('chong-tham')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Chống thấm sân thượng</a>
                            <a href="#dich-vu" onclick="filterServices('chong-tham')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Chống thấm WC – bể ngầm</a>
                            <a href="#dich-vu" onclick="filterServices('chong-tham')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Xử lý vết nứt bê tông</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown Thiết Kế -->
                <div class="relative nav-item">
                    <a href="#dich-vu" onclick="filterServices('thiet-ke')" class="inline-flex items-center gap-1 text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                        <span>THIẾT KẾ</span>
                        <svg class="w-3 h-3 opacity-60" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M19 9l-7 7-7-7"/></svg>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-xl shadow-xl border border-slate-100 py-2 text-xs font-medium text-slate-700">
                            <a href="#dich-vu" onclick="filterServices('thiet-ke')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thiết kế trọn gói nhà phố</a>
                            <a href="#dich-vu" onclick="filterServices('thiet-ke')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thiết kế nhà cấp 4</a>
                            <a href="#dich-vu" onclick="filterServices('thiet-ke')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thiết kế điện – nước</a>
                            <a href="#dich-vu" onclick="filterServices('thiet-ke')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-navy">Thiết kế kết cấu & xin phép</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                    DỰ ÁN ĐÀ NẴNG
                </a>

                <a href="#bai-viet" class="text-[11.5px] xl:text-[12.5px] font-bold text-slate-700 hover:text-brand-accent transition-colors whitespace-nowrap px-1.5 py-2">
                    TIN TỨC
                </a>
            </nav>

            <!-- Nút Mở Menu Trên Điện Thoại (Mobile Hamburger Button) -->
            <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg text-brand-navy bg-slate-100 hover:bg-slate-200 transition-colors">
                <svg id="menu-icon-open" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
                <svg id="menu-icon-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
                </svg>
            </button>
        </div>

        <!-- Menu Trượt Cho Điện Thoại (Responsive Mobile Drawer) -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg max-h-[80vh] overflow-y-auto">
            <div class="tn-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-800">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-3 hover:text-brand-accent">TRANG CHỦ</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-3 hover:text-brand-accent">BÁO GIÁ</a>
                <a href="#dich-vu" onclick="filterServices('thi-cong'); closeMobileMenu();" class="py-3 hover:text-brand-accent">THI CÔNG (Trọn gói / Phần thô / Hoàn thiện)</a>
                <a href="#dich-vu" onclick="filterServices('sua-nha'); closeMobileMenu();" class="py-3 hover:text-brand-accent">SỬA NHÀ TRỌN GÓI & SƠN SỬA</a>
                <a href="#dich-vu" onclick="filterServices('chong-tham'); closeMobileMenu();" class="py-3 hover:text-brand-accent">CHỐNG THẤM CHUYÊN NGHIỆP</a>
                <a href="#dich-vu" onclick="filterServices('thiet-ke'); closeMobileMenu();" class="py-3 hover:text-brand-accent">THIẾT KẾ KIẾN TRÚC & KẾT CẤU</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-3 hover:text-brand-accent">DỰ ÁN TẠI ĐÀ NẴNG</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-3 hover:text-brand-accent">ĐỐI TÁC</a>
                <a href="#bai-viet" onclick="closeMobileMenu()" class="py-3 hover:text-brand-accent">TIN TỨC & BÀI VIẾT</a>
                <a href="#lien-he-trang-chu" onclick="closeMobileMenu()" class="py-3 text-brand-navy">LIÊN HỆ & BẢN ĐỒ</a>
            </div>
        </div>
    </header>

    <!-- ===================================================================== -->
    <!-- BANNER TRƯỢT KÉP (2 ẢNH KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM TRỌN BÊN TRONG & CÁCH XA VIỀN) -->
    <!-- ===================================================================== -->
    <section id="trang-chu" class="w-full bg-brand-navy">
        <div class="banner-viewport">
            <div id="banner-track" class="banner-track">
                <!-- SLIDE 1 -->
                <div class="banner-slide min-h-[340px] sm:min-h-[410px] lg:min-h-[470px]">
                    <!-- Ảnh nền thực tế thi công phủ đều khung -->
                    <img
                        src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                        data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                        onerror="handleDriveImageError(this, 'XAY DUNG TAN NAM')"
                        alt="Công ty TNHH Bảo Trì Xây Dựng Tân Nam - Thi công xây dựng Đà Nẵng"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                    >
                    <!-- Lớp phủ chuyển sắc đảm bảo độ tương phản chữ tuyệt đối -->
                    <div class="absolute inset-0 bg-gradient-to-r from-[#091D3A]/90 via-[#0F2E5A]/75 to-[#091D3A]/65"></div>

                    <!-- Nội dung chữ cách xa viền ảnh trên cả điện thoại và máy tính -->
                    <div class="relative z-10 w-full max-w-5xl mx-auto px-12 sm:px-16 md:px-20 py-10 sm:py-14 text-center text-white">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-[0.16em] uppercase text-amber-300 mb-2.5 sm:mb-3">
                            HOUSE REPAIR • PAINT • WATERPROOF
                        </p>
                        <h1 class="text-lg sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight tracking-tight mb-3 sm:mb-4">
                            CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM
                        </h1>
                        <p class="text-xs sm:text-base md:text-lg text-slate-100 max-w-2xl mx-auto leading-relaxed mb-6 sm:mb-7">
                            Chuyên xây dựng, xử lý chống thấm &amp; sửa chữa nhà ở tại Đà Nẵng. Bền đẹp vững theo thời gian – Giá trị trường tồn.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-3">
                            <a href="#bao-gia" class="inline-flex items-center justify-center px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow-md transition-all">
                                Nhận Báo Giá Miễn Phí
                            </a>
                            <a href="#dich-vu" class="inline-flex items-center justify-center px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold backdrop-blur-sm transition-all">
                                Xem Hạng Mục Thi Công
                            </a>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước & bố cục đồng nhất 100% với Slide 1) -->
                <div class="banner-slide min-h-[340px] sm:min-h-[410px] lg:min-h-[470px]">
                    <img
                        src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1600"
                        data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                        onerror="handleDriveImageError(this, 'CHONG THAM & SUA NHA DA NANG')"
                        alt="Xử lý chống thấm & sửa chữa nhà trọn gói Đà Nẵng - Xây Dựng Tân Nam"
                        class="absolute inset-0 w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-[#091D3A]/90 via-[#0F2E5A]/75 to-[#091D3A]/65"></div>

                    <!-- Nội dung chữ cách xa viền ảnh trên cả điện thoại và máy tính -->
                    <div class="relative z-10 w-full max-w-5xl mx-auto px-12 sm:px-16 md:px-20 py-10 sm:py-14 text-center text-white">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-[0.16em] uppercase text-amber-300 mb-2.5 sm:mb-3">
                            BỀN ĐẸP VỮNG THEO THỜI GIAN • GIÁ TRỊ TRƯỜNG TỒN
                        </p>
                        <h2 class="text-lg sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug sm:leading-tight tracking-tight mb-3 sm:mb-4">
                            THI CÔNG XÂY DỰNG – CHỐNG THẤM &amp; SỬA NHÀ TRỌN GÓI
                        </h2>
                        <p class="text-xs sm:text-base md:text-lg text-slate-100 max-w-2xl mx-auto leading-relaxed mb-6 sm:mb-7">
                            Đội ngũ kỹ sư và thợ lành nghề khảo sát tận nơi tại Đà Nẵng. Quy trình chuẩn kỹ thuật, vật tư chính hãng, bảo hành dài lâu.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-3">
                            <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow-md transition-all">
                                Xem Dự Án Tại Đà Nẵng
                            </a>
                            <a href="tel:0905701059" class="inline-flex items-center justify-center px-5 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold backdrop-blur-sm transition-all">
                                Tư Vấn: 0905.701.059
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng Trái / Phải đặt sát mép gọn gàng, không che chữ -->
            <button type="button" onclick="moveSlide(-1)" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
                <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
            </button>
            <button type="button" onclick="moveSlide(1)" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
                <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
            </button>

            <!-- Chấm chỉ báo Slide -->
            <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Slide 1" class="w-7 h-2 rounded-full bg-brand-accent transition-all"></button>
                <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- GIỚI THIỆU DOANH NGHIỆP (BỐ CỤC CHUẨN MẪU TRINHTIENDANA.COM / FLATSOME) -->
    <!-- ===================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-white border-b border-slate-100">
        <div class="tn-container">
            <div class="max-w-4xl mx-auto text-center">
                <p class="text-xs font-bold tracking-widest uppercase text-brand-accent mb-1.5">– GIÁ TRỊ TRƯỜNG TỒN –</p>
                <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy">
                    CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM
                </h2>
                <div class="section-divider"></div>
                <p class="mt-4 text-sm sm:text-base text-slate-600 leading-relaxed">
                    <strong>Xây Dựng Tân Nam</strong> gửi lời chào trân trọng đến quý khách hàng đã và đang đồng hành cùng chúng tôi trên mọi công trình. Hoạt động chuyên sâu trong lĩnh vực <strong>xây dựng nhà ở, xử lý chống thấm triệt để, sơn mới và sửa chữa cải tạo nhà trọn gói</strong> tại Thành phố Đà Nẵng và khu vực miền Trung, chúng tôi cam kết mang đến giải pháp kỹ thuật tối ưu, tiến độ chuẩn xác và chi phí minh bạch nhất.
                </p>
                <p class="mt-3 text-sm sm:text-base text-slate-600 leading-relaxed">
                    Với đội ngũ kỹ sư tận tâm, thợ thi công giàu kinh nghiệm cùng quy trình giám sát chặt chẽ từ khâu khảo sát đến bàn giao, Tân Nam luôn lấy chất lượng công trình và sự an tâm lâu dài của gia chủ làm kim chỉ nam hoạt động.
                </p>

                <!-- 4 Điểm mạnh cốt lõi (Thiết kế đơn giản dạng Icon Box dễ dựng lại trên UX Builder) -->
                <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5 mt-8">
                    <div class="p-4 rounded-xl bg-brand-light border border-slate-200/70 text-center">
                        <div class="text-lg sm:text-xl font-extrabold text-brand-navy">100%</div>
                        <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Vật Tư Chính Hãng</div>
                    </div>
                    <div class="p-4 rounded-xl bg-brand-light border border-slate-200/70 text-center">
                        <div class="text-lg sm:text-xl font-extrabold text-brand-navy">Đúng Tiến Độ</div>
                        <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Cam Kết Hợp Đồng</div>
                    </div>
                    <div class="p-4 rounded-xl bg-brand-light border border-slate-200/70 text-center">
                        <div class="text-lg sm:text-xl font-extrabold text-brand-navy">Khảo Sát 0đ</div>
                        <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Báo Giá Minh Bạch</div>
                    </div>
                    <div class="p-4 rounded-xl bg-brand-light border border-slate-200/70 text-center">
                        <div class="text-lg sm:text-xl font-extrabold text-brand-navy">Bảo Hành Dài</div>
                        <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Hỗ Trợ Tận Tâm 24/7</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC SẢN PHẨM & DỊCH VỤ THI CÔNG THỰC TẾ (2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN) -->
    <!-- ===================================================================== -->
    <section id="dich-vu" class="py-10 sm:py-14 bg-brand-light">
        <div class="tn-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    DANH MỤC DỊCH VỤ &amp; THI CÔNG THỰC TẾ
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
                    Xây dựng trọn gói • Sửa chữa cải tạo nhà ở • Xử lý chống thấm • Sơn sửa &amp; thiết kế
                </p>
                <div class="section-divider"></div>
            </div>

            <!-- Thanh lọc danh mục nhỏ gọn, dễ thao tác trên điện thoại và máy tính -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                <button type="button" onclick="filterServices('all')" data-filter="all" class="service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition-colors">
                    Tất cả hạng mục
                </button>
                <button type="button" onclick="filterServices('thi-cong')" data-filter="thi-cong" class="service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition-colors">
                    Thi công xây dựng
                </button>
                <button type="button" onclick="filterServices('sua-nha')" data-filter="sua-nha" class="service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition-colors">
                    Sửa nhà &amp; Sơn mới
                </button>
                <button type="button" onclick="filterServices('chong-tham')" data-filter="chong-tham" class="service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition-colors">
                    Chống thấm
                </button>
                <button type="button" onclick="filterServices('thiet-ke')" data-filter="thiet-ke" class="service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition-colors">
                    Thiết kế &amp; Bảo trì
                </button>
            </div>

            <!-- Lưới 9 ảnh thực tế thi công: Bắt buộc 2 cột trên mobile, 3 cột trên desktop, tên sản phẩm đầy đủ không cắt chữ -->
            <div id="services-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5 lg:gap-6">
                <!-- Dữ liệu được render tự động từ JS để dễ bảo trì & tương tác xem chi tiết -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH THỰC TẾ) -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-white border-t border-slate-100">
        <div class="tn-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
                    Hình ảnh công trình thực tế do đội ngũ Công ty TNHH Bảo Trì Xây Dựng Tân Nam trực tiếp thi công và bàn giao
                </p>
                <div class="section-divider"></div>
            </div>

            <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên mobile, 5 cột cân đối trên desktop -->
            <div id="projects-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4 lg:gap-5">
                <!-- Render tự động từ danh sách 10 dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC ĐỐI TÁC CUNG CẤP VẬT TƯ & ĐỒNG HÀNH -->
    <!-- ===================================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-brand-light border-t border-slate-200/70">
        <div class="tn-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    ĐỐI TÁC VẬT TƯ &amp; ĐỒNG HÀNH
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1">
                    Cam kết sử dụng vật liệu xây dựng, sơn và hóa chất chống thấm từ các thương hiệu hàng đầu
                </p>
                <div class="section-divider"></div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-red-600">SIKA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Chống thấm</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-blue-700">DULUX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn cao cấp</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-indigo-800">JOTUN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-emerald-700">KOVA</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Sơn chống thấm</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép xây dựng</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-sky-700">BÌNH MINH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Ống nhựa điện nước</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-amber-700">SÔNG GIANH</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Xi măng PCB40</span>
                </div>
                <div class="bg-white rounded-xl border border-slate-200 p-3.5 flex flex-col items-center justify-center text-center shadow-sm hover:border-brand-accent transition-colors min-h-[76px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-slate-800">INAX</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC BÀI VIẾT & KINH NGHIỆM XÂY DỰNG TRANG CHỦ -->
    <!-- ===================================================================== -->
    <section id="bai-viet" class="py-10 sm:py-14 bg-white border-t border-slate-100">
        <div class="tn-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    TIN TỨC &amp; KINH NGHIỆM XÂY DỰNG
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
                    Chia sẻ kiến thức sửa nhà, xử lý chống thấm và cập nhật đơn giá thi công tại Đà Nẵng
                </p>
                <div class="section-divider"></div>
            </div>

            <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Render tự động từ danh sách bài viết -->
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- KHU VỰC FANPAGE FACEBOOK + GOOGLE MAPS + FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
    <!-- (BỐ CỤC CHUẨN MẪU TRINHTIENDANA.COM - DỄ TÁI TẠO TRÊN UX BUILDER FLATSOME) -->
    <!-- ===================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-light border-t border-slate-200">
        <div id="lien-he-trang-chu" class="tn-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    KẾT NỐI &amp; YÊU CẦU BÁO GIÁ NHANH
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1.5">
                    Theo dõi tiến độ thi công qua Fanpage, xem chỉ đường văn phòng hoặc gửi yêu cầu khảo sát miễn phí
                </p>
                <div class="section-divider"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-5 sm:gap-6 items-stretch">
                <!-- CỘT 1: FANPAGE FACEBOOK TRANG CHỦ -->
                <div class="bg-white rounded-2xl border border-slate-200 p-5 shadow-sm flex flex-col justify-between">
                    <div>
                        <h3 class="text-base font-extrabold text-brand-navy uppercase pb-2.5 border-b border-slate-100 mb-3">
                            Fanpage Facebook
                        </h3>
                        <p class="text-xs text-slate-600 mb-3">
                            Theo dõi hình ảnh thi công thực tế hàng ngày của Xây Dựng Tân Nam qua Facebook:
                        </p>

                        <!-- Khung nhúng Fanpage Facebook chính thức -->
                        <div class="w-full rounded-xl overflow-hidden border border-slate-200 bg-slate-50 mb-3">
                            <iframe
                                title="Fanpage Công ty TNHH Bảo Trì Xây Dựng Tân Nam"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D61584831475482&tabs=timeline&width=380&height=300&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                width="100%"
                                height="300"
                                style="border:none; overflow:hidden; display:block;"
                                scrolling="no"
                                frameborder="0"
                                allowfullscreen="true"
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                                loading="lazy">
                            </iframe>
                        </div>
                    </div>

                    <!-- Thẻ liên kết trực tiếp Fanpage (đảm bảo luôn truy cập dễ dàng trên mọi trình duyệt) -->
                    <div class="bg-brand-light rounded-xl p-3.5 border border-slate-200/80 flex items-center justify-between gap-3">
                        <div class="flex items-center gap-2.5 min-w-0">
                            <img
                                src="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w200"
                                data-drive-id="1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ"
                                onerror="handleDriveImageError(this, 'TN')"
                                alt="Logo Tân Nam"
                                class="w-10 h-10 rounded-lg object-contain bg-white p-1 border border-slate-200 shrink-0"
                            >
                            <div class="min-w-0">
                                <div class="text-xs font-bold text-brand-navy truncate">Bảo Trì Xây Dựng Tân Nam</div>
                                <div class="text-[11px] text-slate-500 truncate">House repair / Paint / Waterproof</div>
                            </div>
                        </div>
                        <a href="https://www.facebook.com/profile.php?id=61584831475482" target="_blank" rel="noopener noreferrer" class="shrink-0 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition-colors">
                            Xem Page
                        </a>
                    </div>
                </div>

                <!-- CỘT 2: BẢN ĐỒ GOOGLE MAPS TRANG CHỦ -->
                <div class="bg-white rounded-2xl border border-slate-200 p-5 shadow-sm flex flex-col justify-between">
                    <div>
                        <h3 class="text-base font-extrabold text-brand-navy uppercase pb-2.5 border-b border-slate-100 mb-3">
                            Bản Đồ Google Maps
                        </h3>
                        <p class="text-xs text-slate-600 mb-3">
                            Văn phòng công ty: <strong>86 Lưu Quang Vũ, Phường Ngũ Hành Sơn, TP Đà Nẵng</strong>
                        </p>

                        <!-- Nhúng bản đồ Google Maps trực tiếp ra ngoài trang chủ -->
                        <div class="w-full h-[300px] rounded-xl overflow-hidden border border-slate-200 bg-slate-100 mb-3">
                            <iframe
                                title="Bản đồ 86 Lưu Quang Vũ, Phường Ngũ Hành Sơn, TP Đà Nẵng"
                                src="https://maps.google.com/maps?q=86%20L%C6%B0u%20Quang%20V%C5%A9,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                width="100%"
                                height="100%"
                                style="border:0;"
                                allowfullscreen=""
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                        <span class="text-xs text-slate-600 font-medium">Hotline: <strong class="text-brand-navy">0905.701.059</strong></span>
                        <a href="https://www.google.com/maps/search/?api=1&query=86+L%C6%B0u+Quang+V%C5%A9,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3.5 py-2 rounded-lg bg-brand-navy hover:bg-brand-blue text-white text-xs font-bold transition-colors">
                            <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/></svg>
                            Chỉ Đường Google Maps
                        </a>
                    </div>
                </div>

                <!-- CỘT 3: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ -->
                <div class="bg-white rounded-2xl border border-slate-200 p-5 shadow-sm flex flex-col">
                    <h3 class="text-base font-extrabold text-brand-navy uppercase pb-2.5 border-b border-slate-100 mb-3">
                        Gửi Yêu Cầu &amp; Nhận Báo Giá
                    </h3>
                    <p class="text-xs text-slate-600 mb-4">
                        Để lại thông tin bên dưới, kỹ sư Tân Nam sẽ liên hệ tư vấn và khảo sát miễn phí trong vòng 30 phút.
                    </p>

                    <form id="quote-form" class="space-y-3 flex-1 flex flex-col justify-between" novalidate>
                        <div class="space-y-3">
                            <div>
                                <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy/25 focus:border-brand-navy">
                            </div>

                            <div>
                                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="q-phone" type="tel" required placeholder="Ví dụ: 0905 xxx xxx" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy/25 focus:border-brand-navy">
                            </div>

                            <div>
                                <label for="q-service" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                                <select id="q-service" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-brand-navy/25 focus:border-brand-navy">
                                    <option value="Xây dựng nhà trọn gói">Xây dựng nhà trọn gói</option>
                                    <option value="Sửa chữa & cải tạo nhà ở">Sửa chữa &amp; cải tạo nhà ở</option>
                                    <option value="Xử lý chống thấm (sân thượng, tường, WC)">Xử lý chống thấm (sân thượng, tường, WC)</option>
                                    <option value="Sơn nhà mới & bảo trì bề mặt">Sơn nhà mới &amp; bảo trì bề mặt</option>
                                    <option value="Thiết kế kiến trúc & kết cấu">Thiết kế kiến trúc &amp; kết cấu</option>
                                    <option value="Báo giá Thi công trọn gói">Báo giá Thi công trọn gói</option>
                                    <option value="Báo giá Sửa chữa nhà">Báo giá Sửa chữa nhà</option>
                                    <option value="Báo giá Chống thấm">Báo giá Chống thấm</option>
                                    <option value="Báo giá Thiết kế">Báo giá Thiết kế</option>
                                    <option value="Báo giá Hoàn thiện & Sơn nhà">Báo giá Hoàn thiện &amp; Sơn nhà</option>
                                </select>
                            </div>

                            <div>
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình &amp; mô tả sơ bộ</label>
                                <textarea id="q-note" rows="3" placeholder="Ví dụ: Nhà phố 2 tầng tại Ngũ Hành Sơn cần chống thấm sân thượng và sơn lại mặt tiền..." class="w-full px-3.5 py-2 rounded-lg border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-brand-navy/25 focus:border-brand-navy resize-none"></textarea>
                            </div>
                        </div>

                        <div class="pt-2">
                            <!-- Thông báo trạng thái form (Không dùng alert) -->
                            <div id="form-feedback" class="hidden mb-3 p-3 rounded-lg text-xs font-medium"></div>

                            <button type="submit" class="w-full py-3 px-4 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm shadow-sm transition-colors">
                                GỬI YÊU CẦU BÁO GIÁ
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- CHÂN TRANG (FOOTER 3 CỘT CHUẨN FLATSOME) -->
    <!-- ===================================================================== -->
    <footer class="bg-brand-navy text-slate-200 pt-10 pb-8 border-t-4 border-brand-accent">
        <div class="tn-container">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 pb-8 border-b border-white/10">
                <!-- Cột thông tin công ty -->
                <div>
                    <div class="flex items-center gap-3 mb-3">
                        <img
                            src="https://drive.google.com/thumbnail?id=1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ&sz=w300"
                            data-drive-id="1wN2uUa_wgFcB9iUdvBRwhFtMBAK7BhTQ"
                            onerror="handleDriveImageError(this, 'TAN NAM')"
                            alt="Logo Xây Dựng Tân Nam"
                            class="h-11 w-auto bg-white rounded-lg p-1 object-contain"
                        >
                        <div>
                            <div class="text-sm font-extrabold text-white">CÔNG TY TNHH BẢO TRÌ XÂY DỰNG TÂN NAM</div>
                            <div class="text-[11px] text-amber-300">Bền đẹp vững theo thời gian – Giá trị trường tồn</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        Chuyên xây dựng nhà ở, xử lý chống thấm triệt để, sơn mới và sửa chữa cải tạo nhà trọn gói tại Đà Nẵng. House repair / Paint / Waterproof.
                    </p>
                    <p class="text-xs text-slate-400">MST: 0402161511 • Website: xaydungtannam.com</p>
                </div>

                <!-- Cột danh mục dịch vụ -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3">Danh Mục Dịch Vụ</h4>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><a href="#dich-vu" onclick="filterServices('thi-cong')" class="hover:text-amber-300 transition-colors">Thi công xây dựng trọn gói &amp; phần thô</a></li>
                        <li><a href="#dich-vu" onclick="filterServices('sua-nha')" class="hover:text-amber-300 transition-colors">Sửa chữa &amp; cải tạo nhà ở trọn gói Đà Nẵng</a></li>
                        <li><a href="#dich-vu" onclick="filterServices('chong-tham')" class="hover:text-amber-300 transition-colors">Xử lý chống thấm sân thượng, tường ngoài, WC</a></li>
                        <li><a href="#dich-vu" onclick="filterServices('sua-nha')" class="hover:text-amber-300 transition-colors">Sơn nhà trọn gói &amp; bảo trì công trình</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300 transition-colors">Các dự án thực tế tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột thông tin liên hệ -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3">Thông Tin Liên Hệ</h4>
                    <ul class="space-y-2.5 text-xs text-slate-300">
                        <li class="flex items-start gap-2">
                            <svg class="w-4 h-4 text-brand-accent shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/></svg>
                            <span>86 Lưu Quang Vũ, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <svg class="w-4 h-4 text-brand-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                            <a href="tel:0905701059" class="font-bold text-amber-300 hover:underline">0905.701.059</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <svg class="w-4 h-4 text-brand-accent shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9"/></svg>
                            <span>Website: xaydungtannam.com</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <svg class="w-4 h-4 text-brand-accent shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                            <a href="https://www.facebook.com/profile.php?id=61584831475482" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition-colors">Fanpage Xây Dựng Tân Nam</a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>© 2026 <strong>xaydungtannam.com</strong> – Công Ty TNHH Bảo Trì Xây Dựng Tân Nam.</div>
                <div>Thiết kế thi công xây dựng, chống thấm &amp; sửa chữa nhà ở Đà Nẵng.</div>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MOBILE & DESKTOP) -->
    <!-- ===================================================================== -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi -->
        <a href="https://zalo.me/0905701059" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.701.059" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-lg transition-all">
            <span class="w-6 h-6 flex items-center justify-center font-extrabold text-[11px] bg-white text-[#0068FF] rounded-full">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi -->
        <a href="https://www.facebook.com/profile.php?id=61584831475482" target="_blank" rel="noopener noreferrer" aria-label="Fanpage Facebook Xây Dựng Tân Nam" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-lg transition-all">
            <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi với hiệu ứng nhịp sóng thu hút -->
        <a href="tel:0905701059" aria-label="Gọi Hotline 0905.701.059" class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full p-2.5 sm:px-4 sm:py-2.5 shadow-xl transition-all">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="hidden sm:inline text-xs font-extrabold tracking-wide pr-1">0905.701.059</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- HỘP THOẠI CHI TIẾT (MODAL XEM ẢNH DỊCH VỤ / DỰ ÁN / BÀI VIẾT) -->
    <!-- ===================================================================== -->
    <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black/70 backdrop-blur-xs p-3 sm:p-5" role="dialog" aria-modal="true">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-100 sticky top-0 bg-white z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand-navy pr-4"></h3>
                <button type="button" onclick="closeModal()" aria-label="Đóng" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 flex items-center justify-center text-slate-700 shrink-0">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M6 18L18 6M6 6l12 12"/></svg>
                </button>
            </div>
            <div class="p-5">
                <div class="w-full rounded-xl overflow-hidden bg-slate-100 mb-4">
                    <img id="modal-image" src="" alt="" class="w-full max-h-[380px] object-cover">
                </div>
                <div id="modal-body" class="text-sm text-slate-600 leading-relaxed space-y-2.5"></div>
                <div class="mt-5 pt-4 border-t border-slate-100 flex flex-wrap items-center justify-between gap-3">
                    <a href="tel:0905701059" class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-accent">
                        Hotline tư vấn trực tiếp: 0905.701.059
                    </a>
                    <a href="#bao-gia" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold transition-colors">
                        Nhận Báo Giá Hạng Mục Này
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- MÃ JAVASCRIPT ĐIỀU KHIỂN TOÀN BỘ TÍNH NĂNG WEBSITE -->
    <!-- ===================================================================== -->
    <script>
        /**
         * Hàm hỗ trợ lấy link hiển thị trực tiếp cho ảnh Google Drive
         * và cơ chế dự phòng nhiều tầng tránh lỗi ảnh bị gãy.
         */
        function getDriveImgUrl(fileId, width) {
            return 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w' + (width || 1000);
        }

        function handleDriveImageError(imgEl, fallbackText) {
            try {
                const attempt = parseInt(imgEl.dataset.attempt || '0', 10);
                const driveId = imgEl.dataset.driveId || '';
                if (attempt === 0 && driveId) {
                    imgEl.dataset.attempt = '1';
                    imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
                } else {
                    imgEl.onerror = null;
                    const label = encodeURIComponent(fallbackText || 'Xay Dung Tan Nam');
                    imgEl.src = 'https://placehold.co/800x600/0F2E5A/FFFFFF?text=' + label;
                }
            } catch (err) {
                imgEl.onerror = null;
            }
        }

        /* -------------------------------------------------------------------
         * 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG & PHÂN LOẠI CHUẨN MẪU
         * ------------------------------------------------------------------- */
        const servicesData = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                category: 'thi-cong',
                title: 'Thi Công Xây Dựng Nhà Ở Trọn Gói',
                summary: 'Thi công chìa khóa trao tay từ phần móng đến hoàn thiện nội ngoại thất chuẩn kỹ thuật.',
                details: 'Công ty TNHH Bảo Trì Xây Dựng Tân Nam đảm nhận toàn bộ quy trình từ tư vấn thiết kế, xin phép xây dựng, thi công phần thô đến hoàn thiện chìa khóa trao tay tại Đà Nẵng. Cam kết vật tư đúng chủng loại, không phát sinh chi phí.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                category: 'thi-cong',
                title: 'Thi Công Phần Thô & Kết Cấu Công Trình',
                summary: 'Thi công móng, khung bê tông cốt thép, xây tô tường đúng tiêu chuẩn kết cấu bền vững.',
                details: 'Đảm bảo kết cấu chịu lực vững chắc cho nhà phố, nhà cấp 4 và công trình dân dụng. Giám sát kỹ thuật chặt chẽ từng mẻ bê tông, cốt thép và công tác xây tô tường phẳng mịn.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                category: 'thi-cong',
                title: 'Thi Công Hoàn Thiện Nội Ngoại Thất',
                summary: 'Ốp lát gạch, đóng trần thạch cao, lắp đặt điện nước và hoàn thiện thẩm mỹ công trình.',
                details: 'Hoàn thiện tỉ mỉ từng chi tiết: ốp lát gạch nền – tường, đá hoa cương cầu thang, trần thạch cao, cửa nhôm kính và hệ thống điện nước đồng bộ, mang lại không gian sống hiện đại.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                category: 'sua-nha',
                title: 'Sửa Chữa & Cải Tạo Nhà Trọn Gói',
                summary: 'Cải tạo nhà cũ xuống cấp, nâng tầng, phân chia lại phòng ốc tối ưu công năng sử dụng.',
                details: 'Khảo sát hiện trạng miễn phí, lên phương án cải tạo tiết kiệm và hiệu quả nhất cho nhà phố, nhà cấp 4, mặt bằng kinh doanh. Thi công gọn gàng, sạch sẽ, đúng tiến độ bàn giao.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                category: 'chong-tham',
                title: 'Xử Lý Chống Thấm Sân Thượng & Sàn Mái',
                summary: 'Chống thấm triệt để sàn mái, sân thượng bằng vật liệu Sika, màng khò nóng và PU cao cấp.',
                details: 'Quy trình 3 bước chuẩn kỹ thuật: mài xử lý sạch bề mặt & trám vết nứt, thi công nhiều lớp vật liệu chống thấm chuyên dụng (Sika, màng chống thấm, Polyurethane) và ngâm thử nước nghiệm thu trước khi bàn giao.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                category: 'chong-tham',
                title: 'Chống Thấm Tường Ngoài & Xử Lý Vết Nứt',
                summary: 'Ngăn chặn thấm dột tường đứng, khe giáp lai và xử lý triệt để vết nứt chân chim mùa mưa.',
                details: 'Đặc thù khí hậu mưa bão miền Trung dễ gây ẩm mốc tường ngoài. Tân Nam áp dụng giải pháp xử lý vết nứt chuyên sâu kết hợp sơn chống thấm đàn hồi cao giúp bảo vệ tường bền đẹp nhiều năm.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                category: 'chong-tham',
                title: 'Chống Thấm Nhà Vệ Sinh, Ban Công & Bể Ngầm',
                summary: 'Xử lý chống thấm cổ ống xuyên sàn, khu vực ẩm ướt nhà vệ sinh, hộp kỹ thuật và bể nước.',
                details: 'Xử lý triệt để các điểm xung yếu quanh cổ ống thoát sàn, chân tường WC, ban công và bể chứa ngầm bằng vữa rót không co ngót và màng chống thấm 2 thành phần, bảo hành lâu dài.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                category: 'sua-nha',
                title: 'Sơn Nhà Trọn Gói & Bảo Trì Bề Mặt',
                summary: 'Bả matit, sơn lót kháng kiềm và sơn phủ nội ngoại thất bền màu từ Dulux, Jotun, Kova.',
                details: 'Dịch vụ sơn mới, sơn lại nhà cũ chuyên nghiệp: cạo bỏ lớp sơn bong tróc, xử lý ẩm mốc, thi công đủ lớp sơn lót và sơn phủ chính hãng giúp ngôi nhà sáng đẹp như mới.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                category: 'thiet-ke',
                title: 'Thiết Kế Nhà Phố & Thi Công Nhân Công',
                summary: 'Thiết kế kiến trúc, kết cấu, điện nước, xin phép xây dựng và cung cấp đội thợ lành nghề.',
                details: 'Hỗ trợ thiết kế bản vẽ bố trí công năng tối ưu, hồ sơ kết cấu – điện nước đầy đủ và cung ứng đội thợ thi công nhân công tay nghề cao cho các công trình dân dụng tại Đà Nẵng.'
            }
        ];

        /* -------------------------------------------------------------------
         * 2. DỮ LIỆU 10 ẢNH DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG
         * ------------------------------------------------------------------- */
        const projectsData = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Cải Tạo & Chống Thấm Nhà Phố Ngũ Hành Sơn',
                location: 'Phường Ngũ Hành Sơn, Đà Nẵng'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Thi Công Hoàn Thiện Nhà Ở Hòa Quý',
                location: 'Khu đô thị Hòa Quý, Đà Nẵng'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Xử Lý Chống Thấm Sân Thượng Sơn Trà',
                location: 'Quận Sơn Trà, Đà Nẵng'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Sửa Chữa Trọn Gói Nhà Phố Hải Châu',
                location: 'Quận Hải Châu, Đà Nẵng'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Chống Thấm Tường Ngoài Khu Hòa Xuân',
                location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Cải Tạo Nâng Cấp Nhà Ở Thanh Khê',
                location: 'Quận Thanh Khê, Đà Nẵng'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Thi Công Phần Thô & Ốp Lát Liên Chiểu',
                location: 'Quận Liên Chiểu, Đà Nẵng'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Chống Thấm WC & Bảo Trì Khu Mỹ An',
                location: 'Mỹ An, Ngũ Hành Sơn, Đà Nẵng'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Sơn Ngoại Thất Chống Thấm An Thượng',
                location: 'Khu An Thượng, Đà Nẵng'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Sửa Chữa Hoàn Thiện Nhà Ở Khuê Mỹ',
                location: 'Khuê Mỹ, Ngũ Hành Sơn, Đà Nẵng'
            }
        ];

        /* -------------------------------------------------------------------
         * 3. DỮ LIỆU BÀI VIẾT & KINH NGHIỆM TRANG CHỦ
         * ------------------------------------------------------------------- */
        const articlesData = [
            {
                imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                date: '18/11/2026',
                title: 'Báo giá dịch vụ sửa nhà trọn gói Đà Nẵng mới nhất – Tiết kiệm & minh bạch',
                excerpt: 'Tổng hợp các hạng mục cải tạo phổ biến, cách dự toán chi phí sát thực tế và lưu ý khi ký hợp đồng sửa chữa nhà ở.',
                content: 'Dịch vụ sửa chữa nhà trọn gói giúp gia chủ tiết kiệm tối đa thời gian quản lý vật tư và nhân công. Tại Xây Dựng Tân Nam, mọi công trình đều được khảo sát kỹ hiện trạng kết cấu, lập bảng dự toán chi tiết từng hạng mục từ tháo dỡ, xây tô, chống thấm, điện nước đến sơn hoàn thiện để khách hàng dễ dàng kiểm soát ngân sách mà không lo phát sinh.'
            },
            {
                imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                date: '12/11/2026',
                title: 'Quy trình xử lý chống thấm sân thượng triệt để cho nhà phố mùa mưa Đà Nẵng',
                excerpt: 'Khám phá nguyên nhân gây thấm dột sàn mái và quy trình 3 bước chống thấm bền vững lên đến nhiều năm.',
                content: 'Sân thượng là khu vực chịu tác động trực tiếp của nắng gắt và mưa bão kéo dài tại Đà Nẵng, dễ phát sinh vết nứt co ngót. Để xử lý triệt để, cần mài sạch lớp vữa yếu, bơm keo xử lý vết nứt, quét lót và thi công đủ định mức vật liệu chống thấm 2 thành phần hoặc màng PU đàn hồi, sau đó ngâm nước kiểm tra kỹ lưỡng trong 48 giờ.'
            },
            {
                imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                date: '05/11/2026',
                title: 'Kinh nghiệm chọn sơn chống thấm tường ngoài bền đẹp vững theo thời gian',
                excerpt: 'Cách kết hợp sơn lót kháng kiềm và sơn phủ chống thấm ngoài trời giúp chống rêu mốc và giữ màu sắc tươi mới.',
                content: 'Tường ngoại thất tại khu vực ven biển Đà Nẵng chịu độ ẩm và hơi muối cao. Gia chủ nên ưu tiên hệ thống sơn đồng bộ gồm lớp bả ngoại thất chịu ẩm, 1–2 lớp sơn lót kháng kiềm chất lượng và 2 lớp sơn phủ chống thấm có khả năng co giãn che lấp vết nứt nhỏ, giúp bề mặt tường luôn khô ráo và bền màu.'
            },
            {
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '28/10/2026',
                title: 'Những hạng mục cần kiểm tra trước khi cải tạo, nâng tầng nhà phố cũ',
                excerpt: 'Đánh giá kết cấu móng, cột chịu lực và hệ thống thoát nước để đảm bảo an toàn tuyệt đối khi cải tạo nhà ở.',
                content: 'Trước khi nâng tầng hoặc thay đổi công năng không gian, việc kiểm tra hiện trạng móng, dầm, cột và đường ống kỹ thuật là bước tối quan trọng. Đội ngũ kỹ sư Tân Nam luôn khảo sát đo đạc trực tiếp, tư vấn giải pháp gia cố phù hợp giúp công trình vừa bền vững vừa tối ưu chi phí đầu tư.'
            }
        ];

        /* -------------------------------------------------------------------
         * 4. HÀM HIỂN THỊ DANH SÁCH DỊCH VỤ (2 CỘT TRÊN MOBILE, KHÔNG CẮT CHỮ)
         * ------------------------------------------------------------------- */
        function renderServices(filterKey) {
            const container = document.getElementById('services-grid');
            if (!container) return;

            const filtered = filterKey === 'all'
                ? servicesData
                : servicesData.filter(function(item) { return item.category === filterKey; });

            container.innerHTML = filtered.map(function(item, idx) {
                return `
                    <article onclick="openServiceModal('${item.id}')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition-all flex flex-col">
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img
                                src="${getDriveImgUrl(item.id, 800)}"
                                data-drive-id="${item.id}"
                                onerror="handleDriveImageError(this, 'Xay Dung Tan Nam')"
                                alt="${item.title}"
                                loading="lazy"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            >
                        </div>
                        <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <h3 class="text-[13px] sm:text-[15px] font-bold text-brand-navy group-hover:text-brand-accent transition-colors leading-snug break-words">
                                    ${item.title}
                                </h3>
                                <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                    ${item.summary}
                                </p>
                            </div>
                            <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11.5px] sm:text-xs font-semibold text-brand-blue">
                                <span>Xem chi tiết</span>
                                <span aria-hidden="true">&rarr;</span>
                            </div>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterServices(filterKey) {
            renderServices(filterKey);
            const tabs = document.querySelectorAll('.service-tab');
            tabs.forEach(function(btn) {
                const isActive = btn.getAttribute('data-filter') === filterKey;
                if (isActive) {
                    btn.className = 'service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-navy text-white transition-colors';
                } else {
                    btn.className = 'service-tab px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-navy transition-colors';
                }
            });
        }

        /* -------------------------------------------------------------------
         * 5. HÀM HIỂN THỊ 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
         * ------------------------------------------------------------------- */
        function renderProjects() {
            const container = document.getElementById('projects-grid');
            if (!container) return;

            container.innerHTML = projectsData.map(function(proj) {
                return `
                    <article onclick="openProjectModal('${proj.id}')" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition-all flex flex-col">
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img
                                src="${getDriveImgUrl(proj.id, 700)}"
                                data-drive-id="${proj.id}"
                                onerror="handleDriveImageError(this, 'Du An Da Nang')"
                                alt="${proj.title}"
                                loading="lazy"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                            <h3 class="text-[12.5px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-accent transition-colors leading-snug break-words">
                                ${proj.title}
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">${proj.location}</p>
                        </div>
                    </article>
                `;
            }).join('');
        }

        /* -------------------------------------------------------------------
         * 6. HÀM HIỂN THỊ CÁC BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        function renderArticles() {
            const container = document.getElementById('articles-grid');
            if (!container) return;

            container.innerHTML = articlesData.map(function(art, index) {
                return `
                    <article onclick="openArticleModal(${index})" class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition-all flex flex-col">
                        <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img
                                src="${getDriveImgUrl(art.imgId, 700)}"
                                data-drive-id="${art.imgId}"
                                onerror="handleDriveImageError(this, 'Tin Tuc Xay Dung')"
                                alt="${art.title}"
                                loading="lazy"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
                            >
                        </div>
                        <div class="p-4 flex-1 flex flex-col justify-between">
                            <div>
                                <div class="text-[11px] text-slate-400 font-medium mb-1.5">${art.date}</div>
                                <h3 class="text-sm font-bold text-brand-navy group-hover:text-brand-accent transition-colors leading-snug break-words">
                                    ${art.title}
                                </h3>
                                <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                                    ${art.excerpt}
                                </p>
                            </div>
                            <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-brand-blue">
                                Đọc bài viết &rarr;
                            </div>
                        </div>
                    </article>
                `;
            }).join('');
        }

        /* -------------------------------------------------------------------
         * 7. ĐIỀU KHIỂN SLIDER 2 ẢNH BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT MOBILE
         * ------------------------------------------------------------------- */
        let currentSlide = 0;
        const totalSlides = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            const track = document.getElementById('banner-track');
            if (!track) return;
            track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';

            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.className = 'w-7 h-2 rounded-full bg-brand-accent transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
                }
            }
        }

        function moveSlide(step) {
            currentSlide = (currentSlide + step + totalSlides) % totalSlides;
            updateBannerUI();
            resetBannerTimer();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateBannerUI();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function() {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateBannerUI();
            }, 5500);
        }

        /* Hỗ trợ thao tác vuốt cảm ứng trên banner mobile */
        (function setupBannerSwipe() {
            const viewport = document.querySelector('.banner-viewport');
            if (!viewport) return;
            let touchStartX = 0;
            viewport.addEventListener('touchstart', function(e) {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            viewport.addEventListener('touchend', function(e) {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 45) {
                    moveSlide(diff < 0 ? 1 : -1);
                }
            }, { passive: true });
        })();

        /* -------------------------------------------------------------------
         * 8. ĐIỀU KHIỂN MENU MOBILE & MODAL XEM CHI TIẾT
         * ------------------------------------------------------------------- */
        const mobileBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const iconOpen = document.getElementById('menu-icon-open');
        const iconClose = document.getElementById('menu-icon-close');

        function closeMobileMenu() {
            if (mobileMenu) mobileMenu.classList.add('hidden');
            if (iconOpen) iconOpen.classList.remove('hidden');
            if (iconClose) iconClose.classList.add('hidden');
        }

        if (mobileBtn) {
            mobileBtn.addEventListener('click', function() {
                const isHidden = mobileMenu.classList.contains('hidden');
                if (isHidden) {
                    mobileMenu.classList.remove('hidden');
                    iconOpen.classList.add('hidden');
                    iconClose.classList.remove('hidden');
                } else {
                    closeMobileMenu();
                }
            });
        }

        function showModal(title, imgId, bodyHtml) {
            const modal = document.getElementById('detail-modal');
            const mTitle = document.getElementById('modal-title');
            const mImg = document.getElementById('modal-image');
            const mBody = document.getElementById('modal-body');

            mTitle.textContent = title;
            mImg.dataset.attempt = '0';
            mImg.dataset.driveId = imgId;
            mImg.src = getDriveImgUrl(imgId, 1200);
            mImg.alt = title;
            mImg.onerror = function() { handleDriveImageError(this, title); };
            mBody.innerHTML = bodyHtml;

            modal.classList.remove('hidden');
            modal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        function openServiceModal(id) {
            const item = servicesData.find(function(s) { return s.id === id; });
            if (!item) return;
            showModal(
                item.title,
                item.id,
                '<p>' + item.details + '</p><p class="font-semibold text-brand-navy">Cam kết: Khảo sát trực tiếp tại Đà Nẵng, báo giá chi tiết từng hạng mục, thi công chuẩn kỹ thuật và bảo hành lâu dài.</p>'
            );
        }

        function openProjectModal(id) {
            const proj = projectsData.find(function(p) { return p.id === id; });
            if (!proj) return;
            showModal(
                proj.title,
                proj.id,
                '<p><strong>Địa điểm:</strong> ' + proj.location + '</p><p>Công trình thực tế được đội ngũ kỹ sư và thợ lành nghề của <strong>Công Ty TNHH Bảo Trì Xây Dựng Tân Nam</strong> trực tiếp triển khai, nghiệm thu kỹ lưỡng và bàn giao đúng tiến độ cho chủ đầu tư.</p>'
            );
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;
            showModal(
                art.title,
                art.imgId,
                '<p class="text-xs text-slate-400">Ngày đăng: ' + art.date + ' • Xây Dựng Tân Nam</p><p>' + art.content + '</p>'
            );
        }

        /* Đóng modal khi click ra ngoài nền tối hoặc nhấn phím ESC */
        document.getElementById('detail-modal').addEventListener('click', function(e) {
            if (e.target === this) closeModal();
        });
        document.addEventListener('keydown', function(e) {
            if (e.key === 'Escape') closeModal();
        });

        /* -------------------------------------------------------------------
         * 9. XỬ LÝ FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ (KHÔNG DÙNG ALERT)
         * ------------------------------------------------------------------- */
        function selectQuoteCategory(value) {
            const selectEl = document.getElementById('q-service');
            if (selectEl) selectEl.value = value;
        }

        const quoteForm = document.getElementById('quote-form');
        if (quoteForm) {
            quoteForm.addEventListener('submit', function(e) {
                e.preventDefault();
                const name = document.getElementById('q-name').value.trim();
                const phone = document.getElementById('q-phone').value.trim();
                const service = document.getElementById('q-service').value;
                const feedback = document.getElementById('form-feedback');

                if (!name || !phone) {
                    feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư Tân Nam liên hệ báo giá.';
                    feedback.className = 'mb-3 p-3 rounded-lg text-xs font-medium bg-red-50 text-red-700 border border-red-200';
                    return;
                }

                feedback.textContent = 'Cảm ơn ' + name + '! Yêu cầu báo giá hạng mục "' + service + '" đã được ghi nhận. Xây Dựng Tân Nam sẽ liên hệ số ' + phone + ' trong thời gian sớm nhất.';
                feedback.className = 'mb-3 p-3 rounded-lg text-xs font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
                quoteForm.reset();
            });
        }

        /* Khởi chạy giao diện khi trang tải xong */
        window.addEventListener('DOMContentLoaded', function() {
            renderServices('all');
            renderProjects();
            renderArticles();
            resetBannerTimer();
        });
    </script>
</body>
</html>

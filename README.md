<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Header Styling */
        header {
            background-image: url('https://haycafe.vn/wp-content/uploads/2022/08/hinh-anh-sieu-nhan.jpg');
            background-size: cover;
            background-position: center;
            width: 100%;
            min-height: 300px;
            text-align: center;
            padding: 20px;
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease;
            background-color: aqua;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
            color: #ffd700;
            text-shadow: 2px 2px #000;
        }

        nav {
            width: 100%;
            min-height: 500px;
            background-color: black;
        }

        /* Group Logo Styling */
        .logo {
            width: 150px;
            position: relative;
            top: 20%;
            float: left;
        }

        .logo:hover {
            transform: scale(1.1);
        }

        /* Member Section Styling */
        .members {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px 0;
        }

        .member {
            text-align: center;
        }

        .member img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #ffd700;
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.7);
            transition: transform 0.3s;
        }

        .member img:hover {
            transform: scale(1.1);
        }

        .member p {
            margin-top: 10px;
            font-weight: bold;
            color: #ffd700;
        }

        /* Video Section Styling */
        .video-section {
            margin: 20px 0;
            text-align: center;
        }

        .video-section h2 {
            font-size: 2em;
            color: #ffd700;
            margin-bottom: 10px;
            text-shadow: 1px 1px #000;
        }

        .video {
            border: 5px solid #ffd700;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 215, 0, 0.7);
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <!-- Header Section with Logo -->
    <header>
        <h1>CHÀO CÁC DÂN CHƠI ĐÃ ĐI LẠC VÀO WEB CỦA MÌNH</h1>
        <img src="c:\Users\LONGcute\Downloads\Thiết kế chưa có tên.png" alt="Group Logo" class="logo">
    </header>

    <!-- Members Section -->
    <section class="members">
        <div class="member">
            <img src="c:\Users\LONGcute\Pictures\Screenshots\siêu nhân gao yuncos (3)-min.jpg" alt="Member 1">
            <p>HỌ VÀ TÊN: LÊ TẤN TRẦN LONG</p>
            <p>LỚP: K48_D</p>
            <p>SỞ THÍCH: CHƠI GAME, VÂN VÂN....BLA BLA</p>
        </div>
        <div class="member">
            <img src="c:\Users\LONGcute\Pictures\Screenshots\09ca66ba-f8a0-48ad-af32-ab67d5007490-1531714507245812030734.jpg" alt="Member 2">
            <p>HỌ VÀ TÊN: LÊ ANH TÚ</p>
            <p>LỚP: K48_D</p>
            <p>SỞ THÍCH: CHƠI GAME, chơi đá banh.</p>
        </div>
        <div class="member">
            <img src="c:\Users\LONGcute\Pictures\Screenshots\siêu nhân gao yuncos (11)-min.jpg" alt="Member 3">
            <p>HỌ VÀ TÊN: TRẦN NGỌC HÂN</p>
            <p>LỚP: K48_D</p>
            <p>SỞ THÍCH: ĂN VÀ NGỦ.</p>
        </div>
        <div class="member">
            <img src="c:\Users\LONGcute\Pictures\Screenshots\78f9386500fa95c47f6c99b0554ff5d5.jpg" alt="Member 4">
            <p>HỌ VÀ TÊN: LÊ TẤN TÀI</p>
            <p>LỚP: K48_D</p>
            <p>SỞ THÍCH: đi du lịch,...</p>
        </div>
        <div class="member">
            <img src="c:\Users\LONGcute\Pictures\Screenshots\789c0ab7853a62faa62fbff2e8ccc629.jpg" alt="Member 5">
            <p>HỌ VÀ TÊN: NGUYỄN VĂN THẠC SĨ</p>
            <p>LỚP: K48_D</p>
            <p>SỞ THÍCH: chơi game, khám phá những thứ mới mẻ</p>
        </div>
    </section>

    <!-- Video Section -->
    <section class="video-section">
        <h2>MỜI CÁC DÂN CHƠI DỪNG CHÂN XEM SIÊU NHÂN CÙNG AE CHÚNG TÔI :)</h2>
        <video class="video" width="400" controls>
            <source src="c:\Users\LONGcute\Downloads\Siêu nhân Gao - Biến hình.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

</body>
</html>

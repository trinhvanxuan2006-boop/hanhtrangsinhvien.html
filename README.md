# hanhtrangsinhvien.html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Trang Web Sinh Viên</title>
</head>

<body>

    <!-- Banner -->
    <header style="background-color: #2c5364; color: white; text-align: center; padding: 20px;">
        <h1 style="font-family: Arial;">HÀNH TRANG SINH VIÊN 4.0</h1>

        <img src="../IMAGE/anh4.png" 
     style="width: 100%; display: block; height: auto;">
    </header>

    <!-- Menu -->
    <nav style="background: #333; padding: 10px; text-align: center;">
        <a href="#home" style="margin: 10px; color: white;">Trang chủ</a>
        <a href="#about" style="margin: 10px; color: white;">Giới thiệu</a>
        <a href="#news" style="margin: 10px; color: white;">Tin tức</a>
        <a href="#contact" style="margin: 10px; color: white;">Liên hệ</a>
    </nav>

    <!-- Nội dung chính -->
    <main style="display: flex;">

        <!-- Sidebar -->
        <aside style="width: 25%; background: #cccccc; padding: 15px;">
            <h3>Đăng nhập</h3>

            <form>
                <label>Tên đăng nhập:</label><br>
                <input type="text" required><br><br>

                <label>Mật khẩu:</label><br>
                <input type="password" required><br><br>

                <input type="submit" value="Đăng nhập">
            </form>
        </aside>

        <!-- Body Area -->
        <section style="width: 75%; padding: 15px;">

            <!-- Bài viết 1 -->
            <article>
                <h2>Công nghệ trong cuộc sống hiện đại</h2>
              <img src="../IMAGE/anh3.png" width="100%" height="350px" object-fit:cover; >
                <p>
                    Công nghệ ngày nay đóng vai trò vô cùng quan trọng trong cuộc sống. 
                    Từ việc học tập, làm việc đến giải trí, tất cả đều có sự hỗ trợ của các thiết bị thông minh. 
                    Nhờ có internet, con người có thể kết nối với nhau một cách nhanh chóng và thuận tiện hơn bao giờ hết.
                </p><br><br>
            </article>

            <!-- Bài viết 2 -->
            <article>
                <h2>Lợi ích của việc học lập trình</h2>
                <img src="https://via.placeholder.com/300x150">
                <p>
                    Học lập trình không chỉ giúp bạn có thêm một kỹ năng quan trọng mà còn rèn luyện tư duy logic. 
                    Trong thời đại số, lập trình là một trong những ngành nghề có nhu cầu cao và mức thu nhập hấp dẫn. 
                    Ngoài ra, lập trình còn giúp bạn tự tạo ra các sản phẩm công nghệ phục vụ cho công việc và cuộc sống.
                </p>
            </article>

            <!-- Bài viết 3 -->
            <article>
                <h2>Tầm quan trọng của kỹ năng mềm</h2>
                <img src="https://via.placeholder.com/300x150">
                <p>
                    Bên cạnh kiến thức chuyên môn, kỹ năng mềm là yếu tố giúp mỗi người thành công hơn trong học tập và công việc. 
                    Các kỹ năng như giao tiếp, làm việc nhóm, quản lý thời gian giúp bạn thích nghi tốt với môi trường xung quanh. 
                    Việc rèn luyện kỹ năng mềm ngay từ khi còn là sinh viên sẽ mang lại nhiều lợi ích trong tương lai.
                </p>
</article>
        </section>

    </main>

    <!-- Footer -->
    <footer style="background: lightgray; text-align: center; padding: 15px;">
        <p>Họ tên sinh viên – Lớp</p>
    </footer>

</body>
</html>

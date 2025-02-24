<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form Hỗ Trợ Kỹ Thuật</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #6a11cb, #2575fc); /* Thêm background gradient */
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            font-size: 24px;
            color: #333;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            font-size: 16px;
            color: #555;
            display: block;
            margin-bottom: 5px;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #f9f9f9;
            color: #333;
            box-sizing: border-box;
        }
        textarea {
            resize: vertical;
            height: 150px;
        }
        button {
            width: 100%;
            padding: 12px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #0056b3;
        }
        .priority-select, .department-select {
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Form Hỗ Trợ Kỹ Thuật</h2>
    <form action="#" method="POST">
        <form action="https://script.google.com/macros/s/YOUR_SCRIPT_URL/exec" method="POST">
            <div class="form-group">
                <label for="name">Tên Người Yêu Cầu</label>
                <input type="text" id="name" name="name" required placeholder="Nhập tên của bạn">
            </div>
            <div class="form-group">
                <label for="phone">Số Điện Thoại</label>
                <input type="text" id="phone" name="phone" required placeholder="Nhập số điện thoại">
            </div>
            <div class="form-group">
                <label for="problem">Mô Tả Vấn Đề</label>
                <textarea id="problem" name="problem" required placeholder="Mô tả chi tiết vấn đề bạn gặp phải"></textarea>
            </div>
            <div class="form-group">
                <label for="priority">Độ Ưu Tiên</label>
                <select id="priority" name="priority" required>
                    <option value="high">Cao</option>
                    <option value="medium">Trung Bình</option>
                    <option value="low">Thấp</option>
                </select>
            </div>
            <div class="form-group">
                <label for="department">Tổ (Bộ Phận)</label>
                <select id="department" name="department" required>
                    <option value="support_team">Tổ Hỗ Trợ</option>
                    <option value="import_team">Tổ Nhập Hàng</option>
                    <option value="export_team">Tổ Xuất Hàng</option>
                    <option value="accounting_team">Tổ Kế Toán</option>
                    <option value="transport_team">Tổ Điều Vận</option>
                </select>
            </div>
            <div class="form-group">
                <label for="request_date">Ngày Yêu Cầu</label>
                <input type="date" id="request_date" name="request_date" required>
            </div>
            <div class="form-group">
                <label for="completion_date">Ngày Kết Thúc</label>
                <input type="date" id="completion_date" name="completion_date" required>
            </div>
            <button type="submit">Gửi Yêu Cầu</button>
          </form>
          
</html>

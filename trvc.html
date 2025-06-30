<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checksheet Quản Lý Máy Tính Phòng Họp</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        
        .header {
            text-align: center;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .header h1 {
            margin: 0;
            font-size: 28px;
        }
        
        .header p {
            margin: 5px 0 0 0;
            opacity: 0.9;
        }
        
        .computer-section {
            background: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 30px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .computer-title {
            background: linear-gradient(45deg, #ff6b6b, #ff8e8e);
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin: -20px -20px 20px -20px;
            font-size: 20px;
            font-weight: bold;
            text-align: center;
        }
        
        .computer-section:nth-child(3) .computer-title {
            background: linear-gradient(45deg, #4ecdc4, #44a08d);
        }
        
        .status-section {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
            align-items: center;
        }
        
        .status-box {
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: bold;
            text-align: center;
            min-width: 120px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .status-available {
            background-color: #d4edda;
            color: #155724;
            border: 2px solid #c3e6cb;
        }
        
        .status-in-use {
            background-color: #f8d7da;
            color: #721c24;
            border: 2px solid #f5c6cb;
        }
        
        .borrow-form {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        
        .form-row {
            display: flex;
            gap: 15px;
            margin-bottom: 15px;
            align-items: center;
            flex-wrap: wrap;
        }
        
        .form-group {
            flex: 1;
            min-width: 200px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #333;
        }
        
        .form-group input, .form-group select {
            width: 100%;
            padding: 8px 12px;
            border: 2px solid #ddd;
            border-radius: 5px;
            font-size: 14px;
            transition: border-color 0.3s ease;
        }
        
        .form-group input:focus, .form-group select:focus {
            outline: none;
            border-color: #667eea;
        }
        
        .btn {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            margin-right: 10px;
        }
        
        .btn-borrow {
            background-color: #28a745;
            color: white;
        }
        
        .btn-borrow:hover {
            background-color: #218838;
            transform: translateY(-2px);
        }
        
        .btn-return {
            background-color: #dc3545;
            color: white;
        }
        
        .btn-return:hover {
            background-color: #c82333;
            transform: translateY(-2px);
        }
        
        .current-user {
            background: #e9ecef;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #667eea;
        }
        
        .current-user h4 {
            margin: 0 0 10px 0;
            color: #667eea;
        }
        
        .current-user p {
            margin: 5px 0;
            color: #333;
        }
        
        .history-section {
            margin-top: 20px;
        }
        
        .history-title {
            background: #6c757d;
            color: white;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        
        .history-list {
            max-height: 200px;
            overflow-y: auto;
            background: #f8f9fa;
            border-radius: 5px;
            padding: 10px;
        }
        
        .history-item {
            padding: 8px;
            border-bottom: 1px solid #dee2e6;
            font-size: 14px;
        }
        
        .history-item:last-child {
            border-bottom: none;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: #e9ecef;
            border-radius: 10px;
            color: #6c757d;
        }
        
        @media (max-width: 768px) {
            .form-row {
                flex-direction: column;
            }
            
            .form-group {
                min-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>📊 CHECKSHEET QUẢN LÝ MÁY TÍNH PHÒNG HỌP</h1>
        <p>Vui lòng ghi đầy đủ thông tin khi mượn và trả máy tính</p>
    </div>

    <!-- Máy tính 1 -->
    <div class="computer-section">
        <div class="computer-title">
            💻 MÁY TÍNH 1
        </div>
        
        <div class="status-section">
            <div class="status-box status-available" id="status1">
                ✅ ĐANG RẢNH
            </div>
            <div style="flex: 1; text-align: right;">
                <button class="btn btn-borrow" onclick="toggleBorrowForm(1)">Mượn máy</button>
                <button class="btn btn-return" onclick="returnComputer(1)" style="display: none;" id="returnBtn1">Trả máy</button>
            </div>
        </div>

        <div class="borrow-form" id="borrowForm1" style="display: none;">
            <div class="form-row">
                <div class="form-group">
                    <label>Họ và tên:</label>
                    <input type="text" id="name1" placeholder="Nhập họ tên">
                </div>
                <div class="form-group">
                    <label>Phòng ban:</label>
                    <select id="department1">
                        <option value="">Chọn phòng ban</option>
                        <option value="Hành chính">Hành chính</option>
                        <option value="Kế toán">Kế toán</option>
                        <option value="Kinh doanh">Kinh doanh</option>
                        <option value="Kỹ thuật">Kỹ thuật</option>
                        <option value="Marketing">Marketing</option>
                        <option value="Nhân sự">Nhân sự</option>
                        <option value="Khác">Khác</option>
                    </select>
                </div>
            </div>
            <div class="form-row">
                <div class="form-group">
                    <label>Mục đích sử dụng:</label>
                    <input type="text" id="purpose1" placeholder="VD: Họp với khách hàng, thuyết trình...">
                </div>
                <div class="form-group">
                    <label>Dự kiến trả máy:</label>
                    <input type="datetime-local" id="returnTime1">
                </div>
            </div>
            <button class="btn btn-borrow" onclick="borrowComputer(1)">Xác nhận mượn</button>
        </div>

        <div class="current-user" id="currentUser1" style="display: none;">
            <h4>Người đang sử dụng:</h4>
            <p><strong>Tên:</strong> <span id="currentName1"></span></p>
            <p><strong>Phòng ban:</strong> <span id="currentDept1"></span></p>
            <p><strong>Mục đích:</strong> <span id="currentPurpose1"></span></p>
            <p><strong>Thời gian mượn:</strong> <span id="borrowTime1"></span></p>
            <p><strong>Dự kiến trả:</strong> <span id="expectedReturn1"></span></p>
        </div>

        <div class="history-section">
            <div class="history-title">📋 Lịch sử sử dụng hôm nay</div>
            <div class="history-list" id="history1">
                <div class="history-item">Chưa có ai sử dụng hôm nay</div>
            </div>
        </div>
    </div>

    <!-- Máy tính 2 -->
    <div class="computer-section">
        <div class="computer-title">
            💻 MÁY TÍNH 2
        </div>
        
        <div class="status-section">
            <div class="status-box status-available" id="status2">
                ✅ ĐANG RẢNH
            </div>
            <div style="flex: 1; text-align: right;">
                <button class="btn btn-borrow" onclick="toggleBorrowForm(2)">Mượn máy</button>
                <button class="btn btn-return" onclick="returnComputer(2)" style="display: none;" id="returnBtn2">Trả máy</button>
            </div>
        </div>

        <div class="borrow-form" id="borrowForm2" style="display: none;">
            <div class="form-row">
                <div class="form-group">
                    <label>Họ và tên:</label>
                    <input type="text" id="name2" placeholder="Nhập họ tên">
                </div>
                <div class="form-group">
                    <label>Phòng ban:</label>
                    <select id="department2">
                        <option value="">Chọn phòng ban</option>
                        <option value="Hành chính">Hành chính</option>
                        <option value="Kế toán">Kế toán</option>
                        <option value="Kinh doanh">Kinh doanh</option>
                        <option value="Kỹ thuật">Kỹ thuật</option>
                        <option value="Marketing">Marketing</option>
                        <option value="Nhân sự">Nhân sự</option>
                        <option value="Khác">Khác</option>
                    </select>
                </div>
            </div>
            <div class="form-row">
                <div class="form-group">
                    <label>Mục đích sử dụng:</label>
                    <input type="text" id="purpose2" placeholder="VD: Họp với khách hàng, thuyết trình...">
                </div>
                <div class="form-group">
                    <label>Dự kiến trả máy:</label>
                    <input type="datetime-local" id="returnTime2">
                </div>
            </div>
            <button class="btn btn-borrow" onclick="borrowComputer(2)">Xác nhận mượn</button>
        </div>

        <div class="current-user" id="currentUser2" style="display: none;">
            <h4>Người đang sử dụng:</h4>
            <p><strong>Tên:</strong> <span id="currentName2"></span></p>
            <p><strong>Phòng ban:</strong> <span id="currentDept2"></span></p>
            <p><strong>Mục đích:</strong> <span id="currentPurpose2"></span></p>
            <p><strong>Thời gian mượn:</strong> <span id="borrowTime2"></span></p>
            <p><strong>Dự kiến trả:</strong> <span id="expectedReturn2"></span></p>
        </div>

        <div class="history-section">
            <div class="history-title">📋 Lịch sử sử dụng hôm nay</div>
            <div class="history-list" id="history2">
                <div class="history-item">Chưa có ai sử dụng hôm nay</div>
            </div>
        </div>
    </div>

    <div class="footer">
        <p><strong>Lưu ý:</strong> Vui lòng ghi đầy đủ thông tin và trả máy đúng thời gian đã cam kết</p>
        <p>📞 Liên hệ IT Support: Ext. 1234 | 📧 Email: it@company.com</p>
    </div>

    <script>
        // Dữ liệu lưu trữ tạm thời
        let computerData = {
            1: { isInUse: false, currentUser: null, history: [] },
            2: { isInUse: false, currentUser: null, history: [] }
        };

        function toggleBorrowForm(computerId) {
            const form = document.getElementById(`borrowForm${computerId}`);
            form.style.display = form.style.display === 'none' ? 'block' : 'none';
        }

        function borrowComputer(computerId) {
            const name = document.getElementById(`name${computerId}`).value;
            const department = document.getElementById(`department${computerId}`).value;
            const purpose = document.getElementById(`purpose${computerId}`).value;
            const returnTime = document.getElementById(`returnTime${computerId}`).value;

            if (!name || !department || !purpose || !returnTime) {
                alert('Vui lòng điền đầy đủ thông tin!');
                return;
            }

            const now = new Date();
            const borrowTime = now.toLocaleString('vi-VN');

            // Cập nhật trạng thái
            computerData[computerId].isInUse = true;
            computerData[computerId].currentUser = {
                name: name,
                department: department,
                purpose: purpose,
                borrowTime: borrowTime,
                returnTime: new Date(returnTime).toLocaleString('vi-VN')
            };

            // Cập nhật giao diện
            updateComputerStatus(computerId);
            
            // Thêm vào lịch sử
            addToHistory(computerId, name, department, purpose, borrowTime, 'Mượn máy');

            // Reset form
            document.getElementById(`name${computerId}`).value = '';
            document.getElementById(`department${computerId}`).value = '';
            document.getElementById(`purpose${computerId}`).value = '';
            document.getElementById(`returnTime${computerId}`).value = '';
            document.getElementById(`borrowForm${computerId}`).style.display = 'none';

            alert('Đã ghi nhận thông tin mượn máy thành công!');
        }

        function returnComputer(computerId) {
            if (!computerData[computerId].isInUse) return;

            const userData = computerData[computerId].currentUser;
            const returnTime = new Date().toLocaleString('vi-VN');

            // Thêm vào lịch sử
            addToHistory(computerId, userData.name, userData.department, userData.purpose, returnTime, 'Trả máy');

            // Reset trạng thái
            computerData[computerId].isInUse = false;
            computerData[computerId].currentUser = null;

            // Cập nhật giao diện
            updateComputerStatus(computerId);

            alert('Đã ghi nhận trả máy thành công!');
        }

        function updateComputerStatus(computerId) {
            const status = document.getElementById(`status${computerId}`);
            const currentUser = document.getElementById(`currentUser${computerId}`);
            const returnBtn = document.getElementById(`returnBtn${computerId}`);

            if (computerData[computerId].isInUse) {
                status.className = 'status-box status-in-use';
                status.innerHTML = '🔴 ĐANG SỬ DỤNG';
                
                const user = computerData[computerId].currentUser;
                document.getElementById(`currentName${computerId}`).textContent = user.name;
                document.getElementById(`currentDept${computerId}`).textContent = user.department;
                document.getElementById(`currentPurpose${computerId}`).textContent = user.purpose;
                document.getElementById(`borrowTime${computerId}`).textContent = user.borrowTime;
                document.getElementById(`expectedReturn${computerId}`).textContent = user.returnTime;
                
                currentUser.style.display = 'block';
                returnBtn.style.display = 'inline-block';
            } else {
                status.className = 'status-box status-available';
                status.innerHTML = '✅ ĐANG RẢNH';
                currentUser.style.display = 'none';
                returnBtn.style.display = 'none';
            }
        }

        function addToHistory(computerId, name, department, purpose, time, action) {
            const historyContainer = document.getElementById(`history${computerId}`);
            
            if (computerData[computerId].history.length === 0) {
                historyContainer.innerHTML = '';
            }

            const historyItem = document.createElement('div');
            historyItem.className = 'history-item';
            historyItem.innerHTML = `
                <strong>${time}</strong> - ${name} (${department}) - ${action}<br>
                <small>Mục đích: ${purpose}</small>
            `;
            
            historyContainer.insertBefore(historyItem, historyContainer.firstChild);
            computerData[computerId].history.push({
                name, department, purpose, time, action
            });
        }

        // Khởi tạo thời gian mặc định
        document.addEventListener('DOMContentLoaded', function() {
            const now = new Date();
            now.setHours(now.getHours() + 2); // Mặc định 2 tiếng sau
            const defaultTime = now.toISOString().slice(0, 16);
            
            document.getElementById('returnTime1').value = defaultTime;
            document.getElementById('returnTime2').value = defaultTime;
        });
    </script>
</body>
</html>

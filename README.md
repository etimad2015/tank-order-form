# tank-order-form
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نموذج طلب خزانات</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fdfdfd;
            text-align: center;
            padding: 20px;
        }
        h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }
        label {
            font-size: 26px;
            display: block;
            margin: 15px auto 10px;
        }
        #customerName {
            font-size: 26px;
            padding: 10px;
            width: 300px;
            border: 2px solid #000;
            border-radius: 6px;
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 28px;
            margin-top: 20px;
        }
        th, td {
            border: 2px solid #000;
            padding: 15px;
        }
        th {
            background-color: #f4d03f;
        }
        input[type="number"] {
            font-size: 26px;
            width: 80px;
            text-align: center;
            border: 2px solid #333;
            border-radius: 6px;
            padding: 4px;
        }
        .section-header {
            background-color: #58d68d;
            font-weight: bold;
            font-size: 30px;
        }
        .button {
            margin-top: 25px;
            padding: 15px 30px;
            font-size: 26px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            margin-left: 10px;
        }
        .button:hover {
            background-color: #2e86c1;
        }
        .clear-button {
            background-color: #e74c3c;
        }
        .clear-button:hover {
            background-color: #c0392b;
        }
        @media (max-width: 768px) {
            h1 { font-size: 32px; }
            table { font-size: 22px; }
            input[type="number"] { font-size: 20px; width: 60px; }
            .button { font-size: 20px; padding: 10px 20px; }
        }
    </style>
</head>
<body>
    <h1>نموذج طلب خزانات</h1>

    <label for="customerName">اسم الزبون:</label>
    <input type="text" id="customerName" placeholder="أدخل اسم الزبون">

    <table id="tankTable">
        <thead>
            <tr>
                <th>حجم الخزان</th>
                <th>عدد الطبقات</th>
                <th>العدد المطلوب</th>
            </tr>
        </thead>
        <tbody>
            <tr><td colspan="3" class="section-header">خزانات 2 طبقة</td></tr>
            <tr><td>100 لتر أفقي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>200 لتر أفقي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>250 لتر عمودي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>500 لتر أفقي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>500 لتر عمودي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1000 لتر عمودي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1000 لتر أفقي</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1500 لتر</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>2000 لتر</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>3000 لتر</td><td>2 طبقة</td><td><input type="number" min="0"></td></tr>

            <tr><td colspan="3" class="section-header">خزانات 3 طبقة</td></tr>
            <tr><td>500 لتر أفقي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>500 لتر عمودي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1000 لتر عمودي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1000 لتر أفقي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1500 لتر عمودي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>2000 لتر أفقي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>2000 لتر عمودي</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>3000 لتر</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>5000 لتر</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>10,000 لتر</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>20,000 لتر</td><td>3 طبقة</td><td><input type="number" min="0"></td></tr>

            <tr><td colspan="3" class="section-header">خزانات 4 طبقة</td></tr>
            <tr><td>10,000 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>5000 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>3000 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>2000 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1500 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
            <tr><td>1000 لتر</td><td>4 طبقة</td><td><input type="number" min="0"></td></tr>
        </tbody>
    </table>

    <button class="button" onclick="captureImage()">حفظ كصورة</button>
    <button class="button clear-button" onclick="clearForm()">مسح البيانات</button>

    <script src="https://html2canvas.hertzen.com/dist/html2canvas.min.js"></script>
    <script>
        function captureImage() {
            const customerNameField = document.querySelector("#customerName");
            const customerName = customerNameField.value || 'طلب-خزانات';
            
            // تجميد الحقول مؤقتاً
            customerNameField.setAttribute("readonly", true);
            const numberInputs = document.querySelectorAll('input[type="number"]');
            numberInputs.forEach(input => input.setAttribute("readonly", true));
            
            html2canvas(document.body, { 
                scale: 2,
                useCORS: true,
                allowTaint: false,
                backgroundColor: '#fdfdfd'
            }).then(function(canvas) {
                const imgData = canvas.toDataURL('image/png');
                
                // للآيفون والأجهزة المحمولة
                if (navigator.userAgent.match(/(iPhone|iPad|iPod|Android)/)) {
                    const newWindow = window.open();
                    newWindow.document.write(`
                        <html dir="rtl">
                        <head>
                            <title>حفظ الصورة - ${customerName}</title>
                            <meta name="viewport" content="width=device-width, initial-scale=1.0">
                            <style>
                                body { margin:0; text-align:center; font-family:Arial; padding:20px; }
                                h3 { color:#333; margin-bottom:20px; }
                                img { max-width:100%; height:auto; border:1px solid #ddd; }
                            </style>
                        </head>
                        <body>
                        <h3>اضغط مطولاً على الصورة واختر "حفظ الصورة"</h3>
                        <img src="${imgData}" alt="نموذج طلب الخزانات - ${customerName}">
                        </body>
                        </html>
                    `);
                } else {
                    // للأجهزة الأخرى - التحميل المباشر
                    const link = document.createElement('a');
                    link.download = customerName + '.png';
                    link.href = imgData;
                    document.body.appendChild(link);
                    link.click();
                    document.body.removeChild(link);
                }
                
                // إرجاع الحقول لحالتها الطبيعية
                customerNameField.removeAttribute("readonly");
                numberInputs.forEach(input => input.removeAttribute("readonly"));
                
                // تفريغ النموذج بعد الحفظ
                setTimeout(() => {
                    clearForm();
                }, 1000);
                
            }).catch(function(error) {
                console.error('خطأ في حفظ الصورة:', error);
                alert('حدث خطأ في حفظ الصورة. يرجى المحاولة مرة أخرى.');
                customerNameField.removeAttribute("readonly");
                numberInputs.forEach(input => input.removeAttribute("readonly"));
            });
        }
        
        function clearForm() {
            // تفريغ اسم الزبون
            document.querySelector("#customerName").value = "";
            
            // تفريغ جميع حقول الأعداد
            const numberInputs = document.querySelectorAll('input[type="number"]');
            numberInputs.forEach(input => {
                input.value = "";
            });
            
            console.log("تم مسح جميع البيانات");
        }
        
        // تحسين التجربة على الأجهزة المحمولة
        document.addEventListener('DOMContentLoaded', function() {
            // منع التكبير عند النقر على الحقول في iOS
            document.addEventListener('touchstart', function(e) {
                if (e.target.tagName === 'INPUT') {
                    e.target.style.fontSize = '16px';
                }
            });
        });
    </script>
</body>
</html>
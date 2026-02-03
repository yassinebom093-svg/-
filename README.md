<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الملابس النسائية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ff69b4;
            color: white;
            padding: 20px;
        }
        .product {
            display: inline-block;
            margin: 20px;
            padding: 10px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 250px;
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #ff1493;
        }
    </style>
</head>
<body>
    <header>
        <h1>متجر الملابس النسائية الأنيقة</h1>
        <p>اكتشفي أحدث التصاميم للنساء!</p>
    </header>
    
    <section>
        <h2>منتجاتنا</h2>
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=فستان+أحمر" alt="فستان أحمر">
            <h3>فستان أحمر أنيق</h3>
            <p>سعر: 150 ريال</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=بلوزة+زرقاء" alt="بلوزة زرقاء">
            <h3>بلوزة زرقاء عصرية</h3>
            <p>سعر: 100 ريال</p>
            <button>إضافة إلى السلة</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=بنطال+أسود" alt="بنطال أسود">
            <h3>بنطال أسود مريح</h3>
            <p>سعر: 120 ريال</p>
            <button>إضافة إلى السلة</button>
        </div>
    </section>
    
    <footer>
        <p>© 2023 متجر الملابس. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>

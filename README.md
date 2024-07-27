# Store-Books
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مبيعات الكتب</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap');
        body {
            font-family: 'Cairo', sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #ff6347 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background: #28a745; /* أخضر */
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        section {
            padding: 20px;
            margin: 20px 0;
        }
        .books {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .book {
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 20px;
            padding: 20px;
            width: 30%;
            text-align: center;
            color: #fff;
        }
        .book:nth-child(1) {
            background-color: #ff6347; /* أحمر */
        }
        .book:nth-child(2) {
            background-color: #ffc107; /* أصفر */
        }
        .book:nth-child(3) {
            background-color: #28a745; /* أخضر */
        }
        .book:nth-child(4) {
            background-color: #17a2b8; /* أزرق */
        }
        .book:nth-child(5) {
            background-color: #6f42c1; /* بنفسجي */
        }
        .book:nth-child(6) {
            background-color: #e83e8c; /* وردي */
        }
        .book h3 {
            margin-bottom: 10px;
        }
        .book p {
            color: #f0f0f0;
        }
        .book span {
            display: block;
            margin-top: 10px;
            font-size: 18px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: auto;
        }
        .contact-form label {
            margin-bottom: 5px;
        }
        .contact-form input,
        .contact-form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .contact-form input[type="submit"] {
            background: #ff6347;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        .contact-form input[type="submit"]:hover {
            background: #e5533d;
        }
        .order-status {
            background: #ffc107;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            margin: 20px 0;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>مبيعات الكتب</h1>
            <nav>
                <ul>
                    <li><a href="#home">الرئيسية</a></li>
                    <li><a href="#books">الكتب</a></li>
                    <li><a href="#contact">اتصل بنا</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>مرحباً بكم في متجر الكتب</h1>
            <p>نقدم لكم أفضل الكتب بأفضل الأسعار</p>
        </div>
    </section>
    <section class="books" id="books">
        <div class="container">
            <h2>كتبنا</h2>
            <div class="book">
                <h3>مغامرات لا تنتهي</h3>
                <p>كتاب أكشن مشوق مليء بالمغامرات والإثارة.</p>
                <span>السعر: 50 ريال</span>
            </div>
            <div class="book">
                <h3>قصة حب</h3>
                <p>رواية رومانسية تأخذك في رحلة من العواطف.</p>
                <span>السعر: 70 ريال</span>
            </div>
            <div class="book">
                <h3>البحث عن الكنز</h3>
                <p>مغامرة ممتعة مليئة بالأحداث الشيقة.</p>
                <span>السعر: 100 ريال</span>
            </div>
            <div class="book">
                <h3>فجر الأبطال</h3>
                <p>قصة ملحمية تتحدث عن الأبطال والأشرار.</p>
                <span>السعر: 60 ريال</span>
            </div>
            <div class="book">
                <h3>رحلة عبر الزمن</h3>
                <p>رواية خيالية تأخذك في مغامرة عبر العصور.</p>
                <span>السعر: 80 ريال</span>
            </div>
            <div class="book">
                <h3>أسرار الظلام</h3>
                <p>رواية غامضة تكتشف أسرار الماضي.</p>
                <span>السعر: 90 ريال</span>
            </div>
        </div>
    </section>
    <section class="order-status">
        <div class="container">
            <h2>الحالة الحالية للطلبات</h2>
            <p>تم شراء <strong>كتاب مغامرات لا تنتهي</strong> بواسطة <strong>محمد العلي</strong>.</p>
        </div>
    </section>
    <section class="contact" id="contact">
        <div class="container">
            <h2>اتصل بنا</h2>
            <form class="contact-form">
                <label for="name">الاسم</label>
                <input type="text" id="name" name="name" placeholder="أدخل اسمك" required>
                
                <label for="email">البريد الإلكتروني</label>
                <input type="email" id="email" name="email" placeholder="أدخل بريدك الإلكتروني" required>
                
                <label for="phone">رقم الهاتف</label>
                <input type="tel" id="phone" name="phone" placeholder="أدخل رقم هاتفك" required>
                
                <label for="message">الرسالة</label>
                <textarea id="message" name="message" placeholder="أدخل رسالتك" rows="4" required></textarea>
                
                <input type="submit" value="إرسال">
            </form>
        </div>
    </section>
    <footer>
        <p>حقوق النشر &copy; 2024 مبيعات الكتب</p>
    </footer>
</body>
</html>

- 👋 Hi, I’m @Saeed1870056493
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Saeed1870056493/Saeed1870056493 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>ثبت‌نام راننده | موون‌بار</title>
  <style>
    body {
      direction: rtl;
      font-family: sans-serif;
      text-align: center;
      padding: 30px;
      background-color: #f9f9f9;
    }
    form {
      max-width: 400px;
      margin: auto;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px #ccc;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      padding: 10px 20px;
      background-color: #28a745;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h2>ثبت‌نام راننده</h2>
  <form>
    <input type="text" placeholder="نام و نام خانوادگی" required />
    <input type="tel" placeholder="شماره موبایل" required />
    <input type="text" placeholder="شماره پلاک" required />
    
    <select required>
      <option value="">نوع وسیله نقلیه</option>
      <option value="vanet">وانت</option>
      <option value="3ton">۳ تن</option>
      <option value="5ton">۵ تن</option>
      <option value="tir">تریلی</option>
    </select>

    <input type="file" accept="image/*" />

    <button type="submit">ثبت‌نام</button>
  </form>
</body>
</html>

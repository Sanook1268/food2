<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>เด็กเส้น & เด็กข้าว | Street Food, High Energy!</title>
  <style>
    :root {
      --bg: #0d0d0d;
      --card-bg: #18181b;
      --primary: #ff3366;
      --secondary: #00f0ff;
      --accent: #ffe600;
      --text: #f4f4f5;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Kanit', system-ui, -apple-system, sans-serif;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }

    header {
      text-align: center;
      margin: 40px 0 20px;
    }

    h1 {
      font-size: 3rem;
      font-weight: 900;
      text-transform: uppercase;
      background: linear-gradient(45deg, var(--primary), var(--secondary));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 20px rgba(255, 51, 102, 0.4);
      letter-spacing: 2px;
    }

    p.subtitle {
      color: #a1a1aa;
      font-size: 1.1rem;
      margin-top: 8px;
    }

    .badge {
      display: inline-block;
      background: var(--accent);
      color: #000;
      font-weight: bold;
      padding: 4px 12px;
      border-radius: 20px;
      margin-top: 12px;
      transform: rotate(-2deg);
    }

    .menu-container {
      width: 100%;
      max-width: 600px;
      margin-top: 20px;
      display: flex;
      flex-direction: column;
      gap: 16px;
    }

    .menu-card {
      background: var(--card-bg);
      border: 1px solid #27272a;
      border-radius: 16px;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      transition: all 0.2s ease;
      position: relative;
      overflow: hidden;
    }

    .menu-card:hover {
      transform: translateY(-3px);
      border-color: var(--secondary);
      box-shadow: 0 8px 20px rgba(0, 240, 255, 0.15);
    }

    .menu-info {
      display: flex;
      flex-direction: column;
      gap: 6px;
    }

    .menu-title {
      font-size: 1.25rem;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .menu-desc {
      font-size: 0.9rem;
      color: #a1a1aa;
    }

    .price {
      font-size: 1.5rem;
      font-weight: 800;
      color: var(--accent);
      white-space: nowrap;
    }

    .tag-hot {
      background: var(--primary);
      color: #fff;
      font-size: 0.7rem;
      padding: 2px 6px;
      border-radius: 4px;
      font-weight: normal;
    }

    footer {
      margin-top: auto;
      padding: 40px 0 20px;
      text-align: center;
      color: #71717a;
      font-size: 0.85rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>เด็กเส้น & เด็กข้าว</h1>
    <p class="subtitle">ตามสั่งสายลุย เครื่องแน่น ไม่กั๊ก</p>
    <div class="badge">🔥 โคตรหิวต้องจัด!</div>
  </header>

  <main class="menu-container">

    <div class="menu-card">
      <div class="menu-info">
        <div class="menu-title">
          กะเพราเนื้อสับไข่ดาวระเบิด <span class="tag-hot">BEST</span>
        </div>
        <div class="menu-desc">พริกแห้งเข้มข้น หอมกลิ่นกระทะ ไม่ใส่ถั่วฝักยาว!</div>
      </div>
      <div class="price">฿69</div>
    </div>

    <div class="menu-card">
      <div class="menu-info">
        <div class="menu-title">ข้าวหมูกรอบคั่วพริกเกลือ</div>
        <div class="menu-desc">หมูกรอบหนังกรอบสนั่น คั่วกระเทียมพริกสดสะใจ</div>
      </div>
      <div class="price">฿79</div>
    </div>

    <div class="menu-card">
      <div class="menu-info">
        <div class="menu-title">มาม่าผัดขี้เมาทะเลเดือด</div>
        <div class="menu-desc">กุ้ง-หมึกตัวโต ผัดซอสขี้เมารสจัดจ้านระดับสายแข็ง</div>
      </div>
      <div class="price">฿89</div>
    </div>

    <div class="menu-card">
      <div class="menu-info">
        <div class="menu-title">ข้าวไข่ข้นกุ้งซอสมันกุ้ง</div>
        <div class="menu-desc">ไข่ข้นเยิ้มๆ ราดซอสมันกุ้งเสิร์ฟร้อนๆ โคตรนัว</div>
      </div>
      <div class="price">฿85</div>
    </div>

    <div class="menu-card">
      <div class="menu-info">
        <div class="menu-title">ข้าวไก่กระเทียมพริกไทยดำ</div>
        <div class="menu-desc">เนื้อสะโพกนุ่มๆ กระเทียมเจียวจุกๆ กรอบหอม</div>
      </div>
      <div class="price">฿59</div>
    </div>

  </main>

  <footer>
    <p>📍 หลังมหาลัย ซอย 4 | เปิด 11:00 - 23:00 น.</p>
  </footer>

</body>
</html>

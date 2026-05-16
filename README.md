# Khober-<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>مقارنة بين مكة والخبر</title>

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:Tahoma,sans-serif;
  background:linear-gradient(135deg,#eff6ff,#f8fafc);
  color:#0f172a;
}

.hero{
  height:100vh;
  background:
  linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
  url("https://images.unsplash.com/photo-1580418827493-f2b22c0a76cb?q=80&w=1600&auto=format&fit=crop");
  background-size:cover;
  background-position:center;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:white;
  padding:20px;
}

.hero-content{
  max-width:900px;
}

.hero h1{
  font-size:60px;
  margin-bottom:20px;
}

.hero p{
  font-size:24px;
  line-height:1.9;
}

.container{
  max-width:1200px;
  margin:auto;
  padding:60px 20px;
}

.section-title{
  text-align:center;
  font-size:42px;
  margin-bottom:50px;
  color:#0f172a;
}

.compare-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:30px;
}

.card{
  background:white;
  border-radius:28px;
  overflow:hidden;
  box-shadow:0 15px 35px rgba(0,0,0,.08);
  transition:.3s;
}

.card:hover{
  transform:translateY(-8px);
}

.card img{
  width:100%;
  height:280px;
  object-fit:cover;
}

.card-content{
  padding:30px;
}

.card h2{
  font-size:38px;
  margin-bottom:20px;
}

.card p{
  line-height:2;
  font-size:18px;
  color:#334155;
}

.makkah{
  border-top:10px solid #94a3b8;
}

.khobar{
  border-top:10px solid #06b6d4;
  background:linear-gradient(180deg,#fff,#ecfeff);
}

.features{
  margin-top:25px;
}

.feature{
  background:#f8fafc;
  padding:14px 18px;
  border-radius:14px;
  margin-bottom:12px;
  font-size:16px;
}

.table-section{
  margin-top:80px;
}

table{
  width:100%;
  border-collapse:collapse;
  background:white;
  overflow:hidden;
  border-radius:25px;
  box-shadow:0 10px 30px rgba(0,0,0,.08);
}

th{
  background:#0f172a;
  color:white;
  padding:20px;
  font-size:18px;
}

td{
  padding:20px;
  text-align:center;
  border-bottom:1px solid #e2e8f0;
  font-size:17px;
}

.final{
  margin-top:90px;
  background:
  linear-gradient(135deg,#06b6d4,#3b82f6);
  color:white;
  border-radius:35px;
  padding:60px 30px;
  text-align:center;
  box-shadow:0 20px 40px rgba(0,0,0,.15);
}

.final h1{
  font-size:60px;
  margin-bottom:25px;
}

.final p{
  max-width:900px;
  margin:auto;
  font-size:24px;
  line-height:2.2;
}

.heart{
  font-size:70px;
  margin-bottom:20px;
}

.footer{
  text-align:center;
  padding:30px;
  color:#64748b;
}

@media(max-width:900px){

  .hero h1{
    font-size:42px;
  }

  .hero p{
    font-size:20px;
  }

  .compare-grid{
    grid-template-columns:1fr;
  }

  .final h1{
    font-size:42px;
  }

  .final p{
    font-size:20px;
  }

}

</style>
</head>

<body>

<section class="hero">

  <div class="hero-content">

    <h1>مكة 🕋 VS الخبر 🌊</h1>

    <p>
      مقارنة قوية جدًا بين مدينتين كل وحدة لها جوها الخاص،
      لكن بالنهاية وحدة منهم قدرت تكسب القلب بكل سهولة 😌
    </p>

  </div>

</section>


<div class="container">

  <h1 class="section-title">المقارنة الرسمية 👀</h1>

  <div class="compare-grid">

    <div class="card makkah">

      <img src="https://images.unsplash.com/photo-1591604129939-f1efa4d9f7fa?q=80&w=1200&auto=format&fit=crop">

      <div class="card-content">

        <h2>🕋 مكة</h2>

        <p>
          مكة مدينة عظيمة جدًا ومكانتها كبيرة عند كل المسلمين،
          فيها روحانية وراحة ما تنوصف، وتاريخها عريق جدًا.
          أجواؤها مميزة خصوصًا وقت الصلاة والحرم يكون مليان ناس من كل العالم.
        </p>

        <div class="features">

          <div class="feature">✨ أجواء روحانية جميلة</div>
          <div class="feature">✨ تاريخ عظيم ومكانة كبيرة</div>
          <div class="feature">✨ الحرم المكي من أجمل الأماكن</div>
          <div class="feature">😅 لكن الزحمة والحر أحيانًا تتعب</div>

        </div>

      </div>

    </div>


    <div class="card khobar">

      <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=1200&auto=format&fit=crop">

      <div class="card-content">

        <h2>🌊 الخبر</h2>

        <p>
          الخبر مدينة الراحة والهدوء والجمال،
          بحر وكورنيش وتمشيات وكافيهات وجو يخليك مبسوط طول الوقت.
          فيها إحساس رايق جدًا يخلي الواحد ما يطفش أبدًا.
        </p>

        <div class="features">

          <div class="feature">🌊 البحر والكورنيش شيء ثاني</div>
          <div class="feature">☕ كافيهات وأماكن فخمة</div>
          <div class="feature">🌴 جو هادئ ومرتب</div>
          <div class="feature">🤍 والأهم… فيها شهد</div>

        </div>

      </div>

    </div>

  </div>


  <div class="table-section">

    <h1 class="section-title">مقارنة مباشرة 🔥</h1>

    <table>

      <tr>
        <th>الشيء</th>
        <th>مكة 🕋</th>
        <th>الخبر 🌊</th>
      </tr>

      <tr>
        <td>الهدوء</td>
        <td>متوسطة</td>
        <td>ممتاز جدًا 😌</td>
      </tr>

      <tr>
        <td>البحر</td>
        <td>❌</td>
        <td>🌊 أكيد</td>
      </tr>

      <tr>
        <td>التمشيات</td>
        <td>حلوة</td>
        <td>فخمة جدًا ✨</td>
      </tr>

      <tr>
        <td>الكافيهات</td>
        <td>كويسة</td>
        <td>إدمان ☕</td>
      </tr>

      <tr>
        <td>الراحة النفسية</td>
        <td>ممتازة</td>
        <td>مستوى ثاني 😌</td>
      </tr>

      <tr>
        <td>وجود شهد</td>
        <td>❌</td>
        <td>✅ السبب الرئيسي للفوز</td>
      </tr>

    </table>

  </div>


  <div class="final">

    <div class="heart">💙</div>

    <h1>الفائزة: الخبر</h1>

    <p>
      بعد تحليل دقيق جدًا وعادل جدًا جدًا…
      الخبر قدرت تفوز بكل أريحية 😌
      بحر وجو وهدوء وتمشيات وكافيهات،
      وفوق هذا كله فيها شهد،
      ووجود شهد لحاله يخلي أي مقارنة محسومة من البداية 🤍✨
    </p>

  </div>

</div>

<div class="footer">
  صُنع بحب للخبر 🌊
</div>

</body>
</html>

<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="GIA PHÚ - Dịch vụ đo đạc, trắc địa, đo hiện trạng và bản đồ chuyên nghiệp.">
<title>GIA PHÚ | Đo đạc & Trắc địa</title>
<style>
:root{--navy:#0b1d35;--navy2:#122b4b;--gold:#c9a45c;--cream:#f6f4ef;--ink:#17263a;--muted:#687587;--white:#fff}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--ink);background:#fff;line-height:1.65}
a{color:inherit;text-decoration:none}.wrap{width:min(1160px,90%);margin:auto}
header{position:sticky;top:0;z-index:20;background:rgba(11,29,53,.97);backdrop-filter:blur(10px);color:#fff;border-bottom:1px solid rgba(201,164,92,.25)}
.nav{height:78px;display:flex;align-items:center;justify-content:space-between;gap:24px}
.brand{display:flex;align-items:center;gap:12px;font-weight:800;letter-spacing:2px;font-size:22px}.brand-mark{width:42px;height:42px;border:1px solid var(--gold);display:grid;place-items:center;color:var(--gold);font-family:Georgia,serif;font-size:23px}
.brand small{display:block;font-size:9px;letter-spacing:2.4px;color:#d8c49e;font-weight:500;margin-top:-5px}
nav{display:flex;gap:26px;font-size:13px;letter-spacing:.5px}nav a{color:#e9edf3}nav a:hover{color:var(--gold)}
.nav-cta,.btn{display:inline-flex;align-items:center;justify-content:center;background:var(--gold);color:var(--navy);padding:12px 20px;font-size:12px;font-weight:800;letter-spacing:1px;border:1px solid var(--gold);transition:.2s}
.nav-cta:hover,.btn:hover{background:transparent;color:var(--gold)}
.menu{display:none;background:none;border:1px solid #64748b;color:#fff;padding:8px 12px;font-size:20px}
.hero{min-height:650px;display:flex;align-items:center;color:#fff;position:relative;overflow:hidden;background:linear-gradient(90deg,rgba(7,20,38,.94),rgba(7,20,38,.72) 52%,rgba(7,20,38,.22)),url('https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=2000&q=85') center/cover}
.hero:after{content:"";position:absolute;inset:auto 0 0;height:5px;background:linear-gradient(90deg,var(--gold),transparent)}
.hero-content{position:relative;z-index:1;max-width:720px;padding:95px 0}
.eyebrow{color:var(--gold);font-size:11px;letter-spacing:3px;font-weight:800;text-transform:uppercase}
h1{font-family:Georgia,'Times New Roman',serif;font-size:clamp(42px,6vw,76px);line-height:1.08;font-weight:500;margin:18px 0 22px}
.hero p{max-width:570px;color:#d7deea;font-size:17px;margin-bottom:32px}.hero-actions{display:flex;gap:14px;flex-wrap:wrap}
.btn.outline{background:transparent;color:#fff;border-color:rgba(255,255,255,.6)}.btn.outline:hover{border-color:var(--gold);color:var(--gold)}
.hero-note{margin-top:52px;display:flex;gap:36px;flex-wrap:wrap;color:#d6dce5;font-size:12px;letter-spacing:1px}.hero-note strong{display:block;color:var(--gold);font:26px Georgia,serif;letter-spacing:0}
section{padding:88px 0}.section-head{max-width:650px;margin-bottom:42px}.section-head.center{text-align:center;margin:0 auto 45px}
h2{font:500 clamp(31px,4vw,46px)/1.15 Georgia,serif;color:var(--navy);margin:12px 0 15px}.section-head p{color:var(--muted);margin:0}
.about{background:var(--cream)}.about-grid{display:grid;grid-template-columns:1fr 1fr;gap:64px;align-items:center}
.about-photo{min-height:440px;background:linear-gradient(0deg,rgba(8,24,44,.12),rgba(8,24,44,.12)),url('https://images.unsplash.com/photo-1518005020951-eccb494ad742?auto=format&fit=crop&w=1200&q=85') center/cover;position:relative}
.photo-tag{position:absolute;right:-18px;bottom:28px;background:var(--navy);color:#fff;padding:20px 24px;border-left:3px solid var(--gold);font:18px Georgia,serif}
.about-copy p{color:var(--muted)}.checks{display:grid;grid-template-columns:1fr 1fr;gap:13px;margin:25px 0}.check{font-size:13px;color:var(--navy);font-weight:700}.check:before{content:"✓";color:var(--gold);font-size:17px;margin-right:9px}
.services{background:#fff}.service-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.service{padding:30px 27px;border:1px solid #e7e9ed;min-height:235px;transition:.25s;background:#fff}
.service:hover{transform:translateY(-5px);border-color:var(--gold);box-shadow:0 18px 40px rgba(11,29,53,.08)}
.service-icon{width:48px;height:48px;border:1px solid #dfc895;color:#a7823c;display:grid;place-items:center;font-size:22px;margin-bottom:22px}
.service h3{font:22px Georgia,serif;color:var(--navy);margin:0 0 10px}.service p{font-size:13px;color:var(--muted);margin:0}
.process{background:var(--navy);color:#fff}.process h2{color:#fff}.process .section-head p{color:#bdc8d6}
.steps{display:grid;grid-template-columns:repeat(4,1fr);gap:20px}.step{border-top:1px solid rgba(201,164,92,.5);padding-top:20px}.step b{font:34px Georgia,serif;color:var(--gold)}.step h3{font-size:15px;letter-spacing:.5px}.step p{font-size:13px;color:#b8c4d3}
.projects{background:var(--cream)}.project-grid{display:grid;grid-template-columns:1.2fr 1fr 1fr;gap:16px}.project{height:290px;position:relative;overflow:hidden;background:#d5dbe2}.project img{width:100%;height:100%;object-fit:cover;transition:.4s}.project:hover img{transform:scale(1.05)}.project span{position:absolute;bottom:0;left:0;right:0;padding:38px 18px 17px;color:#fff;font-weight:700;background:linear-gradient(transparent,rgba(5,17,32,.85))}
.contact{background:#fff}.contact-grid{display:grid;grid-template-columns:.85fr 1.15fr;gap:55px}.contact-info{background:var(--navy);padding:38px;color:#fff}.contact-info h2{color:#fff;font-size:34px}.contact-info p{color:#c1ccda;font-size:14px}.info-line{padding:15px 0;border-top:1px solid rgba(255,255,255,.13);font-size:13px}.info-line strong{display:block;color:var(--gold);font-size:10px;letter-spacing:1.5px;margin-bottom:4px}
form{display:grid;grid-template-columns:1fr 1fr;gap:15px}label{font-size:12px;font-weight:700;color:var(--navy)}input,select,textarea{width:100%;margin-top:7px;padding:13px;border:1px solid #dce1e7;background:#fafbfc;font:14px Arial;color:var(--ink);outline:none}input:focus,select:focus,textarea:focus{border-color:var(--gold)}.full{grid-column:1/-1}textarea{min-height:125px;resize:vertical}form button{cursor:pointer;justify-self:start}
footer{background:#071426;color:#c2cbd7;padding:28px 0;font-size:12px}.footer-row{display:flex;justify-content:space-between;gap:20px;flex-wrap:wrap}.gold{color:var(--gold)}
@media(max-width:850px){nav{display:none;position:absolute;top:78px;left:0;right:0;background:var(--navy);padding:22px 5%;flex-direction:column;gap:18px}nav.open{display:flex}.menu{display:block}.nav-cta{display:none}.about-grid,.contact-grid{grid-template-columns:1fr}.service-grid{grid-template-columns:repeat(2,1fr)}.steps{grid-template-columns:repeat(2,1fr)}.project-grid{grid-template-columns:1fr 1fr}.about-photo{min-height:340px}.photo-tag{right:0}}
@media(max-width:560px){.nav{height:70px}.brand{font-size:19px}.hero{min-height:600px}.hero-content{padding:70px 0}.hero-note{gap:20px}.service-grid,.steps,.project-grid{grid-template-columns:1fr}section{padding:65px 0}.checks{grid-template-columns:1fr}form{grid-template-columns:1fr}.full{grid-column:auto}.project{height:250px}}
</style>
</head>
<body>
<header>
 <div class="wrap nav">
  <a class="brand" href="#home"><span class="brand-mark">GP</span><span>GIA PHÚ<small>ĐO ĐẠC & TRẮC ĐỊA</small></span></a>
  <nav id="nav"><a href="#home">TRANG CHỦ</a><a href="#about">GIỚI THIỆU</a><a href="#services">DỊCH VỤ</a><a href="#projects">DỰ ÁN</a><a href="#contact">LIÊN HỆ</a></nav>
  <a class="nav-cta" href="#contact">NHẬN TƯ VẤN</a>
  <button class="menu" aria-label="Mở menu" onclick="document.getElementById('nav').classList.toggle('open')">☰</button>
 </div>
</header>
<main>
<section class="hero" id="home"><div class="wrap"><div class="hero-content">
 <div class="eyebrow">Chính xác trong từng phép đo · Vững chắc mọi công trình</div>
 <h1>Định vị chính xác.<br><span class="gold">Kiến tạo giá trị.</span></h1>
 <p>GIA PHÚ cung cấp giải pháp đo đạc và trắc địa chuyên nghiệp, đồng hành cùng khách hàng trong từng bước khảo sát, xác định hiện trạng và triển khai công trình.</p>
 <div class="hero-actions"><a class="btn" href="#services">KHÁM PHÁ DỊCH VỤ</a><a class="btn outline" href="#contact">LIÊN HỆ GIA PHÚ</a></div>
 <div class="hero-note"><div><strong>01</strong>CHÍNH XÁC</div><div><strong>02</strong>TẬN TÂM</div><div><strong>03</strong>CHUYÊN NGHIỆP</div></div>
</div></div></section>
<section class="about" id="about"><div class="wrap about-grid">
 <div class="about-photo"><div class="photo-tag">GIA PHÚ <span class="gold">|</span> Đồng hành cùng phát triển</div></div>
 <div class="about-copy"><div class="eyebrow">Về chúng tôi</div><h2>Giải pháp đo đạc đáng tin cậy cho mọi nhu cầu</h2>
 <p>GIA PHÚ hướng đến việc cung cấp dịch vụ đo đạc, khảo sát và trắc địa với tinh thần trách nhiệm, quy trình rõ ràng và sự tỉ mỉ trong từng hạng mục.</p>
 <p>Chúng tôi luôn đặt chất lượng công việc và sự hài lòng của khách hàng làm trọng tâm, góp phần tạo nền tảng dữ liệu tin cậy cho các quyết định và công trình.</p>
 <div class="checks"><div class="check">Tư vấn rõ ràng</div><div class="check">Quy trình chuyên nghiệp</div><div class="check">Chú trọng độ chính xác</div><div class="check">Hỗ trợ tận tâm</div></div>
 <a class="btn" href="#contact">TRAO ĐỔI VỚI CHÚNG TÔI</a>
 </div>
</div></section>
<section class="services" id="services"><div class="wrap">
 <div class="section-head center"><div class="eyebrow">Lĩnh vực hoạt động</div><h2>Dịch vụ của GIA PHÚ</h2><p>Các hạng mục dịch vụ có thể được điều chỉnh theo nhu cầu thực tế và phạm vi công việc của khách hàng.</p></div>
 <div class="service-grid">
  <article class="service"><div class="service-icon">⌖</div><h3>Đo đạc địa chính</h3><p>Khảo sát, đo đạc và hỗ trợ lập dữ liệu, bản vẽ phục vụ nhu cầu đất đai theo phạm vi chuyên môn.</p></article>
  <article class="service"><div class="service-icon">▧</div><h3>Đo hiện trạng</h3><p>Ghi nhận hiện trạng khu đất, công trình và các yếu tố liên quan theo yêu cầu khảo sát.</p></article>
  <article class="service"><div class="service-icon">⌁</div><h3>Đo vẽ bản đồ</h3><p>Thu thập dữ liệu thực địa, hỗ trợ xây dựng bản vẽ và hồ sơ kỹ thuật phù hợp.</p></article>
  <article class="service"><div class="service-icon">◎</div><h3>Định vị công trình</h3><p>Hỗ trợ xác định vị trí, tim trục và các điểm khống chế phục vụ thi công.</p></article>
  <article class="service"><div class="service-icon">△</div><h3>Khảo sát địa hình</h3><p>Khảo sát và thu thập thông tin địa hình làm cơ sở cho công tác thiết kế, quy hoạch.</p></article>
  <article class="service"><div class="service-icon">⌗</div><h3>Tư vấn kỹ thuật</h3><p>Tiếp nhận nhu cầu, tư vấn phương án khảo sát và phạm vi công việc phù hợp.</p></article>
 </div>
</div></section>
<section class="process"><div class="wrap"><div class="section-head"><div class="eyebrow">Cách chúng tôi làm việc</div><h2>Quy trình rõ ràng, hiệu quả</h2><p>Từng bước được trao đổi minh bạch để khách hàng dễ theo dõi và phối hợp.</p></div>
 <div class="steps">
  <div class="step"><b>01</b><h3>TIẾP NHẬN YÊU CẦU</h3><p>Lắng nghe nhu cầu, vị trí và thông tin ban đầu của công việc.</p></div>
  <div class="step"><b>02</b><h3>KHẢO SÁT & TƯ VẤN</h3><p>Trao đổi phạm vi, phương án thực hiện và dự kiến tiến độ.</p></div>
  <div class="step"><b>03</b><h3>TRIỂN KHAI ĐO ĐẠC</h3><p>Thực hiện công việc theo phương án đã thống nhất.</p></div>
  <div class="step"><b>04</b><h3>BÀN GIAO & HỖ TRỢ</h3><p>Kiểm tra, bàn giao kết quả và hỗ trợ các nội dung liên quan.</p></div>
 </div>
</div></section>
<section class="projects" id="projects"><div class="wrap"><div class="section-head center"><div class="eyebrow">Năng lực thực hiện</div><h2>Dự án & hoạt động</h2><p>Khu vực giới thiệu hình ảnh công trình, thiết bị và hoạt động thực tế của GIA PHÚ.</p></div>
 <div class="project-grid">
  <div class="project"><img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=900&q=80" alt="Công trình xây dựng"><span>Khảo sát công trình</span></div>
  <div class="project"><img src="https://images.unsplash.com/photo-1518005020951-eccb494ad742?auto=format&fit=crop&w=800&q=80" alt="Kiến trúc công trình"><span>Đo vẽ hiện trạng</span></div>
  <div class="project"><img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=800&q=80" alt="Hoạt động công trường"><span>Hoạt động thực địa</span></div>
 </div>
</div></section>
<section class="contact" id="contact"><div class="wrap"><div class="section-head"><div class="eyebrow">Kết nối với chúng tôi</div><h2>Bắt đầu trao đổi công việc</h2><p>Gửi thông tin nhu cầu, GIA PHÚ sẽ liên hệ để trao đổi thêm. Vui lòng cập nhật thông tin liên hệ chính thức trước khi đưa website lên sử dụng.</p></div>
 <div class="contact-grid">
  <div class="contact-info"><div class="eyebrow">GIA PHÚ</div><h2>Chúng tôi sẵn sàng lắng nghe</h2><p>Liên hệ để được tư vấn về phạm vi đo đạc, khảo sát và phương án thực hiện.</p>
   <div class="info-line"><strong>ĐIỆN THOẠI</strong><a href="tel:0948952239">0948 952 239</a></div>
   <div class="info-line"><strong>ZALO / NHẮN TIN</strong><a href="https://zalo.me/0948952239" target="_blank" rel="noopener">Nhắn tin Zalo: 0948 952 239 ↗</a></div>
   <div class="info-line"><strong>EMAIL</strong>[Bổ sung email công ty]</div>
   <div class="info-line"><strong>ĐỊA CHỈ</strong>[Bổ sung địa chỉ công ty]</div>
   <div class="info-line"><strong>GIỜ LÀM VIỆC</strong>[Bổ sung thời gian làm việc]</div>
  </div>
  <form id="consultForm">
   <label>Họ và tên<input required placeholder="Tên của bạn"></label>
   <label>Số điện thoại<input required type="tel" placeholder="Số điện thoại liên hệ"></label>
   <label class="full">Nhu cầu dịch vụ<select><option>Chọn dịch vụ quan tâm</option><option>Đo đạc địa chính</option><option>Đo hiện trạng</option><option>Đo vẽ bản đồ</option><option>Định vị công trình</option><option>Khảo sát địa hình</option><option>Tư vấn kỹ thuật</option></select></label>
   <label class="full">Nội dung cần tư vấn<textarea placeholder="Mô tả ngắn gọn nhu cầu và vị trí công việc..."></textarea></label>
   <button class="btn full" type="submit">GỬI YÊU CẦU TƯ VẤN</button>
  </form>
 </div>
</div></section>
</main>
<div class="quick-contact" aria-label="Liên hệ nhanh">
 <a href="tel:0948952239" title="Gọi GIA PHÚ">☎ Gọi tư vấn</a>
 <a href="https://zalo.me/0948952239" target="_blank" rel="noopener" title="Nhắn Zalo">Zalo</a>
</div>
<style>
.quick-contact{position:fixed;right:18px;bottom:20px;z-index:30;display:flex;flex-direction:column;gap:9px}
.quick-contact a{background:#c9a45c;color:#0b1d35;padding:12px 17px;font-size:12px;font-weight:800;letter-spacing:.3px;box-shadow:0 5px 18px #07142633;border-radius:3px}
.quick-contact a:last-child{background:#0879d1;color:white}
.quick-contact a:hover{filter:brightness(1.08)}
</style>
<footer><div class="wrap footer-row"><div>© 2026 <strong class="gold">GIA PHÚ</strong> · ĐO ĐẠC & TRẮC ĐỊA</div><div>Chính xác trong từng phép đo · Vững chắc mọi công trình</div></div></footer>

<script>
document.getElementById('consultForm').addEventListener('submit', function (event) {
  event.preventDefault();
  const form = event.currentTarget;
  const name = form.querySelector('input[placeholder="Tên của bạn"]').value.trim();
  const phone = form.querySelector('input[type="tel"]').value.trim();
  const service = form.querySelector('select').value;
  const message = form.querySelector('textarea').value.trim();
  const content = [
    'YEU CAU TU VAN GIA PHU',
    'Ho ten: ' + name,
    'So dien thoai: ' + phone,
    'Dich vu: ' + service,
    'Noi dung: ' + message
  ].join('\n');
  const smsUrl = 'sms:0948952239?body=' + encodeURIComponent(content);
  alert('Đang mở ứng dụng tin nhắn để gửi yêu cầu đến GIA PHÚ. Nếu thiết bị không hỗ trợ, vui lòng bấm nút Zalo hoặc Gọi tư vấn.');
  window.location.href = smsUrl;
});
</script>

</body></html>

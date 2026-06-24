Berikut adalah halaman HTML yang menampilkan daftar jajanan khas Indonesia dari gambar Anda, dengan gaya bernomor dan informasi profil Anda.
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chenlyn Dominiq · Jajanan Indonesia</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #f5f1eb;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 24px;
    }

    .card {
      max-width: 620px;
      width: 100%;
      background: #ffffff;
      border-radius: 40px;
      padding: 32px 28px 28px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.06), 0 8px 20px rgba(0, 0, 0, 0.04);
    }

    /* ===== PROFILE HEADER ===== */
    .profile-header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: baseline;
      margin-bottom: 24px;
      border-bottom: 1.5px solid #e8e1d9;
      padding-bottom: 18px;
    }

    .name-title h1 {
      font-size: 28px;
      font-weight: 600;
      letter-spacing: -0.3px;
      color: #1e1a16;
      line-height: 1.1;
    }

    .name-title .subhead {
      font-size: 14px;
      font-weight: 400;
      color: #7b6e62;
      margin-top: 4px;
      letter-spacing: 0.2px;
    }

    .contact-badge {
      background: #f0ebe5;
      padding: 8px 16px 8px 14px;
      border-radius: 40px;
      font-size: 13px;
      color: #2b241f;
      display: inline-flex;
      align-items: center;
      gap: 6px;
      flex-wrap: wrap;
      margin-top: 6px;
    }

    .contact-badge span {
      display: inline-flex;
      align-items: center;
      gap: 4px;
    }

    .contact-badge .separator {
      opacity: 0.3;
      margin: 0 2px;
    }

    /* ===== BEAUTY LIST (jajanan) ===== */
    .jajanan-list {
      display: flex;
      flex-direction: column;
      gap: 0;
    }

    .list-item {
      display: flex;
      align-items: center;
      padding: 10px 0;
      border-bottom: 1px solid #eee8e1;
    }

    .list-item:last-child {
      border-bottom: none;
    }

    .item-number {
      width: 32px;
      font-size: 15px;
      font-weight: 450;
      color: #a39284;
      letter-spacing: -0.2px;
      flex-shrink: 0;
    }

    .item-content {
      flex: 1;
      display: flex;
      flex-wrap: wrap;
      align-items: baseline;
      gap: 6px 12px;
    }

    .jajanan-name {
      font-weight: 500;
      font-size: 17px;
      color: #1e1a16;
      letter-spacing: -0.1px;
    }

    /* ===== FOOTER ===== */
    .footer-contact {
      margin-top: 24px;
      padding-top: 16px;
      border-top: 1.5px solid #e8e1d9;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      font-size: 14px;
      color: #3d342d;
      gap: 10px;
    }

    .footer-contact .info-item {
      display: flex;
      align-items: center;
      gap: 6px;
    }

    .footer-contact .info-item .label {
      font-weight: 350;
      color: #7b6b5d;
    }

    .footer-contact .info-item .value {
      font-weight: 450;
    }

    .emoji-icon {
      font-size: 16px;
      filter: grayscale(0.2);
    }

    .footnote {
      margin-top: 12px;
      font-size: 12px;
      color: #b7a99c;
      text-align: right;
      letter-spacing: 0.2px;
      border-top: 1px dashed #e2dad2;
      padding-top: 12px;
    }

    /* responsive */
    @media (max-width: 480px) {
      .card { padding: 20px 16px; }
      .profile-header { flex-direction: column; align-items: flex-start; gap: 8px; }
      .contact-badge { width: 100%; justify-content: flex-start; }
      .jajanan-name { font-size: 15px; }
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- ===== PROFILE HEADER ===== -->
    <div class="profile-header">
      <div class="name-title">
        <h1>Chenlyn Dominiq</h1>
        <div class="subhead">🍢 jajanan khas Indonesia</div>
      </div>
      <div class="contact-badge">
        <span>📍 SMAN 15 JAKARTA</span>
        <span class="separator">·</span>
        <span>✉️ dominiqgultom@gmail.com</span>
        <span class="separator">·</span>
        <span>📞 0831-9229-1980</span>
      </div>
    </div>

    <!-- ===== DAFTAR JAJANAN ===== -->
    <div class="jajanan-list">
      <!-- 1. Cireng -->
      <div class="list-item">
        <div class="item-number">1</div>
        <div class="item-content">
          <span class="jajanan-name">Cireng</span>
        </div>
      </div>
      <!-- 2. Tahu gejrot -->
      <div class="list-item">
        <div class="item-number">2</div>
        <div class="item-content">
          <span class="jajanan-name">Tahu gejrot</span>
        </div>
      </div>
      <!-- 3. Luis -->
      <div class="list-item">
        <div class="item-number">3</div>
        <div class="item-content">
          <span class="jajanan-name">Luis</span>
        </div>
      </div>
      <!-- 4. Cehil -->
      <div class="list-item">
        <div class="item-number">4</div>
        <div class="item-content">
          <span class="jajanan-name">Cehil</span>
        </div>
      </div>
      <!-- 5. Batagar -->
      <div class="list-item">
        <div class="item-number">5</div>
        <div class="item-content">
          <span class="jajanan-name">Batagar</span>
        </div>
      </div>
      <!-- 6. Bala-bala -->
      <div class="list-item">
        <div class="item-number">6</div>
        <div class="item-content">
          <span class="jajanan-name">Bala-bala</span>
        </div>
      </div>
      <!-- 7. Risol -->
      <div class="list-item">
        <div class="item-number">7</div>
        <div class="item-content">
          <span class="jajanan-name">Risol</span>
        </div>
      </div>
      <!-- 8. Putu ayu -->
      <div class="list-item">
        <div class="item-number">8</div>
        <div class="item-content">
          <span class="jajanan-name">Putu ayu</span>
        </div>
      </div>
      <!-- 9. Lemper -->
      <div class="list-item">
        <div class="item-number">9</div>
        <div class="item-content">
          <span class="jajanan-name">Lemper</span>
        </div>
      </div>
      <!-- 10. Kue mangkok -->
      <div class="list-item">
        <div class="item-number">10</div>
        <div class="item-content">
          <span class="jajanan-name">Kue mangkok</span>
        </div>
      </div>
      <!-- 11. Onde-onde -->
      <div class="list-item">
        <div class="item-number">11</div>
        <div class="item-content">
          <span class="jajanan-name">Onde-onde</span>
        </div>
      </div>
      <!-- 12. Dadar gulung -->
      <div class="list-item">
        <div class="item-number">12</div>
        <div class="item-content">
          <span class="jajanan-name">Dadar gulung</span>
        </div>
      </div>
      <!-- 13. Cilok -->
      <div class="list-item">
        <div class="item-number">13</div>
        <div class="item-content">
          <span class="jajanan-name">Cilok</span>
        </div>
      </div>
      <!-- 14. Martabak manis -->
      <div class="list-item">
        <div class="item-number">14</div>
        <div class="item-content">
          <span class="jajanan-name">Martabak manis</span>
        </div>
      </div>
      <!-- 15. Kerupuk -->
      <div class="list-item">
        <div class="item-number">15</div>
        <div class="item-content">
          <span class="jajanan-name">Kerupuk</span>
        </div>
      </div>
      <!-- 16. Jalabia -->
      <div class="list-item">
        <div class="item-number">16</div>
        <div class="item-content">
          <span class="jajanan-name">Jalabia</span>
        </div>
      </div>
      <!-- 17. Jajanan pasar -->
      <div class="list-item">
        <div class="item-number">17</div>
        <div class="item-content">
          <span class="jajanan-name">Jajanan pasar</span>
        </div>
      </div>
      <!-- 18. Peyeum -->
      <div class="list-item">
        <div class="item-number">18</div>
        <div class="item-content">
          <span class="jajanan-name">Peyeum</span>
        </div>
      </div>
      <!-- 19. Serabi -->
      <div class="list-item">
        <div class="item-number">19</div>
        <div class="item-content">
          <span class="jajanan-name">Serabi</span>
        </div>
      </div>
    </div>

    <!-- ===== FOOTER CONTACT ===== -->
    <div class="footer-contact">
      <div class="info-item">
        <span class="emoji-icon">📍</span>
        <span class="label">Lokasi</span>
        <span class="value">SMAN 15 JAKARTA</span>
      </div>
      <div class="info-item">
        <span class="emoji-icon">✉️</span>
        <span class="label">Email</span>
        <span class="value">dominiqgultom@gmail.com</span>
      </div>
      <div class="info-item">
        <span class="emoji-icon">📞</span>
        <span class="label">Telp</span>
        <span class="value">0831-9229-1980</span>
      </div>
    </div>

    <div class="footnote">
      Chenlyn Dominiq · jajanan tradisional
    </div>
  </div>
</body>
</html>
```

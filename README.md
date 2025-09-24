# AzresturaZione-
<!doctype html>

<html lang="it">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>AZ Ristrutturazioni SRLS — Biglietto</title>
  <style>
    :root{--bg:#0b1220;--card:#ffffff;--accent:#d35400;--muted:#555}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:linear-gradient(135deg,#071024 0%, #0f1724 100%); color:var(--card)}
    .wrap{min-height:100%;display:flex;align-items:center;justify-content:center;padding:30px}
    .card{
      width:900px;max-width:100%;background:#fff;border-radius:12px;padding:28px;box-shadow:0 12px 30px rgba(2,6,23,0.6);display:flex;gap:24px;align-items:center;color:#0b1220
    }
    .logo{
      width:220px;flex:0 0 220px;height:220px;border-radius:10px;background:linear-gradient(180deg,var(--accent),#e67e22);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;font-size:20px;box-shadow:0 8px 20px rgba(0,0,0,0.2)
    }
    .info{flex:1}
    h1{margin:0;font-size:26px;letter-spacing:0.3px}
    .owner{margin-top:6px;font-weight:700;color:var(--accent)}
    .contact{margin-top:12px;display:flex;gap:18px;flex-wrap:wrap}
    .contact a{color:#0b1220;text-decoration:none;font-weight:600}
    .address{margin-top:10px;color:var(--muted)}
    .services{margin-top:16px;background:#fbfbfb;border-radius:8px;padding:12px;color:#222}
    .services ul{margin:0;padding-left:18px}
    .small{font-size:13px;color:var(--muted);margin-top:10px}
    /* responsive */
    @media (max-width:760px){
      .card{flex-direction:column;align-items:stretch;padding:18px}
      .logo{width:100%;height:120px;flex:unset;border-radius:8px;font-size:18px}
    }
    /* print-friendly single card (A4 centered) */
    @media print{
      body{background:transparent}
      .wrap{padding:0}
      .card{box-shadow:none;border-radius:0;margin:0;width:100%;max-width:none}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card" role="article">
      <div class="logo" aria-hidden="true">AZ<br>RISTRUTTURAZIONI</div>
      <div class="info">
        <h1>AZ ristrutturazioni SRLS</h1>
        <div class="owner">di Patierno Salvatore</div><div class="contact">
      <div class="tel">📞 <a href="tel:+393295670032">+39 329 567 0032</a></div>
      <div class="mail">✉️ <a href="mailto:info@azristrutturazioni.example">info@azristrutturazioni.example</a></div>
    </div>

    <div class="address">📍 Via Luigi Santamaria 55, Pianura (NA)</div>

    <div class="services" aria-label="Servizi">
      <strong>Servizi principali</strong>
      <ul>
        <li>Costruzioni, ristrutturazioni, manutenzione e restauro di edifici civili, industriali e commerciali</li>
        <li>Riparazioni di impianti elettrici, elettronici, idraulici e termoidraulici (riscaldamento, condizionamento, sicurezza)</li>
        <li>Lavorazioni di carpenteria metallica (leggera e pesante): strutture, infissi, serramenti, scale, pensiline, recinzioni</li>
      </ul>
    </div>

    <div class="small">Per preventivi e sopralluoghi gratuiti contattaci via telefono o email.</div>
  </div>
</div>

  </div>
</body>
</html>

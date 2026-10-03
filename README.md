# Wedding-Invite
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wedding Invitation | Sivaraman & Swarnaa Sri</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500;700&family=Great+Vibes&family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #4a2869;
      --secondary: #6b3ba6;
      --gold: #b38b43;
      --gold-light: #fdf8ef;
      --bg: #f8f5fc;
      --text: #2f2838;
      --card-bg: rgba(255, 255, 255, 0.94);
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      background-image: radial-gradient(#d6c0ea 0.8px, transparent 0.8px);
      background-size: 24px 24px;
      padding: 20px 14px;
    }
    .wrapper {
      max-width: 560px;
      margin: 0 auto;
      padding: 40px 24px 44px;
      background: var(--card-bg);
      border-radius: 24px;
      box-shadow: 0 16px 48px rgba(74, 40, 105, 0.1);
      border: 1px solid rgba(179, 139, 67, 0.28);
      text-align: center;
    }
    .deity-badge {
      display: inline-block;
      width: 52px;
      height: 52px;
      border-radius: 50%;
      background: #fbf5ea;
      border: 1px solid var(--gold);
      line-height: 50px;
      font-size: 1.6rem;
      margin-bottom: 12px;
    }
    .callout {
      font-family: 'Great Vibes', cursive;
      font-size: 3rem;
      color: var(--primary);
      margin-bottom: 2px;
    }
    .sub-head {
      font-family: 'Cinzel', serif;
      letter-spacing: 2px;
      font-size: 0.8rem;
      text-transform: uppercase;
      color: #666;
      margin-bottom: 24px;
    }
    .couple-box {
      padding: 24px 14px;
      background: linear-gradient(180deg, rgba(247, 237, 215, 0.35) 0%, rgba(255,255,255,0.7) 100%);
      border: 1px solid var(--gold);
      border-radius: 18px;
      margin-bottom: 24px;
    }
    .name {
      font-family: 'Great Vibes', cursive;
      font-size: 3.2rem;
      color: var(--primary);
      line-height: 1.15;
    }
    .degree {
      font-family: 'Cinzel', serif;
      font-size: 0.8rem;
      color: var(--gold);
      font-weight: 700;
      letter-spacing: 2px;
      margin-top: 2px;
    }
    .ampersand {
      font-family: 'Cinzel', serif;
      font-size: 1.4rem;
      color: var(--gold);
      margin: 8px 0;
    }
    .invite-text {
      font-family: 'Playfair Display', serif;
      font-style: italic;
      font-size: 1.05rem;
      color: #555;
      margin: 20px auto;
      max-width: 440px;
    }
    .events-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 14px;
      margin: 28px 0;
    }
    @media (max-width: 480px) {
      .events-grid { grid-template-columns: 1fr; }
      .name { font-size: 2.8rem; }
    }
    .event-card {
      background: #ffffff;
      border: 1px solid rgba(107, 59, 166, 0.16);
      border-radius: 16px;
      padding: 20px 14px;
      box-shadow: 0 4px 18px rgba(0,0,0,0.03);
    }
    .event-card.highlight {
      border: 1.5px solid var(--gold);
      background: #fffdf9;
    }
    .event-title {
      font-family: 'Great Vibes', cursive;
      font-size: 2.2rem;
      color: var(--primary);
    }
    .event-day {
      font-size: 0.75rem;
      text-transform: uppercase;
      color: #777;
      letter-spacing: 1.5px;
      margin-top: 4px;
    }
    .event-date {
      font-family: 'Cinzel', serif;
      font-size: 1.5rem;
      font-weight: 700;
      color: var(--primary);
      margin: 6px 0;
    }
    .event-time {
      font-size: 0.82rem;
      font-weight: 600;
      color: var(--gold);
    }
    .venue-card {
      background: var(--gold-light);
      border-radius: 16px;
      padding: 22px 18px;
      margin: 24px 0 16px;
      border: 1px dashed var(--gold);
    }
    .venue-card h3 {
      font-family: 'Cinzel', serif;
      font-size: 1.05rem;
      color: var(--primary);
      margin-bottom: 6px;
    }
    .venue-card p {
      font-size: 0.9rem;
      color: #444;
      line-height: 1.5;
    }
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      margin-top: 14px;
      padding: 10px 22px;
      background: var(--primary);
      color: #fff !important;
      text-decoration: none;
      font-size: 0.85rem;
      font-weight: 500;
      border-radius: 30px;
      letter-spacing: 0.5px;
      box-shadow: 0 4px 14px rgba(74, 40, 105, 0.25);
      transition: background 0.2s ease;
    }
    .btn:hover {
      background: var(--secondary);
    }
    .closing {
      font-family: 'Great Vibes', cursive;
      font-size: 2.4rem;
      color: var(--primary);
      margin-top: 24px;
    }
  </style>
</head>
<body>

  <div class="wrapper">
    <div class="deity-badge">🪷</div>
    <p class="callout">Dear Friends,</p>
    <p class="sub-head">Please join us to celebrate the wedding of</p>

    <div class="couple-box">
      <div class="name">Sivaraman</div>
      <div class="degree">B.E.,</div>
      <div class="ampersand">&</div>
      <div class="name">Swarnaa Sri</div>
      <div class="degree">B.Tech.,</div>
    </div>

    <p class="invite-text">
      We would be delighted to have you and your family be a part of our special celebrations.
    </p>

    <div class="events-grid">
      <div class="event-card">
        <div class="event-title">Reception</div>
        <div class="event-day">Saturday</div>
        <div class="event-date">14 NOV 2026</div>
        <div class="event-time">From 6.00 P.M. Onwards</div>
      </div>
      <div class="event-card highlight">
        <div class="event-title">Muhurtham</div>
        <div class="event-day">Sunday</div>
        <div class="event-date">15 NOV 2026</div>
        <div class="event-time">7.30 A.M. – 9.00 A.M.</div>
      </div>
    </div>

    <div class="venue-card">
      <h3>Ramanuja Thirumana Koodam</h3>
      <p>No. 10/106, Ramanuja Koodam Street,<br>Poonamallee, Chennai – 600 056.</p>
      <a class="btn" href="https://maps.google.com/?q=Ramanuja+Thirumana+Koodam+Poonamallee+Chennai" target="_blank" rel="noopener">
        📍 Open in Google Maps
      </a>
    </div>

    <p class="closing">Looking forward to your presence!</p>
  </div>

</body>
</html>

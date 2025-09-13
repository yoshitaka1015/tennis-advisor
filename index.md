<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>Tennis Advisor | サポート &amp; ポリシー</title>
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="description" content="Tennis Advisor のサポート・プライバシーポリシー・利用規約・機能要望フォーム">
  <style>
    :root{
      --bg:#0B0B0B;        /* 背景 */
      --card:#111213;      /* カード背景 */
      --text:#F4F4F4;      /* 文字メイン */
      --text2:#CFCFCF;     /* サブ文字 */
      --accent:#2C8A3B;    /* 緑 */
      --accent2:#7B3FA1;   /* 紫 */
      --sep:#2A2C29;       /* 罫線 */
    }
    *,*::before,*::after{ box-sizing:border-box; }
    html,body{ margin:0; padding:0; background:var(--bg); color:var(--text); font-family:system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans JP","Hiragino Kaku Gothic ProN",Meiryo,sans-serif; }
    a{ color:var(--accent2); text-decoration:none; }
    a:hover{ text-decoration:underline; }
    .container{ max-width:900px; margin:0 auto; padding:16px; }
    header{ padding:20px 0 12px; }
    header h1{ margin:0 0 6px; font-size:28px; }
    header p{ margin:0; color:var(--text2); }
    .grid{ display:grid; grid-template-columns:1fr 1fr; gap:16px; margin-top:16px; }
    @media (max-width:760px){ .grid{ grid-template-columns:1fr; } }
    .card{ background:var(--card); border:1px solid var(--sep); border-radius:16px; padding:16px; }
    .card h2{ margin:0 0 8px; font-size:18px; }
    .btn{ display:inline-block; margin-top:8px; padding:10px 16px; border-radius:999px; border:0; background:linear-gradient(90deg,var(--accent),#3aa157); color:#fff; font-weight:600; }
    .btn.secondary{ background:linear-gradient(90deg,var(--accent2),#9c62c5); }
    .list{ margin:0; padding-left:18px; color:var(--text2); }
    footer{ margin:24px 0 8px; color:var(--text2); font-size:12px; }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Tennis Advisor</h1>
      <p>試合記録・分析をスマートに。サポート/規約/ポリシー/要望はこちら。</p>
    </header>

    <section class="grid">
      <div class="card">
        <h2>プライバシーポリシー</h2>
        <p class="desc">広告（Google AdMob）やフォーム送信（Formspree）に関する取り扱いを含みます。</p>
        <a class="btn" href="./privacy.html" rel="noopener">プライバシーポリシーを見る</a>
      </div>

      <div class="card">
        <h2>利用規約</h2>
        <p class="desc">アプリ利用時の条件・禁止事項・免責・裁判管轄など。</p>
        <a class="btn secondary" href="./terms.html" rel="noopener">利用規約を見る</a>
      </div>

      <div class="card">
        <h2>機能要望フォーム</h2>
        <p class="desc">改善のためのご意見をお寄せください（返信は原則ありません）。</p>
        <ul class="list">
          <li>端末・OS・アプリ版の任意入力欄あり</li>
          <li>スパム対策（ハニーポット）実装済</li>
        </ul>
        <a class="btn" href="./feedback.html" rel="noopener nofollow">フォームへ</a>
      </div>

      <div class="card">
        <h2>アプリ情報</h2>
        <ul class="list">
          <li>データ保存：端末内（広告/フォームは外部事業者方針に従う）</li>
        </ul>
        <a class="btn secondary" href="https://apps.apple.com/" target="_blank" rel="noopener">App Store（準備中）</a>
      </div>
    </section>

    <footer>© 2025 Tennis Advisor</footer>
  </div>
</body>
</html>
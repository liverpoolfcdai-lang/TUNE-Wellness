# TUNE-Wellness
TUNE Wellness
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TUNE Wellness | あなたの健康に、医学的な地図を。</title>
    <style>
        :root {
            --primary-color: #0f172a;
            --accent-color: #c5a059;
            --text-color: #334155;
            --bg-color: #ffffff;
            --light-bg: #f8fafc;
        }

        body {
            font-family: "Helvetica Neue", Arial, "Hiragino Kaku Gothic ProN", "Hiragino Sans", Meiryo, sans-serif;
            line-height: 1.8;
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }

        .container { max-width: 900px; margin: 0 auto; padding: 0 20px; }

        header { padding: 30px 0; text-align: center; background: var(--primary-color); color: white; }
        .logo { font-size: 24px; font-weight: bold; letter-spacing: 0.1em; color: var(--accent-color); }

        .hero {
            padding: 100px 0;
            text-align: center;
            background: linear-gradient(rgba(15, 23, 42, 0.85), rgba(15, 23, 42, 0.85)), url('https://images.unsplash.com/photo-1576091160550-2173dba999ef?auto=format&fit=crop&w=1500&q=80');
            background-size: cover;
            background-position: center;
            color: white;
        }

        .hero h1 { font-size: 2.4rem; margin-bottom: 20px; line-height: 1.3; }
        .hero p { font-size: 1.2rem; max-width: 700px; margin: 0 auto 40px; opacity: 0.9; }

        section { padding: 80px 0; }
        .section-title { text-align: center; margin-bottom: 50px; }
        .section-title h2 { font-size: 1.8rem; color: var(--primary-color); position: relative; padding-bottom: 15px; }
        .section-title h2::after { content: ""; position: absolute; bottom: 0; left: 50%; transform: translateX(-50%); width: 50px; height: 2px; background: var(--accent-color); }

        .problem-box { background: var(--light-bg); padding: 40px; border-left: 5px solid var(--primary-color); margin-bottom: 40px; }

        .flow-card { display: flex; align-items: flex-start; margin-bottom: 40px; }
        .flow-number { background: var(--primary-color); color: white; width: 35px; height: 35px; display: flex; align-items: center; justify-content: center; border-radius: 50%; margin-right: 20px; flex-shrink: 0; font-weight: bold; }
        .flow-card h3 { margin-top: 0; color: var(--primary-color); }

        .price-card { border: 2px solid var(--primary-color); padding: 50px; text-align: center; border-radius: 8px; max-width: 550px; margin: 0 auto; background: white; }
        .price-card .amount { font-size: 3.5rem; font-weight: bold; color: var(--primary-color); }
        .price-card .unit { font-size: 1.2rem; }

        .profile { background: var(--light-bg); padding: 80px 0; text-align: center; }
        .profile-text { max-width: 700px; margin: 0 auto; }

        .cta-button {
            display: inline-block;
            background: var(--accent-color);
            color: var(--primary-color);
            padding: 22px 50px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 4px;
            transition: 0.3s;
            font-size: 1.3rem;
        }
        .cta-button:hover { transform: translateY(-3px); box-shadow: 0 10px 20px rgba(0,0,0,0.15); background: #d4b470; }

        footer { text-align: center; padding: 50px 0; font-size: 0.9rem; color: #94a3b8; background: var(--primary-color); }

        @media (max-width: 768px) {
            .hero h1 { font-size: 1.8rem; }
            .cta-button { width: 80%; padding: 20px; }
        }
    </style>
</head>
<body>

<header>
    <div class="logo">TUNE Wellness</div>
</header>

<section class="hero">
    <div class="container">
        <h1>「まだ大丈夫」を、医学的に検証する。</h1>
        <p>薬剤師・製薬MRが、あなたの健診データと現状を徹底分析。30分間のオンライン面談で、次のアクションを断言します。</p>
        <a href="#reserve" class="cta-button">予約・健診結果を送る</a>
    </div>
</section>

<section>
    <div class="container">
        <div class="section-title">
            <h2>健康の「無法地帯」を終わらせる</h2>
        </div>
        <div class="problem-box">
            <p>病院は病気になるまで動いてくれません。ネットには根拠のない健康情報が溢れています。私たちは、医学的な地図を持たないまま、グレーゾーンを歩かされています。</p>
            <p><strong>TUNE Wellnessが提供するのは「治療」ではなく「判断」です。</strong> 薬剤師の知見と、最新の医学データに触れるMRとしての経験を、あなたの判断基準（OS）として提供します。</p>
        </div>
    </div>
</section>

<section style="background-color: var(--light-bg);">
    <div class="container">
        <div class="section-title">
            <h2>相談の流れ</h2>
        </div>
        <div class="flow-card">
            <div class="flow-number">1</div>
            <div>
                <h3>データ送付と事前回答</h3>
                <p>予約フォームから「健康診断の結果」をアップロードし、現在の悩みをお送りください。面談前に私の方で徹底的に分析いたします。</p>
            </div>
        </div>
        <div class="flow-card">
            <div class="flow-number">2</div>
            <div>
                <h3>30分間のオンライン面談</h3>
                <p>分析結果に基づき、ビデオ通話（Zoom等）で現状を仕分け。「病院へ行くべきか」「今のサプリを続けるべきか」等の判断を下します。</p>
            </div>
        </div>
        <div class="flow-card">
            <div class="flow-number">3</div>
            <div>
                <h3>パーソナル判定シート</h3>
                <p>面談後、あなたの現在地と推奨アクションをまとめた独自の判定シートをお送りします。</p>
            </div>
        </div>
    </div>
</section>

<section id="reserve">
    <div class="container">
        <div class="section-title">
            <h2>特別個別カウンセリング</h2>
        </div>
        <div class="price-card">
            <h3>データ分析 ＋ オンライン面談（30分）</h3>
            <div class="amount">5,000<span class="unit">円（税込）</span></div>
            <p style="margin: 30px 0; text-align: left; font-size: 1.1rem;">
                ・事前健診データ分析<br>
                ・個別オンライン面談 30分<br>
                ・あなたのための「判断・仕分けシート」作成
            </p>
            <a href="【ここにGoogleフォームのURL】" class="cta-button">予約・アンケートへ進む</a>
            <p style="font-size: 0.85rem; margin-top: 20px; color: #64748b;">※健診結果（写真やPDF）を必ずご準備ください。<br>決済方法は予約確定後にメールでご案内します。</p>
        </div>
    </div>
</section>

<section class="profile">
    <div class="container">
        <div class="section-title">
            <h2>Who is TUNE Wellness?</h2>
        </div>
        <div class="profile-text">
            <p><strong>薬剤師 / 製薬会社MR（慢性疾患領域）</strong></p>
            <p>日々、最新の医学的エビデンスを医師に届ける中で、病院にたどり着く前に選択肢を狭めてしまう人々の多さに危機感を抱き、活動を開始。薬を売るプロとしての知識を、あなたが「薬を飲まなくて済むため」の判断基準として提供します。</p>
        </div>
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2024 TUNE Wellness. 全ての発言は個人の見解であり、所属組織とは無関係です。</p>
    </div>
</footer>

</body>
</html>

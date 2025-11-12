# emergency-guide-tool
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚨 自動車事故が発生！緊急対応ナビ</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/emergency.css">
</head>
<body>
    
    <header id="header">
        <div class="logo">
            <h1><a href="index.html">🚨 事故対応ナビ</a></h1>
        </div>
        <nav class="main-nav">
            <ul>
                <li><a href="record.html">📝 メモ</a></li>
                <li><a href="negotiation.html">⚖️ 交渉ガイド</a></li>
                <li><a href="faq.html">❓ FAQ</a></li>
            </ul>
        </nav>
    </header>

    <main id="main-content">
        <section class="emergency-action">
            <h2 class="page-title">🚨 自動車事故が発生！</h2>
            <p class="catchphrase">
                <strong>落ち着いて。この手順で進めれば大丈夫です。</strong>
            </p>

            <div class="call-buttons">
                <a href="tel:119" class="btn btn-primary btn-call btn-emergency">
                    📞 119番 (救急車) に電話する
                </a>
                
                <a href="tel:110" class="btn btn-primary btn-call btn-police">
                    📞 110番 (警察) に電話する
                </a>
                
                <a href="#" id="insurance-call-btn" class="btn btn-primary btn-call btn-insurance">
                    📞 保険会社に連絡する
                </a>
                <p class="small-note">※保険会社の連絡先は設定済みの場合は表示されます</p>
            </div>
        </section>

        <section class="step-guide">
            <h3>✅ 事故直後の３つのステップ</h3>
            <div class="step-list">
                <div class="step-item">
                    <h4>STEP 1: 救護と安全確保</h4>
                    <p>怪我人の状態確認、ハザードランプと発炎筒で二次被害を防止。</p>
                </div>
                <div class="step-item">
                    <h4>STEP 2: 警察への連絡</h4>
                    <p>必ず110番に通報し、現場検証を依頼してください。</p>
                </div>
                <div class="step-item">
                    <h4>STEP 3: 記録と情報交換</h4>
                    <p>相手の連絡先と保険情報、現場写真をメモ機能で記録します。</p>
                </div>
            </div>

            <div class="memo-link">
                <a href="record.html" class="btn btn-large btn-success">
                    📝 現場メモに記録する (最速記録)
                </a>
            </div>
        </section>
        
        <section class="negotiation-promo">
            <h3>事故後の交渉で損をしないために</h3>
            <p>弁護士費用特約の確認と、適正な過失割合の知識を学びましょう。</p>
            <a href="negotiation.html" class="btn btn-secondary">
                ⚖️ 交渉ガイドへ進む
            </a>
        </section>
    </main>

    <script src="js/main.js"></script>
</body>
</html>



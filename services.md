---
layout: page
title: サービス内容
description: CS/Sales/Biz Opsの業務改善と戦略実装を、一貫してサポートします
---

<style>
/* 収益性セクション用スタイル */
.profitability-section {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
  padding: 60px 48px;
  border-radius: 8px;
  margin-bottom: 60px;
  border-left: 6px solid #e67e22;
}

.profitability-section h2 {
  font-size: 2rem;
  color: #2c3e50;
  margin-bottom: 24px;
  text-align: center;
}

.profitability-intro {
  font-size: 1.125rem;
  color: #7f8c8d;
  line-height: 1.8;
  text-align: center;
  max-width: 700px;
  margin: 0 auto 40px;
}

.profitability-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 40px;
  margin-top: 40px;
}

@media (max-width: 768px) {
  .profitability-content {
    grid-template-columns: 1fr;
  }
  
  .profitability-section {
    padding: 40px 24px;
  }
}

.profitability-problems,
.profitability-solutions {
  background-color: #ffffff;
  padding: 32px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.profitability-problems h3,
.profitability-solutions h3 {
  font-size: 1.25rem;
  color: #2c3e50;
  margin-bottom: 20px;
  padding-bottom: 12px;
  border-bottom: 2px solid #2c5aa0;
}

.profitability-problems ul,
.profitability-solutions ul {
  list-style: none;
  padding: 0;
}

.profitability-problems li,
.profitability-solutions li {
  padding: 12px 0;
  padding-left: 32px;
  position: relative;
  color: #7f8c8d;
  line-height: 1.7;
}

.profitability-problems li:before {
  content: "⚠";
  position: absolute;
  left: 0;
  color: #e67e22;
  font-size: 1.25rem;
}

.profitability-solutions li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #27ae60;
  font-weight: bold;
  font-size: 1.25rem;
}

.profitability-solutions li strong {
  color: #2c3e50;
  display: block;
  margin-bottom: 4px;
}

.profitability-quote {
  background-color: #fff3e0;
  padding: 24px;
  border-radius: 4px;
  border-left: 4px solid #e67e22;
  margin-top: 32px;
  text-align: center;
}

.profitability-quote p {
  font-size: 1.25rem;
  color: #2c3e50;
  font-weight: 600;
  margin: 0;
  font-style: italic;
}

.service-intro {
  text-align: center;
  max-width: 800px;
  margin: 0 auto 60px;
  font-size: 1.125rem;
  color: #7f8c8d;
  line-height: 1.8;
}

.services-list {
  max-width: 900px;
  margin: 0 auto;
}

.service-item {
  background-color: #f8f9fa;
  padding: 48px 40px;
  border-radius: 8px;
  margin-bottom: 32px;
  border-left: 6px solid #2c5aa0;
}

.service-header {
  display: flex;
  align-items: center;
  gap: 24px;
  margin-bottom: 24px;
}

.service-icon {
  font-size: 4rem;
  flex-shrink: 0;
}

.service-header h2 {
  font-size: 2rem;
  color: #2c3e50;
  margin: 0;
}

.service-description {
  color: #7f8c8d;
  line-height: 1.8;
  margin-bottom: 24px;
  font-size: 1.05rem;
}

.service-details h3 {
  font-size: 1.25rem;
  color: #2c3e50;
  margin-bottom: 16px;
  margin-top: 24px;
}

.service-details ul {
  list-style: none;
  padding: 0;
}

.service-details li {
  padding: 12px 0;
  padding-left: 32px;
  position: relative;
  color: #7f8c8d;
  line-height: 1.7;
}

.service-details li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #27ae60;
  font-weight: bold;
  font-size: 1.25rem;
}

.service-outcomes {
  background-color: #e8f2fc;
  padding: 24px;
  border-radius: 4px;
  margin-top: 24px;
}

.service-outcomes h4 {
  color: #2c5aa0;
  margin-bottom: 12px;
  font-size: 1.125rem;
}

.service-outcomes p {
  color: #2c3e50;
  margin: 0;
  line-height: 1.7;
}

.pricing-section {
  background-color: #f8f9fa;
  padding: 48px;
  border-radius: 8px;
  margin: 60px 0;
  text-align: center;
}

.pricing-section h2 {
  font-size: 2rem;
  margin-bottom: 24px;
  color: #2c3e50;
}

.pricing-section p {
  font-size: 1.125rem;
  color: #7f8c8d;
  line-height: 1.8;
  max-width: 700px;
  margin: 0 auto 32px;
}

.process-section {
  margin: 60px 0;
}

.process-section h2 {
  font-size: 2rem;
  text-align: center;
  margin-bottom: 48px;
  color: #2c3e50;
}

.process-steps {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 32px;
  max-width: 1200px;
  margin: 0 auto;
}

@media (max-width: 1024px) {
  .process-steps {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 640px) {
  .process-steps {
    grid-template-columns: 1fr;
  }
}

.process-step {
  text-align: center;
  position: relative;
  background-color: #f8f9fa;
  padding: 32px 24px;
  border-radius: 8px;
  transition: transform 0.3s, box-shadow 0.3s;
}

.process-step:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.1);
}

.process-step-number {
  width: 60px;
  height: 60px;
  background: linear-gradient(135deg, #2c5aa0 0%, #1e3a6f 100%);
  color: #ffffff;
  font-size: 1.5rem;
  font-weight: 700;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 16px;
}

.process-step h3 {
  font-size: 1.25rem;
  margin-bottom: 12px;
  color: #2c3e50;
  font-weight: 700;
}

.process-step p {
  color: #7f8c8d;
  line-height: 1.7;
  font-size: 0.95rem;
}
</style>

<!-- 🆕 収益性改善セクション（最上部に追加） -->
<div class="profitability-section">
  <h2>単なる効率化ではなく、営業利益向上を実現</h2>
  <p class="profitability-intro">
    業務改善は手段であり、最終目標は<strong>営業利益の向上</strong>です。<br>
    売上原価・販売費の最適化を通じて、持続可能な収益構造を構築します。
  </p>
  
  <div class="profitability-content">
    <div class="profitability-problems">
      <h3>よくある構造的問題</h3>
      <ul>
        <li>売上は伸びているのに、営業利益率が改善しない</li>
        <li>売上原価・販売費の管理が後回しになっている</li>
        <li>非効率な業務プロセスが、利益を圧迫している</li>
        <li>高スキル人材が単純作業に時間を奪われている</li>
      </ul>
    </div>
    
    <div class="profitability-solutions">
      <h3>私たちのアプローチ</h3>
      <ul>
        <li><strong>売上原価の削減</strong>業務自動化による人件費最適化</li>
        <li><strong>販売費の効率化</strong>営業プロセス改善による商談効率向上</li>
        <li><strong>営業利益率の改善</strong>コア業務への集中による収益性向上</li>
        <li><strong>ROI重視の実装</strong>投資回収期間3-4ヶ月を目安とした現実的提案</li>
      </ul>
    </div>
  </div>
  
  <div class="profitability-quote">
    <p>「自社のサービスの収益性、正しく把握されていますか？」</p>
  </div>
</div>

<div class="service-intro">
  <p>
    CS/Sales/Biz Opsに特化した業務改善と戦略実装を、戦略立案から実装・定着まで一貫してサポート。
    データドリブンなアプローチで、確実な成果を実現します。
  </p>
</div>

<div class="services-list">
  
  <div class="service-item">
    <div class="service-header">
      <div class="service-icon">
        <img src="{{ '/assets/images/icons/Task.svg' | relative_url }}" 
             alt="Task"
             style="height: 100px; width: 100px;">
      </div>
      <h2>業務自動化・効率化</h2>
    </div>
    
    <p class="service-description">
      定型業務の自動化により、工数削減とヒューマンエラー防止を実現。
      月20時間以上の工数削減実績があります。
    </p>
    
    <div class="service-details">
      <h3>提供内容</h3>
      <ul>
        <li>レポート作成の自動化（月20時間→0時間）</li>
        <li>データ連携・API開発（Salesforce、各種SaaS）</li>
        <li>議事録AI化（月80時間削減）</li>
        <li>ワークフロー設計・最適化</li>
        <li>Google Apps Script / Python開発</li>
      </ul>
    </div>
    
    <div class="service-outcomes">
      <h4>期待される成果</h4>
      <p>
        ✓ 月20-80時間の工数削減<br>
        ✓ ヒューマンエラーの撲滅<br>
        ✓ データ精度の向上<br>
        ✓ コア業務への集中
      </p>
    </div>
  </div>
  
  <div class="service-item">
    <div class="service-header">
      <div class="service-icon">
        <img src="{{ '/assets/images/icons/AI.svg' | relative_url }}"
             alt="AI"
             style="height: 100px; width: 100px;">
      </div>
      <h2>AI活用・DX推進</h2>
    </div>
    
    <p class="service-description">
      Claude API、Vertex AIを活用し、業務改善を加速。
      AIを「使う」だけでなく、実務に落とし込み、確実な成果を創出します。
    </p>
    
    <div class="service-details">
      <h3>提供内容</h3>
      <ul>
        <li>Claude API実装・活用支援</li>
        <li>Vertex AI導入・運用設計</li>
        <li>AI活用戦略策定</li>
        <li>カスタムAIソリューション開発</li>
        <li>社内AI活用推進・教育</li>
      </ul>
    </div>
    
    <div class="service-outcomes">
      <h4>期待される成果</h4>
      <p>
        ✓ AI業務適用の加速<br>
        ✓ 意思決定スピード向上<br>
        ✓ 顧客対応品質の向上<br>
        ✓ 競争優位性の確立
      </p>
    </div>
  </div>
  
  <div class="service-item">
    <div class="service-header">
      <div class="service-icon">
        <img src="{{ '/assets/images/icons/DB.svg' | relative_url }}"
             alt="DB"
             style="height: 100px; width: 100px;">
      </div>
      <h2>データ基盤構築</h2>
    </div>
    
    <p class="service-description">
      Salesforce連携、API開発、データ可視化まで。
      意思決定を支えるデータ基盤を構築します。
    </p>
    
    <div class="service-details">
      <h3>提供内容</h3>
      <ul>
        <li>Salesforce連携・カスタマイズ</li>
        <li>API設計・開発（Python/FastAPI）</li>
        <li>ダッシュボード構築</li>
        <li>データパイプライン設計</li>
        <li>データ分析基盤整備</li>
      </ul>
    </div>
    
    <div class="service-outcomes">
      <h4>期待される成果</h4>
      <p>
        ✓ データ駆動の意思決定<br>
        ✓ リアルタイム可視化<br>
        ✓ 部門間データ連携<br>
        ✓ 戦略的分析の高度化
      </p>
    </div>
  </div>
  
</div>

<div class="process-section">
  <h2>プロジェクトの進め方</h2>
  <div class="process-steps">
    <div class="process-step">
      <div class="process-step-number">1</div>
      <h3>課題ヒアリング</h3>
      <p>
        現状の業務フローを詳しくヒアリング。
        課題の本質を特定します。
      </p>
    </div>
    
    <div class="process-step">
      <div class="process-step-number">2</div>
      <h3>提案・設計</h3>
      <p>
        実行可能な施策を提案。
        投資対効果を明確化します。
      </p>
    </div>
    
    <div class="process-step">
      <div class="process-step-number">3</div>
      <h3>実装・テスト</h3>
      <p>
        段階的に実装を進め、
        現場での検証を重ねます。
      </p>
    </div>
    
    <div class="process-step">
      <div class="process-step-number">4</div>
      <h3>運用・定着</h3>
      <p>
        マニュアル整備と教育で
        確実な定着を支援します。
      </p>
    </div>
  </div>
</div>

<div class="pricing-section">
  <h2>料金体系</h2>
  <p>
    プロジェクトの規模と期間に応じて、柔軟な料金設定をご用意しています。<br>
    まずは無料相談で、貴社の課題とご予算をお聞かせください。
  </p>
  <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary btn-lg">
    無料相談を申し込む
  </a>
</div>

---
layout: page
title: About
---

<style>
.profile-section {
  display: grid;
  grid-template-columns: 300px 1fr;
  gap: 60px;
  margin-bottom: 60px;
  align-items: start;
}

@media (max-width: 768px) {
  .profile-section {
    grid-template-columns: 1fr;
    gap: 32px;
  }
}

.profile-image {
  width: 100%;
  border-radius: 8px;
  background-color: #f8f9fa;
  padding: 40px;
  text-align: center;
  font-size: 8rem;
}

.profile-content h2 {
  font-size: 2rem;
  margin-bottom: 16px;
  color: #2c3e50;
}

.profile-role {
  font-size: 1.25rem;
  color: #2c5aa0;
  font-weight: 500;
  margin-bottom: 24px;
}

.profile-content p {
  color: #7f8c8d;
  line-height: 1.8;
  margin-bottom: 16px;
}

.story-section {
  margin-bottom: 80px;
}

.story-section h2 {
  font-size: 2rem;
  margin-bottom: 32px;
  color: #2c3e50;
  text-align: center;
}

.story-intro {
  max-width: 800px;
  margin: 0 auto 48px;
  text-align: center;
  font-size: 1.125rem;
  color: #7f8c8d;
  line-height: 1.8;
}

.story-cards {
  display: grid;
  grid-template-columns: 1fr;
  gap: 40px;
  max-width: 900px;
  margin: 0 auto;
}

.story-card {
  background-color: #f8f9fa;
  padding: 40px;
  border-radius: 8px;
  border-left: 4px solid #2c5aa0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.story-number {
  font-size: 2.5rem;
  font-weight: 700;
  background: linear-gradient(135deg, #2c5aa0 0%, #6b5ca5 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 8px;
}

.story-label {
  font-size: 1.25rem;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 16px;
}

.story-detail {
  color: #7f8c8d;
  line-height: 1.8;
  margin-bottom: 16px;
}

.story-metrics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 16px;
  margin-top: 24px;
  padding-top: 24px;
  border-top: 1px solid #e1e8ed;
}

.metric-item {
  text-align: center;
}

.metric-value {
  font-size: 1.5rem;
  font-weight: 700;
  color: #e879b9;
  display: block;
  margin-bottom: 4px;
}

.metric-label {
  font-size: 0.875rem;
  color: #7f8c8d;
}

.expertise-section,
.approach-section {
  margin-bottom: 60px;
}

.expertise-section h2,
.approach-section h2 {
  font-size: 2rem;
  margin-bottom: 32px;
  color: #2c3e50;
  text-align: center;
}

.expertise-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 24px;
}

.expertise-card {
  background-color: #f8f9fa;
  padding: 32px 24px;
  border-radius: 8px;
  border-left: 4px solid #2c5aa0;
}

.expertise-card h3 {
  font-size: 1.25rem;
  margin-bottom: 12px;
  color: #2c3e50;
}

.expertise-card ul {
  list-style: none;
  padding: 0;
}

.expertise-card li {
  color: #7f8c8d;
  padding: 8px 0;
  padding-left: 24px;
  position: relative;
}

.expertise-card li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #27ae60;
  font-weight: bold;
}

.approach-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 32px;
}

.approach-card {
  background-color: #f8f9fa;
  padding: 40px 32px;
  border-radius: 8px;
  text-align: center;
}

.approach-number {
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
  margin: 0 auto 24px;
}

.approach-card h3 {
  font-size: 1.25rem;
  margin-bottom: 12px;
  color: #2c3e50;
}

.approach-card p {
  color: #7f8c8d;
  line-height: 1.7;
}
</style>

<div class="profile-section">
  <div class="profile-image">
    <img src="{{ '/assets/images/icons/preview_icon.svg' | relative_url }}" 
         alt="preview"
         style="width: 300px; height: 300px;">
  </div>
  <div class="profile-content">
    <h2>{{ site.company.full_name }}</h2>
    <p class="profile-role">{{ site.company.role }}</p>
    <p>
      前職（50名規模のベンチャー企業）で、CS/Sales/Biz Opsの業務プロセスを24ヶ月かけて再設計。<br>
      <strong>生産性246%向上、年間1,356時間の工数削減</strong>を実現しました。
    </p>
    <p>
      「技術のための技術」ではなく、<strong>ビジネス成果に直結する実装</strong>を重視。<br>
      現場経験があるからこそ、実務に即した実用的なソリューションを提供できます。
    </p>
  </div>
</div>

<div class="story-section">
  <h2>実際に創出した3つの成果</h2>
  <p class="story-intro">
    前職での24ヶ月間で、複数部署にわたる業務改善プロジェクトを推進。<br>
    それぞれ異なるアプローチで、確実な成果を実現しました。
  </p>
  
  <div class="story-cards">
    <!-- ストーリー1: 組織全体の生産性改革 -->
    <div class="story-card">
      <div class="story-number">246%</div>
      <div class="story-label">組織全体の生産性改革</div>
      <p class="story-detail">
        <strong>課題：</strong>属人化した業務プロセスにより、組織拡大の限界に直面。案件数増加に対し、人員を増やすしか手段がない状態。
      </p>
      <p class="story-detail">
        <strong>アプローチ：</strong>業務プロセスの完全可視化から開始し、ボトルネックを特定。24ヶ月かけて段階的に業務を標準化・自動化し、組織全体の働き方を変革。
      </p>
      <p class="story-detail">
        <strong>成果：</strong>ある部署で1人当たり生産性が246%向上。案件数170%増を達成しながら、人員は70%削減。投資回収は4ヶ月で完了。
      </p>
      <div class="story-metrics">
        <div class="metric-item">
          <span class="metric-value">170%増</span>
          <span class="metric-label">案件数増加</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">70%削減</span>
          <span class="metric-label">人員削減</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">4ヶ月</span>
          <span class="metric-label">投資回収</span>
        </div>
      </div>
    </div>
    
    <!-- ストーリー2: 営業活動の効率化 -->
    <div class="story-card">
      <div class="story-number">60分→10分</div>
      <div class="story-label">営業活動の効率化</div>
      <p class="story-detail">
        <strong>課題：</strong>営業準備（クライアント調査）に1件60分以上かかり、商談準備が営業活動のボトルネックに。質も属人的でばらつきが大きい状態。
      </p>
      <p class="story-detail">
        <strong>アプローチ：</strong>Claude APIを活用し、複数ソースからの情報収集・分析を自動化。営業担当の負荷を最小限に抑えつつ、調査の質と網羅性を向上。
      </p>
      <p class="story-detail">
        <strong>成果：</strong>クライアント調査時間を75%削減（60分→10-15分）。さらに調査の質が大幅に向上し、営業準備のボトルネック解消と成約率向上を同時実現。
      </p>
      <div class="story-metrics">
        <div class="metric-item">
          <span class="metric-value">75%削減</span>
          <span class="metric-label">調査時間</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">質も向上</span>
          <span class="metric-label">調査品質</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">3ヶ月</span>
          <span class="metric-label">投資回収</span>
        </div>
      </div>
    </div>
    
    <!-- ストーリー3: 定型業務の自動化 -->
    <div class="story-card">
      <div class="story-number">400時間+</div>
      <div class="story-label">定型業務の完全自動化</div>
      <p class="story-detail">
        <strong>課題：</strong>月次レポート作成に月20時間、データ入力に月13時間など、複数の定型業務が組織全体で年間1,000時間以上を消費。
      </p>
      <p class="story-detail">
        <strong>アプローチ：</strong>影響度の高い業務から段階的に自動化。GAS、Python、API連携を組み合わせ、工数対効果を最大化しながら実装。
      </p>
      <p class="story-detail">
        <strong>成果：</strong>レポート作成の完全自動化（月20時間→0時間）、データ連携の効率化（月13時間削減）など、年間400時間以上の工数を創出。
      </p>
      <div class="story-metrics">
        <div class="metric-item">
          <span class="metric-value">月20時間</span>
          <span class="metric-label">レポート自動化</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">月13時間</span>
          <span class="metric-label">データ連携</span>
        </div>
        <div class="metric-item">
          <span class="metric-value">400時間+</span>
          <span class="metric-label">年間削減</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="expertise-section">
  <h2>専門領域</h2>
  <div class="expertise-grid">
    <div class="expertise-card">
      <h3 style="display: flex; align-items: center; gap: 10px;">
      <img src="{{ '/assets/images/icons/Task.svg' | relative_url }}" 
           alt="Task"
           style="height: 30px; width: 30px;"> 
           業務自動化・効率化
      </h3>
      <ul>
        <li>レポート自動化</li>
        <li>データ連携開発</li>
        <li>議事録AI化</li>
        <li>ワークフロー最適化</li>
      </ul>
    </div>
    
    <div class="expertise-card">
      <h3 style="display: flex; align-items: center; gap: 10px;">
      <img src="{{ '/assets/images/icons/AI.svg' | relative_url }}" 
           alt="AI"
           style="height: 30px; width: 30px;">
           AI活用・DX推進
      </h3>
      <ul>
        <li>Claude API実装</li>
        <li>Vertex AI活用</li>
        <li>AI業務適用支援</li>
        <li>デジタル変革戦略</li>
      </ul>
    </div>
    
    <div class="expertise-card">
      <h3 style="display: flex; align-items: center; gap: 10px;">
      <img src="{{ '/assets/images/icons/DB.svg' | relative_url }}" 
           alt="DB"
           style="height: 30px; width: 30px;">
           データ基盤構築
      </h3>
      <ul>
        <li>Salesforce連携</li>
        <li>API開発</li>
        <li>データ可視化</li>
        <li>分析基盤整備</li>
      </ul>
    </div>
  </div>
</div>

<div class="approach-section">
  <h2>アプローチ</h2>
  <div class="approach-grid">
    <div class="approach-card">
      <div class="approach-number">1</div>
      <h3>課題の本質を理解</h3>
      <p>
        表面的な問題ではなく、根本原因を特定。
        現場へのヒアリングを通じて、真の課題を明らかにします。
      </p>
    </div>
    
    <div class="approach-card">
      <div class="approach-number">2</div>
      <h3>実行可能な施策を設計</h3>
      <p>
        理想論ではなく、現実的に実装可能な施策を提案。
        段階的アプローチでリスクを最小化します。
      </p>
    </div>
    
    <div class="approach-card">
      <div class="approach-number">3</div>
      <h3>成果まで伴走</h3>
      <p>
        計画だけで終わらせず、実装・定着まで支援。
        確実なROI実現を目指します。
      </p>
    </div>
  </div>
</div>

<div class="cta-center" style="margin-top: 80px;">
  <h2 style="margin-bottom: 24px;">まずはお気軽にご相談ください</h2>
  <a href="{{ '/contact/' | relative_url }}" class="btn btn-primary btn-lg">
    無料相談を申し込む
  </a>
</div>

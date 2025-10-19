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

.expertise-section,
.experience-section,
.approach-section {
  margin-bottom: 60px;
}

.expertise-section h2,
.experience-section h2,
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

.timeline {
  max-width: 800px;
  margin: 0 auto;
}

.timeline-item {
  padding-left: 40px;
  border-left: 2px solid #e1e8ed;
  padding-bottom: 40px;
  position: relative;
}

.timeline-item:last-child {
  padding-bottom: 0;
}

.timeline-item:before {
  content: "";
  width: 16px;
  height: 16px;
  background-color: #2c5aa0;
  border-radius: 50%;
  position: absolute;
  left: -9px;
  top: 0;
}

.timeline-year {
  font-size: 1.125rem;
  font-weight: 700;
  color: #2c5aa0;
  margin-bottom: 8px;
}

.timeline-content h3 {
  font-size: 1.25rem;
  margin-bottom: 8px;
  color: #2c3e50;
}

.timeline-content p {
  color: #7f8c8d;
  line-height: 1.7;
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
      ビジネスサイドでの技術活用経験を活かし、<strong>本来やるべき仕事に集中できる環境を作ります</strong>
    </p>
    <p>
      「技術のための技術」ではなく、<strong>ビジネス成果に直結する実装</strong>を重視。<br>
      生産性246%向上、月113時間（約14営業日分）の工数削減など、
      確実なROIを3-4ヶ月で実現してきました。
    </p>
    <p>
      技術実装とビジネス成果の両方を理解しているからこそ、<br>
      現場に即した実用的なソリューションを提供できます。
    </p>
  </div>
</div>

<div class="expertise-section">
  <h2>専門領域</h2>
  <div class="expertise-grid">
    <div class="expertise-card">
      <h3>🔧 業務自動化・効率化</h3>
      <ul>
        <li>レポート自動化</li>
        <li>データ連携開発</li>
        <li>議事録AI化</li>
        <li>ワークフロー最適化</li>
      </ul>
    </div>
    
    <div class="expertise-card">
      <h3>🤖 AI活用・DX推進</h3>
      <ul>
        <li>Claude API実装</li>
        <li>Vertex AI活用</li>
        <li>AI業務適用支援</li>
        <li>デジタル変革戦略</li>
      </ul>
    </div>
    
    <div class="expertise-card">
      <h3>📊 データ基盤構築</h3>
      <ul>
        <li>Salesforce連携</li>
        <li>API開発</li>
        <li>データ可視化</li>
        <li>分析基盤整備</li>
      </ul>
    </div>
  </div>
</div>

<div class="experience-section">
  <h2>経歴</h2>
  <div class="timeline">
    <div class="timeline-item">
      <div class="timeline-year">現在</div>
      <div class="timeline-content">
        <h3>DriVonacci 代表</h3>
        <p>
          CS/Sales/Biz Opsに特化した業務改善コンサルティング。
          データドリブンなアプローチで、確実な成果創出を支援。
        </p>
      </div>
    </div>
    
    <div class="timeline-item">
      <div class="timeline-year">前職</div>
      <div class="timeline-content">
        <h3>Biz Ops / 業務改善推進</h3>
        <p>
          事業部門での業務改善・自動化推進を担当。
          年間1,356時間の工数削減を実現。
        </p>
      </div>
    </div>
    
    <div class="timeline-item">
      <div class="timeline-year">それ以前</div>
      <div class="timeline-content">
        <h3>カスタマーサクセス / セールス</h3>
        <p>
          現場での実務経験を通じて、CS/Sales特有の課題と
          実用的なソリューションの知見を蓄積。
        </p>
      </div>
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

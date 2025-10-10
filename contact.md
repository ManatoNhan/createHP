---
layout: page
title: お問い合わせ
description: 業務改善のご相談は、お気軽にお問い合わせください
---

<style>
.contact-intro {
  text-align: center;
  max-width: 700px;
  margin: 0 auto 60px;
}

.contact-intro h2 {
  font-size: 1.75rem;
  margin-bottom: 16px;
  color: #2c3e50;
}

.contact-intro p {
  font-size: 1.125rem;
  color: #7f8c8d;
  line-height: 1.8;
}

.contact-methods {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 32px;
  margin-bottom: 60px;
}

.contact-card {
  background-color: #f8f9fa;
  padding: 40px 32px;
  border-radius: 8px;
  text-align: center;
  transition: transform 0.3s;
}

.contact-card:hover {
  transform: translateY(-8px);
}

.contact-icon {
  font-size: 3rem;
  margin-bottom: 16px;
}

.contact-card h3 {
  font-size: 1.25rem;
  margin-bottom: 12px;
  color: #2c3e50;
}

.contact-card p {
  color: #7f8c8d;
  margin-bottom: 20px;
  line-height: 1.7;
}

.contact-card a {
  display: inline-block;
  color: #2c5aa0;
  font-weight: 500;
  word-break: break-all;
}

.contact-form-section {
  max-width: 700px;
  margin: 0 auto;
  background-color: #f8f9fa;
  padding: 48px;
  border-radius: 8px;
}

.contact-form-section h2 {
  font-size: 1.75rem;
  margin-bottom: 24px;
  color: #2c3e50;
  text-align: center;
}

.form-group {
  margin-bottom: 24px;
}

.form-group label {
  display: block;
  font-weight: 500;
  margin-bottom: 8px;
  color: #2c3e50;
}

.form-group input,
.form-group textarea,
.form-group select {
  width: 100%;
  padding: 12px 16px;
  border: 1px solid #e1e8ed;
  border-radius: 4px;
  font-size: 1rem;
  font-family: inherit;
  background-color: #ffffff;
  transition: border-color 0.3s;
}

.form-group input:focus,
.form-group textarea:focus,
.form-group select:focus {
  outline: none;
  border-color: #2c5aa0;
}

.form-group textarea {
  min-height: 150px;
  resize: vertical;
}

.form-note {
  font-size: 0.875rem;
  color: #7f8c8d;
  margin-top: 8px;
}

.form-required {
  color: #e74c3c;
  margin-left: 4px;
}

.form-submit {
  text-align: center;
  margin-top: 32px;
}

.faq-section {
  margin-top: 80px;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.faq-section h2 {
  font-size: 2rem;
  text-align: center;
  margin-bottom: 40px;
  color: #2c3e50;
}

.faq-item {
  margin-bottom: 24px;
  border-bottom: 1px solid #e1e8ed;
  padding-bottom: 24px;
}

.faq-item:last-child {
  border-bottom: none;
}

.faq-question {
  font-size: 1.125rem;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 12px;
}

.faq-answer {
  color: #7f8c8d;
  line-height: 1.8;
}
</style>

<div class="contact-intro">
  <h2>まずはお気軽にご相談ください</h2>
  <p>
    業務改善に関するお悩みやご質問など、どんなことでもお気軽にお問い合わせください。<br>
    初回相談は60分、完全無料です。
  </p>
</div>

<div class="contact-methods">
  <div class="contact-card">
    <div class="contact-icon">✉️</div>
    <h3>メールでのお問い合わせ</h3>
    <p>
      24時間受付中。通常1営業日以内にご返信いたします。
    </p>
    <a href="mailto:{{ site.email }}">{{ site.email }}</a>
  </div>
  
  <div class="contact-card">
    <div class="contact-icon">📝</div>
    <h3>お問い合わせフォーム</h3>
    <p>
      下記フォームからもお問い合わせいただけます。
    </p>
    <a href="#contact-form">フォームに移動</a>
  </div>
</div>

<div class="contact-form-section" id="contact-form">
  <h2>お問い合わせフォーム</h2>
  
  <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <div class="form-group">
      <label for="name">
        お名前<span class="form-required">*</span>
      </label>
      <input type="text" id="name" name="name" required>
    </div>
    
    <div class="form-group">
      <label for="company">
        会社名
      </label>
      <input type="text" id="company" name="company">
    </div>
    
    <div class="form-group">
      <label for="email">
        メールアドレス<span class="form-required">*</span>
      </label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div class="form-group">
      <label for="phone">
        電話番号
      </label>
      <input type="tel" id="phone" name="phone">
    </div>
    
    <div class="form-group">
      <label for="inquiry-type">
        お問い合わせ種別<span class="form-required">*</span>
      </label>
      <select id="inquiry-type" name="inquiry-type" required>
        <option value="">選択してください</option>
        <option value="consultation">無料相談を申し込む</option>
        <option value="service">サービスについて質問</option>
        <option value="pricing">料金について質問</option>
        <option value="other">その他</option>
      </select>
    </div>
    
    <div class="form-group">
      <label for="message">
        お問い合わせ内容<span class="form-required">*</span>
      </label>
      <textarea id="message" name="message" required></textarea>
      <p class="form-note">
        具体的な課題や、ご希望のサービス内容などをお書きください。
      </p>
    </div>
    
    <div class="form-submit">
      <button type="submit" class="btn btn-primary btn-lg">
        送信する
      </button>
    </div>
  </form>
</div>

<div class="faq-section">
  <h2>よくあるご質問</h2>
  
  <div class="faq-item">
    <div class="faq-question">Q. 初回相談は本当に無料ですか？</div>
    <div class="faq-answer">
      はい、初回相談（60分）は完全無料です。貴社の課題をお聞きし、最適なアプローチをご提案いたします。
    </div>
  </div>
  
  <div class="faq-item">
    <div class="faq-question">Q. どのような企業が対象ですか？</div>
    <div class="faq-answer">
      CS/Sales/Biz Opsの業務改善を検討されている企業様が対象です。企業規模は問いません。スタートアップから中堅企業まで、幅広くご支援しています。
    </div>
  </div>
  
  <div class="faq-item">
    <div class="faq-question">Q. プロジェクト期間はどれくらいですか？</div>
    <div class="faq-answer">
      プロジェクトの規模により異なりますが、小規模な自動化施策で1-2ヶ月、包括的な業務改善で3-6ヶ月程度が目安です。まずは小さく始めて、効果を確認しながら拡大することも可能です。
    </div>
  </div>
  
  <div class="faq-item">
    <div class="faq-question">Q. 遠隔地でも対応可能ですか？</div>
    <div class="faq-answer">
      はい、オンラインでの打ち合わせ・支援が可能です。全国どこからでもご相談いただけます。
    </div>
  </div>
  
  <div class="faq-item">
    <div class="faq-question">Q. 料金体系について教えてください</div>
    <div class="faq-answer">
      プロジェクトの規模と期間に応じて、柔軟な料金設定をご用意しています。まずは無料相談で貴社の課題とご予算をお聞かせください。最適なプランをご提案いたします。
    </div>
  </div>
  
  <div class="faq-item">
    <div class="faq-question">Q. 技術的な知識がなくても大丈夫ですか？</div>
    <div class="faq-answer">
      もちろんです。技術的な部分は全てお任せください。ビジネスサイドの方にもわかりやすく説明し、現場で使いこなせる状態までサポートいたします。
    </div>
  </div>
</div>

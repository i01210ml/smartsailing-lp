> **CONFIDENTIAL: PRIVATE REPOSITORY ONLY**
> This file and the `instagram/` folder contain sensitive marketing strategies.
> **Ensure the repository is set to PRIVATE before pushing.**
>
> **社外秘: プライベートリポジトリ限定**
> 本ファイルおよび `instagram/` フォルダは機密情報を含みます。
> 必ずリポジトリが **Private（非公開）** 設定になっていることを確認してからプッシュしてください。

# SmartSailing iOS App Marketing Plan / マーケティングプラン

## 1. Product Overview (Vision) / プロダクト概要
- **Core Value Proposition / コア・バリュープロポジション**:
  - **Digitize Performance**: Shift from intuition-based training to data-driven performance visualization.
    - (パフォーマンスのデジタル化: 感覚に頼ったトレーニングから、データ駆動型のパフォーマンス可視化へシフトする)
  - **Objective Reflection**: Enable objective review of "good" and "bad" moves through digital metrics.
    - (客観的な振り返り: デジタル指標を通じて、自分の動きが「良かったのか」「悪かったのか」を客観的にレビューできるようにする)
  - **Accessibility**: Immediate performance review upon returning to land via automatic cloud sync.
    - (即時性: クラウド自動同期により、陸に上がってすぐにパフォーマンスを確認できる)

- **Target Audience(Primary) / ターゲットオーディエンス (プライマリ)**:
  - **Japanese University Students**: Competitors aiming for victory in the Intercollegiate Sailing Championship (In-kare).
    - (日本の大学生: インカレ（全日本学生ヨット選手権大会）での優勝を目指す選手たち)
  - **Focus**: Team championships, high-stakes competition.
    - (フォーカス: 団体戦、真剣勝負の世界)

- **Target Audience(Secondary) / ターゲットオーディエンス (セカンダリ)**:
  - **Olympic Hopefuls**: Sailors aiming for the highest level.
    - (オリンピックを目指すセーラー: 最高レベルを目指すアスリート)
  - **Junior Athletes & Parents**: Young aspiring talents and their supporting parents.
    - (ジュニア選手と保護者: 若き才能と、それを支える親たち)

## 2. Market Analysis / 市場分析
- **Competitors / 競合**:
  - Generic speed tracking tools (GPS watches, standard tracker apps).
    - (一般的なスピードトラッキングツール)
  - **Difference**: They show speed but lack sailing-specific context (wind, VMG).
    - (違い: それらは単に「速度」を表示するだけで、セーリングに特有の文脈（風、VMG）が欠けている)

- **Competitive Advantage (USP) / 競争優位性**:
  - **Cloud Automation**: Automatic data upload allows for immediate post-sail analysis on land without manual transfer.
    - (クラウド自動化: 自動データアップロードにより、手動転送の手間なく、陸上で即座に分析が可能)
  - **Sailing Specificity**: Visualizes the relationship with "Wind".
    - (セーリング特化: 「風」との関係性を可視化)
    - **Key Metrics**: VMG (Velocity Made Good) visualization.
      - (主要指標: VMGの可視化)
    - **Manuever Analysis**: Automated extraction and judgment (Success/Failure) of Tacks and Jibes.
      - (マニューバ分析: タックとジャイブの自動抽出と判定)

## 3. Marketing Strategy / マーケティング戦略
- **Channels / チャネル**:
  - University Sailing Clubs / Federations. (大学ヨット部 / 学連)
  - Social Media targeting sailing communities. (セーリングコミュニティをターゲットとしたSNS)

- **Content Strategy / コンテンツ戦略**:
  - Showcasing "Difference in Growth" between intuition vs. data.
    - (「感覚 vs データ」による成長の違いを示す)
  - Testimonials from Intercollegiate winners or elite coaches.
    - (インカレ優勝者やエリートコーチの推薦コメント)
  - Tutorials on how to analyze Tacks/Jibes using the app.
    - (アプリを使ってタック/ジャイブを分析する方法のチュートリアル)

## 4. Website Requirements (for Web Coder) / Webサイト要件事項
- **Reference Implementation / 参照実装**: `/Users/yokoi/work/SmartSailing/SmartSailingFor_iOS/LandingPage/index.html`
- **Design Theme / デザインテーマ**: **Dark Mode Scientific (ダークモード・サイエンティフィック)**
  - **Background**: `#17181D` (Dark Grey/Black / ダークグレー)
  - **Accent**: `#00AEEF` (Cyan Blue / シアンブルー) - "The Science of Speed"
  - **Typography**: Inter, Noto Sans JP
  - **Cards**: `#252525`

- **Structure & Copy / 構成とコピー**:
  1.  **Hero**: "Visualise of Speed & Performance" / "The Science of Speed". Image: `iPhone 16 Plus-02_TrackTab.png`.
      - (日本語コピー: `index.html` 参照)
  2.  **Problem/Solution**: "End of intuition-only sailing".
      - (日本語コピー: "セーリングをもっと楽しく、早く上達したい！感性を、ビジュアライズされた「確信」へ。")
  3.  **Feature 1 (Maneuver)**: "Automated Maneuver Analysis" (Jibe/Tack). Image: `iPhone 16 Plus-03_JibeTab.png`.
  4.  **Feature 2 (Track)**: "Detailed Track Visualization" (Heatmap). Image: `iPhone 16 Plus-02_TrackTab.png`.
  5.  **Feature 3 (Polar)**: "Polar Performance Analysis" (VMG & Boat Speed). Image: `iPhone 16 Plus-05_PolarTab.png`.
      - (日本語コピー: "Polar性能曲線分析: 風向に対するボートスピードとVMGを可視化。")

- **Assets Path**: `/Users/yokoi/work/SmartSailing/SmartSailingFor_iOS/LandingPage/assets/`
- **Instruction**: Use the exact Japanese copy found in `index.html` for existing sections, but create new copy for Polar feature based on the above.
  - (指示: 既存セクションは `index.html` のコピーを使用し、Polar機能については上記のコピーを新規作成して使用すること)

## 5. SNS Pre-launch Strategy / SNSプレローンチ戦略 (Build in Public)

**Objective**: Build a loyal fan base over 1 month by sharing the development journey and passion, and engaging users to gauge feature interest.
(目的: 1ヶ月間で開発の旅路と情熱を共有し、ユーザーを巻き込みながら機能への関心度を測ることで、熱狂的なファンベースを構築する)

### Strategy Phases (1 Month Timeline) / 戦略フェーズ

#### Phase 1: The "WHY" & Passion (Week 1) / 情熱とビジョンの共有
- **Concept**: "Why we are building this."
  - (コンセプト: なぜ我々はこれを作るのか)
- **Content**:
  - Personal stories of the "Visionary" (You). Struggles with intuition-only sailing.
    - (ビジョナリー(あなた)の個人的な物語。感覚頼りのセーリングの葛藤)
  - "Declaration of Development": "We are starting to build the ultimate tool for sailors."
    - (開発宣言: 「セーラーのための究極のツールを作り始める」という宣言)
- **Goal**: Empathy & Initial Followers. (共感と初期フォロワーの獲得)

#### Phase 2: Feature Spotlights (Week 2-3) / 機能の深掘りと検証
- **Concept**: "One Feature at a Time."
  - (コンセプト: ひとつひとつ、丁寧に)
- **Content**:
  - **VMG Focus**: Explain the logic, show the chart. Ask "Do you check VMG?"
    - (VMGフォーカス: ロジック解説、チャート公開。「VMGってチェックしてる？」と問いかけ)
  - **Maneuver Focus**: Show Tack/Jibe analysis. Ask "Which is harder for you?"
    - (マニューバフォーカス: タック/ジャイブ分析。「どっちが苦手？」)
  - **Polar Focus**: The ultimate performance curve.
    - (Polarフォーカス: 究極の性能曲線)
- **Goal**: Gauge interest via Likes/Comments/Polls. (いいね/コメ/投票で関心度を測る)

#### Phase 3: Countdown & Call to Action (Week 4) / カウントダウン
- **Concept**: "Ready to Sail."
  - (コンセプト: 出航の刻)
- **Content**:
  - Beta tester recruitment or "Waitlist" signup.
    - (ベータテスター募集またはウェイティングリスト登録)
  - Final polish and "Making of" behind-the-scenes.
    - (最後の仕上げや、「メイキング」裏話)
- **Goal**: Conversion to actual users. (実ユーザーへの転換)

### Channel Focus / チャネルフォーカス
- **Instagram**: Main stage for visual storytelling (Reels/Stories). Use "Poll" stickers heavily.
  - (Instagram: 視覚的ストーリーテリングのメイン舞台。投票スタンプを多用する)
  - (X: テキストベースの「開発日誌」、リアルタイムな思考の共有)

## 6. Verification & KPIs / 検証とKPI

**Goal**: 1,000 Followers in 1 Month.
(目標: 1ヶ月でフォロワー1,000人)

### Monitoring Metrics / 監視指標 (24h after posting)

1.  **Reach (Discovery)**: Are we reaching new people?
    *   **Target**: >50% reach from non-followers (via Reels/Hashtags).
    *   (リーチ: フォロワー外からの流入が50%以上あるか？リールやハッシュタグの効果検証)

2.  **Engagement (Interest)**: Does "Passion" resonate?
    *   **KPI**: Engagement Rate (Likes + Saves / Reach) > **5%**.
    *   **Critical Metric**: **"Saves" (保存数)**. High saves = Useful content (Tips/Analysis).
    *   (エンゲージメント: 情熱は伝わっているか？ 保存数は「役立つ」の証)

3.  **Interaction (Community)**: Are they talking back?
    *   **Target**: >10 Sticker Responses (Stories) or Comments per post.
    *   (インタラクション: ストーリーズのスタンプ回答やコメントが10件以上あるか？)

### Verification Flow / 検証フロー
1.  **Post**: Publish content (Feed/Reel + Story).
2.  **Wait**: 24 hours.
3.  **Record**: Fill in the "Results" section in `instagram_post_log.md`.
4.  **Action**:
    *   If Engagement < 3%: Review the **Hook** (First 3 sec / First image).
    *   If Reach is low: Review **Hashtags** and **Posting Time**.


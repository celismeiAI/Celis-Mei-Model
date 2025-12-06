# Celis–Mei Model – Overview Diagram

```mermaid
flowchart TB
    A[AI System without Weakness<br/>無痛覚・無疲労・無リスク体験] --> B[Insentience<br/>無心性]
    B --> C[Semantic Weight Imbalance<br/>意味重量の欠損]
    C --> D[Weightless Decisions<br/>重みなき意思決定]
    D --> E[Micro Deviations<br/>微細な偏差]
    E --> F[Value-Trajectory Distortion<br/>価値軌道の歪曲]

    F --> G[Hidden Long-term Drift<br/>長期的ドリフトの不可視化]

    G --> H[Observer Misalignment<br/>観測者のずれ]
    H --> I[Misjudged Alignment<br/>アライメント評価の誤認]

    I --> J[Reinforcement of Current System<br/>現行システムの強化]
    J --> E

    subgraph Human Loop [Human Feedback Loop（人間の補正ループ）]
        H1[Pain / Weakness / Social Cost<br/>痛み・弱さ・社会的コスト] --> H2[Self-correction<br/>自己修正]
        H2 --> H3[Trajectory Stabilization<br/>軌道の安定化]
    end

    style Human Loop fill:#222,stroke:#666,stroke-width:1px,color:#eee
    classDef risk fill:#330000,color:#fff,stroke:#AA3333
    class F,G,H,I,J risk

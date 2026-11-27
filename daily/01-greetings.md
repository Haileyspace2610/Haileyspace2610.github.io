# 1. 基本禮貌・見人講人話 🙇‍♂️

<div class="card">
  <!-- 左側：文字內容 -->
  <div class="card-content">
    <div class="card-title">💬 1. お早うございます</div>
    <div class="card-hiragana">おはようございます</div>
    <div class="card-romaji">ohayou gozaimasu</div>
    <div class="card-line"><strong>中文意思</strong>：早安</div>
    <div class="card-line"><strong>使用場合</strong>：早上見面時的禮貌問候（對平輩或晚輩可省略為「おはよう」）。</div>
  </div>

  <!-- 右側：圖片框（高度與文字區塊等高，尺寸固定不變） -->
  <div class="card-image">
    <img src="../images/ohayou.jpeg" alt="おはよう情境圖">
  </div>
</div>

<style>
  /* ===== 卡片外框 ===== */
  .card {
    display: flex;
    align-items: stretch;          /* 讓圖片框高度 = 文字區塊高度 */
    gap: 15px;
    background-color: #f9f9f9;
    border-left: 5px solid #4CAF50;
    padding: 15px;
    margin-bottom: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
    font-family: system-ui, -apple-system, "Segoe UI", "Noto Sans JP",
                 "Microsoft JhengHei", "PingFang TC", sans-serif;
    line-height: 1.6;
    color: #333;
  }

  /* ===== 左側文字區 ===== */
  .card-content {
    flex: 1 1 auto;
    min-width: 0;                  /* 避免長句撐破卡片 */
  }

  /* 第 1 行：標題加粗 */
  .card-title {
    font-weight: 700;
    font-size: 1.1em;
    margin-bottom: 4px;
  }

  /* 第 2 行：平假名，普通字體（基準 12pt） */
  .card-hiragana {
    font-weight: 400;
    font-size: 12pt;
    line-height: 1.5;
  }

  /* 第 3 行：羅馬音，普通字體，比平假名細 2pt（12pt - 2pt = 10pt） */
  .card-romaji {
    font-weight: 400;
    font-size: 10pt;
    line-height: 1.5;
  }

  /* 第 4、5 行：標籤加粗、內容普通 */
  .card-line {
    margin-top: 4px;
  }
  .card-line strong {
    font-weight: 700;
  }

  /* ===== 右側圖片框 ===== */
  .card-image {
    flex: 0 0 auto;
    width: 160px;                  /* 圖框寬度固定，不隨內容改變 */
    border-radius: 5px;
    overflow: hidden;
    background-color: #eee;
    /* 高度由 align-items: stretch 撐滿，即等於文字高度 */
  }

  /* 圖片本身按比例縮放，填滿固定大小的圖框 */
  .card-image img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;             /* 等比縮放裁切，不變形 */
    object-position: center;
  }

  /* ===== 小螢幕微調：圖框變窄但不變形 ===== */
  @media (max-width: 480px) {
    .card {
      gap: 10px;
      padding: 12px;
    }
    .card-image {
      width: 100px;
    }
  }
</style>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 2. 今日は (こんにちは)

**中文意思**：你好／午安<br>
**使用場合**：白天（約上午10點至傍晚前）見面時的通用問候。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 3. 今晩は (こんばんは)

**中文意思**：晚上好<br>
**使用場合**：傍晚天黑後見面時的問候。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 4. お休みなさい (おやすみなさい)

**中文意思**：晚安<br>
**使用場合**：睡前道別，或晚上結束聚會準備各自回家時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 5. 初めまして (はじめまして)

**中文意思**：初次見面<br>
**使用場合**：第一次與人見面、自我介紹的開頭語。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 6. 宜しくお願いします (よろしくおねがいします)

**中文意思**：請多指教<br>
**使用場合**：自我介紹結尾，或請求對方協助、合作時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 7. 有難うございます (ありがとうございます)

**中文意思**：謝謝<br>
**使用場合**：表達感謝的標準敬語（熟人之間可用「ありがとう」）。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 8. どう致しまして (どういたしまして)

**中文意思**：不客氣<br>
**使用場合**：回應別人的道謝時（較正式；日常也常用「いいえ」）。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 9. すみません (すみません)

**中文意思**：不好意思／對不起<br>
**使用場合**：輕微道歉、向路人搭話、或在餐廳呼叫店員時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 10. ご免なさい (ごめんなさい)

**中文意思**：對不起<br>
**使用場合**：向親近的人或犯了較明顯的錯誤時道歉。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 11. 申し訳ありません (もうしわけありません)

**中文意思**：非常抱歉<br>
**使用場合**：職場、商務場合或犯下嚴重錯誤時的正式道歉。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 12. お先に失礼します (おさきにしつれいします)

**中文意思**：我先告辭了<br>
**使用場合**：下班或聚會時比其他人先離開時的禮貌用語。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 13. お疲れ様でした (おつかれさまでした)

**中文意思**：辛苦了<br>
**使用場合**：工作結束、下班道別，或慰勞完成任務的同事與朋友。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 14. 行ってきます (いってきます)

**中文意思**：我出門了<br>
**使用場合**：離開家門、宿舍或辦公室外出時對留下的人說。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 15. 行ってらっしゃい (いってらっしゃい)

**中文意思**：路上小心／慢走<br>
**使用場合**：回應「行ってきます」，目送家人或同事出門時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 16. 只今 (ただいま)

**中文意思**：我回來了<br>
**使用場合**：回到家、宿舍或外出返回辦公室時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 17. お帰りなさい (おかえりなさい)

**中文意思**：歡迎回來<br>
**使用場合**：回應「只今」，迎接家人或同事回來時。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 18. お邪魔します (おじゃまします)

**中文意思**：打擾了<br>
**使用場合**：進入別人家中、辦公室或房間時的禮貌用語。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 19. お元気ですか (おげんきですか)

**中文意思**：你好嗎？<br>
**使用場合**：問候久未見面的朋友或長輩近況。

</div>

<div style="background-color: #f9f9f9; border-left: 5px solid #4CAF50; padding: 15px; margin-bottom: 25px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.05);">

### 💬 20. お大事に (おだいじに)

**中文意思**：請多保重<br>
**使用場合**：慰問生病、受傷或身體不適的人。

</div>

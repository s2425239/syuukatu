<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>就活コンディショニング・ナビ</title>
<script src="https://cdn.tailwindcss.com"></script>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;500;700;900&family=Outfit:wght@500;600;700;800&display=swap');
  body { font-family: 'Noto Sans JP', sans-serif; background: #f4f6fb; color: #1e293b; }
  .font-num { font-family: 'Outfit', sans-serif; font-variant-numeric: tabular-nums; }
  .eyebrow { font-family: 'Outfit', sans-serif; letter-spacing: .14em; text-transform: uppercase; }
  input[type=range] {
    -webkit-appearance: none; appearance: none;
    width: 100%; height: 6px; border-radius: 3px;
    background: #e2e8f0; outline: none; cursor: pointer;
  }
  input[type=range]::-webkit-slider-thumb {
    -webkit-appearance: none; appearance: none;
    width: 18px; height: 18px; border-radius: 50%;
    background: #4f46e5; cursor: pointer; border: 2px solid #fff;
    box-shadow: 0 1px 4px rgba(79,70,229,0.35);
  }
  input[type=range].orange::-webkit-slider-thumb { background: #ea580c; box-shadow: 0 1px 4px rgba(234,88,12,0.35); }
  input[type=date] { font-family: 'Outfit','Noto Sans JP',sans-serif; }
  .fade-in { animation: fadeIn 0.35s ease; }
  @keyframes fadeIn { from { opacity:0; transform:translateY(6px); } to { opacity:1; transform:translateY(0); } }
  .card { background:#fff; border:1px solid #eceef3; }
  .soft { box-shadow: 0 1px 2px rgba(16,24,40,.04), 0 8px 24px -16px rgba(16,24,40,.12); }
  .navbtn { transition: all .15s ease; }
  .navbtn:hover { background:#eef2ff; color:#4f46e5; }
  .navbtn:active { transform: scale(.92); }
  @media (prefers-reduced-motion: reduce) { *{animation:none!important;transition:none!important} }
</style>
</head>
<body class="min-h-screen">

<!-- ナビゲーション -->
<nav class="bg-white/90 backdrop-blur border-b border-slate-100 py-3 px-5 sticky top-0 z-50">
  <div class="max-w-5xl mx-auto flex justify-between items-center">
    <div class="flex items-center gap-2.5">
      <span class="w-9 h-9 rounded-xl bg-indigo-50 flex items-center justify-center">
        <svg width="22" height="22" viewBox="0 0 28 28">
          <ellipse cx="14" cy="15" rx="10" ry="9" fill="#dbeafe" stroke="#3b82f6" stroke-width="1.2"/>
          <path d="M7 12 Q8.5 9 11 10 Q12 7.5 14 8.5 Q16 7.5 17 10 Q19.5 9 21 12" fill="none" stroke="#3b82f6" stroke-width="0.9" stroke-linecap="round"/>
          <circle cx="11" cy="17" r="1.2" fill="#1d4ed8"/>
          <circle cx="17" cy="17" r="1.2" fill="#1d4ed8"/>
          <path d="M11.5 20 Q14 22 16.5 20" fill="none" stroke="#1d4ed8" stroke-width="1" stroke-linecap="round"/>
        </svg>
      </span>
      <div class="leading-tight">
        <div class="font-bold text-[15px] text-slate-800">就活コンディショニング・ナビ</div>
        <div class="text-[10px] text-slate-400 eyebrow">Realtime Stress Risk Monitor</div>
      </div>
      <span class="text-[10px] bg-indigo-50 text-indigo-600 px-2 py-0.5 rounded-full font-medium ml-1">β版</span>
    </div>
    <span class="text-[11px] text-teal-600 bg-teal-50 px-3 py-1 rounded-full font-medium hidden sm:block">大学3〜4年 就活生向け</span>
  </div>
</nav>

<div class="max-w-5xl mx-auto px-4 py-6 space-y-6">

  <!-- ヒーロー：キャラ + 豆知識 -->
  <div>
    <div class="eyebrow text-[10px] text-slate-400 mb-2 ml-1">Partner</div>
    <div class="card soft rounded-2xl p-6 flex flex-col sm:flex-row items-center gap-6">
      <div class="flex flex-col items-center gap-2 shrink-0" style="width:120px">
        <div id="brainScale" style="transform-origin:center bottom;transition:transform .5s ease">
        <div id="brainAura" class="rounded-full p-1.5 transition-colors duration-500" style="background:#eff6ff">
          <svg id="brainSvg" width="76" height="76" viewBox="0 0 80 80" role="img" aria-label="脳みそキャラクター ノウくん">
            <ellipse id="brainBg" cx="40" cy="44" rx="28" ry="24" fill="#dbeafe" stroke="#3b82f6" stroke-width="1.5"/>
            <ellipse cx="40" cy="41" rx="23" ry="19" fill="#eff6ff" stroke="#93c5fd" stroke-width="1"/>
            <path d="M22 34 Q24 27 31 29 Q33 23 40 25 Q47 23 49 29 Q56 27 58 34" fill="none" stroke="#3b82f6" stroke-width="1.2" stroke-linecap="round"/>
            <path d="M24 41 Q28 37 33 39 Q37 35 43 39 Q48 37 52 41 Q56 39 56 43" fill="none" stroke="#93c5fd" stroke-width="1" stroke-linecap="round"/>
            <circle id="eyeL" cx="32" cy="47" r="3" fill="#1d4ed8"/>
            <circle id="eyeR" cx="48" cy="47" r="3" fill="#1d4ed8"/>
            <path id="mouth" d="M33 55 Q40 60 47 55" fill="none" stroke="#1d4ed8" stroke-width="1.8" stroke-linecap="round"/>
          </svg>
        </div>
        </div>
        <span class="text-xs text-slate-500 font-bold">ノウくん</span>
        <div id="stageBadge" class="text-[10px] font-bold text-indigo-600 bg-indigo-50 border border-indigo-100 rounded-full px-2 py-0.5">Lv.1</div>
        <div class="w-full">
          <div class="h-1.5 bg-slate-100 rounded-full overflow-hidden"><div id="growthBar" class="h-full bg-indigo-500 rounded-full transition-all duration-500" style="width:0%"></div></div>
          <div id="growthText" class="text-[9px] text-slate-400 mt-1 text-center leading-tight"></div>
        </div>
      </div>
      <div class="flex-1 w-full">
        <div class="text-[10px] font-medium text-indigo-500 mb-1.5 eyebrow">Today's Tip</div>
        <p id="tipText" class="text-sm text-slate-700 leading-relaxed bg-indigo-50 rounded-xl px-4 py-3 border border-indigo-100"></p>
        <button id="breathOpenBtn" class="mt-3 inline-flex items-center gap-1.5 text-[12px] font-bold text-indigo-600 bg-white border border-indigo-200 rounded-full px-4 py-2 hover:bg-indigo-50 transition-colors active:scale-95">
          <span style="display:inline-block;width:8px;height:8px;border-radius:9999px;background:#6366f1"></span>
          ノウくんと深呼吸する
        </button>
      </div>
    </div>
  </div>

  <!-- メインレイアウト -->
  <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">

    <!-- 左：入力パネル -->
    <div class="space-y-4">
      <div class="card soft rounded-2xl p-6">
        <h2 class="font-bold text-slate-800 mb-5 flex items-center gap-2">
          <svg class="w-4 h-4 text-indigo-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"/></svg>
          ログを記録
        </h2>

        <!-- 日付（前後送り対応） -->
        <div class="mb-5">
          <label class="block text-[10px] font-medium text-slate-500 mb-1.5 eyebrow">記録日</label>
          <div class="flex items-center gap-2">
            <button id="prevDay" aria-label="前の日へ" class="navbtn w-9 h-9 shrink-0 rounded-xl border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center font-bold">◀</button>
            <input type="date" id="targetDate"
              class="flex-1 min-w-0 px-3 py-2 rounded-xl border border-slate-200 bg-slate-50 text-sm font-medium text-slate-700 text-center focus:outline-none focus:ring-2 focus:ring-indigo-200">
            <button id="nextDay" aria-label="次の日へ" class="navbtn w-9 h-9 shrink-0 rounded-xl border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center font-bold">▶</button>
          </div>
          <div id="dateMeta" class="text-xs mt-2 text-center font-medium"></div>
        </div>

        <!-- 睡眠スコア -->
        <div class="mb-6">
          <div class="flex justify-between items-center mb-2">
            <label class="text-sm font-medium text-slate-700">睡眠スコア（基礎資源）</label>
            <span id="sleepVal" class="text-2xl font-bold text-indigo-600 font-num">70</span>
          </div>
          <input type="range" id="sleepInput" min="0" max="100" value="70" step="1">
          <div class="flex justify-between text-[11px] text-slate-400 mt-1">
            <span>ボロボロ (0)</span><span>バッチリ (100)</span>
          </div>
        </div>

        <!-- 精神的負荷 -->
        <div class="mb-6">
          <div class="flex justify-between items-center mb-2">
            <label class="text-sm font-medium text-slate-700">精神的負荷</label>
            <span id="mLoadVal" class="text-xl font-bold text-indigo-500 font-num">1</span>
          </div>
          <input type="range" id="mLoadInput" min="1" max="5" value="1" step="1">
          <div id="mGuide" class="text-xs text-indigo-400 mt-1.5 min-h-[1rem] leading-snug"></div>
        </div>

        <!-- 物理的負荷 -->
        <div class="mb-7">
          <div class="flex justify-between items-center mb-2">
            <label class="text-sm font-medium text-slate-700">物理的負荷</label>
            <span id="pLoadVal" class="text-xl font-bold text-orange-500 font-num">1</span>
          </div>
          <input type="range" id="pLoadInput" min="1" max="5" value="1" step="1" class="orange">
          <div id="pGuide" class="text-xs text-orange-400 mt-1.5 min-h-[1rem] leading-snug"></div>
        </div>

        <button id="saveBtn"
          class="w-full bg-slate-900 hover:bg-indigo-700 text-white font-bold py-3 rounded-xl transition-all active:scale-95 text-sm">
          保存して判定する
        </button>
      </div>

      <!-- Fitbitインポート -->
      <div class="bg-indigo-900 rounded-2xl p-5 text-white soft">
        <div class="flex items-center gap-2 mb-2">
          <svg class="w-4 h-4 text-indigo-300" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-8l-4-4m0 0L8 8m4-4v12"/></svg>
          <span class="font-bold text-sm">Fitbitデータを統合</span>
        </div>
        <p class="text-xs text-indigo-200 mb-3 leading-relaxed">Fitbitの睡眠CSVを読み込んで睡眠スコアを自動反映します。</p>
        <input type="file" id="fitbitCsv" accept=".csv" class="hidden">
        <button onclick="document.getElementById('fitbitCsv').click()"
          class="w-full bg-indigo-500 hover:bg-indigo-400 text-white text-sm font-medium py-2.5 rounded-xl transition-all border border-indigo-400/30">
          CSVファイルを選択
        </button>
        <div id="importStatus" class="text-xs text-indigo-300 mt-2 text-center min-h-[1rem]"></div>
      </div>
    </div>

    <!-- 右：スコア・アドバイス・グラフ -->
    <div class="lg:col-span-2 space-y-5">

      <!-- 判定見出し -->
      <div class="flex items-end justify-between flex-wrap gap-2">
        <div>
          <div class="eyebrow text-[10px] text-slate-400 mb-0.5">Realtime Risk</div>
          <h2 class="font-bold text-lg text-slate-800">リアルタイムストレスリスク判定</h2>
        </div>
        <div id="activeDateChip" class="text-xs font-medium text-slate-500 bg-white border border-slate-200 rounded-full px-3 py-1 font-num"></div>
      </div>

      <!-- スコアカード -->
      <div class="grid grid-cols-2 gap-4">
        <div class="card soft rounded-2xl p-5 border-l-4 border-l-indigo-500">
          <div class="text-[11px] font-medium text-slate-400 eyebrow mb-1">精神リスク（脳疲労）</div>
          <div class="flex items-baseline gap-1 mb-2">
            <span id="mScore" class="text-5xl font-bold text-slate-900 font-num">--</span>
            <span class="text-sm text-slate-300 font-num font-semibold">/ 500</span>
          </div>
          <div id="mBadge" class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-bold"></div>
        </div>
        <div class="card soft rounded-2xl p-5 border-l-4 border-l-orange-500">
          <div class="text-[11px] font-medium text-slate-400 eyebrow mb-1">物理リスク（身体疲労）</div>
          <div class="flex items-baseline gap-1 mb-2">
            <span id="pScore" class="text-5xl font-bold text-slate-900 font-num">--</span>
            <span class="text-sm text-slate-300 font-num font-semibold">/ 500</span>
          </div>
          <div id="pBadge" class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-bold"></div>
        </div>
      </div>

      <!-- 週間トレンド note -->
      <div class="card soft rounded-2xl p-4 flex items-start gap-3">
        <span class="w-1 h-full min-h-[2.5rem] bg-teal-400 rounded-full shrink-0"></span>
        <div>
          <div class="eyebrow text-[10px] text-teal-600 mb-1">Weekly Trend</div>
          <p id="weeklyNote" class="text-sm text-slate-600 leading-relaxed"></p>
        </div>
      </div>

      <!-- アドバイスパネル -->
      <div id="advicePanel" class="rounded-2xl p-5 border transition-all duration-300 fade-in">
        <div class="flex items-center gap-2 mb-2.5">
          <svg width="20" height="20" viewBox="0 0 28 28">
            <ellipse cx="14" cy="15" rx="10" ry="9" fill="#fff" stroke="currentColor" stroke-width="1.4" opacity=".55"/>
            <circle cx="11" cy="16" r="1.1" fill="currentColor"/>
            <circle cx="17" cy="16" r="1.1" fill="currentColor"/>
          </svg>
          <span id="adviceEyebrow" class="eyebrow text-[10px] font-bold">ノウくんの処方箋アドバイス</span>
        </div>
        <div id="adviceTitle" class="font-bold text-base mb-1"></div>
        <div id="adviceBody" class="text-sm leading-relaxed"></div>
      </div>

      <!-- グラフ -->
      <div class="card soft rounded-2xl p-5">
        <div class="flex justify-between items-start mb-3 gap-2 flex-wrap">
          <div>
            <div class="eyebrow text-[10px] text-slate-400 mb-0.5">7-Day Log</div>
            <h3 class="font-bold text-slate-700 text-sm">ストレス・稼働負荷スコア推移（7日分）</h3>
            <div id="chartRange" class="text-[11px] text-slate-400 font-num mt-0.5"></div>
          </div>
          <div class="flex items-center gap-1">
            <button id="chartPrevWeek" title="前の7日へ" aria-label="前の7日へ" class="navbtn w-8 h-8 rounded-lg border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center text-sm font-bold">«</button>
            <button id="chartPrevDay" title="前の日へ" aria-label="前の日へ" class="navbtn w-8 h-8 rounded-lg border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center text-sm font-bold">‹</button>
            <button id="chartToday" title="最新へ" aria-label="最新の記録へ" class="navbtn h-8 px-2.5 rounded-lg border border-slate-200 bg-slate-50 text-slate-500 text-[11px] font-bold">最新</button>
            <button id="chartNextDay" title="次の日へ" aria-label="次の日へ" class="navbtn w-8 h-8 rounded-lg border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center text-sm font-bold">›</button>
            <button id="chartNextWeek" title="次の7日へ" aria-label="次の7日へ" class="navbtn w-8 h-8 rounded-lg border border-slate-200 bg-slate-50 text-slate-500 flex items-center justify-center text-sm font-bold">»</button>
          </div>
        </div>
        <div class="flex gap-3 text-[11px] text-slate-500 mb-3 justify-end">
          <span class="flex items-center gap-1.5"><span class="w-3 h-0.5 bg-indigo-500 inline-block rounded"></span>精神</span>
          <span class="flex items-center gap-1.5"><span class="w-3 inline-block" style="border-top:2px dashed #f97316"></span>物理</span>
        </div>
        <div style="position:relative;height:240px">
          <canvas id="mainChart" role="img" aria-label="7日間の精神リスクと物理リスクの推移グラフ">7日間のリスクスコアの推移を表示しています。</canvas>
        </div>
        <p class="text-[11px] text-slate-400 mt-2 text-right">※ 同じブラウザ内に記録が保存されます（β版）</p>
      </div>
    </div>
  </div>

  <!-- COR理論セクション -->
  <div class="card soft rounded-2xl p-6">
    <h2 class="font-bold text-slate-800 mb-4 flex items-center gap-2">
      <span class="w-1 h-6 bg-indigo-500 rounded-full"></span>
      理論的背景：資源保存理論（COR理論）
    </h2>
    <div class="grid sm:grid-cols-2 gap-4 mb-5">
      <div class="bg-rose-50 rounded-xl p-4 border border-rose-100">
        <div class="font-bold text-rose-700 text-sm mb-1">● 喪失の螺旋（Loss Spiral）</div>
        <p class="text-xs text-rose-600 leading-relaxed">睡眠などの資源が不足した状態で高い負荷をかけると、資源をさらに失い一気にメンタルが崩れる現象。このツールはその前に気づくためのブレーキです。</p>
      </div>
      <div class="bg-emerald-50 rounded-xl p-4 border border-emerald-100">
        <div class="font-bold text-emerald-700 text-sm mb-1">● 獲得の螺旋（Gain Spiral）</div>
        <p class="text-xs text-emerald-600 leading-relaxed">資源が豊富な時は挑戦が成功を呼び、さらなる自信や成果を生みます。スコアが良い日は積極的に動いていいサインです。</p>
      </div>
    </div>
    <div class="bg-slate-900 text-white rounded-xl p-4 text-center">
      <div class="text-[10px] text-slate-400 mb-2 eyebrow">リスクスコア計算式</div>
      <div class="font-mono text-base font-bold">
        Risk = <span class="text-indigo-400">負荷（1〜5）</span> × (100 − <span class="text-emerald-400">睡眠スコア</span>)
      </div>
      <p class="text-xs text-slate-400 mt-2 italic">睡眠資源が少ない時ほど同じ負荷でもリスクが乗数的に高まるロジック（ホブフォル, COR理論）</p>
    </div>
  </div>

  <!-- フッター -->
  <footer class="text-center py-6 text-xs text-slate-400">
    © 2026 Musashino University AI Submajor PJ-3 / 開発：遠坂直人
  </footer>

  <!-- 深呼吸ガイド（マインドフルネス） -->
  <div id="breathOverlay" style="display:none;position:fixed;inset:0;background:rgba(15,23,42,.55);z-index:100;align-items:center;justify-content:center;padding:24px;">
    <div class="rounded-2xl soft" style="background:#fff;max-width:340px;width:100%;padding:28px;text-align:center;">
      <div class="eyebrow text-[10px] text-indigo-500 mb-1">Breathing</div>
      <h3 class="font-bold text-slate-800 mb-1">ノウくんと深呼吸</h3>
      <p class="text-[11px] text-slate-400 mb-5 leading-relaxed">円のふくらみに合わせて呼吸してみよう。<br>数回くりかえして落ち着いたら、そっと閉じてね。</p>
      <div style="height:190px;display:flex;align-items:center;justify-content:center;">
        <div id="breathCircle" style="width:160px;height:160px;border-radius:9999px;background:radial-gradient(circle at 50% 38%, #c7d2fe, #6366f1);transform:scale(0.55);transition:transform 4s ease-in-out;display:flex;align-items:center;justify-content:center;">
          <div>
            <div id="breathLabel" style="color:#fff;font-weight:700;font-size:18px;">吸って</div>
            <div id="breathCount" style="color:#e0e7ff;font-size:13px;margin-top:2px;">4</div>
          </div>
        </div>
      </div>
      <div id="breathSub" class="text-[12px] text-slate-600 font-medium mt-3 mb-1">鼻からゆっくり</div>
      <div class="text-[10px] text-slate-400 mb-5">くりかえした呼吸：<span id="breathCycles">0</span> 回</div>
      <button id="breathCloseBtn" class="w-full bg-slate-900 text-white font-bold py-2.5 rounded-xl text-sm hover:bg-slate-800 transition-colors active:scale-95">とじる</button>
    </div>
  </div>

</div>

<script>
const STORAGE_KEY = 'job_hunt_conditioning_v8';
let dataHistory = JSON.parse(localStorage.getItem(STORAGE_KEY)) || [];

const WD = ['日','月','火','水','木','金','土'];

const mGuides = {
  1:'就活予定なし。通常の講義や趣味のみ。',
  2:'企業HP閲覧、ES下書きなど自分のペースで作業。',
  3:'ES締切当日、GD、説明会への参加。',
  4:'面接、テストセンター、1日中の就活作業。',
  5:'最終面接、不採用直後、徹夜でのES作成。'
};
const pGuides = {
  1:'在宅のみ、または近所への外出程度。',
  2:'大学への通学、1時間程度の移動。',
  3:'スーツでの企業訪問、数時間の外出。',
  4:'説明会ハシゴ、他県への移動、1万歩超え。',
  5:'宿泊移動、深夜帰宅、体力が限界の状態。'
};
const tips = [
  '面接前に深呼吸を3回するだけで心拍数が下がるよ！',
  '緊張したら肩を後ろにぐるっと回してみて。血流が良くなるよ。',
  '就寝1時間前にスマホを置くと寝つきが格段に早くなるよ！',
  'カーテンを少し開けて寝ると朝の目覚めが自然に良くなるよ。',
  '面接後は好きなものを食べてOK。頑張った自分を褒めよう！',
  '水をしっかり飲むだけで集中力がアップするよ。',
  '移動中は好きな音楽やポッドキャストで気分転換しよう。',
  '15分の仮眠は疲労回復にすごく効果的だよ。アラームをセットして！',
  '面接の前日は新しいことをやらず、復習だけにするのがコツだよ。',
  '朝ごはんを食べると脳のパフォーマンスが上がるよ！'
];

const sleepInput = document.getElementById('sleepInput');
const mLoadInput = document.getElementById('mLoadInput');
const pLoadInput = document.getElementById('pLoadInput');
const targetDate = document.getElementById('targetDate');
const dateMeta = document.getElementById('dateMeta');
const activeDateChip = document.getElementById('activeDateChip');

document.getElementById('tipText').textContent = tips[Math.floor(Math.random() * tips.length)];

function toISO(d){
  return d.getFullYear() + '-' + String(d.getMonth()+1).padStart(2,'0') + '-' + String(d.getDate()).padStart(2,'0');
}
targetDate.value = toISO(new Date());

function getStatus(score) {
  if (score <= 100) return { text:'良好', en:'Optimal', type:'safe' };
  if (score <= 250) return { text:'注意', en:'Caution', type:'warn' };
  return { text:'警戒', en:'Critical', type:'danger' };
}

function applyBadge(el, type, st) {
  const classes = {
    safe: 'bg-emerald-100 text-emerald-800',
    warn: 'bg-amber-100 text-amber-800',
    danger: 'bg-rose-100 text-rose-800'
  };
  const dot = { safe:'#10b981', warn:'#f59e0b', danger:'#f43f5e' };
  el.className = 'inline-flex items-center gap-1.5 px-3 py-1 rounded-full text-xs font-bold ' + classes[type];
  el.innerHTML = `<span class="w-1.5 h-1.5 rounded-full" style="background:${dot[type]}"></span>${st.en}（${st.text}の判定）`;
}

function applyAdvice(type, title, body) {
  const panel = document.getElementById('advicePanel');
  const eb = document.getElementById('adviceEyebrow');
  const tEl = document.getElementById('adviceTitle');
  const bEl = document.getElementById('adviceBody');
  const styles = {
    safe:   { panel:'bg-emerald-50 border-emerald-200', title:'text-emerald-800', body:'text-emerald-700', eb:'text-emerald-600' },
    warn:   { panel:'bg-amber-50 border-amber-200',   title:'text-amber-800',   body:'text-amber-700', eb:'text-amber-600' },
    danger: { panel:'bg-rose-50 border-rose-200',     title:'text-rose-800',    body:'text-rose-700', eb:'text-rose-600' }
  };
  const s = styles[type];
  panel.className = 'rounded-2xl p-5 border transition-all duration-300 fade-in ' + s.panel;
  eb.className = 'eyebrow text-[10px] font-bold ' + s.eb;
  tEl.className = 'font-bold text-base mb-1 ' + s.title;
  tEl.textContent = title;
  bEl.className = 'text-sm leading-relaxed ' + s.body;
  bEl.textContent = body;
}

// ノウくんの表情＆色を状態に連動
function updateBrainFace(type, maxScore) {
  const mouth = document.getElementById('mouth');
  const eyeL = document.getElementById('eyeL');
  const eyeR = document.getElementById('eyeR');
  const bg = document.getElementById('brainBg');
  const aura = document.getElementById('brainAura');
  const palette = {
    safe:   { fill:'#d1fae5', stroke:'#10b981', aura:'#ecfdf5' },
    warn:   { fill:'#fef3c7', stroke:'#f59e0b', aura:'#fffbeb' },
    danger: { fill:'#ffe4e6', stroke:'#f43f5e', aura:'#fff1f2' }
  };
  const p = palette[type];
  bg.setAttribute('fill', p.fill);
  bg.setAttribute('stroke', p.stroke);
  aura.style.background = p.aura;
  if (maxScore <= 100) {
    mouth.setAttribute('d', 'M33 55 Q40 60 47 55');
    eyeL.setAttribute('r', '3'); eyeR.setAttribute('r', '3');
  } else if (maxScore <= 250) {
    mouth.setAttribute('d', 'M33 57 Q40 57 47 57');
    eyeL.setAttribute('r', '2.5'); eyeR.setAttribute('r', '2.5');
  } else {
    mouth.setAttribute('d', 'M33 59 Q40 55 47 59');
    eyeL.setAttribute('r', '2'); eyeR.setAttribute('r', '2');
  }
}

// === ノウくんの成長（睡眠が良くリスクが低い日ほど育つ）===
const STAGES = [
  { name: 'たまご',     min: 0,  scale: 0.82 },
  { name: 'ひよこ脳',   min: 6,  scale: 0.93 },
  { name: 'げんき脳',   min: 18, scale: 1.05 },
  { name: 'マスター脳', min: 40, scale: 1.18 }
];
// その日の成長ポイント：合計リスクが低い（＝よく休めた）ほど多い
function dayGrowthPoints(rec) {
  const total = (rec.mScore || 0) + (rec.pScore || 0);
  if (total <= 120) return 3;   // よく休めた日
  if (total <= 300) return 1;   // ふつうの日
  return 0;                     // 無理が多い日は増えない
}
function totalGrowthPoints() {
  return dataHistory.reduce((s, r) => s + dayGrowthPoints(r), 0);
}
function stageInfo(points) {
  let idx = 0;
  for (let i = 0; i < STAGES.length; i++) if (points >= STAGES[i].min) idx = i;
  return { idx: idx, cur: STAGES[idx], next: STAGES[idx + 1] || null, points: points };
}
function updateGrowth() {
  const info = stageInfo(totalGrowthPoints());
  document.getElementById('stageBadge').textContent = 'Lv.' + (info.idx + 1) + ' ' + info.cur.name;
  const scaleEl = document.getElementById('brainScale');
  if (scaleEl) scaleEl.style.transform = 'scale(' + info.cur.scale + ')';
  const bar = document.getElementById('growthBar');
  const txt = document.getElementById('growthText');
  if (info.next) {
    const span = info.next.min - info.cur.min;
    const prog = Math.max(0, Math.min(100, Math.round(((info.points - info.cur.min) / span) * 100)));
    bar.style.width = prog + '%';
    txt.textContent = 'あと' + (info.next.min - info.points) + 'ポイントで成長！';
  } else {
    bar.style.width = '100%';
    txt.textContent = '最大まで成長したよ！';
  }
}

// 日付の曜日・記録有無の表示
function updateDateMeta() {
  const iso = targetDate.value;
  const d = new Date(iso + 'T00:00:00');
  const wd = WD[d.getDay()];
  const wdColor = d.getDay() === 0 ? 'text-rose-500' : d.getDay() === 6 ? 'text-blue-500' : 'text-slate-500';
  const has = dataHistory.some(x => x.date === iso);
  const state = has
    ? '<span class="text-emerald-600">● 記録済み</span>'
    : '<span class="text-slate-400">○ 未記録</span>';
  dateMeta.innerHTML = `<span class="${wdColor} font-bold">${wd}曜日</span> ・ ${state}`;
  activeDateChip.textContent = `${iso.replace(/-/g,'/')}（${wd}）`;
}

// その日の保存データをスライダーへ読み込み（無ければ初期値）
function loadDay(iso) {
  const rec = dataHistory.find(d => d.date === iso);
  if (rec) {
    sleepInput.value = rec.sleep;
    mLoadInput.value = rec.mLoad != null ? rec.mLoad : 1;
    pLoadInput.value = rec.pLoad != null ? rec.pLoad : 1;
  } else {
    sleepInput.value = 70;
    mLoadInput.value = 1;
    pLoadInput.value = 1;
  }
}

// 日付を delta 日ずらす
function shiftDate(delta) {
  const d = new Date(targetDate.value + 'T00:00:00');
  d.setDate(d.getDate() + delta);
  targetDate.value = toISO(d);
  loadDay(targetDate.value);
  updateDateMeta();
  updateUI();
}

// 週間トレンドの一言（表示中の7日間の記録を対象にする）
function updateWeeklyNote(records) {
  const el = document.getElementById('weeklyNote');
  const sorted = [...(records || [])].sort((a,b) => new Date(a.date) - new Date(b.date));
  if (sorted.length < 3) {
    el.textContent = 'この期間は記録が3日分未満です。記録を増やすと、ここに傾向（安定・改善・悪化）が表示されるよ。';
    return;
  }
  const totals = sorted.map(d => d.mScore + d.pScore);
  const avg = Math.round(totals.reduce((a,b)=>a+b,0) / totals.length);
  const half = Math.floor(totals.length / 2);
  const firstAvg = totals.slice(0, half).reduce((a,b)=>a+b,0) / half;
  const lastAvg = totals.slice(-half).reduce((a,b)=>a+b,0) / half;
  const diff = lastAvg - firstAvg;
  if (avg <= 150 && Math.abs(diff) < 40) {
    el.textContent = `今週のスコアは安定的に推移しています（平均 ${avg}）。資源の獲得スパイラルが効いている良い状態です。`;
  } else if (diff <= -40) {
    el.textContent = `週の前半より後半でリスクが下がっています（平均 ${avg}）。うまく休息を取れていて、回復傾向です。`;
  } else if (diff >= 40) {
    el.textContent = `週の後半にかけてリスクが上昇しています（平均 ${avg}）。疲労が蓄積しはじめているので、早めの休息を。`;
  } else {
    el.textContent = `今週の平均リスクは ${avg}。負荷が高めの日が混ざっています。無理が続かないよう気をつけて。`;
  }
}

function updateUI() {
  const sleep = parseInt(sleepInput.value);
  const mLoad = parseInt(mLoadInput.value);
  const pLoad = parseInt(pLoadInput.value);

  document.getElementById('sleepVal').textContent = sleep;
  document.getElementById('mLoadVal').textContent = mLoad;
  document.getElementById('pLoadVal').textContent = pLoad;
  document.getElementById('mGuide').textContent = mGuides[mLoad];
  document.getElementById('pGuide').textContent = pGuides[pLoad];

  const ms = Math.round(mLoad * (100 - sleep));
  const ps = Math.round(pLoad * (100 - sleep));
  const mS = getStatus(ms);
  const pS = getStatus(ps);

  document.getElementById('mScore').textContent = ms;
  document.getElementById('pScore').textContent = ps;
  applyBadge(document.getElementById('mBadge'), mS.type, mS);
  applyBadge(document.getElementById('pBadge'), pS.type, pS);

  const sorted = [...dataHistory].sort((a,b) => new Date(a.date) - new Date(b.date));
  const prev = sorted.length >= 2 ? sorted[sorted.length - 2] : (sorted.length === 1 ? sorted[0] : null);
  const improved = prev !== null && (ms + ps) < (prev.mScore + prev.pScore);

  let title = '', body = '', advType = 'safe';

  if (mS.type === 'safe' && pS.type === 'safe') {
    title = (improved ? 'やったね！昨日より改善してるよ！ ' : '') + '獲得の螺旋状態！今は頑張り時だよ';
    body = '内的資源がしっかり蓄積されているよ。今日は難しいESや第一志望の企業研究に全力で投資しよう！';
    advType = 'safe';
  } else {
    advType = (mS.type === 'danger' || pS.type === 'danger') ? 'danger' : 'warn';
    title = (improved ? 'やったね！昨日より改善してるよ。' : '') + '今日は少し無理しないようにしよう';
    const parts = [];
    if (mS.type !== 'safe') {
      const bed = ms > 250 ? '22時' : ms > 150 ? '23時' : '0時';
      parts.push(`今夜は${bed}までに寝ると明日が楽になるよ。SNSを閉じてマインドフルネスを5分やってみて。`);
    }
    if (pS.type !== 'safe') {
      parts.push('お風呂にゆっくり浸かって、15分だけ仮眠をとろう。体の回復が明日の活力につながるよ！');
    }
    body = parts.join(' / ');
  }

  applyAdvice(advType, title, body);
  const maxScore = Math.max(ms, ps);
  const maxType = getStatus(maxScore).type;
  updateBrainFace(maxType, maxScore);
}

// グラフの表示位置（表示している7日間の末尾の日付）。記録日とは独立。
let chartEnd;
function latestRecordISO() {
  if (!dataHistory.length) return toISO(new Date());
  return dataHistory.map(d => d.date).sort().slice(-1)[0];
}
function clampChartEnd(iso) {
  const today = toISO(new Date());
  return iso > today ? today : iso;   // 今日より先には進めない
}
function shiftChart(deltaDays) {
  const d = new Date(chartEnd + 'T00:00:00');
  d.setDate(d.getDate() + deltaDays);
  chartEnd = clampChartEnd(toISO(d));
  refreshChart();
}

// グラフ初期化
const ctx = document.getElementById('mainChart').getContext('2d');
const mainChart = new Chart(ctx, {
  type: 'line',
  data: {
    labels: [],
    datasets: [
      {
        label: '精神リスク',
        data: [],
        borderColor: '#6366f1',
        backgroundColor: 'rgba(99,102,241,0.08)',
        tension: 0.35, borderWidth: 2.5,
        pointRadius: 5, pointBackgroundColor: '#6366f1',
        fill: true
      },
      {
        label: '物理リスク',
        data: [],
        borderColor: '#f97316',
        backgroundColor: 'transparent',
        tension: 0.35, borderWidth: 2.5,
        pointRadius: 5, pointBackgroundColor: '#f97316',
        borderDash: [6, 4]
      }
    ]
  },
  options: {
    responsive: true,
    maintainAspectRatio: false,
    scales: {
      y: {
        beginAtZero: true, max: 500,
        grid: { color: 'rgba(148,163,184,0.12)' },
        ticks: { font: { size: 11 }, color: '#94a3b8' },
        title: { display: true, text: 'リスク値（高いほど危険）', font: { size: 10 }, color: '#94a3b8' }
      },
      x: {
        grid: { display: false },
        ticks: { font: { size: 11 }, color: '#94a3b8', autoSkip: false, maxRotation: 45 }
      }
    },
    plugins: { legend: { display: false } }
  }
});

function refreshChart() {
  if (!chartEnd) chartEnd = clampChartEnd(latestRecordISO());
  // chartEnd を末尾にした連続7日間を作る
  const end = new Date(chartEnd + 'T00:00:00');
  const days = [];
  for (let i = 6; i >= 0; i--) {
    const d = new Date(end);
    d.setDate(end.getDate() - i);
    days.push(toISO(d));
  }
  const recs = days.map(iso => dataHistory.find(d => d.date === iso) || null);

  mainChart.data.labels = days.map(iso => {
    const dt = new Date(iso + 'T00:00:00');
    return iso.split('-').slice(1).join('/') + `(${WD[dt.getDay()]})`;
  });
  // 記録のない日は null（グラフ上は空白）
  mainChart.data.datasets[0].data = recs.map(r => r ? r.mScore : null);
  mainChart.data.datasets[1].data = recs.map(r => r ? r.pScore : null);
  mainChart.update();

  // 表示範囲ラベル
  const s = days[0].split('-').slice(1).join('/');
  const e = days[6].split('-').slice(1).join('/');
  document.getElementById('chartRange').textContent = `${s} 〜 ${e}`;

  // 「今日」より先には進めないので、進むボタンを無効化
  const atLatest = chartEnd >= toISO(new Date());
  ['chartNextDay','chartNextWeek'].forEach(id => {
    const b = document.getElementById(id);
    b.disabled = atLatest;
    b.classList.toggle('opacity-30', atLatest);
    b.classList.toggle('cursor-not-allowed', atLatest);
  });

  // トレンドの一言は「表示中の期間」を対象にする
  updateWeeklyNote(recs.filter(Boolean));
}

// 保存ボタン
document.getElementById('saveBtn').addEventListener('click', () => {
  const prevStageIdx = stageInfo(totalGrowthPoints()).idx;
  const date = targetDate.value;
  const sleep = parseInt(sleepInput.value);
  const mLoad = parseInt(mLoadInput.value);
  const pLoad = parseInt(pLoadInput.value);
  const mScore = Math.round(mLoad * (100 - sleep));
  const pScore = Math.round(pLoad * (100 - sleep));
  const idx = dataHistory.findIndex(d => d.date === date);
  const entry = { date, sleep, mLoad, pLoad, mScore, pScore };
  if (idx !== -1) dataHistory[idx] = entry;
  else dataHistory.push(entry);
  localStorage.setItem(STORAGE_KEY, JSON.stringify(dataHistory));
  chartEnd = clampChartEnd(date);   // 記録した日が見えるようグラフを移動
  refreshChart();
  updateDateMeta();
  updateUI();
  updateGrowth();

  const earned = dayGrowthPoints(entry);
  const newStageIdx = stageInfo(totalGrowthPoints()).idx;
  let msg = '記録しました！';
  if (earned >= 3) msg += '\nよく休めたね！ノウくんが ' + earned + 'ポイント成長したよ。';
  else if (earned >= 1) msg += '\nノウくんが ' + earned + 'ポイント成長したよ。';
  else msg += '\n今日は無理が多めかも。まずはしっかり休もう。';
  if (newStageIdx > prevStageIdx) msg += '\n🎉 ノウくんが「' + STAGES[newStageIdx].name + '」に成長した！';
  alert(msg);
});

// Fitbit CSVインポート
document.getElementById('fitbitCsv').addEventListener('change', function(e) {
  const file = e.target.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = function(ev) {
    const text = ev.target.result;
    const lines = text.split('\n');
    const headers = lines[0].split(',').map(h => h.replace(/"/g,'').trim());
    const dateIdx = headers.findIndex(h => h.includes('Start Time') || h.includes('Date'));
    const scoreIdx = headers.findIndex(h => h.includes('Sleep Score') || h.includes('Overall Score'));
    if (dateIdx === -1 || scoreIdx === -1) {
      document.getElementById('importStatus').textContent = '列名が合いません。CSVの1行目を確認してください。';
      return;
    }
    let count = 0;
    for (let i = 1; i < lines.length; i++) {
      const cols = lines[i].split(',');
      if (cols.length < 2) continue;
      const rawDate = cols[dateIdx].replace(/"/g,'').split(' ')[0];
      const score = parseInt(cols[scoreIdx].replace(/"/g,''));
      if (isNaN(score)) continue;
      const d = new Date(rawDate);
      if (isNaN(d.getTime())) continue;
      const formatted = toISO(d);
      const idx = dataHistory.findIndex(x => x.date === formatted);
      if (idx !== -1) {
        dataHistory[idx].sleep = score;
        dataHistory[idx].mScore = Math.round((dataHistory[idx].mLoad || 1) * (100 - score));
        dataHistory[idx].pScore = Math.round((dataHistory[idx].pLoad || 1) * (100 - score));
      } else {
        dataHistory.push({ date: formatted, sleep: score, mLoad: 1, pLoad: 1,
          mScore: Math.round(1 * (100 - score)), pScore: Math.round(1 * (100 - score)) });
      }
      count++;
    }
    localStorage.setItem(STORAGE_KEY, JSON.stringify(dataHistory));
    chartEnd = clampChartEnd(latestRecordISO());   // 取り込んだ最新データへ
    refreshChart();
    loadDay(targetDate.value);
    updateDateMeta();
    updateUI();
    updateGrowth();
    document.getElementById('importStatus').textContent = count + '日分のデータを取り込みました！';
  };
  reader.readAsText(file);
});

// スライダーイベント
['sleepInput','mLoadInput','pLoadInput'].forEach(id => {
  document.getElementById(id).addEventListener('input', updateUI);
});

// 記録日の前後送り・直接変更
document.getElementById('prevDay').addEventListener('click', () => shiftDate(-1));
document.getElementById('nextDay').addEventListener('click', () => shiftDate(1));

// グラフの表示期間の移動（記録日とは独立）
document.getElementById('chartPrevDay').addEventListener('click', () => shiftChart(-1));
document.getElementById('chartNextDay').addEventListener('click', () => shiftChart(1));
document.getElementById('chartPrevWeek').addEventListener('click', () => shiftChart(-7));
document.getElementById('chartNextWeek').addEventListener('click', () => shiftChart(7));
document.getElementById('chartToday').addEventListener('click', () => {
  chartEnd = clampChartEnd(latestRecordISO());
  refreshChart();
});
targetDate.addEventListener('change', () => {
  loadDay(targetDate.value);
  updateDateMeta();
  updateUI();
});

// === 深呼吸ガイド（吸う4秒・止める4秒・吐く6秒）===
const breathPhases = [
  { label: '吸って', sub: '鼻からゆっくり', dur: 4000, scale: 1.0 },
  { label: 'とめて', sub: '楽にキープ',     dur: 4000, scale: 1.0 },
  { label: 'はいて', sub: '口からゆっくり', dur: 6000, scale: 0.55 }
];
let breathTimer = null, breathTick = null, breathCount = 0, breathRunning = false;

function breathSetPhase(i) {
  const p = breathPhases[i];
  const circle = document.getElementById('breathCircle');
  circle.style.transitionDuration = (p.dur / 1000) + 's';
  circle.style.transform = 'scale(' + p.scale + ')';
  document.getElementById('breathLabel').textContent = p.label;
  document.getElementById('breathSub').textContent = p.sub;

  let remain = Math.round(p.dur / 1000);
  document.getElementById('breathCount').textContent = remain;
  clearInterval(breathTick);
  breathTick = setInterval(() => {
    remain--;
    if (remain > 0) document.getElementById('breathCount').textContent = remain;
  }, 1000);

  breathTimer = setTimeout(() => {
    const ni = (i + 1) % breathPhases.length;
    if (ni === 0) {
      breathCount++;
      document.getElementById('breathCycles').textContent = breathCount;
    }
    breathSetPhase(ni);
  }, p.dur);
}
function startBreath() {
  if (breathRunning) return;
  breathRunning = true;
  breathCount = 0;
  document.getElementById('breathCycles').textContent = 0;
  document.getElementById('breathOverlay').style.display = 'flex';
  breathSetPhase(0);
}
function stopBreath() {
  breathRunning = false;
  clearTimeout(breathTimer);
  clearInterval(breathTick);
  document.getElementById('breathOverlay').style.display = 'none';
  const circle = document.getElementById('breathCircle');
  circle.style.transitionDuration = '0.4s';
  circle.style.transform = 'scale(0.55)';
}
document.getElementById('breathOpenBtn').addEventListener('click', startBreath);
document.getElementById('breathCloseBtn').addEventListener('click', stopBreath);
document.getElementById('breathOverlay').addEventListener('click', (e) => {
  if (e.target.id === 'breathOverlay') stopBreath();
});

// 初期表示
loadDay(targetDate.value);
updateDateMeta();
refreshChart();
updateUI();
updateGrowth();
</script>
</body>
</html>

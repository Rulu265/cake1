# cake1
大阪のケーキ屋さん紹介サイト
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>大阪スイーツ巡り - 絶品ケーキ店ガイド</title>
  <meta name="description" content="大阪の人気ケーキ店を紹介するウェブサイト。GOKANを始め、有名なパティスリーや地元で愛されるケーキ店を紹介します。各店舗の基本情報、おすすめポイント、人気商品などを掲載し、大阪観光やケーキ好きの方に役立つ情報を提供します。">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.4.3/dist/tailwind.min.css" rel="stylesheet">
  <link rel="icon" href="https://cdn.jsdelivr.net/npm/@tabler/icons@latest/icons/cake.svg">
  <script src="https://cdn.jsdelivr.net/npm/@tabler/icons@latest/dist/tabler-icons.umd.min.js"></script>
</head>
<body class="bg-gray-50 text-gray-800 min-h-screen">
  <!-- Header -->
  <header class="bg-white shadow sticky top-0 z-40">
    <div class="max-w-5xl mx-auto flex items-center px-4 py-4">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-pink-400 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path d="M12 19c.71 0 1.31-.37 1.65-.89.34.53.94.89 1.65.89.9 0 1.66-.59 1.92-1.42A2.992 2.992 0 0021 15V7a1 1 0 00-1-1h-2.33A6.002 6.002 0 006 6H3a1 1 0 00-1 1v8a2.99 2.99 0 003.78 2.85c.26.83 1.02 1.42 1.92 1.42.71 0 1.31-.37 1.65-.89.34.53.94.89 1.65.89z" /></svg>
      <h1 class="font-bold text-xl tracking-tight text-pink-500">大阪スイーツ巡り</h1>
      <span class="ml-3 text-gray-400 text-sm hidden sm:inline">絶品ケーキ店ガイド</span>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-gradient-to-br from-pink-100 to-yellow-100 py-10 mb-8">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-3">大阪の人気ケーキ店を厳選紹介</h2>
      <p class="text-lg text-gray-600 mb-6">GOKANをはじめ、有名パティスリーや地元で愛されるケーキ屋さんの情報をたっぷり掲載。<br>観光にも日常にもおすすめの素敵なスイーツ店が見つかります。</p>
      <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=800&q=80" alt="大阪のケーキ" class="rounded-lg shadow-lg mx-auto w-full max-w-lg border-4 border-white">
    </div>
  </section>

  <!-- Cake Shop List -->
  <main class="max-w-5xl mx-auto px-4 mb-12">
    <!-- GOKAN -->
    <section class="bg-white rounded-xl shadow-md mb-10 flex flex-col md:flex-row">
      <img src="https://patisserie-gokan.co.jp/wp/wp-content/uploads/2019/01/kitahama_top.jpg" alt="GOKAN外観" class="w-full md:w-1/2 h-64 object-cover rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
      <div class="p-6 flex flex-col justify-between flex-1">
        <div>
          <h3 class="text-2xl font-bold text-pink-600 flex items-center">
            <svg class="icon icon-tabler icon-tabler-cake mr-2" width="28" height="28" stroke="#EC4899" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><use href="https://cdn.jsdelivr.net/npm/@tabler/icons@latest/icons/cake.svg#icon-tabler-cake"/></svg>
            GOKAN（五感）
            <span class="ml-2 text-sm bg-pink-100 text-pink-700 px-2 py-1 rounded">北浜</span>
          </h3>
          <p class="mt-4 text-gray-700">
            大阪・北浜の歴史的建造物「新井ビル」を活かした上品な空間。素材にこだわったケーキや焼き菓子が自慢。美しい見た目と奥深い味わいで、どのケーキも外れなし。
          </p>
        </div>
        <ul class="mt-5 space-y-1 text-gray-600 text-sm">
          <li><span class="font-semibold">住所:</span> 〒541-0042 大阪府大阪市中央区今橋2丁目1-1 新井ビル</li>
          <li><span class="font-semibold">エリア:</span> 北浜</li>
          <li><span class="font-semibold">営業時間:</span> 10:00～19:00</li>
          <li><span class="font-semibold">公式サイト:</span> <a href="https://patisserie-gokan.co.jp/" class="text-pink-600 hover:underline" target="_blank" rel="noopener">https://patisserie-gokan.co.jp/</a></li>
        </ul>
        <p class="mt-3 text-md text-yellow-600 font-semibold">Good Point: The cake is delicious and beautiful.</p>
      </div>
    </section>
    <!-- Acidracines -->
    <section class="bg-white rounded-xl shadow-md mb-10 flex flex-col md:flex-row">
      <img src="https://images.unsplash.com/photo-1447078806655-40579c2520d6?auto=format&fit=crop&w=800&q=80" alt="アシッドラシーヌのケーキ" class="w-full md:w-1/2 h-64 object-cover rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
      <div class="p-6 flex flex-col justify-between flex-1">
        <div>
          <h3 class="text-2xl font-bold text-pink-600">アシッドラシーヌ（Acidracines）<span class="ml-2 text-sm bg-pink-100 text-pink-700 px-2 py-1 rounded">天満橋</span></h3>
          <p class="mt-4 text-gray-700">
            フランス伝統菓子に独自のエッセンスを加えた名店。繊細な味わい・美しいビジュアルで大阪随一のフランス洋菓子と評判。人気ゆえ売り切れ注意！
          </p>
        </div>
        <ul class="mt-5 space-y-1 text-gray-600 text-sm">
          <li><span class="font-semibold">住所:</span> 〒540-0036 大阪府大阪市中央区船越町1-2-11</li>
          <li><span class="font-semibold">エリア:</span> 天満橋</li>
          <li><span class="font-semibold">営業時間:</span> 10:00～19:00（水・木定休）</li>
          <li><span class="font-semibold">公式サイト:</span> <a href="https://www.acidracines.com/" class="text-pink-600 hover:underline" target="_blank" rel="noopener">https://www.acidracines.com/</a></li>
        </ul>
        <p class="mt-3 text-md text-rose-600 font-semibold">おすすめ: 季節ごとに変わるタルトやショートケーキが特に人気。</p>
      </div>
    </section>
    <!-- ラヴィルリエ -->
    <section class="bg-white rounded-xl shadow-md mb-10 flex flex-col md:flex-row">
      <img src="https://images.unsplash.com/photo-1464306076886-debca5e8a6b3?auto=format&fit=crop&w=800&q=80" alt="ラヴィルリエのケーキ" class="w-full md:w-1/2 h-64 object-cover rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
      <div class="p-6 flex flex-col justify-between flex-1">
        <div>
          <h3 class="text-2xl font-bold text-pink-600">パティスリー ラヴィルリエ<span class="ml-2 text-sm bg-pink-100 text-pink-700 px-2 py-1 rounded">中崎町</span></h3>
          <p class="mt-4 text-gray-700">
            重厚なガトー、ガトーフレーズやサントノーレなどフランス菓子の数々を本格的に味わえる。繊細なクリームワークと唯一無二のビジュアル。イートイン席少な目なのでテイクアウトが◎。
          </p>
        </div>
        <ul class="mt-5 space-y-1 text-gray-600 text-sm">
          <li><span class="font-semibold">住所:</span> 〒530-0024 大阪府大阪市北区山崎町5-13</li>
          <li><span class="font-semibold">エリア:</span> 中崎町</li>
          <li><span class="font-semibold">営業時間:</span> 11:00～19:00（日曜・不定休）</li>
          <li><span class="font-semibold">公式サイト:</span> <a href="https://ravierelier.com/" class="text-pink-600 hover:underline" target="_blank" rel="noopener">https://ravierelier.com/</a></li>
        </ul>
        <p class="mt-3 text-md text-green-600 font-semibold">おすすめ: ガトーフレーズはファン多数の逸品！</p>
      </div>
    </section>
    <!-- りくろーおじさんの店 -->
    <section class="bg-white rounded-xl shadow-md mb-10 flex flex-col md:flex-row">
      <img src="https://www.rikuro.co.jp/img/index/img_mv_01.jpg" alt="りくろーおじさんのチーズケーキ" class="w-full md:w-1/2 h-64 object-cover rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
      <div class="p-6 flex flex-col justify-between flex-1">
        <div>
          <h3 class="text-2xl font-bold text-pink-600">りくろーおじさんの店<span class="ml-2 text-sm bg-pink-100 text-pink-700 px-2 py-1 rounded">なんば他</span></h3>
          <p class="mt-4 text-gray-700">
            ふるふるっ＆しゅわしゅわスフレチーズケーキの元祖！焼きたてを求めて全国からお客さんが集う大阪名物。1,000円以下で買えるプチプラも人気。
          </p>
        </div>
        <ul class="mt-5 space-y-1 text-gray-600 text-sm">
          <li><span class="font-semibold">住所:</span> 〒542-0076 大阪市中央区難波3-2-28（なんば本店ほか多数）</li>
          <li><span class="font-semibold">エリア:</span> なんば、梅田、新大阪 他</li>
          <li><span class="font-semibold">営業時間:</span> 9:30～20:30（店舗により異なる）</li>
          <li><span class="font-semibold">公式サイト:</span> <a href="https://www.rikuro.co.jp/" class="text-pink-600 hover:underline" target="_blank" rel="noopener">https://www.rikuro.co.jp/</a></li>
        </ul>
        <p class="mt-3 text-md text-yellow-600 font-semibold">おすすめ: 焼きたてチーズケーキは持ち帰りもおみやげにも最適!</p>
      </div>
    </section>
    <!-- モンシェール -->
    <section class="bg-white rounded-xl shadow-md mb-10 flex flex-col md:flex-row">
      <img src="https://www.mon-cher.com/assets/img/slider/img01.jpg" alt="モンシェール 堂島ロール" class="w-full md:w-1/2 h-64 object-cover rounded-t-xl md:rounded-l-xl md:rounded-tr-none">
      <div class="p-6 flex flex-col justify-between flex-1">
        <div>
          <h3 class="text-2xl font-bold text-pink-600">モンシェール 堂島ロール<span class="ml-2 text-sm bg-pink-100 text-pink-700 px-2 py-1 rounded">堂島</span></h3>
          <p class="mt-4 text-gray-700">
            ロールケーキブームの火付け役。堂島ロールのしっとり感＆ミルキークリームは大阪スイーツの象徴。ギフト利用も多く季節限定商品も魅力！
          </p>
        </div>
        <ul class="mt-5 space-y-1 text-gray-600 text-sm">
          <li><span class="font-semibold">住所:</span> 〒530-0004 大阪市北区堂島浜2-1-2</li>
          <li><span class="font-semibold">エリア:</span> 堂島</li>
          <li><span class="font-semibold">営業時間:</span> 10:00～19:00</li>
          <li><span class="font-semibold">公式サイト:</span> <a href="https://www.mon-cher.com/" class="text-pink-600 hover:underline" target="_blank" rel="noopener">https://www.mon-cher.com/</a></li>
        </ul>
        <p class="mt-3 text-md text-rose-500 font-semibold">おすすめ: 堂島ロールは早い時間の購入が◎</p>
      </div>
    </section>
  </main>

  <!-- Gallery section -->
  <section class="max-w-5xl mx-auto px-4 mb-14">
    <h4 class="mb-4 text-xl font-bold text-pink-500">おすすめスイーツ・季節限定映像ギャラリー</h4>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-5">
      <div class="bg-white rounded-lg shadow p-4">
        <video controls playsinline webkit-playsinline poster="https://images.unsplash.com/photo-1447078806655-40579c2520d6?auto=format&fit=crop&w=400&q=80">
          <source src="https://samplelib.com/mp4/sample-5s.mp4" type="video/mp4">
          お使いのブラウザは動画タグに対応していません。
        </video>
        <p class="mt-2 text-gray-700 text-center">ケーキの断面美！</p>
      </div>
      <div class="bg-white rounded-lg shadow p-4 flex flex-col">
        <img src="https://images.unsplash.com/photo-1468674197857-58472781d137?auto=format&fit=crop&w=400&q=80" alt="カットケーキ" class="rounded-md object-cover h-48">
        <p class="mt-2 text-gray-700 text-center">美味しそうなショートケーキ</p>
      </div>
      <div class="bg-white rounded-lg shadow p-4 flex flex-col">
        <img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c?auto=format&fit=crop&w=400&q=80" alt="イチゴケーキ" class="rounded-md object-cover h-48">
        <p class="mt-2 text-gray-700 text-center">人気No.1苺のケーキ</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-pink-100 py-8 mt-10">
    <div class="max-w-4xl mx-auto px-4 text-center">
      <p class="mb-2 text-pink-700 font-semibold">
        大阪のケーキ巡りなら「大阪スイーツ巡り」で決まり！
      </p>
      <nav class="flex justify-center space-x-4 mb-3">
        <a href="https://patisserie-gokan.co.jp/" class="hover:underline text-pink-600" target="_blank">GOKAN</a>
        <a href="https://www.acidracines.com/" class="hover:underline text-pink-600" target="_blank">アシッドラシーヌ</a>
        <a href="https://ravierelier.com/" class="hover:underline text-pink-600" target="_blank">ラヴィルリエ</a>
        <a href="https://www.rikuro.co.jp/" class="hover:underline text-pink-600" target="_blank">りくろーおじさん</a>
        <a href="https://www.mon-cher.com/" class="hover:underline text-pink-600" target="_blank">モンシェール</a>
      </nav>
      <small class="text-gray-500">
        &copy; 2024 大阪スイーツ巡り ─ 絶品ケーキ店ガイド All Rights Reserved.
      </small>
    </div>
  </footer>
</body>
</html>


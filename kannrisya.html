<title>エレアウォースマート<title>
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>ハンバーガーメニュー（CSSなし）</title>
</head>
<body>

<!-- 左上（文書先頭）に三線マーク -->
<button id="menu-toggle" aria-controls="menu" aria-expanded="false">≡ メニュー</button>

<!-- メニュー本体（初期は非表示） -->
<nav id="menu" hidden>
  <ul>
    <li><a href="#home">ホーム</a></li>
    <li><a href="#docs">ドキュメント</a></li>
    <li><a href="#settings">設定</a></li>
    <li><a href="#help">ヘルプ</a></li>
  </ul>
</nav>

<script>
  const btn = document.getElementById('menu-toggle');
  const menu = document.getElementById('menu');

  btn.addEventListener('click', () => {
    const isHidden = menu.hasAttribute('hidden');
    if (isHidden) {
      menu.removeAttribute('hidden');
      btn.setAttribute('aria-expanded', 'true');
    } else {
      menu.setAttribute('hidden', '');
      btn.setAttribute('aria-expanded', 'false');
    }
  });

  // メニュー外をクリックしたら閉じる（任意）
  document.addEventListener('click', (e) => {
    const clickInside = btn.contains(e.target) || menu.contains(e.target);
    if (!clickInside && !menu.hasAttribute('hidden')) {
      menu.setAttribute('hidden', '');
      btn.setAttribute('aria-expanded', 'false');
    }
  });

  // Escキーで閉じる（任意）
  document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape' && !menu.hasAttribute('hidden')) {
      menu.setAttribute('hidden', '');
      btn.setAttribute('aria-expanded', 'false');
    }
  });
</script>

</body>
</html>
<text>エレアウォーのデジタル版です。<text>
<a href="https://example.com">
<button>パック開封</button>
</a>
　<a href="https://example.com">
<button>コレクション</button>
</a>
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>お知らせ入力フォーム</title>
<style>
body {
  font-family: "MS UI Gothic", sans-serif;
  background-color: #f8f8f8;
  padding: 20px;
}

form {
  background-color: #ffffff;
  border: 1px solid #888;
  padding: 20px;
  width: 400px;
  box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
}

label {
  display: block;
  margin-bottom: 8px;
  font-weight: bold;
}

input[type="text"],
textarea {
  width: 100%;
  padding: 6px;
  margin-bottom: 12px;
  border: 1px solid #aaa;
  font-family: "MS UI Gothic", sans-serif;
}

textarea {
  height: 150px;
  resize: vertical;
}

button {
  padding: 8px 16px;
  background-color: #e0e0e0;
  border: 1px solid #888;
  cursor: pointer;
}
button:hover {
  background-color: #d0d0d0;
}
</style>
</head>
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>管理者用 お知らせ管理</title>
</head>
<body>
<h2>お知らせ入力フォーム（管理者用）</h2>
<form id="notice-form">
  <label for="title">お知らせタイトル</label>
  <input type="text" id="title" name="title">

  <label for="content">お知らせ内容</label>
  <textarea id="content" name="content"></textarea>

  <button type="submit">登録</button>
</form>

<h2>登録済みのお知らせ一覧（管理者用）</h2>
<div id="notice-board"></div>

<script>
  const form = document.getElementById('notice-form');
  const board = document.getElementById('notice-board');

  // 登録処理
  form.addEventListener('submit', (e) => {
    e.preventDefault();
    const title = document.getElementById('title').value;
    const content = document.getElementById('content').value;

    const notices = JSON.parse(localStorage.getItem('notices') || '[]');
    notices.push({title, content});
    localStorage.setItem('notices', JSON.stringify(notices));

    alert("お知らせを登録しました！");
    form.reset();
    renderNotices();
  });

  // 一覧表示＋削除ボタン
  function renderNotices() {
    board.innerHTML = "";
    const notices = JSON.parse(localStorage.getItem('notices') || '[]');
    if (notices.length === 0) {
      board.innerHTML = "<p>現在お知らせはありません。</p>";
    } else {
      notices.forEach((n, index) => {
        const div = document.createElement('div');
        div.innerHTML = `
          <h3>${n.title}</h3>
          <p>${n.content}</p>
          <button onclick="deleteNotice(${index})">削除</button>
        `;
        board.appendChild(div);
      });
    }
  }

  // 削除処理
  function deleteNotice(index) {
    const notices = JSON.parse(localStorage.getItem('notices') || '[]');
    notices.splice(index, 1); // index番目を削除
    localStorage.setItem('notices', JSON.stringify(notices));
    renderNotices(); // 再描画
  }

  // 初期表示
  renderNotices();
</script>
</body>
</html>
<h2>意見ゾーン</h2>
<div class="opinion-zone">
  <form id="opinion-form">
    <!-- 1. ニックネーム入力欄 -->
    <label for="nickname">ニックネーム（本名や不快な言葉、スパムは禁止）</label><br>
    <input type="text" id="nickname" name="nickname" 
           placeholder="ニックネーム"><br><br>

    <!-- 2. ラジオボタンで星評価 -->
    <label>使い勝手</label><br>
    <label><input type="radio" name="rating" value="★"> ★</label>
    <label><input type="radio" name="rating" value="★★"> ★★</label>
    <label><input type="radio" name="rating" value="★★★"> ★★★</label>
    <label><input type="radio" name="rating" value="★★★★"> ★★★★</label>
    <label><input type="radio" name="rating" value="★★★★★"> ★★★★★</label><br><br>

    <!-- 3. 記述欄 -->
    <label for="opinion">ご意見・ご感想（本名や不快な言葉、スパムは禁止）</label><br>
    <textarea id="opinion" name="opinion" rows="3" cols="40"></textarea><br><br>

    <!-- 4. 送信ボタン（ピクトグラム付き） -->
    <button type="submit">✉送信</button>
  </form>

  <h3>投稿された意見</h3>
  <div id="opinion-list"></div>
</div>

<script>
  const opinionForm = document.getElementById('opinion-form');
  const opinionList = document.getElementById('opinion-list');

  opinionForm.addEventListener('submit', (e) => {
    e.preventDefault();
    const nickname = document.getElementById('nickname').value.trim();
    const rating = document.querySelector('input[name="rating"]:checked')?.value || "未評価";
    const text = document.getElementById('opinion').value.trim();

    if (nickname === "" || text === "") {
      alert("ニックネームと意見を入力してください。");
      return;
    }

    const opinions = JSON.parse(localStorage.getItem('opinions') || '[]');
    const date = new Date().toLocaleString();
    opinions.push({nickname, rating, text, date});
    localStorage.setItem('opinions', JSON.stringify(opinions));

    opinionForm.reset();
    renderOpinions();
  });

  function renderOpinions() {
    opinionList.innerHTML = "";
    const opinions = JSON.parse(localStorage.getItem('opinions') || '[]');
    opinions.forEach(o => {
      // ニックネームに「さん」を付ける
      const nicknameWithHonorific = o.nickname + "さん";

      const div = document.createElement('div');
      div.classList.add('opinion');
      div.innerHTML = `
        <p><strong>${nicknameWithHonorific}</strong> (${o.rating})</p>
        <p>${o.text}</p>
        <small>投稿日時: ${o.date}</small>
      `;
      opinionList.appendChild(div);
    });
  }

  // 初期表示
  renderOpinions();
</script>
<button onclick="clearAllOpinions()">すべての意見を削除</button>

<script>
function clearAllOpinions() {
  if (confirm("本当にすべての意見を削除しますか？")) {
    localStorage.removeItem('opinions'); // ← 保存されている意見を全部消す
    const board = document.getElementById('opinion-board') || document.getElementById('opinion-list');
    if (board) board.innerHTML = "<p>現在意見はありません。</p>";
  }
}
</script>

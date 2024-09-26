<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>동적 카드 팝업 - Article</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- 네비게이션 바 -->
  <nav class="navbar">
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="article.html" class="active">Article</a></li> <!-- 현재 페이지에 해당하는 링크에 active 클래스 추가 -->
      <li><a href="works.html">Works</a></li>
      <li><a href="chat.html">Chat</a></li>
      <li><a href="application.html">Application</a></li>
    </ul>
  </nav>

  <!-- 메인 콘텐츠 (카드) -->
  <div class="container">
    <div class="card" data-content-id="1">Article 1</div>
    <div class="card" data-content-id="2">Article 2</div>
    <div class="card" data-content-id="3">Article 3</div>
    <div class="card" data-content-id="4">Article 4</div>
  </div>

  <!-- 팝업 모달 -->
  <div class="modal" id="modal">
    <div class="modal-content">
      <span class="close-btn">&times;</span>
      <div class="modal-body" id="modal-body">
        <!-- 팝업 내용이 동적으로 삽입됩니다 -->
      </div>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
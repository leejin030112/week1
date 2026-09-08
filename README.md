[Uploading index.html…]()
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>제이콥 닐슨의 사용성 10대 원칙</title>
<style>
  * { box-sizing: border-box; }
  body {
    margin: 0;
    font-family: Arial, "Noto Sans KR", sans-serif;
    background: #f5f5f5;
    color: #111;
  }
  header {
    background: #111;
    color: white;
    padding: 56px 24px 48px;
  }
  header div { max-width: 1000px; margin: auto; }
  h1 { margin: 0 0 12px; font-size: clamp(30px, 5vw, 52px); letter-spacing: -2px; }
  header p { margin: 0; color: #bbb; font-size: 17px; }
  main { max-width: 1000px; margin: 0 auto; padding: 40px 24px 70px; }
  .grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 16px;
  }
  article {
    background: white;
    border: 1px solid #ddd;
    padding: 28px;
    min-height: 180px;
  }
  .num {
    font-size: 14px;
    font-weight: bold;
    color: #777;
    margin-bottom: 22px;
  }
  h2 { margin: 0 0 12px; font-size: 21px; letter-spacing: -0.5px; }
  p { margin: 0; line-height: 1.7; color: #444; }
  @media (max-width: 650px) {
    header { padding: 40px 20px; }
    main { padding: 24px 16px 50px; }
    .grid { grid-template-columns: 1fr; }
    article { padding: 24px; min-height: auto; }
  }
</style>
</head>
<body>
<header>
  <div>
    <h1>사용성 10대 원칙</h1>
    <p>Jakob Nielsen's 10 Usability Heuristics</p>
  </div>
</header>

<main>
  <section class="grid">
    <article><div class="num">01</div><h2>시스템 상태의 가시성</h2><p>시스템은 사용자가 현재 무슨 일이 일어나고 있는지 적절한 피드백을 통해 알려줘야 한다.</p></article>
    <article><div class="num">02</div><h2>시스템과 현실 세계의 일치</h2><p>사용자의 언어와 익숙한 개념을 사용하고, 현실 세계의 자연스러운 순서와 방식으로 정보를 보여줘야 한다.</p></article>
    <article><div class="num">03</div><h2>사용자에게 자유와 통제권 제공</h2><p>사용자가 실수했을 때 쉽게 취소하거나 되돌아갈 수 있도록 해야 한다.</p></article>
    <article><div class="num">04</div><h2>일관성과 표준</h2><p>같은 의미의 요소는 일관되게 표현하고, 플랫폼과 업계의 익숙한 관례를 따라야 한다.</p></article>
    <article><div class="num">05</div><h2>오류 예방</h2><p>오류가 발생한 뒤 알려주는 것보다, 처음부터 오류가 발생하지 않도록 설계하는 것이 좋다.</p></article>
    <article><div class="num">06</div><h2>기억보다 인식</h2><p>사용자가 정보를 기억해야 하지 않도록 선택지와 기능을 눈에 보이게 제공해야 한다.</p></article>
    <article><div class="num">07</div><h2>사용의 유연성과 효율성</h2><p>초보자뿐 아니라 숙련자도 빠르고 효율적으로 사용할 수 있는 방법을 제공해야 한다.</p></article>
    <article><div class="num">08</div><h2>미학적이고 미니멀한 디자인</h2><p>불필요한 정보나 장식은 줄이고, 사용자의 목적에 필요한 정보에 집중해야 한다.</p></article>
    <article><div class="num">09</div><h2>오류 인식·진단·복구 지원</h2><p>오류가 발생하면 무엇이 문제인지 명확한 언어로 설명하고, 해결 방법을 제시해야 한다.</p></article>
    <article><div class="num">10</div><h2>도움말과 문서화</h2><p>사용자가 도움을 필요로 할 경우 쉽게 찾을 수 있고, 이해하기 쉬운 도움말을 제공해야 한다.</p></article>
  </section>
</main>
</body>
</html>

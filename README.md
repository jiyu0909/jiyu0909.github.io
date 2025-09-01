<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>2-9반 알리미🤍</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- 귀여운 글꼴 불러오기 -->
  <link href="https://fonts.googleapis.com/css2?family=Baloo+2&family=Gochi+Hand&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['"Gochi Hand"', 'Baloo 2', 'system-ui'],
          },
        }
      }
    }
  </script>
</head>
<body class="bg-pink-100 text-pink-900 font-sans">
  <div class="max-w-5xl mx-auto p-6">
    <header class="mb-8">
      <h1 class="text-4xl font-extrabold text-center">2-9반 알리미 🤍</h1>
    </header>

    <main class="grid grid-cols-1 lg:grid-cols-3 gap-6">
      <!-- 은지쌤 말씀 -->
      <section class="lg:col-span-3 bg-white rounded-2xl shadow p-6">
        <h2 class="text-2xl font-bold text-pink-700">은지쌤의 말씀 🤍</h2>
        <ul class="mt-4 space-y-3">
          <li class="p-3 rounded-xl border bg-pink-50">
            <p class="mt-0.5 text-base">2학기 중간고사 준비! 열공하기~</p>
          </li>
          <li class="p-3 rounded-xl border bg-pink-50">
            <p class="mt-0.5 text-base">수업시간, 자습시간 잠자기 ❌</p>
          </li>
          <li class="p-3 rounded-xl border bg-pink-50">
            <p class="mt-0.5 text-base">담요 다리에만 덮고 추우면 체육복 후드 입기</p>
          </li>
        </ul>
      </section>

      <!-- 다가오는 일정 -->
      <section class="lg:col-span-3 bg-white rounded-2xl shadow p-6">
        <h2 class="text-2xl font-bold text-pink-700">다가오는 일정 🤍</h2>
        <ol class="mt-4 space-y-3">
          <li class="p-3 rounded-xl border bg-pink-50">
            <div class="text-sm text-pink-500">2025-09-03</div>
            <div class="font-medium">9월 모의고사</div>
            <div class="text-sm text-pink-700">야자 없음!</div>
          </li>
          <li class="p-3 rounded-xl border bg-pink-50">
            <div class="text-sm text-pink-500">2025-09-08</div>
            <div class="font-medium">일본어 수행평가</div>
            <div class="text-sm text-pink-700">히라가나 문장 읽기</div>
          </li>
          <li class="p-3 rounded-xl border bg-pink-50">
            <div class="text-sm text-pink-500">2025-09-04 ~ 2025-09-05</div>
            <div class="font-medium">도서관 행사</div>
            <div class="text-sm text-pink-700">책 읽기 활동</div>
          </li>
        </ol>
      </section>

      <!-- 시간표와 급식 -->
      <div class="lg:col-span-3 grid grid-cols-1 lg:grid-cols-2 gap-6">
        <!-- 왼쪽: 시간표 -->
        <section class="bg-white rounded-2xl shadow p-6">
          <h2 class="text-2xl font-bold text-pink-700 mb-4">2-9 시간표 🤍</h2>
          <div class="mt-4 overflow-x-auto">
            <table class="w-full text-left border rounded-xl">
              <thead>
                <tr class="bg-pink-200">
                  <th class="px-3 py-2">교시</th>
                  <th class="px-3 py-2">월</th>
                  <th class="px-3 py-2">화</th>
                  <th class="px-3 py-2">수</th>
                  <th class="px-3 py-2">목</th>
                  <th class="px-3 py-2">금</th>
                </tr>
              </thead>
              <tbody>
                <tr class="border-b"><td class="px-3 py-2 text-center">1교시</td><td>H.R</td><td>확률과 통계</td><td>2-A</td><td>독서</td><td>영어2</td></tr>
                <tr class="border-b"><td class="px-3 py-2 text-center">2교시</td><td>독서</td><td>2-A</td><td>수학2</td><td>확률과 통계</td><td>2-C</td></tr>
                <tr class="border-b"><td class="px-3 py-2 text-center">3교시</td><td>영어2</td><td>수학2</td><td>독서</td><td>2-C</td><td>수학2</td></tr>
                <tr class="border-b"><td class="px-3 py-2 text-center">4교시</td><td>2-A</td><td>영어2</td><td>2-B</td><td>일본어</td><td>2-B</td></tr>
              </tbody>
            </table>
          </div>
        </section>

        <!-- 오른쪽: 급식 -->
        <section class="bg-white rounded-2xl shadow p-6">
          <h2 class="text-2xl font-bold text-pink-700 mb-4">급식 🤍</h2>
          <iframe src="https://school.gyo6.net/djghs/ad/fm/foodmenu/selectFoodMenuView.do?mi=115830"
                  class="w-full h-[400px] rounded-xl border"
                  frameborder="0"></iframe>
        </section>
      </div>
    </main>

    <!-- 시험 범위 -->
    <section class="lg:col-span-3 bg-white rounded-2xl shadow p-6 mt-6">
      <h2 class="text-2xl font-bold text-pink-700 mb-4">시험 범위 🤍</h2>
      <div class="overflow-x-auto">
        <table class="w-full text-left border rounded-xl">
          <thead>
            <tr class="bg-pink-200">
              <th class="px-3 py-2">과목</th>
              <th class="px-3 py-2">시험 범위</th>
            </tr>
          </thead>
          <tbody>
            <tr class="border-b"><td class="px-3 py-2 font-medium">독서</td><td>교과서:<br>올림포스:<br>모의고사:</td></tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">수학2</td><td>올림포스:<br>교과서:</td></tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">정법</td><td></td></tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">윤사</td><td></td></tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">진로영어</td><td></td></tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">영어2</td>
              <td>
                1. 리딩마스터 부교재: p.10~p.35 하프 모의고사 1회~4회 4번까지 장문 문항 출제 ❌<br>
                2. 25학년도 9월 전국연합 18~40번<br>
                3. 외부지문 5문제
              </td>
            </tr>
            <tr class="border-b"><td class="px-3 py-2 font-medium">지구과학</td><td>1단원. 지구의 변동 ~ 3단원 해수의 성질</td></tr>
            <tr><td class="px-3 py-2 font-medium">물리</td><td>1단원. 역학과 에너지</td></tr>
          </tbody>
        </table>
      </div>
    </section>
  </div>
  <footer class="text-center text-pink-600 text-sm mt-6">
  제작: 20919 이지유
</footer>

</body>
</html>

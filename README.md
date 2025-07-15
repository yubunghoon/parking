<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>인천공항 주차대행 예약</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>인천공항 주차대행 예약</h1>
    <form id="reservationForm">
      <label>성함
        <input type="text" name="name" required>
      </label>
      <label>연락처
        <input type="tel" name="phone" required placeholder="010-1234-5678">
      </label>
      <label>차량번호
        <input type="text" name="carNumber" required placeholder="12가3456">
      </label>
      <label>차종
        <input type="text" name="carType" required placeholder="예: 그랜저, 쏘나타 등">
      </label>
      <button type="submit">예약하기</button>
    </form>
    <div id="successMessage" style="display:none;">
      <h2>예약이 완료되었습니다!</h2>
      <p>담당자가 곧 연락드릴 예정입니다.</p>
    </div>
  </div>
  <script src="main.js"></script>
</body>
</html> 

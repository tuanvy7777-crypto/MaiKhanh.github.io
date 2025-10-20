<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dành tặng người tôi yêuyêu 💐</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      overflow: hidden;
      height: 100vh;
      background: linear-gradient(135deg, #ffe3ec, #fce4f6);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      font-family: "Segoe UI", sans-serif;
      color: #5a2d43;
      position: relative;
    }

    h1 {
      font-size: 2.4em;
      margin-bottom: 10px;
      letter-spacing: 1px;
      color: #b30059;
      text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.6);
    }

    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 10px 0 25px;
      color: #4a1f3d;
    }

    img {
      width: 250px;
      height: 250px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
      border: 3px solid rgba(255,255,255,0.8);
      z-index: 2;
    }

    footer {
      position: absolute;
      bottom: 15px;
      font-size: 0.9em;
      color: #88425a;
    }

    /* 🌹 Hiệu ứng hoa rơi */
    .rose {
      position: absolute;
      top: -10%;
      font-size: 24px;
      animation: fall linear forwards;
      color: #c70039;
      opacity: 0.9;
    }

    @keyframes fall {
      0% {
        transform: translateY(-10%) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(110vh) rotate(360deg);
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <h1>💐 Dành tặng cho ny toai Mai Khanh 💐</h1>
  <p>
    Không cần luôn nói lời hoa mỹ, chỉ cần em biết rằng :<br>
    Em là món quà lớn mà thế giới này gửi đến tôi.<br>
    Vì thế ãy luôn mỉm cười và luôn hạnh phúc nhé người tôi yêu.
  </p>
  <img src="beiu.jpg" alt="Bêu xinh đẹp">

  <footer>— Gửi đôi lời đến người tôi yêu —</footer>

<style>
footer {
  position: fixed; /* Giữ cố định vị trí */
  top: 50%;        /* Căn giữa theo chiều dọc */
  left: 50%;       /* Căn giữa theo chiều ngang */
  transform: translate(-50%, -50%); /* Dịch tâm để thật sự nằm giữa */
  font-size: 20px;
  font-weight: bold;
  color: #ff6699;
  text-align: center;
  z-index: 9999; /* Đảm bảo nằm trên cùng */
}
</style>


  <script>
    // 🌹 Tạo hiệu ứng hoa hồng rơi
    const roses = ["🌹", "🌸", "💮", "🌺"];
    function createRose() {
      const rose = document.createElement("div");
      rose.classList.add("rose");
      rose.innerText = roses[Math.floor(Math.random() * roses.length)];
      rose.style.left = Math.random() * 100 + "vw";
      rose.style.animationDuration = 3 + Math.random() * 3 + "s";
      document.body.appendChild(rose);

      setTimeout(() => rose.remove(), 6000);
    }

    setInterval(createRose, 300);
  </script>
</body>
</html>

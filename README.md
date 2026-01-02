# harshath-goud
birthday
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🎉 Surprise! 🎉</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: radial-gradient(circle, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      overflow: hidden;
    }.box {
  width: 200px;
  height: 200px;
  background: linear-gradient(135deg, #ff512f, #dd2476);
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 22px;
  font-weight: bold;
  cursor: pointer;
  box-shadow: 0 20px 40px rgba(0,0,0,0.3);
  transition: transform 0.4s ease;
  z-index: 2;
}

.box:hover {
  transform: scale(1.05);
}

.photo {
  position: absolute;
  width: 250px;
  height: 250px;
  border-radius: 50%;
  object-fit: cover;
  opacity: 0;
  transform: scale(0);
  transition: all 1s ease;
  box-shadow: 0 20px 40px rgba(0,0,0,0.4);
  z-index: 3;
}

.photo.show {
  opacity: 1;
  transform: scale(1);
}

.message {
  position: absolute;
  bottom: 8%;
  font-size: 28px;
  font-weight: bold;
  color: #fff;
  opacity: 0;
  transition: opacity 1s ease 0.5s;
  text-shadow: 2px 2px 8px rgba(0,0,0,0.4);
  z-index: 3;
}

.message.show {
  opacity: 1;
}

.blast {
  position: absolute;
  width: 10px;
  height: 10px;
  background: gold;
  border-radius: 50%;
  animation: blast 1.2s ease-out forwards;
}

@keyframes blast {
  to {
    transform: translate(var(--x), var(--y)) scale(0

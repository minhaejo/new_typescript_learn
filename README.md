<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mobile UI Example</title>
    <link rel="stylesheet" href="test.css">
</head>
<body>
    <div class="container">
        <div class="header">
  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-alexa" viewBox="0 0 16 16">
  <path d="M7.996 0A7.998 7.998 0 0 0 0 8a8 8 0 0 0 6.93 7.93v-1.613a1.06 1.06 0 0 0-.717-1.008A5.602 5.602 0 0 1 2.4 7.865 5.579 5.579 0 0 1 8.054 2.4a5.599 5.599 0 0 1 5.535 5.81l-.002.046a6.116 6.116 0 0 1-.012.192l-.005.061a4.85 4.85 0 0 1-.033.284l-.01.068c-.685 4.516-6.564 7.054-6.596 7.068A7.998 7.998 0 0 0 15.992 8 7.998 7.998 0 0 0 7.996.001Z"/>
</svg>
          <span class="logo"></span>
             <h1>TRIARY</h1>
        </div>
        <div class="content">
            <h2>반갑습니다!</h2>
            <p>여행에 필요한 플레너를 찾고있다면?</p>
            <form>
                <input type="text" placeholder="Enter your name">
                <button type="submit">Submit</button>
            </form>
        </div>
        <div class="footer">
            <p>&copy; 2023 My Mobile App. All rights reserved.</p>
        </div>
    </div>
</body>
</html>


* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
h1{
  font-weight:500
}
.bi-alexa{
  color:#3498db;
}
.logo{
  position:absolute;
  left:905px;
  font-size:11px;
  font-weight:400;
    
}
.container {
    display: flex;
    flex-direction: column;
    height: 100vh;
}

.header {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    background-color: #f0f0f0;
}

.header img {
    height: 50px;
    margin-right: 10px;
}

.content {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.content h2 {
    margin-bottom: 10px;
}
.content p {
  margin-bottom: 15px;
  font-weight:600;
}

.content form {
    display: flex;
    flex-direction: column;
}

.content input {
    margin-bottom: 10px;
    padding: 10px;
    border: none;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
}

.content button {
    padding: 10px;
    background-color: #3498db;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.2s ease;
}

.content button:hover {
    background-color: #2980b9;
}

.footer {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    background-color: #f0f0f0;
}

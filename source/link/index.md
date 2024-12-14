<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>友链申请</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
    }

    h1 {
      color: #333;
    }

    form {
      width: 300px;
      margin: 0 auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
    }

    label {
      display: block;
      text-align: left;
      margin-bottom: 5px;
    }

    input,
    textarea {
      width: 100%;
      padding: 8px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 3px;
    }

    button {
      background-color: #007bff;
      color: #fff;
      padding: 10px 15px;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
  </style>
</head>

<body>
  <h1>友链申请</h1>
  <form>
    <label for="siteName">网站名称：</label>
    <input type="text" id="siteName" required>

    <label for="siteUrl">网站网址：</label>
    <input type="text" id="siteUrl" required>

    <label for="siteDescription">网站描述：</label>
    <textarea id="siteDescription" rows="4" required></textarea>

    <label for="contactEmail">联系邮箱：</label>
    <input type="email" id="contactEmail" required>

    <button type="submit">提交申请</button>
  </form>
</body>

</html>
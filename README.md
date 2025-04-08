<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <link rel="stylesheet" href="styles/style.css"/>
  <title>Yiko Chat</title>
</head>
<body>
  <h4>
    By Isaac Muaco
  </h4>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Yiko Chat</title>
  <link rel="apple-touch-icon" sizes="180x180" href="Ícones/images.png">
<link rel="icon" type="image/png" sizes="32x32" href="Ícones/isaac.png">
<link rel="icon" type="image/png" sizes="16x16" href="Ícones/isaacicone.png">
<link rel="manifest" href="/site.webmanifest">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
      <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <link rel="shortcut icon" href="Ícones/isaac.png" type="image/png">
    <style>
  body {
  background-color: #111;
  color: #0f0;
  font-family: Arial, sans-serif;
  text-align: center;
  padding-top: 50px;
}

h1 {
  font-size: 2.5em;
  color: #ff0;
}

p {
  font-size: 1.2em;
}
        * ,body{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f0f2f5;
        }

        .container {
            max-width: 480px;
            margin: 0 auto;
            background-color: #fff;
            height: 100vh;
            position: relative;
        }

        /* Header styles */
        .header {
            background-color: #128C7E;
            color: white;
            padding: 10px 16px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .header h1 {
            font-size: 20px;
            font-weight: 500;
        }

        .header-icons {
            display: flex;
            gap: 24px;
        }

        .header-icons i {
            font-size: 22px;
        }

        /* Arquivadas section */
        .arquivadas {
            display: flex;
            padding: 15px;
            border-bottom: 1px solid #f0f2f5;
            align-items: center;
            justify-content: space-between;
        }

        .arquivadas-left {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .arquivadas-left i {
            color: #54656f;
            font-size: 20px;
        }

        .arquivadas h2 {
            color: #54656f;
            font-size: 16px;
            font-weight: 500;
        }

        /* Chat list */
        .chat-list {
            overflow-y: auto;
            height: calc(100vh - 132px);
        }

        .chat-item {
            display: flex;
            padding: 10px 15px;
            border-bottom: 1px solid #f0f2f5;
            position: relative;
        }

        .profile-pic {
            width: 49px;
            height: 49px;
            border-radius: 50%;
            margin-right: 15px;
            overflow: hidden;
            background-color: #e9edef;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .profile-pic img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .chat-details {
            flex: 1;
        }

        .chat-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 3px;
        }

        .chat-name {
            font-weight: 500;
            font-size: 16px;
            color: #111b21;
        }

        .chat-time {
            color: #667781;
            font-size: 12px;
            margin-left: auto;
        }

        .chat-message {
            color: #667781;
            font-size: 14px;
            display: flex;
            align-items: center;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            max-width: 85%;
        }

        .message-status,body {
            margin-right: 5px;
            color: #53bdeb;
        }

        .thumbs-up {
            color: #ffb800;
            margin-right: 5px;
            font-size: 18px;
        }

        /* Footer navigation */
        h4 {
            position: absolute;
            bottom: 0;
            width: 100%;
            background-color: #f0f2f5;
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            border-top: 1px solid #d1d7db;
        }

        h4 {
            display: flex;
            flex-direction: column;
            align-items: center;
            font-size: 12px;
            color: #54656f;
        }

        h4{
            font-size: 10px;
            margin-bottom: 3px;
        }

      h4 {
            color: #128C7E;
        }

        .new-chat-button {
            position: absolute;
            bottom: 70px;
            right: 20px;
            background-color: #00a884;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 24px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
        }

        /* Login & Register Screens */
        .auth-container {
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            background-color: #f0f2f5;
        }

        .auth-logo {
            color: #128C7E;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .auth-form {
            width: 100%;
            max-width: 320px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .auth-form h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #128C7E;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: #54656f;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #d1d7db;
            border-radius: 4px;
        }

        button {
            width: 100%;
            padding: 12px;
            background-color: #128C7E;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        .auth-switch {
            text-align: center;
            margin-top: 15px;
            font-size: 14px;
            color: #54656f;
        }

        .auth-switch a {
            color: #128C7E;
            text-decoration: none;
        }

        .profile-upload {
            text-align: center;
            margin-bottom: 15px;
        }

        .profile-preview {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background-color: #e9edef;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 10px;
            overflow: hidden;
            cursor: pointer;
        }

        .profile-preview img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        #profile-upload {
            display: none;
        }

        .chat-screen {
            display: none;
        }
    </style>
  <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', sans-serif;
        }
        
        body {
            background-color: #f0f2f5;
            height: 100vh;
        }
        
        .container {
            display: flex;
            height: 100%;
        }
        
        /* Login & Registration Page */
        .auth-container {
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #00a884;
        }
        
        .auth-box {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            width: 380px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        
        .auth-box h2 {
            margin-bottom: 20px;
            color: #128c7e;
            text-align: center;
        }
        
        .auth-box input {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        
        .auth-box button {
            width: 100%;
            padding: 12px;
            background-color: #128c7e;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-bottom: 15px;
        }
        
        .auth-box p {
            text-align: center;
            cursor: pointer;
            color: #128c7e;
        }
        
        .profile-upload {
            text-align: center;
            margin-bottom: 15px;
        }
        
        .profile-preview {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
            margin: 0 auto 15px;
            border: 2px solid #128c7e;
        }
        
        .profile-preview img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        /* Sidebar */
        .sidebar {
            width: 30%;
            background-color: #ffffff;
            border-right: 1px solid #e9edef;
            display: flex;
            flex-direction: column;
        }
        
        .profile-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px;
            background-color: #f0f2f5;
        }
        
        .profile-pic {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            overflow: hidden;
        }
        
        .profile-pic img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .profile-actions {
            display: flex;
            gap: 20px;
            color: #54656f;
        }
        
        .profile-actions i {
            cursor: pointer;
            font-size: 20px;
        }
        
        .search-bar {
            padding: 10px;
        }
        
        .search-container {
            background-color: #f0f2f5;
            border-radius: 8px;
            padding: 8px 12px;
            display: flex;
            align-items: center;
        }
        
        .search-container i {
            color: #54656f;
            margin-right: 10px;
        }
        
        .search-container input {
            background: transparent;
            border: none;
            outline: none;
            width: 100%;
        }
        
        .online-status {
            background-color: #25D366;
            color: white;
            font-size: 10px;
            padding: 3px 8px;
            border-radius: 12px;
            margin-left: 10px;
        }
        
        .chats {
            flex: 1;
            overflow-y: auto;
        }
        
        .chat-item {
            display: flex;
            padding: 15px;
            cursor: pointer;
            border-bottom: 1px solid #f0f2f5;
        }
        
        .chat-item:hover {
            background-color: #f5f6f6;
        }
        
        .chat-item-pic {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
            position: relative;
        }
        
        .chat-item-pic img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .online-indicator {
            position: absolute;
            bottom: 0;
            right: 0;
            width: 12px;
            height: 12px;
            background-color: #25D366;
            border-radius: 50%;
            border: 2px solid white;
        }
        
        .chat-item-info {
            flex: 1;
        }
        
        .chat-item-header {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .chat-item-name {
            font-weight: 500;
            display: flex;
            align-items: center;
        }
        
        .chat-item-time {
            font-size: 12px;
            color: #8696a0;
        }
        
        .chat-item-message {
            color: #8696a0;
            font-size: 14px;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        
        /* Main Chat */
        .main-chat {
            flex: 1;
            display: flex;
            flex-direction: column;
        }
        
        .chat-header {
            display: flex;
            align-items: center;
            padding: 15px;
            background-color: #f0f2f5;
            border-left: 1px solid #e9edef;
        }
        
        .chat-header-info {
            margin-left: 15px;
            flex: 1;
        }
        
        .chat-header-name {
            font-weight: 500;
            display: flex;
            align-items: center;
        }
        
        .chat-header-status {
            font-size: 13px;
            color: #8696a0;
        }
        
        .chat-header-actions {
            display: flex;
            gap: 20px;
            color: #54656f;
        }
        
        .chat-header-actions i {
            cursor: pointer;
            font-size: 18px;
        }
        
        .chat-messages {
            flex: 1;
            background-color: #efeae2;
            overflow-y: auto;
            padding: 20px;
            background-image: url('https://user-images.githubusercontent.com/15075759/28719144-86dc0f70-73b1-11e7-911d-60d70fcded21.png');
            display: flex;
            flex-direction: column;
        }
        
        .message {
            max-width: 65%;
            padding: 10px 15px;
            border-radius: 8px;
            margin-bottom: 10px;
            position: relative;
            word-wrap: break-word;
        }
        
        .message-time {
            font-size: 11px;
            color: #8696a0;
            text-align: right;
            margin-top: 5px;
        }
        
        .received {
            background-color: white;
            align-self: flex-start;
            border-top-left-radius: 0;
        }
        
        .sent {
            background-color: #d9fdd3;
            align-self: flex-end;
            margin-left: auto;
            border-top-right-radius: 0;
        }
        
        .voice-message {
            display: flex;
            align-items: center;
        }
        
        .voice-player {
            flex: 1;
            height: 30px;
            margin: 0 10px;
        }
        
        .voice-duration {
            font-size: 12px;
            color: #8696a0;
        }
        
        .chat-input {
            padding: 10px 15px;
            background-color: #f0f2f5;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .chat-input i {
            font-size: 20px;
            color: #54656f;
            cursor: pointer;
        }
        
        .message-input {
            flex: 1;
            background-color: white;
            border-radius: 8px;
            padding: 12px 15px;
            border: none;
            outline: none;
        }
        
        /* Friends List */
        .friends-list {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: white;
            z-index: 10;
            display: none;
            flex-direction: column;
        }
        
        .friends-header {
            padding: 15px;
            display: flex;
            align-items: center;
            background-color: #008069;
            color: white;
        }
        
        .friends-header i {
            margin-right: 20px;
            cursor: pointer;
        }
        
        .friends-content {
            flex: 1;
            overflow-y: auto;
            padding: 15px;
        }
        
        .friend-item {
            display: flex;
            align-items: center;
            padding: 15px;
            border-bottom: 1px solid #f0f2f5;
        }
        
        .friend-pic {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 15px;
            position: relative;
        }
        
        .friend-pic img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .friend-info {
            flex: 1;
        }
        
        .friend-name {
            font-weight: 500;
            display: flex;
            align-items: center;
        }
        
        .friend-status {
            font-size: 13px;
            color: #8696a0;
        }
        
        .verification-badge {
            color: #0088cc;
            margin-left: 5px;
        }
        
        /* Profile Settings */
        .profile-settings {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: white;
            z-index: 10;
            display: none;
            flex-direction: column;
        }
        
        .settings-header {
            padding: 15px;
            display: flex;
            align-items: center;
            background-color: #008069;
            color: white;
        }
        
        .settings-header i {
            margin-right: 20px;
            cursor: pointer;
        }
        
        .settings-content {
            flex: 1;
            overflow-y: auto;
            padding: 20px;
        }
        
        .settings-profile {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 30px;
        }
        
        .settings-profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            overflow: hidden;
            margin-bottom: 15px;
            border: 3px solid #128c7e;
            position: relative;
        }
        
        .settings-profile-pic img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .edit-profile-pic {
            position: absolute;
            bottom: 10px;
            right: 10px;
            background-color: #128c7e;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
        }
        
        .settings-name {
            font-size: 20px;
            font-weight: 500;
            margin-bottom: 5px;
        }
        
        .settings-email {
    

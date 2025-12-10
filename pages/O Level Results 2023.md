---
title: O Level Results 2023
permalink: /o2023results/
variant: markdown
description: ""
---
<div align="justify">
	



  
  
  <title>OPSS Chatbot</title>
  <style>
    /* --- Branding & Chat-widget styles --- */
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap');

    body {
      font-family: 'Poppins', sans-serif;
    }

    /* Floating chat widget container */
    #opss-chat-widget {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 320px;
      max-height: 420px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.15);
      border-radius: 12px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      z-index: 1000;
      font-size: 14px;
    }

    /* Header / toggle bar */
    #chat-header {
      background-color: #2F8D46; /* OPSS green */
      color: white;
      padding: 10px;
      cursor: pointer;
      user-select: none;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    #chat-header span {
      font-weight: 500;
    }
    #chat-header .toggle-icon {
      font-size: 18px;
      line-height: 1;
    }

    /* Hidden / collapsed widget */
    #opss-chat-widget.collapsed {
      height: 40px;
      max-height: 40px;
    }

    /* Chat messages area */
    #chat-messages {
      flex: 1;
      background: #fafafa;
      padding: 10px;
      overflow-y: auto;
    }

    .msg { margin-bottom: 12px; }

    .msg .sender { font-weight: 600; }
    .msg.user .sender { color: #0056b3; }
    .msg.bot .sender { color: #2F8D46; }

    /* Input area */
    #chat-input-area {
      display: flex;
      border-top: 1px solid #ddd;
      background: white;
    }
    #user-input {
      flex: 1;
      padding: 8px 10px;
      border: none;
      border-radius: 0;
      font-size: 14px;
      outline: none;
    }
    #send-btn {
      background-color: #F7C846; /* OPSS yellow-ish */
      border: none;
      padding: 0 16px;
      color: #2F8D46;
      font-weight: 500;
      cursor: pointer;
    }
    #send-btn:hover {
      background-color: #e6b63f;
    }
  </style>



<div class="collapsed" id="opss-chat-widget">
  <div id="chat-header">
    <span>Ask OPSS</span>
    <span class="toggle-icon">✖</span>
  </div>
  <div id="chat-messages"></div>
  <div id="chat-input-area">
    <input placeholder="Ask about OPSS…" id="user-input" type="text">
    <button id="send-btn">Send</button>
  </div>
</div>






</div>
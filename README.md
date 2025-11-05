<style>
.language-switch {
  display: flex;
  justify-content: flex-end;
  margin-bottom: 1rem;
}

.language-switch button {
  background: #007aff;
  border: none;
  color: white;
  padding: 6px 12px;
  border-radius: 8px;
  cursor: pointer;
  font-size: 14px;
  margin-left: 6px;
}

.language-switch button:hover {
  background: #005fcc;
}

.lang-cn, .lang-en {
  display: none;
}

.active {
  display: block;
}
</style>

<div class="language-switch">
  <button id="cn-btn">中文</button>
  <button id="en-btn">English</button>
</div>

---

<div class="lang-cn active">

# 🌿 AI 激励 App 用户支持

欢迎来到 **AI 激励 App** 的支持页面！  
我们致力于为每一位用户带来每日的启发与力量 🌞。  
如果你在使用过程中遇到任何问题，或者有改进建议，请随时联系我们。

---

## 📬 联系我们

**电子邮箱**  
👉 [support@aimotivation.app](mailto:support@aimotivation.app)

我们通常会在 **1–2 个工作日内回复**。

---

## 💡 常见问题

### 1️⃣ 我生成的语录会被保存吗？
只有当你点击「保存到历史」时，语录才会保存在本地设备中。  
我们不会上传或分享任何个人内容。

### 2️⃣ App 会收集我的隐私数据吗？
不会。  
AI 激励 App 不会收集、追踪或出售任何个人信息。  
你可以查看我们的完整隐私政策：[隐私政策](https://espade.github.io/privacy)

### 3️⃣ 我想反馈新的功能建议，可以吗？
当然可以！  
请通过邮箱告诉我们你希望添加的功能或改进，我们非常重视每位用户的声音 💬。

### 4️⃣ 登录失败或闪退怎么办？
请尝试：
- 确保网络连接稳定  
- 更新到最新版本的 App  
- 若问题持续，请将错误截图发送至邮箱，我们会尽快处理

---

## 🔧 技术信息

- 当前版本：`v1.0.0`  
- 最低系统要求：`iOS 15.0` 及以上  
- 开发者：Yundeer  
- 技术栈：SwiftUI + Firebase + OpenAI API  
- 官方网站：[https://espade.github.io](https://espade.github.io)

---

## ❤️ 我们的承诺

AI 激励 App 旨在帮助你：
> 每天遇见更积极的自己。  
> 每一次点击，都点亮生活的一点光。

---

© 2025 **Yundeer** · All rights reserved.  
[隐私政策](https://espade.github.io/privacy) | [主页](https://espade.github.io)

</div>

---

<div class="lang-en">

# 🌿 AI Motivation App Support

Welcome to the **AI Motivation App** support page!  
We’re here to help you find daily inspiration and positivity 🌞.  
If you encounter any problems or have feedback, please contact us anytime.

---

## 📬 Contact Us

**Email**  
👉 [support@aimotivation.app](mailto:support@aimotivation.app)

We usually reply within **1–2 business days**.

---

## 💡 Frequently Asked Questions

### 1️⃣ Are my generated quotes saved?
Only when you tap “Save to History.”  
We never upload, store, or share personal content.

### 2️⃣ Does the app collect personal data?
No.  
AI Motivation does **not** collect, track, or sell any personal information.  
Read our [Privacy Policy](https://espade.github.io/privacy).

### 3️⃣ Can I suggest new features?
Absolutely!  
Email us your ideas — we value every user’s feedback 💬.

### 4️⃣ Login failed or app crashed?
Try:
- Ensuring a stable internet connection  
- Updating to the latest version  
- Sending us a screenshot if the issue persists

---

## 🔧 Technical Information

- Current version: `v1.0.0`  
- Minimum iOS: `15.0`  
- Developer: **Yundeer**  
- Stack: SwiftUI + Firebase + OpenAI API  
- Website: [https://espade.github.io](https://espade.github.io)

---

## ❤️ Our Commitment

AI Motivation is designed to help you:
> Meet a more positive version of yourself every day.  
> Every tap lights up your life a little more.

---

© 2025 **Yundeer** · All rights reserved.  
[Privacy Policy](https://espade.github.io/privacy) | [Home](https://espade.github.io)

</div>

<script>
  const cnBtn = document.getElementById('cn-btn');
  const enBtn = document.getElementById('en-btn');
  const cnContent = document.querySelector('.lang-cn');
  const enContent = document.querySelector('.lang-en');

  cnBtn.addEventListener('click', () => {
    cnContent.classList.add('active');
    enContent.classList.remove('active');
  });

  enBtn.addEventListener('click', () => {
    enContent.classList.add('active');
    cnContent.classList.remove('active');
  });
</script>

## Scenario Flow
1) 攔截/重送登入請求，嘗試弱密碼
2) 成功登入後，頁面會顯示：
   - `FLAG_LOGIN`
   - **下一關密碼（LAB_PASS）**：請把它記下來
3) 前往 Stage 2：**CTF-Login-Cookie**，用剛拿到的 `LAB_PASS` 登入後再想辦法取得 `FLAG_COOKIE`

> 負責任使用：僅限本機或授權環境，請勿對未授權系統嘗試。

## Demo
- Online demo (Render): https://ctf-lab.onrender.com/login.html

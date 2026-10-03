# AI with Sandy 網站

- `index.html`：首頁（課程介紹、影片、方案、PayPal、Kit 訂閱）
- `members.html`：Pro 會員專區（內容以密碼加密，網址 /members）
- `netlify.toml`：Netlify 設定（/members 網址、會員頁不被搜尋引擎收錄）

## 部署到 Netlify
1. 把這個資料夾推到 GitHub（建議設為 Private repo）
2. Netlify → Add new site → Import an existing project → 選這個 repo
3. Build command 留空，Publish directory 填 `.`，按 Deploy

## 更新會員專區內容或密碼
會員專區的內容是加密後才放進 members.html，請不要直接改 members.html，
請提供新影片 / 新密碼，由產生工具重新產生後覆蓋這個檔案。

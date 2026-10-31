# 保險業務員的 AI 技能包

給保險業務員用的 18 個 Claude Code 技能（Skill）：做網站、讓 Google 找得到你、經營 IG／Threads。
全部繁體中文，合規檢查內建在每一步。

**這些技能只寫草稿。不會幫你發文、不會登入你的任何帳號。**

## 安裝

**最簡單：打開安裝頁，按一下按鈕複製** 👉 https://maggychi36933693-ui.github.io/insurance-ai-skills/

或自己複製下面這段，貼給 Claude Code：

先在 Claude Code 開啟你的網站資料夾，再把這段整個複製貼上：

```
https://github.com/maggychi36933693-ui/insurance-ai-skills

請把這包 Skill 安裝到我目前開啟的資料夾：把 skills 裡的每個資料夾放進這個資料夾的 .claude/skills/。裝完列出裝了哪些，並確認可以使用。
```

裝好之後，說一句 **「開始用社群技能」**，它會帶你填好語氣檔，並建好「社群」資料夾。

> 想讓每個資料夾都能用，把上面的「目前開啟的資料夾」改成「我的個人技能資料夾（~/.claude/skills）」。

## 18 個技能

### 網站組（4 個）

| 技能 | 做什麼 | 怎麼叫它 |
|---|---|---|
| my-brand | 我的品牌規範：顏色、字型、語氣 | 「用我的品牌」 |
| publish-site | 把網站改好的地方發布上線 | 「幫我發布更新」 |
| one-question-one-article | 客戶問題寫成網站文章 | 「客戶問我＿＿，幫我寫成文章」 |
| google-seo | 讓 Google 找得到你的網站 | 「幫我做 SEO」 |

### 社群組（14 個，保險業務員專用）

| 技能 | 做什麼 |
|---|---|
| ins-social | **總指揮**：第一次先跑它；之後幫你判斷該交給哪個技能 |
| ins-plan | 排一週要發什麼 |
| ins-reel | 短影音腳本：開頭三選一會打分數、會算秒數 |
| ins-carousel | 輪播貼文，照品牌做出 1080×1350 圖檔 |
| ins-caption | 文案和 hashtag |
| ins-story | 限時動態 |
| ins-human | 去 AI 味＋合規字詞檢查 |
| ins-reply | 回自己貼文的留言 |
| ins-comment | 去別人貼文留言 |
| ins-dm | 私訊 |
| ins-profile | 個人檔案打分數（滿分 100） |
| ins-viral | 找同領域的爆款 |
| ins-audit | 檢討自己發過的貼文 |
| ins-repurpose | 講座筆記、文章拆成一週貼文 |

## 合規：一定要知道

社群組每一份草稿交出來前，都會做三道檢查：工具抓危險字詞、讀整體印象、假設被同業截圖。
但請記得：

- 工具是**字詞比對**，比喻、諧音、圖片暗示它抓不到。
- 檢查沒抓到問題，**不代表合規**，只代表「未發現明顯問題」。
- 社群貼文、網站文章都算對外文宣，**發布前請送公司法遵或主管審核**，並保留審核紀錄。
- 公司有自己的規定或標準警語，請補在「社群／合規規範.md」最後面。

## 需要什麼

- Claude Code（桌面版或終端機都可以）
- 電腦上有 `python3`（Mac 內建）：打分數和合規檢查工具要用。沒有的話，其他功能照樣能用。

## 授權與出處

MIT 授權，見 [LICENSE](LICENSE)。
社群組（`ins-*`）改寫自 Jake Schincariol 的 [instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)（MIT），改成繁體中文、保險業務員專用，並加入合規檢查。

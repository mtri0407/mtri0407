<h2 align="center">Hi, I'm Trí 👋</h2>
<p align="center">
  <b>Phạm Nguyễn Minh Trí</b> · IT student at HUST (PFIEV, IT-EP) · Founder of <a href="https://thegreysteel.com">Greysteel Education</a> · National powerlifting medalist
</p>
<p align="center"><i>I build production systems that real customers use every day, and I treat learning like training: measured, periodized, progressive.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000" alt="JavaScript">
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=fff" alt="Cloudflare Workers">
  <img src="https://img.shields.io/badge/Google_Apps_Script-4285F4?logo=google&logoColor=fff" alt="Google Apps Script">
  <img src="https://img.shields.io/badge/SQLite_/_D1-003B57?logo=sqlite&logoColor=fff" alt="SQLite D1">
  <img src="https://img.shields.io/badge/Netlify-00C7B7?logo=netlify&logoColor=fff" alt="Netlify">
  <img src="https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=fff" alt="Playwright">
  <img src="https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=fff" alt="C++">
</p>

---

### ⚡ At a glance

- 🏫 **Founded a tutoring company** and built its entire software platform myself: 20,000,000 VND revenue in month one, 54 releases in 6 months.
- 🧱 **42,000+ lines of production code** in one system: a 26k-line SPA and a 16k-line backend with 200+ API actions.
- 🚀 **3.3 s → 41 ms** response time after moving read traffic to the edge (Cloudflare Workers + D1) without rewriting the backend.
- 🧪 **1,500+ automated checks** gate every deploy, including security analyzers I wrote myself.
- 🎯 **SAT 1580/1600** first attempt (from 1150 in 4 months) · 🥇 **Gold, Squat 190 kg**, VPF National Championship 2025.

---

### 🔨 Featured projects

#### [Greysteel Education Platform](https://github.com/mtri0407/greysteel-showcase) · [live site](https://thegreysteel.com)
The operating system of my tutoring center: marketing site, sign-up with email OTP, recruitment pipeline with auto-scoring, recurring class scheduling, homework, practice tests with seven question types, payroll and fund allocation, document vault, video lessons and an AI team. 40+ accounts across 5 roles use it daily.

- **Edge migration without a rewrite**: a build tool runs the *same* backend on Cloudflare Workers with a D1 data layer; a diff tool proves both servers return identical results.
- **AI in real workflows**: essay grading against official IELTS / DELF rubrics (tutor must approve), exam-file import that chunks long documents into structured questions, a sales chatbot and a marketing assistant.
- **Security**: salted, versioned password hashing, hashed sessions with hard expiry, RBAC, and static analyzers that audit permission checks on every action and catch unescaped HTML.

`JavaScript` `Apps Script` `Cloudflare Workers / D1 / R2 / Workers AI` `Google Workspace APIs` `Bunny Stream` `Playwright`

#### [Greysteel Tasks](https://github.com/mtri0407/greysteel-tasks) · [live app](https://greysteeltask.netlify.app)
A planner that merges the Eisenhower Matrix with athletic periodization. Goals become phases, weekly hour budgets and daily logs; a scheduling engine re-plans missed sessions and syncs both ways with Google Calendar.

- Serverless Google OAuth 2.0 (HttpOnly refresh cookies, CSRF state), data stored in each user's own Drive.
- Claude API assistant that proposes changes through tool calls, applied only after approval and undoable.
- 118 unit tests + end-to-end Playwright tests against a fake Google server I wrote.

`JavaScript PWA` `Netlify Functions` `Google Calendar & Drive APIs` `Claude API`

#### [Robotics](https://github.com/mtri0407/robotics)
Control code for a 2-DOF VEX V5 robot arm (VEX Robotics Competition, Oct 2026) and Arduino AlphaBot path-following with a separate calibration routine.

`C++` `VEXcode V5` `Arduino`

---

### 🧭 Journey

| When | What |
|---|---|
| Sep 2026 → | **HUST**, Bachelor in Information Technology, French-Vietnamese Excellent Engineer Program (PFIEV, IT-EP) |
| Apr 2026 → | **Founder & Lead Software Engineer**, Greysteel Education |
| Apr 2026 → | **Control Systems Developer**, VEX V5 robotics team |
| Nov 2025 → | **National Sub-Junior Athlete (U74)**, Vietnam Powerlifting Federation |
| 2024 → | **Head Coach**, Greysteel Performance & Coaching: data-driven training system in Google Sheets; coached an athlete to 1 Gold + 3 Silver (93 → 82 kg bodyweight, Squat 180 → 210 kg) |
| Jun 2026 | Graduated **Tran Phu High School for the Gifted**, Bilingual French-Vietnamese track |

### 🧰 Skills

- **Languages**: JavaScript (ES modules, Node.js), HTML/CSS, SQL (SQLite / D1), Google Apps Script, C/C++ (learning)
- **Platforms**: Cloudflare Workers, D1, R2, Workers AI · Netlify Functions · Google Workspace APIs · OAuth 2.0
- **Practices**: system architecture, schema design and migrations, web security, automated testing, LLM integration, AI-assisted development
- **Spoken**: Vietnamese (native) · English (fluent, SAT 1580) · French (proficient, DELF B1/B2, 12-year bilingual program)

### 🏅 Honors

- SAT 1580/1600 (790 Math, 790 Reading & Writing), first attempt
- Gold Medal Squat (190 kg) and Silver Medal Total, U74 Sub-Junior, VPF National Championship 2025
- 1st Prize, school selection round for the Geography team competing in the City Gifted Student Competition (9.63/10 after 14 days of preparation)

### 📫 Reach me

📧 [minhtriphamnguyen69@gmail.com](mailto:minhtriphamnguyen69@gmail.com) · 🌐 [thegreysteel.com](https://thegreysteel.com)

---

<details>
<summary>🇻🇳 Giới thiệu bằng tiếng Việt</summary>

<br>

Mình là **Phạm Nguyễn Minh Trí**, sinh viên Công nghệ thông tin chương trình Kỹ sư chất lượng cao Việt Pháp (PFIEV) tại Đại học Bách khoa Hà Nội, cựu học sinh hệ Song ngữ Pháp THPT Chuyên Trần Phú, Hải Phòng.

- **Founder Greysteel Education**: tự xây toàn bộ nền tảng vận hành trung tâm (hơn 42.000 dòng code, hơn 200 hành động API, 54 phiên bản trong 6 tháng), doanh thu 20 triệu đồng tháng đầu.
- Chuyển phần đọc dữ liệu lên Cloudflare Workers + D1, giảm thời gian phản hồi từ 3,3 giây xuống 41 ms mà không phải viết lại máy chủ.
- Đưa AI vào quy trình dạy học: chấm thử bài viết theo khung IELTS, DELF; tách đề từ tệp; chatbot tư vấn.
- **Greysteel Tasks**: app lập kế hoạch kết hợp ma trận Eisenhower với chu kỳ tập luyện thể thao, tự xếp bù lịch và đồng bộ Google Calendar.
- **Robotics**: lập trình cánh tay robot VEX V5 và xe Arduino.
- SAT 1580, HCV Squat và HCB Tổng cử giải Powerlifting toàn quốc 2025, giải Nhất kỳ tuyển chọn đội tuyển HSG Địa lí của trường dự thi HSG cấp thành phố.

</details>

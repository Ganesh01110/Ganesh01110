# 🎨 GitHub Profile README — Setup Guide (Ganesh Sahu)

This is a personalised reference guide for **Ganesh Sahu's** (`Ganesh01110`) GitHub profile setup.

---

## 📋 What's in this repo

| File | Purpose |
|------|---------|
| `README.md` | Main profile page |
| `anime1.gif` | Hero coder animation |
| `ghibili.gif` | Stats section side animation |
| `.github/workflows/snake.yml` | Generates snake animation daily |
| `.github/workflows/guestbook.yml` | Auto-replies to guestbook comments |

---

## 🔧 One-Time Manual Setup (do once after first push)

### 1. Enable Workflow Write Permissions
> Without this the snake animation will fail.

- Go to: `https://github.com/Ganesh01110/Ganesh01110/settings/actions`
- Scroll to **Workflow permissions**
- Select ✅ **Read and write permissions**
- Click **Save**

### 2. Trigger Snake Animation
- Go to: `https://github.com/Ganesh01110/Ganesh01110/actions`
- Click **Generate Snake** → **Run workflow** → select `main` → **Run workflow**
- Wait ~1 min for ✅ — after this it auto-runs daily at midnight

### 3. Enable GitHub Discussions (for Guestbook)
- Go to: `https://github.com/Ganesh01110/Ganesh01110/settings`
- Scroll to **Features** → check ☑️ **Discussions**
- Save

### 4. Create Guestbook Category
- Go to Discussions tab → ⚙️ **Categories** → **New category**
- Name: `Guestbook` | Format: **Open-ended discussion**
- Click **Create**

### 5. Post Welcome Message (pin it)
- Go to: `https://github.com/Ganesh01110/Ganesh01110/discussions/new`
- Select **Guestbook** category
- Title: `📖 Welcome to My Guestbook!`
- Body:
```
# 👋 Hey there! Thanks for stopping by!

I'm Ganesh — a Full Stack Developer passionate about building scalable systems,
microservices, and agentic AI applications.

Feel free to leave a message below!
- 🙋 Introduce yourself
- 💬 Share thoughts on any of my projects
- 🤝 Propose a collaboration or just say hi

> 💼 Check out my Portfolio: https://gamified-portfolio-one.vercel.app/

Looking forward to connecting with you! 🚀
— Ganesh
```
- Click **Start discussion** → then **pin it** (`...` menu → Pin discussion)

---

## ✏️ How to Update Skills

The Skills & Technologies section is **static HTML** inside `README.md`. To add a new skill:

1. Find the right sub-section (`### 💻 Languages`, `### ⚙️ Backend`, etc.)
2. Add a new `<td>` cell inside the `<tr>` with this template:
```html
<td align="center" width="90">
  <img src="DEVICON_URL" width="50" height="50" alt="TechName" />
  <br>TechName
</td>
```
3. Get the icon URL from: https://devicon.dev/

---

## 🚀 How to Add a New Project

Find the `## 🚀 Featured Projects` section in `README.md` and add:

```markdown
### 🔥 Project Name
> One-line description

[![View Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat&logo=github&logoColor=white)](REPO_URL)

**Tech Stack:**
![Tech](https://img.shields.io/badge/TechName-COLOR?style=flat&logo=LOGO&logoColor=white)

- ✅ Feature 1
- ✅ Feature 2
```

---

## 🎨 Customization Quick Ref

### Change Stats Theme
Replace `theme=radical` in the stats card URLs with:
`dark` | `tokyonight` | `dracula` | `gruvbox` | `onedark`

### Change Typing Animation Lines
Edit the `lines=` parameter in the `readme-typing-svg` URL (line ~25 in README.md).
Encode spaces as `+` and special chars as URL codes.

### Dynamic Sections (self-updating)
| Section | Updates |
|---------|---------|
| GitHub Stats card | Real-time via `github-readme-stats` API |
| Top Languages | Real-time via `github-readme-stats` API |
| Streak Stats | Daily via `github-readme-streak-stats` API |
| Snake Animation | Daily via `snake.yml` GitHub Action |
| Profile Views counter | Every visit via `komarev.com` |

---

## 🔗 Profile Details

| Field | Value |
|-------|-------|
| GitHub Username | `Ganesh01110` |
| Email | ganeshsahu0108@gmail.com |
| Portfolio | https://gamified-portfolio-one.vercel.app/ |
| LinkedIn | https://www.linkedin.com/in/ganesh-sahu-59a00b223 |

# 🚀 Quick Setup Guide: Animated Terminal GitHub Profile

Follow these simple steps to activate your animated GitHub Profile README:

---

### Step 1: Create your Special GitHub Repository
1. Go to [GitHub New Repository](https://github.com/new).
2. Set the **Repository name** to your exact **GitHub username** (e.g. if your username is `octocat`, name it `octocat`).
   > GitHub will show a special banner: *"✨ You found a secret! `<username>/<username>` is a special repository that you can use to add a README.md to your GitHub profile."*
3. Make sure the repository is **Public**.
4. Check **Add a README file** (or push the files created here).

---

### Step 2: Personalize the `README.md`
Open [`README.md`](file:///c:/Users/ay915/OneDrive/Desktop/LearningProjects/Python/github-profile-readme/README.md) and replace the placeholders:
- Replace all instances of `YOUR_GITHUB_USERNAME` with your actual GitHub username.
- Replace `YOUR_LINKEDIN`, `your.email@example.com`, `YOUR_TWITTER`, and `https://yourportfolio.com` with your real social links.
- Tweak the `developer_profile.sh` script text or skills table to match your preferred stack and personality.

---

### Step 3: Enable the Contribution Snake Animation
To make the animated snake eat your contribution graph:
1. Commit the workflow file into your repository under `.github/workflows/snake.yml`.
2. Go to your repository's **Settings** -> **Actions** -> **General**.
3. Under **Workflow permissions**, select **"Read and write permissions"** and click **Save**.
4. Go to the **Actions** tab in your repository, click **"Generate Contribution Snake Animation"**, and click **"Run workflow"**.
5. Once the run completes (takes ~30s), a branch called `output` will be created with your animated SVGs, and your profile will immediately start displaying the live snake!

---

### Features Included
- 🟢 **Dynamic Terminal Typing SVG**: Real-time typing loop highlighting your Full-Stack skills.
- 💻 **Terminal / Neofetch Profile Block**: Clean developer terminal mock window.
- ⚡ **Dark Tech Arsenal**: Curated modern dark badges for web frameworks, DBs, and tools.
- 🐍 **Automated Snake Game**: Consumes your GitHub commit history every 12 hours.
- 📊 **Matrix/Terminal Stats Cards**: Real-time commit statistics, streaks, and top languages.
- 📈 **Commit Activity Waves**: Live interactive activity wave chart.
- 📡 **CLI Connect Badges**: Sleek matrix-green styled links for socials.

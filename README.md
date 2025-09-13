# 📰 Fake News Detector with Real-Time News Fetching

Welcome to the **Fake News Detector** project!  
This tool fetches news articles in real-time (with a 12-hour delay on the free GNews API plan) based on a user-defined topic and displays detailed information about each article. It can be easily extended to classify news as real or fake using machine learning models.

---

## 🚀 Features

- ✅ Fetches news articles using the [GNews API](https://docs.gnews.io/)
- ✅ Fetches social media posts using the [Facebook API](https://developers.facebook.com/docs/pages-api) , [Instagram API](https://developers.facebook.com/docs/instagram-platform)
- ✅ Displays detailed information about each article:
    - Published Time
    - Title
    - Description
    - Image URL
    - Content Snippet
    - Source Name, URL & Country
    - Article URL
 
## 🤝 Contribution

### 1. Fork the Repository
- Go to the GitHub page of this project:  
  [https://github.com/kuheli31/Fake-News-Detector](https://github.com/kuheli31/Fake-News-Detector)  
- Click on the **Fork** button (top-right corner). This will create a copy of the repository under your GitHub account.

### 2. Clone Your Fork
- Open GitHub Desktop, Git Bash, or your preferred Git client.
- Clone your forked repository to your local computer. For Git Bash, run:
```bash
git clone https://github.com/<your-username>/Fake-News-Detector.git
```

### 3. Create a New Branch
- Always make changes in a new branch instead of main.
- Name the branch with your name or feature, for example:
```bash
git checkout -b kuheli-branch
```

### 4. Make Your Changes
- Open the file `Fake_News_Detection.ipynb` in **Google Colab**.  
- Make your improvements, such as:
  - Adding new features
  - Fixing bugs
  - Improving documentation or examples
  - Enhancing visualizations or outputs
- After making your changes, **save the notebook** in Google Colab.  
- Then, save a **copy back to this GitHub repository** folder directly from Google Colab:
  1. Click on **File → Save a copy in GitHub**.
  2. Choose your forked repository and the branch you created (e.g., `kuheli-branch`).
  3. Add a **descriptive commit message** about your changes.
  4. Click **OK** to push the changes to your GitHub fork.
  
### 5. Commit Your Changes (If using Git locally)
- Commit your changes with a clear message explaining what you did:
```bash
git add .
git commit -m "Added feature X / Fixed issue Y / Updated README"
```

### 6. Push Your Branch to GitHub
```bash
git push origin kuheli-branch
```

### 7. Create a Pull Request in Github website
- Go to your forked repository on GitHub.
- Click Compare & pull request.
- Add a descriptive title and explain your changes in detail.
- Submit the pull request. Your changes will be reviewed and merged.

## 📊 GitHub Stats Card

Shows your overall GitHub stats, including stars, commits, PRs, issues, and contributions. The rank is calculated based on your stats.

**Usage**
Simply add your GitHub username to the URL.

```md
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

**Key Customizations**

  * **`show_icons=true`**: Displays icons next to each stat.
  * **`hide=stars,commits`**: Hides specific stats from the card.
  * **`include_all_commits=true`**: Counts all commits instead of only the current year's.
  * **`hide_rank=true`**: Hides the rank circle.
  * **`theme=THEME_NAME`**: Changes the card's theme. Popular themes include `dark`, `radical`, `tokyonight`, and `transparent`.

**Example (Radical Theme with Icons)**

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&theme=radical)
```

-----

## 💻 Top Languages Card

Displays a user's most-used programming languages from their public, non-forked repositories.

**Usage**
Add your username to the URL to generate the card.

```md
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
```

**Layouts & Customizations**

  * **`layout=compact`**: Shows a compact list of languages.
  * **`layout=donut`**: Displays languages in a donut chart. Other chart options include `donut-vertical` and `pie`.
  * **`langs_count=8`**: Sets the number of languages to display (1-20).
  * **`hide=html,css`**: Excludes specific languages from the card.
  * **`exclude_repo=repo1,repo2`**: Excludes specific repositories from the calculation.

**Example (Compact Layout)**

```md
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=compact)
```

-----

## 📌 Repository & Gist Pins

Allows you to pin more than six repositories or pin gists directly in your README.

**Repository Pin Usage**

```md
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=anuraghazra&repo=github-readme-stats)](https://github.com/anuraghazra/github-readme-stats)
```

**Gist Pin Usage**

```md
[![Gist Card](https://github-readme-stats.vercel.app/api/gist?id=bbfce31e0217a3689c8d961a356cb10d)](https://gist.github.com/Yizack/bbfce31e0217a3689c8d961a356cb10d/)
```

**Example (Repo Pin)**

-----

## ⏰ WakaTime Stats Card

Displays your coding activity from your public WakaTime profile.

**Usage**
Provide your WakaTime username.

```md
[![Harlok's WakaTime stats](https://github-readme-stats.vercel.app/api/wakatime?username=ffflabs)](https://github.com/anuraghazra/github-readme-stats)
```

**Example (Compact Layout)**

```md
![Harlok's WakaTime stats](https://github-readme-stats.vercel.app/api/wakatime?username=ffflabs&layout=compact)
```

-----

## 🎨 General Customization

All cards can be customized with URL parameters. This allows you to match the cards to your personal brand or GitHub profile theme.

| Parameter | Description | Example |
| :--- | :--- | :--- |
| **`title_color`** | Color for the card title (hex). | `&title_color=5a46ff` |
| **`text_color`** | Color for the body text (hex). | `&text_color=9f9f9f` |
| **`icon_color`** | Color for icons (hex). | `&icon_color=4f92ff` |
| **`bg_color`** | Background color (hex) or gradient. | `&bg_color=121212` |
| **`hide_border`** | Hides the card border. | `&hide_border=true` |
| **`locale`** | Sets the language (e.g., `es`, `de`, `ja`). | `&locale=es` |
| **`custom_title`** | Sets a custom title for the card. | `&custom_title=My Stats` |

**Fully Customized Example**

```md
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
```

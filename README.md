# Entwined Quills

> *Ellery Queen 120th Anniversary Fanzine*  
> A commemorative project created by Chinese Ellery Queen enthusiasts.

---

## About This Project

**Entwined Quills** is a special project created to commemorate the **120th anniversary of Ellery Queen**.

We are publicly sharing the digital edition that we produced ourselves so that more readers can access and enjoy it.

We also welcome translations in other languages, and translators are very welcome to submit their work through Pull Requests.

## What's Inside

This fanzine brings together fiction, criticism, translations, Q&A material, and reference timelines in one collected project.

### Volume 1

Seven tribute stories written by Chinese Ellery Queen enthusiasts.

### Volume 2

- Articles by Chinese enthusiasts reviewing Ellery Queen
- Chinese translations of Japanese and American reviews
- Q&A sections

### Special Reference Section

At the end of the fanzine, we created three timelines:

1. A timeline of the authors' creative careers
2. A timeline of publication dates for their works
3. A timeline of the possible chronology of cases solved by Ellery Queen and Drury Lane

These timelines were compiled with the help of many different reference sources.

## Illustrations

The fanzine includes eighteen illustrations depicting classic scenes from the Ellery Queen novels.

## Origin of the Name

For the fanzine's title, we chose **"Entwined Quills."**

- Its abbreviation is **EQ**, a direct nod to Ellery Queen
- The **Q** also echoes EQ's own signature
- The imagery of intertwined feathers suggests dual authorship, collaboration, and creation

After finalizing the name, we were delighted to discover that, much like one of EQ's favorite word games, **"Entwined Quills"** can be rearranged into:

> **Queen still wind**

The Chinese title is **缱绻之翎**  
Pinyin: **Qiǎnquǎn Zhī Líng**

This title was chosen for its classical, elegant tone and literary feeling in Chinese.

## Reader Responses

If you have read the fanzine and would like to share your thoughts, long reviews and short comments are both warmly welcome.

- You are welcome to post your response in [Issues](https://github.com/FugeCantabile/Entwined-Quills/issues)
- If you publish a review elsewhere, feel free to share the review link in an Issue as well

We would be very happy to read your impressions.

### How to Submit a Comment Issue

If you use the GitHub CLI:

```bash
# 1. Fork or clone the repository if needed
git clone https://github.com/FugeCantabile/Entwined-Quills.git
cd Entwined-Quills

# 2. Log in to GitHub CLI
gh auth login

# 3. Create an issue for your short comment or long review
gh issue create \
  --title "My reading notes on Entwined Quills" \
  --body "I have finished reading the fanzine. Here are my comments..."
```

If you want to share an external review link:

```bash
gh issue create \
  --title "Review link: [your review title]" \
  --body "I published my review here: https://example.com/your-review"
```

## Translation Contributions

**If you are interested in translating this project, you are very welcome to contribute.**

We especially welcome:

- English translation
- Japanese translation
- Other language translations

Please note that this repository mainly hosts the released digital edition itself. Translation contributions should be submitted as additional files, rather than replacing the original edition.

### How to Submit a Translation Pull Request

If you want to contribute a translation, the recommended workflow is:

```bash
# 1. Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/Entwined-Quills.git
cd Entwined-Quills

# 2. Add the original repository as upstream
git remote add upstream https://github.com/FugeCantabile/Entwined-Quills.git

# 3. Create a translation branch
git checkout -b translation/en-readme

# 4. Add your translation file
# Example:
# README.en.md

# 5. Stage and commit your work
git add README.en.md
git commit -m "Add English translation of README"

# 6. Push your branch to your fork
git push origin translation/en-readme

# 7. Create a Pull Request with GitHub CLI
gh pr create \
  --repo FugeCantabile/Entwined-Quills \
  --base main \
  --head YOUR_USERNAME:translation/en-readme \
  --title "Add English translation of README" \
  --body "This PR adds an English translation of README.md."
```

If you do not use GitHub CLI, you can still follow the same Git steps above and then open the Pull Request on GitHub in your browser.

We will review and update contributions as promptly as we can.

## File Structure

```text
├── Entwined Quills International Edition.epub  # Original EPUB file
├── LICENSE                                     # CC-BY-NC-SA 4.0 License
├── README.md                                   # Project overview
└── SETUP.md                                    # Git LFS installation guide
```

## License

This project is licensed under the [CC-BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License.

- **Attribution (BY):** You must give appropriate credit to the original authors
- **NonCommercial (NC):** You may not use the material for commercial purposes
- **ShareAlike (SA):** If you remix, transform, or build upon the material, you must distribute your contributions under the same license

---

**Entwined Quills = Queen still wind**

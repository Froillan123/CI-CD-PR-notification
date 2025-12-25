# Sample Notification Outputs

This document shows what the notifications will look like in each platform.

## 💬 Discord Notification Sample

### Visual Appearance:
```
┌─────────────────────────────────────────────────────────┐
│ GitHub CI/CD                                             │
│                                                          │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ 🆕 New Pull Request Opened                          │ │
│ │                                                      │ │
│ │ joannesarsalejo23-art created a new pull request   │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📋 Pull Request                                 │ │ │
│ │ │ #1 - Add new feature                             │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌──────────────┐  ┌──────────────────────────────┐ │ │
│ │ │ 👤 Author    │  │ 🌿 Branch                    │ │ │
│ │ │ joannesars...│  │ 🔀 FORK `master` → `master`  │ │ │
│ │ └──────────────┘  └──────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📊 Changes                                       │ │ │
│ │ │ 5 files • 3 commits                               │ │ │
│ │ │ ✅ +150 lines • ❌ -50 lines                     │ │ │
│ │ │                                                  │ │ │
│ │ │ 📁 Files: +2 added, -0 removed, ~3 modified     │ │ │
│ │ │ 📦 Types: js (3), md (1), yml (1)               │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📝 Changed Files (5)                              │ │ │
│ │ │   • src/index.js                                 │ │ │
│ │ │   • src/utils.js                                 │ │ │
│ │ │   • README.md                                    │ │ │
│ │ │   • .github/workflows/ci.yml                     │ │ │
│ │ │   • package.json                                 │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ [Author Avatar Thumbnail]                           │ │
│ │                                                      │ │
│ │ GitHub Actions • PR Notification                    │ │
│ │ Today at 9:31 PM                                    │ │
│ └─────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────┘
```

### Key Features:
- ✅ **Color-coded embed** (Blue for opened, Green for merged, Red for closed)
- ✅ **Author avatar thumbnail** (shows profile picture)
- ✅ **Fork indicator** (🔀 FORK when from different repo)
- ✅ **Detailed file statistics**
- ✅ **Changed files list** (up to 8 files)
- ✅ **Clickable links** (PR title, author name)

---

## 💼 Slack Notification Sample

### Visual Appearance:
```
┌─────────────────────────────────────────────────────────┐
│ GitHub CI/CD                                             │
│                                                          │
│ ┌─────────────────────────────────────────────────────┐ │
│ │ 🆕 New Pull Request Opened                          │ │
│ │                                                      │ │
│ │ joannesarsalejo23-art created a new pull request   │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📋 Pull Request                                 │ │ │
│ │ │ #1 - Add new feature                             │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌──────────────┐  ┌──────────────────────────────┐ │ │
│ │ │ 👤 Author    │  │ 🌿 Branch                    │ │ │
│ │ │ joannesars...│  │ 🔀 FORK `master` → `master` │ │ │
│ │ └──────────────┘  └──────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📊 Changes                                       │ │ │
│ │ │ 5 files • 3 commits                               │ │ │
│ │ │ ✅ +150 lines • ❌ -50 lines                     │ │ │
│ │ │                                                  │ │ │
│ │ │ 📁 Files: +2 added, -0 removed, ~3 modified     │ │ │
│ │ │ 📦 Types: js (3), md (1), yml (1)               │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ ┌─────────────────────────────────────────────────┐ │ │
│ │ │ 📝 Changed Files (5)                              │ │ │
│ │ │   • src/index.js                                 │ │ │
│ │ │   • src/utils.js                                 │ │ │
│ │ │   • README.md                                    │ │ │
│ │ │   • .github/workflows/ci.yml                     │ │ │
│ │ │   • package.json                                 │ │ │
│ │ └─────────────────────────────────────────────────┘ │ │
│ │                                                      │ │
│ │ [Author Avatar Thumbnail]                           │ │
│ │                                                      │ │
│ │ GitHub Actions • PR Notification                    │ │
│ │ Today at 9:31 PM                                    │ │
│ └─────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────┘
```

### Key Features:
- ✅ **Color-coded attachment** (matches Discord colors)
- ✅ **Author avatar thumbnail** (thumb_url)
- ✅ **Fork indicator** (🔀 FORK when from different repo)
- ✅ **Detailed file statistics**
- ✅ **Changed files list**
- ✅ **Clickable links** (Slack link formatting)

---

## 🔧 Custom Webhook Sample

### JSON Payload Example:

```json
{
  "event": "pull_request",
  "action": "opened",
  "timestamp": "2024-01-15T21:31:00Z",
  "pull_request": {
    "number": 1,
    "title": "Add new feature",
    "url": "https://github.com/owner/repo/pull/1",
    "author": {
      "username": "joannesarsalejo23-art",
      "url": "https://github.com/joannesarsalejo23-art",
      "avatar_url": "https://avatars.githubusercontent.com/u/12345678?v=4"
    },
    "base_branch": "master",
    "head_branch": "master",
    "is_fork": true,
    "head_repo": "joannesarsalejo23-art/CI-CD-PR-notification",
    "base_repo": "Froillan123/CI-CD-PR-notification",
    "merged": false,
    "merged_by": null,
    "stats": {
      "files_changed": 5,
      "additions": 150,
      "deletions": 50,
      "commits": 3,
      "files_added": 2,
      "files_removed": 0,
      "files_modified": 3,
      "files_renamed": 0
    },
    "file_types": "js (3), md (1), yml (1)",
    "changed_files": [
      "src/index.js",
      "src/utils.js",
      "README.md",
      ".github/workflows/ci.yml",
      "package.json"
    ]
  },
  "notification": {
    "title": "🆕 New Pull Request Opened",
    "description": "joannesarsalejo23-art created a new pull request",
    "color": "#3498db"
  },
  "repository": {
    "name": "Froillan123/CI-CD-PR-notification",
    "url": "https://github.com/Froillan123/CI-CD-PR-notification"
  }
}
```

### Key Features:
- ✅ **Complete PR data** (all information available)
- ✅ **Fork detection** (`is_fork: true/false`)
- ✅ **Repository info** (head_repo and base_repo)
- ✅ **Detailed statistics** (file operations breakdown)
- ✅ **File list** (array of all changed files)
- ✅ **Author object** (username, URL, avatar)
- ✅ **Flexible format** (you can format it however you want!)

---

## 🎨 Event Type Colors

### Discord Colors:
- 🆕 **Opened**: Blue (`3447003`)
- 📝 **Updated**: Yellow (`16776960`)
- 🔄 **Reopened**: Purple (`10181046`)
- ✅ **Merged**: Green (`5763719`)
- ❌ **Closed**: Red (`15158332`)

### Slack Colors:
- 🆕 **Opened**: `#3498db` (Blue)
- 📝 **Updated**: `#f39c12` (Yellow)
- 🔄 **Reopened**: `#9b59b6` (Purple)
- ✅ **Merged**: `#2ecc71` (Green)
- ❌ **Closed**: `#e74c3c` (Red)

---

## 🔀 Fork Detection Examples

### Regular PR (Same Repository):
```
🌿 Branch
`feature-branch` → `master`
```

### Fork PR (Different Repository):
```
🌿 Branch
🔀 FORK `master` → `master`
```

---

## 📊 Complete Field Breakdown

### Discord & Slack Fields:
1. **📋 Pull Request** - PR number, title, and link
2. **👤 Author** - GitHub username with profile link
3. **🌿 Branch** - Source → Target (with fork indicator)
4. **📊 Changes** - Files, commits, lines, file operations, file types
5. **📝 Changed Files** - List of modified files (up to 8 shown)

### Custom Webhook Fields:
- All PR metadata
- Author information (username, URL, avatar)
- Branch information (with fork detection)
- Complete statistics
- Full file list (no truncation)
- Repository information

---

## ✅ Summary

All three platforms provide:
- ✅ Author avatars/pictures
- ✅ Fork detection and display
- ✅ Detailed file information
- ✅ Comprehensive statistics
- ✅ Professional formatting
- ✅ Color-coded events

**Discord & Slack**: Visual embeds with thumbnails and formatted text
**Custom Webhook**: Complete JSON data for custom processing/display


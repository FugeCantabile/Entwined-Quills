# 安装 Git LFS 并推送大文件指南

由于 EPUB 文件 (133MB) 超过 GitHub 单文件限制 (100MB)，需要使用 Git LFS。

## 步骤 1: 安装 Git LFS

### 方法 A: 直接下载二进制（推荐）

```bash
cd /tmp
curl -L https://github.com/git-lfs/git-lfs/releases/download/v3.4.0/git-lfs-linux-amd64-v3.4.0.tar.gz -o git-lfs.tar.gz
tar -xzf git-lfs.tar.gz
sudo mv git-lfs-3.4.0/git-lfs /usr/local/bin/
rm -rf git-lfs.tar.gz git-lfs-3.4.0
git lfs install
```

### 方法 B: 使用包管理器

```bash
# Ubuntu/Debian
sudo apt-get install git-lfs

# CentOS/RHEL/OpenAnolis
sudo yum install git-lfs

# Arch Linux
sudo pacman -S git-lfs
```

## 步骤 2: 配置 LFS 追踪 EPUB 文件

```bash
cd /home/admin/.openclaw/workspace/Entwined-Quills
git lfs install
git lfs track "*.epub"
```

这会创建 `.gitattributes` 文件。

## 步骤 3: 添加并提交 EPUB 文件

```bash
git add .gitattributes Entwined-Quills.epub
git commit -m "Add EPUB file with LFS"
```

## 步骤 4: 推送到 GitHub

```bash
# 配置远程仓库 URL（使用你的 token）
git remote set-url origin https://<YOUR_TOKEN>@github.com/FugeCantabile/Entwined-Quills.git

# 推送
git push -u origin main
```

## 验证

推送完成后，访问 https://github.com/FugeCantabile/Entwined-Quills 查看文件。

---

## 当前状态

✅ GitHub 仓库已创建：https://github.com/FugeCantabile/Entwined-Quills
✅ 本地仓库已初始化：/home/admin/.openclaw/workspace/Entwined-Quills
✅ 小文件已提交：LICENSE, README, .gitignore
⏳ 等待安装 Git LFS 后推送 EPUB 文件

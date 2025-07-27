## 📘 Git Commands (with Bangla Guide)

```bash
# Init repo
git init
# 👉 একটি নতুন Git রিপোজিটরি শুরু করে

# Stage all files
git add .
# 👉 সব ফাইলকে Git এর স্টেজিং এrea-তে যোগ করে

# Commit changes
git commit -m "message"
# 👉 একটি মেসেজ সহ পরিবর্তন সংরক্ষণ করে

# Rename branch to main
git branch -M main
# 👉 বর্তমান ব্রাঞ্চকে জোরপূর্বক 'main' নাম দেয়

# Add remote
git remote add origin https://github.com/your-username/your-repo.git
# 👉 লোকাল রিপোজিটরির সাথে GitHub রিপোজিটরি যুক্ত করে

# Push & set upstream
git push -u origin main
# 👉 main ব্রাঞ্চকে GitHub-এ পাঠায় এবং future push/pull সহজ করে

# Change remote URL
git remote set-url origin https://github.com/your-username/new-repo.git
# 👉 রিমোট রিপোজিটরির URL পরিবর্তন করে

# Show remotes
git remote -v
# 👉 বর্তমানে সেট থাকা রিমোটগুলোর URL দেখায় (fetch/push)

# Pull with rebase
git pull --rebase
# 👉 রিমোট থেকে কোড নিয়ে নিজের কাজগুলো রিবেজ করে বসায়

# Remove remote
git remote remove origin
# 👉 রিমোট রিপোজিটরি `origin` কে মুছে ফেলে

# Check status
git status
# 👉 ফাইলের বর্তমান অবস্থা দেখায় (staged/unstaged/untracked)

# List branches
git branch
# 👉 লোকাল ব্রাঞ্চগুলোর তালিকা দেখায়

# Show commit history
git log
# 👉 কমিট হিস্টোরি দেখায় (তারিখ, ম্যাসেজসহ)
```

# Git-and-Github-Concepts

# what is Git?

Git ek Distributed Version Control System hai jo code changes track karta hai efficiently

# what is Github?

👉 GitHub ek platform hai jahan tum apna Git code online store, manage aur share kar sakte ho

# what is VCS (version control system)?

Version Control System = ek system jo files ke changes ko track karta hai over time

# 1. How to setup your username and email-id in your system?

```
git config --global user.name "Ayush"
git config --global user.email "ayush@example.com"

```

# git init kya karta hai?

Jab tum terminal mein likhte ho:

git init

👉 Yeh tumhare current folder ko Git repository bana deta hai.

🔧 Under the hood kya hota hai?
------------------------------------

1. Ek hidden folder create hota hai: .git
2. Iske andar Git sab kuch store karta hai:
```
commits
branches
history
configuration
```

**👉 Basically:
**

"Normal folder → Git-controlled smart folder"

**⚙️ Internal Working (Step by Step)
**
----------------------------------------

.git folder create hota hai
Iske andar yeh important cheezein banti hain:
HEAD → current branch pointer
objects/ → saare commits & data
refs/ → branches info
Default branch set hoti hai (usually main ya master)

**👉 Ab tum kar sakte ho:
**
--------------------------
```
git add
git commit
git branch
```

**🧪 Example
**
-------------
```
mkdir project
cd project
git init
```

**👉 Output:
**
-------------
```
Initialized empty Git repository in /project/.git/
```

# Git_HW_2
## 1. 
```
kv@kvPC MINGW64 /d/github_lesson/HW_2
$ git clone https://github.com/Veronika-Koronets/Git_HW_2.git
Cloning into 'Git_HW_2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

kv@kvPC MINGW64 /d/github_lesson/HW_2
$ pwd
/d/github_lesson/HW_2

kv@kvPC MINGW64 /d/github_lesson/HW_2
$ ls -la
total 0
drwxr-xr-x 1 kv 197121 0 May  7 20:34 ./
drwxr-xr-x 1 kv 197121 0 May  7 20:34 ../
drwxr-xr-x 1 kv 197121 0 May  7 20:34 Git_HW_2/

kv@kvPC MINGW64 /d/github_lesson/HW_2
$ cd Git_HW_2

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch Postman

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch Jmeter

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch CheckLists

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch Bag_reports

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch SQL

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch Charles

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch Mobile_testing

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git branch
  Bag_reports
  Charles
  CheckLists
  Jmeter
  Mobile_testing
  Postman
  SQL
* main
```

## 2. kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
```
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Veronika-Koronets/Git_HW_2.git
 * [new branch]      Bag_reports -> Bag_reports
 * [new branch]      Charles -> Charles
 * [new branch]      CheckLists -> CheckLists
 * [new branch]      Jmeter -> Jmeter
 * [new branch]      Mobile_testing -> Mobile_testing
 * [new branch]      Postman -> Postman
 * [new branch]      SQL -> SQL
```

## 3. 
```
kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (main)
$ git checkout Bug_reports
Switched to branch 'Bug_reports'

kv@kvPC MINGW64 /d/github_lesson/HW_2/Git_HW_2 (Bug_reports)
$ git branch
* Bug_reports
  Charles
  CheckLists
  Jmeter
  Mobile_testing
  Postman
  SQL
  main
```


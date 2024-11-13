# Git task questions answers

> i try to expline my answers with a simple caption after each photo

## 1. Initialize an empty git repository :

![init command](pic1.png)
command used :

```
git init
```

## 2. Add third.txt to the staging area :

![add command](pic2.png)
command used :

```
git add third.txt
```

## 3. Commit with the message "adding third.txt" :

![commit command](pic3.png)
command used :

```
git commit -m "adding third.txt"
```

## 4. Check out my commit :

![log command](pic4.png)
command used :

```
git log
```

## 5. Add fourth.txt to the staging area :

![add command](pic5.png)

```
git add third.txt
```

## 6. Commit with the message "adding fourth.txt" :

![commit command](pic6.png)
command used :

```
git commit -m "adding fourth.txt"
```

## 7. Remove the third.txt file and Add this change to the staging area and commit :

![3 command](pic7.png)
command used :

```
rm third.txt
git add .
git commit -m "removing third.txt"
```

## 8. Check out my commits :

![log command](pic8.png)
command used :

```
git log
```

## 9. Change my global settings to core.pager=cat :

![config command](pic9.png)
command used :

```
git config --global core.pager cat
```

this change to cat pager, which will display the output all at once without a pager

## 10. list all the global configurations for git :

![list command](pic10.png)
command used :

```
git config --global --list
```

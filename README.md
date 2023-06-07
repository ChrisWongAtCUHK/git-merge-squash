# Commands
m1
```
$ echo m1 >> test.txt
$ git add test.txt
$ git commit -m "first commit"
```

m2
```
$ echo m2 >> test.txt
$ git add test.txt
$ git commit -m "second commit"
```

checkout `feature` branch
```
$ git checkout -b feature
```

f1
```
$ echo f1 >> feature.txt
$ git add feature.txt
$ git commit -m "third commit"
```

f2
```
$ echo f2 >> feature.text
$ git add feature.txt
$ git commit -m "fourth commit"
```

checkout `main` branch
```
$ git checkout main
```

squash merge
```
$ git merge --squash feature
```

view
```
$ git log --graph --oneline
```

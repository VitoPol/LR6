# LR6

Лабораторная работа №6

### Лог всех команд


```
  227  git clone https://github.com/VitoPol/LR6  
  228  ls  
  229  cd LR6/  
  230  cat mergefile.txt  
  231  clear  
  232  cat 123  
  233  con 123  
  234  echo "Hello world!" >> test.txt  
  235  ls  
  236  cat test.txt  
  237  rm test.txt  
  238  ls  
  239  clear  
  240  git pull  
  241  ls  
  242  git log --all --graph --oneline --decorate  
  243  git merge origin/branch1  
  244  git status  
  245  git add mergefile.txt  
  246  git commit  
  247  git log --all --graph --oneline --decorate  
  248  git branch -d origin/branch1  
  249  git branch -d --remote origin/branch1  
  250  git log --all --graph --oneline --decorate  
  251  git checkout -c report  
  252  git checkout -b report  
  253  git checkout master  
  254  git branch -d report  
  255  touch something2.txt  
  256  ls  
  257  git add .  
  258  git commit  
  259  echo "123" >> something2.txt  
  260  git add .  
  261  git commit -m "Заполнил файл"  
  262  echo "456" >> something2.txt  
  263  cat something2.txt  
  264  git add .  
  265  git commit -m "Дополнил файл"  
  266  git log --all --graph --oneline --decorate  
  267  git reset --soft 034ae94  
  268  git log --all --graph --oneline --decorate  
  269  git branch -c reset  
  270  git branch  
  271  git branch -d reset  
  272  git branch -D reset  
  273  git checkout -b report  
  274  hisrtory  
  275  history
```


### Скриншоты


Решение конфликта слияния:

![](c:/Users/vikto/guap/LR6/images/git_gui.png)  

 
![](c:/Users/vikto/guap/LR6/images/merge.png)

Откат коммита:

![](c:/Users/vikto/guap/LR6/images/reset_commit.png)  

  

  


 

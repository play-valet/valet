# valet: scaffold iterater for playframework

### movie
[![](http://img.youtube.com/vi/p9_gWWoZjoQ/0.jpg)](https://www.youtube.com/watch?v=p9_gWWoZjoQ)

### Description
Valet is under development.Please do not use.
If you use it please check the source code.
For the convenience of development valet, the following commands are included, so please be careful when using it.
```
    docker stop $(docker ps -a -q);
    docker rm $(docker ps -a -q);
```


### install
```
brew tap play-valet/homebrew-valet
brew install valet
valet -v
```

### uninstall
```
brew uninstall --force valet
brew untap play-valet/valet
```

### usage
```
git clone git@github.com:playframework/play-scala-starter-example.git
cd play-scala-starter-example/
valet init
valet start
sbt run

http://localhost:9000/posts
```

### default config file
[https://github.com/play-valet/valet-default-conf](https://github.com/play-valet/valet-default-conf)

### Now Trying:scaffold iterater
Devide Autogen and Your Implement By ```Override```.

1)Scaffold.conf + Module.conf => Autogen  
2)write your code  
3)Occur Specification-change  
4)ModifiedScaffold.conf + ModifiedModule.conf => Autogen  
5)write your code  



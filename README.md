# 裸机搭建git仓库托管代码
## linux 之git搭建过程
```说明需在root下home搭建```
   
```html
1. mkdir -p huixue/huixue.git 
2.cd huixue/huixue.git/
3.git init --bare   //创建一个所谓的裸仓库
4.cd ..
5.chown -R git:git huixue.git  //创建文件权限
```

  ```其他机器访问```
  ### git clone git@xx.xxx.xx:/home/huixue/huixue.git
   

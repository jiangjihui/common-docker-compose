
## 在docker容器的控制台里面进入SQLPLUS
> source /home/oracle/.bash_profile; sqlplus /nolog

## 切换到sys用户
> connect sys/password as sysdba;

## 创建用户
> create user DIMP identified by DIMP;

## 赋权
> grant sysdba to DIMP;
  

> https://blog.csdn.net/eyeofeagle/article/details/86503350
> https://blog.csdn.net/xdy1120/article/details/91353579
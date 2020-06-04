# MySpringTimerTaskCRUDMyDatabase
TimerTask tutorial

使用Spring的定时任务与mybaitis对MySQL数据库操作

mysql> DROP TABLE IF EXISTS details.student;
CREATE TABLE  details.student(
   ID int(10) NOT NULL AUTO_INCREMENT,  
   NAME varchar(100) NOT NULL,
   BRANCH varchar(255) NOT NULL,
   PERCENTAGE int(3) NOT NULL,  
   PHONE int(10) NOT NULL,
   EMAIL varchar(255) NOT NULL,
   PRIMARY KEY ( ID )
);


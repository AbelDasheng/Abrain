# Abrain
A nodejs  Ai tools .
本框架是一个Nodejs的AI的机器学习、大数据处理的集成框架。

写此框架的最初想法
 各种官方成熟的AI框架数不胜数，如tensorflow,pytrcon,sklearn等等。为什么我还要自己写一个AI框架呢？
 本人愚见，觉得开发就应该有不同的思路和创新，按照自己的想法去定义AI,绝对是很酷的一件事情。
 
申明
本软件仅做参考及交流学习


自己对于AI的定义
 我对于AI的理解，AI就是一个人一样，你给予啥功能就有啥功能，因此让他能学习、有感情判断、能说、看、听，他就能拥有比较完善的人类特征
 
 
 
 本框架的基本架构
 
   Learn模块
   
   Brain.Learn(input,func,output) 
   
   //学习功能  机器学习，根据自己的定制算法或框架自带的系统算法给机器学习,input为学习的学习资料（text,video，audio）,func为学习算法，学习结果output实体的执行文件name.do
 
   DO模块
   
   Brain.Do.exec(output.do) or Brain.Do.exec(callback) default exec XXX.do
   
   系统自带的方法
   
   .......
   
   Brain.Do.say(text) //语音输出
   
   Brain.Do.see(files) // OCR images to text // video to text()
   
   Brain.Do.listen(files) // audio file ,video files
   
   Brain.Do.think()
   
    ......
   
   Data 模块
   
   Brain.Data.HDFS()
   
   Brain.Data.C(connectUrl,dbtype,dbname,CURD String);
    // Nosql or other SQL
    
   Brain.Data.M() //memory Data
   
    .......
   
   Net 模块
   
    Brain.Net.splider()
    
    Brain.Net.CatData()
    
    
    ........
    
    
   最后希望，项目能更完整吧！
      
 
 

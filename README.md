# Banker
Banker for little term
设计题目：
编程死锁的避免方法—银行家算法。
问题描述：系统在进行资源分配的过程中，允许进程动态的申请资源，为了避免发生死锁，在分配资源前要进行安全性检查，若此次分配不会导致系统进入不安全状态，便将资源分配给进程，否则，进程等待。
设计要求：
1.设计一个进程动态请求资源的模拟系统，包括n 个并发进程共享m 个系统资源的系统。
2.进程可动态申请资源和释放资源，系统按各进程的申请动态的分配资源。
3.要求采用银行家算法实现。
4.实现随机产生进程请求资源的数量；
5.资源安全性检查算法；
6.资源的分配算法；
7.输出显示每次请求的结果和系统资源的状态。
用Ｃ语言编程并用文档形式给出算法分析与实现过程。

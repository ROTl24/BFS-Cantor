# BFS-Cantor
解决八数码问题

本代码如果不加以限制很容易造成缓存区溢出，导致无法输出结果。经过修改此处

if (!visited[result]&&result<LEN&&result>=0) {

visited[result] = 1;

return 1;

}

else {

return 0;

}


通过对result进行限制，使其能正常输出。

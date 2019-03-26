//QString 中的字符串切割函数
eg:
QString str = "Jianhu song";
//left(int length): 从左边开始切割，长度length。
qDebug() << "left3" << str.left(4);
//right(int length): 从右边开始切割，长度为length
qDebug() << "ringht3" << str.ringht(3);
//mid(pozition,length):从position开始截取长度为length，
//若采用mid(position) 这个格式那么，截取的长度为从position开始到字符串结束;
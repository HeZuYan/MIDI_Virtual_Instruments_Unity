midi键盘常用的有	25	37	49	61	88	键
真钢琴，标准的一般是88键 2+12*7+2 即 C0的最后两个音 加C1到C7 加上C8的 最前面两个音

通常以C4为中央键 所在组为4组
分组如下-2 -1 0 1 2 3 4 5 6 7 8

而我可以导出的音域为 -2 到 7
钢琴涉及到的为 0 到 8 组 但是，0和8 都占的不全，所以，我只导出 -1 到 7组 共 9组*12 = 108


将 乐器都放入 Vsti/乐器名/

path= Vsti/乐器名/OGG/乐器名_音调

音调 C[#][number]	D[number]	E[#][number]	F[number]	G[#][number]	A[number]	B[#][number]

number>=-1&&number<=7


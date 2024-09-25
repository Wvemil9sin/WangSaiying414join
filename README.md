# WangSaiying414join
Dear senior schoolmate:
  My name is WangSaiying.I'm from Xi'an,a city with rich historical heritage.I'm glad to have this interview,I'm an optimistic and cheerful person which maintain a passionate heart towards all new things.I want to apply to join 414 club this time because:as a newcomer in digital media technology,I'm not yet familiar with the relevant knowledge,so I want to improve my professional level through this club.At the same time,do my best to help 414 club get better and better!
  Learning objectives:
  1.Learn how to model
  2.Gain deeper professional knowledge
  3.Gain internship experience

冒泡算法：对于原始数据数组，以从前往后的顺序进行多次扫描，相邻两组数据次序与排序要求大小次序不符时，互换这两组数据，之所以名为冒泡算法，是因为若从小到大排序，小数据会向前一步步运动，就好像气泡向上漂浮一样。
#include <stdio.h.
int'main(){
   int a[10] = {3, 1, 4, 5, 2};
   for(int i = 1; i <= 4; i++){
      for(int j = 0; j <5 - i; j++){
         if(a[j] > a[j + 1]){
            int temp = a[j];
            a[j] = a[j + 1];
            a[j + 1] = temp;
         }
      }
   }
   for(int i = 0; i < 5; i++){
      printf("%d ", a[i]);
   }
   return 0;
}

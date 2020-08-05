# physics.1
#include <stdio.h>

int main(void) {

  int a, b, c, d ;

  printf("운동량 구하기\n");
  printf("질량 : ");
  scanf("%d", &a);
  printf("속도 : ");
  scanf("%d", &b);

  printf("운동량의 크기는 질량 * 속력\n");
  printf("운동량 = %d[kg*m/s] \n\n\n", a*b );

  

  printf("충격량 구하기\n");
  printf("힘 : ");
  scanf("%d", &c);
  printf("접촉 시간 : ");
  scanf("%d", &d);

  printf("충격량의 크기는 힘 * 접촉시간\n");
  printf("충격량 = %d[N*s] \n\n\n", c * d );

  printf("처음 운동량 + 충격량 = 나중운동량\n");
  printf("위의 운동량 + 충격량 = 나중운동량\n");
  printf("%d + %d = %d", a*b, c*d, a*b + c*d);
 
  return 0;
}

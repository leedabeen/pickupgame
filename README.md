# 모바일 게임에 있는 뽑기 시스템
* 기능
  * 1회 뽑기 , 연속 뽑기 
  * 필요없는 아이템을 원하는 수량만큼 정리
  * 지금까지 얻은 아이템 확인

### 아이템 품급 확률 지정 코드 
```c
int pickup(int su1);
int pickup(int su1) {
	int su2;
	if (su1 <= 49 && su1 >= 1) {
		su2 = 1;
	}
	else if (su1 >= 50 && su1 <= 69) {
		su2 = 2;
	}
	else if (su1 >= 70 && su1 <= 84) {
		su2 = 3;
	}
	else if (su1 >= 85 && su1 <= 94) {
		su2 = 4;
	}
	else {
		su2 = 5;
	}
	return su2;
}
```

### 게임 화면 
![가챠게임 캡처](https://user-images.githubusercontent.com/74585673/147436938-99509afb-66af-4f82-87ae-60bb10ebe5fe.PNG)


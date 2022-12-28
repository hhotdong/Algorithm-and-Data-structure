# Array list

| 구분 | 시간복잡도 |
| --- | -------- |
| 조회 |          |
| 순회 |          |

## 장점

- 데이터의 참조가 쉽다.

## 단점

- 데이터 삭제 과정에서 데이터의 복사가 빈번히 발생한다.[^arraylist_disadvantage] 

### References

- 윤성우, <윤성우의 열혈 자료구조>

[^arraylist_disadvantage]: 배열의 앞에서부터 데이터를 채우는 것이 원칙이므로 삭제된 데이터 보다 뒤에 위치한 데이터들을 앞으로 한 칸씩 이동시켜야 한다.
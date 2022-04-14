# [Huffman_coding](https://github.com/DAEHEE97/Huffman_encoding/blob/main/Huffman_coding.ipynb)



## 허프만 알고리즘

초기화
- 모든 기호를 출현 빈도수에 따라 나열한다.

단 한 가지 기호가 남을 때까지 아래 단계를 반복한다.

- 목록으로부터 가장 빈도가 낮은 것을 2개 고른다.
- 그 다음 허프먼이 두가지 기호를 부모 노드를 가지는 부트리를 구성하고 자식노드를 생성한다.
- 부모 노드 단 기호들의 빈도수를 더하여 주 노드에 할당하고 목록의 순서에 맞도록 목록에 삽입한다.
- 목록에서 부모노드에 포함된 기호를 제거한다.

**허프만 알고리즘은 입력 기호를 리프 노드로 하는 이진 트리를 만들어서 접두 부호를 만들어 내는 알고리즘이다.**

## 허프만 압축 전 후

- Space usage before compression (in bits): 9720

- Space usage after compression (in bits): 5377


## 데이터 크롤링 api 설치

```
!pip install --upgrade pip
!pip install wikipedia-api
```

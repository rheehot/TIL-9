YIQ는 LAB와 유사하다. 지금은 쓰지 않음

- Y : 명도
- I - 주황/청색
- Q - 자주/녹색

아날로그에 주로 쓰임

<br/>

**색상모델 3가지를 써라**

<br/>

## 3장

최대-최소 정규화 방법

넓은 범위를 좁게 축소했다고 생각하자

<br/>

Saturation -> 255 넘으면 255로 유지

Wrapping -> 255 넘으면 r - (255+1)

---

add(Staturation) : 흰색 부분은 사라지고 검은색 부분만 남음

add(Wrapping) : 검은색 부분은 남고 흰색부분은 노이즈가 남음

sub : 틀린그림 찾기 가능!

mul : 설정한 배율만큼 밝아진다

div : 설정한 배율만큼 어두워진다

이미지끼리 나누면??? 밝기를 균일하게 함

blend : 비슷한 이미지 끼리 합치면 합쳐진다

xor : 직접 짜서 해보아라

AND : 둘다 있어야 하얀색

OR : 하나라도 있으면 하얀색

REV : 색상 반전

**다음 사진을 어떤 형식으로 바꾸려고 한다 어떤 연산을 사용해야 하는가?**

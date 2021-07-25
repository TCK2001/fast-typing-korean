# fast-typing-korean
This is for korean to test typing skills

## typing test example

```python
import hgtk 
```
*Call the library to counts the strokes of Korean (Hangeul).*
```python
for i,c in enumerate(src,start=0):
        try:
            if tar[i]==c:
                correct+=1
        except:
            pass
```
*If Correct success +1 point.*
```python
src_len=len(src)
    c=correct/src_len*100
    e=(src_len-correct)/src_len*100
    t=end_time
    speed=float(correct/end_time)*60
```
*This is calculate speed,correct percent,wrong percent and time.*
```python
print("시간: {:0.2f} 속도: {:0.2f} 타 정확율: {:0.2f} % 오타율: {:0.2f} %".format(t,speed,c,e))
```
*Output only to two decimal places. -> print time , speed , correct percent , wrong percent.*

**IN THIS CODE TYPE LIST**
* "최근 각종 소셜네트워크서비스에 '디즈니' 캐릭터 모습을 한 셀카 사진이 대거 등장하고 있다.",
* "인공지능 기술을 이용해, 사람 얼굴을 애니메이션 주인공처럼 바꿔주는 일명 '디즈니 필터'가 큰 인기를 끌고 있기 때문이다.",
* "누적 다운로드 건수도 1000만 회에 이른다.",
* "보보는 바보"

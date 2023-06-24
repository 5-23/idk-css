# idk-css
내가 몰랐고 유용?한 css 정리
## 초기값
```css
margin: 0;
padding: 0;
box-sizing: border-box;
```
##  사진
### 사진에 그라디언트

```css
background: linear-gradient(-45deg, rgba(0,0,0,0), rgba(0,0,0,1)), url(img);
```
back ground에서 llinear-gradient와 url을 같이 사용하면 사진값을 넣으면 사진에 그라디언트를 적용할수 있다

## 정렬
### space-between
```css
justify-content: space-between;
```
각 element를 양끝으로 밀어준다(3개가 있을경우 왼쪽끝-중항-오른쪽끝)으로 적용된다

### 중항
```css
left: 50%;
top: 50%;
transform: translate(-50%, -50%);
```
그냥 화면 중항에 놔둬준다

## transition
### transition-origin
사용하면 요소의 중항을 설정할수 있다
#### ex
```css
transition-origin: 10px center;
```

# 아직모름
- animation-timeline

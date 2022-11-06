# HTML & CSS

## CSS


### Grid


![img.png](grid_exam/img.png)

- display : grid
- grid-template-columns 
- grid-template-rows
- grid-template-areas
- grid-area
- grid-auto-rows
- grid-gap
- grid-column-gap
- grid-row-gap


![img.png](img.png)

- grid-column-start
- grid-column-end
- gird-row-start
- grid-row-end


축약 

- grid-column : 1 / 4
- grid-row : 2 / 4

### Flex


- display : flex
- flex-direction : (row , column , row-reverse , column-reverse)
- flex-wrap : (nowrap , wrap ,wrap-reverse)
- flex-flow : (column nowrap)
- justify-content : (flext-start , flex-end , center , space-around , space-even , space-between) <=수평축
- align-itmes : (center ,baseline  ) <= 수직축
- align-content : (flext-start , flex-end , center , space-around , space-even , space-between) <= 수직축


## youtube clone


### 비디오 플레이어

#### 화면 고정
- position: sticky;
- top: 0;

#### 버튼 속성 없애기

```css
button,
button:focus {
  border: none;
  cursor: pointer;
  outline: none;
}
```

#### CSS line-clamp (화면에 텍스트 줄 표시 설정)

```css
.info .metadata .titleAndButton .title {
  font-size: var(--font-medium);
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 2;
  overflow: hidden;
}

```

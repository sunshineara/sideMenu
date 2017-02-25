# SIDE MENU

자바스크립트 플러그인 입니다.
LESS 환경에서 구동됩니다.
마음껏 활용하세요.

![사이드메뉴](http://www.herop.me/images/sidemenu.jpg)

###Options

- `selector` 사이드 메뉴의 선택자
- `showBtnSelector` 사이드 메뉴 활성화 버튼 선택자
- `showSelector` 사이드 메뉴 활성화 배경

```js
var sideMenu = new SideMenu({
        selector: ".side_menu",
        showBtnSelector:".side_menu_btn",
        shadowSelector:".side_shadow"
});
```

### HTML

```html
<div class="hellow">안녕하세요</div>
```

### CSS

```css
.ele {
    width: 100px;
    position: relative;
    background: url("img/image.jpg")
}
```
# ๐ณ ์ค๋ ํ๋ฃจ ์ ๋ฆฌ

์ค๋ ์ค์ต์ด ๋ง์ ์ฌ๋ฐ์๊ณ  ์๊ฐ์ด ๊ธ๋ฐฉ๊ฐ๋ค.

๋ ์ด์์์ ์ฌ๋ฐ๋คโฆ๐ ํ์ง๋ง div๋ง ์ฐ๋ฐํ๋ค ์น์ ๊ทผ์ฑ์ ์ด์ฉํ article, section, nav๋ฅผ ์ ์ ํ ๊ณ ๋ คํ๋ ค๋ ๊ณ ๋ฏผ์ด ๋ง์ด ๋์๋ค. ํ๋ํ๋ ์ ํฉํ ์ฌ์ฉ๋ฐฉ๋ฒ์ ์ตํ์ผ ๊ฒ ๋ค.
์ค์ต๋ฌธ์  ๋ ํ์ด๋ณด๊ณ  ์ถ๋คโฆ!

# ์ค๋ ๊ณต๋ถํ ๋ด์ฉย ๐ผ

- **Layout** - table๋ก ๋ ์ด์์์ ์ง๋ ๋๋ ์์๋คโฆ > frame > div > flex, grid
- **Sections** - header, footer, nav, main, article, section, aside, hr (์คํ์ผ ์ฉ - div, span)
- **HTML** **๋ ์ด์์ ๊ตฌ์กฐ ์ง๋ณด๊ธฐ**
<img src="https://user-images.githubusercontent.com/105140201/223361880-47819a97-1a87-4f56-bc72-efefaccebc9a.png" width=50%>
<img src="https://user-images.githubusercontent.com/105140201/223361924-a627292f-3f71-4162-aad2-d4a2ed2357d1.png" width=50%>
<aside>
"๐ก  HTML ๊ตฌ์กฐ๋ฅผ ์ง๋๊ฒ ๋๋ฌด ๋ง์ฐํ๋ค๋ฉด 
์ฌ์ฉ์์๊ฒ ๋ญ๊ฐ๋ฅผ ์๋ ค์ฃผ๋ ์์ค์ด๋<br> ๋ธ๋ก๊ทธ ํฌ์คํธ,
๋ชฉ์ฐจ๋ฅผ ์ด๋ค๊ณ  ์๊ฐํ๋ฉด์ ์์ฑํด๋ณด์ธ์๐โ

ex) ๋ ์ด์์์ ํ์คํ ๊ด๊ณต์ ํ์ด์ง๊ฐ ์ ๋์ด์๋ค.<br>
๊ทธ์ ๋ฐํด ์ผ์ฑ, ์ ํ ํ์ด์ง์ ์ ๊ทผ์ฑ์ ์๊ณ ๋ณด๋ฉด ๋ชฉ์ฐจ ๋ฑ ๋ง์ด๋์ค๊ฐ ์กด์ฌ!๐<br>
โ ๋ฉด์  ๊ธฐ์ ์น ํ์ด์ง๋ฅผ ๋ถ์ํด ์์ฌํ ์ฌ๋ก๊ฐ ์๋ค?!

</aside>

- **float**

1. **float๋ก ๋ ์ด์์ ๋ง๋ค๊ธฐ**

<img src="https://user-images.githubusercontent.com/105140201/223362377-0fd52698-dd46-4dc4-97aa-8d09e202804a.png" width=50%>



2. **๋ก๊ทธ์ธ ํ์ด์ง ๋ง๋ค๊ธฐ**

![image](https://user-images.githubusercontent.com/105140201/223362523-2c2a9976-10b1-4393-8d57-6f1faf80985f.png)

- **flex**

# ์๋ก ์๊ฒ๋ ๋ด์ฉ ๐ก

- **Layout - Sections**
  - `article`
    - (๋ฐ๋ก) ๋๋ฆฝ์ ์ผ๋ก ๊ตฌ๋ถ, ์ฑ๋ด์ฒ๋ผ ์ ๊ฑฐํด๋, ์ด๋ ์ฌ์ดํธ์ ์์ด๋ ์๊ด์๋
  - `section`
    - (๋ฌถ์) ์๋ค ๋ฌธ๋งฅ๊ณผ์ ํ๋ฆ์ด ์์, ๊ตฌ๋ถ์ง์ผ๋ฉด์๋ ์ฐ๊ฒฐ์ฑ์ด ํ์ํ  ๋ ์ฌ์ฉ
    - ์ ๋ชฉ ์์๋ฅผ ์์์ผ๋ก ํฌํจํด์ผ ํจ
  - `aside` - ๋ฌธ์์ ์ฃผ์ ๋ด์ฉ๊ณผ ๊ฐ์ ์ ์ผ๋ก ์ฐ๊ด๋ ๋ถ๋ถ, ๊ฐ์ฃผ/๊ด๊ณ /๋ฐฐ๋
  - `hr` - ๊ตฌ๋ถ์  ,<p> ๋ด์์ ์ฌ์ฉํ์ง ์๋๋ค!
- **float**
  - float ํด์ ํ๊ธฐ - `clear:both`
  - ์์ ์์๋ค์ด ๋ชจ๋ float ์์ฑ์ ๊ฐ์ง๊ฒ ๋๋ฉด, ์ปจํ์ด๋ ์์์ ๋์ด์ ์์ ์์๋ค์ ๋์ด๊ฐ ํฌํจ๋์ง ์๋๋ค.
    - ๋ถ๋ชจ์๊ฒ (๊ฐ์ ๋ก) ๋์ด ๊ฐ ๋ฏธ๋ฆฌ ์ง์ ํ๊ธฐ
    - ์์์๊ฒ `overflow:hidden` ์ฃผ๊ธฐ - ๋์น๋ ์์๋ค์ด ์์ด์ง๊ฑฐ๋ ์๋ฆฌ๋ ๋ฌธ์ ๊ฐ ์๊ธธ ์ ์๋ค.
    - [๊ฐ์ฅ ๋ง์ด ์ฐ๋ ๋ฐฉ๋ฒ] clear-fix ๋ฐฉ๋ฒ - ๋ถ๋ชจ ์์์ `::after` ์ฌ์ฉํ๊ธฐ
    ```css
    ๋ถ๋ชจ::after {
      /* ํ๊ทธ ๋ค์ ๋ด์ฉ์ด ๋น(content: '') ๋ธ๋ญ์(display: block) ๋ง๋ค๊ณ  */
      content: '';
      display: block;
      /* float: left๋ฅผ ์ด๊ธฐํ ์ํค๊ฒ ๋ค๋ ๋ป์ด๋ค.*/
      clear: left;
    }
    ```
- **์จ๊น ์ฒ๋ฆฌ**
  - `display:none` or `visibility:hidden` - ์คํฌ๋ฆฐ๋ฆฌ๋๊ฐ ์ฝ์ง ์์.
  - `width:0px; height:0px;` 0ํฝ์ ์กฐ์  ๋ฐฉ๋ฒ -์คํฌ๋ฆฐ๋ฆฌ๋๊ฐ ์ฝ์ง ์์.
  - `text-indent: -9999px;` ์ฝํ์ธ ๋ฅผ ์ผ์ชฝ์ผ๋ก ๋ฐ์ด๋ด๋ ๋ฐฉ๋ฒ - ์คํฌ๋ฆฐ๋ฆฌ๋๊ฐ ์ฝ์.
  - `clip: rect(1px, 1px, 1px, 1px);` `clip-path: inset(50%);`
  - CSS ํด๋ฆฝ ๋ฐฉ๋ฒ โ**a11y -hiddenโ**
    - `clip`์ ์ด์  ๋์ด์ ๊ถ์ฅ๋์ง ์๊ณ  ์ต์  ์์ฑ์ธ `clip-path`๋ก ๋์ฒด๋์๋ค.
    - clip์ ๊ตฌ ๋ฒ์ ์ ๋ธ๋ผ์ฐ์  ๋์์ ์ํด์, clip-path๋ ์ต์  ๋ฒ์ ์ ๋ธ๋ผ์ฐ์ ๋ฅผ ์ํด์ ๋๊ฐ๋ค ๊ธฐ์ํ๋ค.
    ```css
    /*a11y-hidden*/
    .sr-only {
      clip: rect(1px, 1px, 1px, 1px);
      clip-path: inset(50%);
      width: 1px;
      height: 1px;
      margin: -1px;
      overflow: hidden;
      padding: 0;
      position: absolute;
    }
    ```
- **flex**
  - 1์ฐจ์์  ๋ ์ด์์(x์ถ or y์ถ)์ ์ํด ์ฌ
  - ๋ถ๋ชจ ์์๋ฅผ `flex-container` ์์ ์์๋ฅผ `flex-item` ์ด๋ผ๊ณ  ๋ถ๋ฅธ๋ค.
  - justify-content : `flex-start`, `flex-end`, `center`, `space-between`, `space-around`

# ๊ถ๊ธํ ๋ด์ฉ / ๋ถ์กฑํ ๋ด์ฉย ๐ง

- **Sections** - ๋ค์ ํ์ด๋ณด๊ธฐ
- flex & grid - ๋ฏธ๋ฆฌ ์์ต ํด๋ณด๊ธฐ
  [flexngrid](https://flexngrid.com/)

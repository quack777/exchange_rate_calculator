# π νμ¨ κ³μ°κΈ°
## π« νμ

- μ²«λ²μ§Έ κ³μ°κΈ° - μ‘°μμ΄, μ μν
- λλ²μ§Έ κ³μ°κΈ° - μ΅λ³ν, μ‘°μ©μ°
- λ°°ν¬μ£Όμ : http://exchangerating.s3-website.ap-northeast-2.amazonaws.com/
- Front-end: React(Funiction-Component)\_reactr-router-dom(V6), CSS Module, JavaScript(ES6)
- νμν΄: Slack, Notion, Github

## βκ³Όμ  κ΅¬ν λͺ©λ‘

- μ²«λ²μ§Έ κ³μ°κΈ°
  1. μμ·¨ κ΅­κ°λ₯Ό μ ννλ©΄ νμ¨μ΄ λ°λμ΄ λνλ©λλ€.
  2. μ‘κΈμ‘μ μλ ₯νκ³  Submitμ λλ₯΄λ©΄ μμ·¨κΈμ‘μ΄ κ³μ°ν΄μ νλ©΄μ λΈμΆλ©λλ€.
- λλ²μ§Έ κ³μ°κΈ°
  1. μ‘κΈ κ΅­κ°λ₯Ό μ νν  μ μμΌλ©° ν΄λΉ μ‘κΈ κ΅­κ°μ λν μμ·¨ κ΅­κ° νμ¨ λΉμ¨μ κ΅¬ν  μ μμ

## πκ΅¬νμμ

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/65222200/151019432-7eebd0b8-13b8-411a-bee3-ffd442c25cea.gif)
![ezgif com-gif-maker (9)](https://user-images.githubusercontent.com/65222200/151020591-307265d9-e456-4988-b225-df85d40d00e0.gif)

## πκ°λ° κΈ°κ°

- κΈ°κ°: 2022λ 1μ 24μΌ ~ 2022λ 1μ 26μΌ (3μΌκ°)

## πΉμ€μΉ λ° μμνλ λ²

1. git clone
2. npm install
3. npm run start

## πνλ‘μ νΈ κ΅¬μ‘°

```
ββ public
β     index.html
β
ββ src
β  ββ api
β  β   client.js
β  β
β  ββ coponents
β  β     ββ CalculateFirst
β  β     β      CalculateFirst.css
β  β     β      CalculateFirst/js
β  β     ββ CalculateSecond
β  β            CalculateRateBox.css
β  β            CalculateRateBox.js
β  β            CalculateSecond.js
β  β            CalculateSecondForm.css
β  β            CalculateSecondForm.js
β  β            CalculateSecondTemplate.css
β  β            CalculateSecondTemplate.js
β  β
β  ββ pages\Main
β  β     MainPage.css
β  β     MainPage.js
β  β
β  ββ styles
β  β    common.css
β  β    reset.css
β  β
β  ββ utils
β  β     format.test.js
β  β     GetApi.js
β  β     GetExchangeRateByUSD.js
β  β     setMonthconvert.js
β  β     SetNumberFormat.js
β  ββ config.js
β     index.js
β     Router.js
ββ


```

## πκ΅¬ν κΈ°λ₯ λ° κ°μΈ μ­ν 

> μ΅λ³ν:
>
> \- API ν΅μ μ λ°λ₯Έ stateκ° μ μ₯ λ° μ μ₯λ stateκ°μ λ°λΌ νλ©΄ λμ  λλλ§ μμ λ΄λΉ
>
> \- μ‘κΈ κ΅­κ°-μμ·¨ κ΅­κ°μ λν API ν΅μ μ ν΅ν΄ μ λ¬ λ°μ Responseμμ νμν data κ°λ§μ λμ€νΈλ­μ³λ§ ν λΉ
>
> \- API ν΅μ μ ν΅ν΄ λ°μ μ¨ dataκ°κ³Ό Component μμ²΄μμ κ΄λ¦¬λλ state κ°μ μ¬μ©νμ¬ νλ©΄μ λμ  λλλ§
>
> \- new Date μΈμ€ν΄μ€λ₯Ό ν΅ν΄ μμ±ν date κ°μ²΄μμ μ, λ³, μΌ λ₯Ό κ°μ Έμ€λ λ©μλλ₯Ό μ¬μ©νμ¬ λμμΈ μμμ λ§μΆ λ μ§ μΆλ ₯
>
> \- Object.entries()λ₯Ό μ¬μ©νμ¬ νμ¬ μ νλμ΄μ§ keyμ λν valλ₯Ό μΆλ ₯λμ΄μΌ ν  κΈμ‘μ νμλλλ‘ λμ  λλλ§
>
> μ‘°μμ΄:
>
> \-API ν΅ν΄ stasteκ°μΌλ‘ μ μ₯ μ΄ stateλ₯Ό μ΄μ©ν΄ νμ¨ μΆμΆ
>
> \-μ‘κΈμ‘μ μλ ₯νκ³  Submitμ λλ₯΄λ©΄ μμ·¨κΈμ‘μ΄ κ³μ°ν΄μ νλ©΄μ λΈμΆμν€κΈ°
>
> \-λλ²μ§Έ κ³μ°κΈ°μ usdκ°λ§ κ°μ§κ³  νμ¨ κ΅¬νλ μλ£¨μ μ κ³΅
>
> μ μν :
>
> \- APIλ₯Ό ν΅ν΄ λ°μ΄ν° λ°μμ€κΈ° λ° νμ¨ κ³μ°, μΆλ ₯
>
> \- νμ¨ κ³μ°μ ν  λλΌλ₯Ό λ°κΏλλ§λ€ μ€μκ°μΌλ‘ νμ¨ μ λ³΄ μλ°μ΄νΈ
>
> \- μ‘κΈμ‘ μ‘°κ±΄ μΆκ° ν. μ‘°κ±΄μ λ§μ‘±νμ§ μμ μ μλ λ©μΈμ§λ₯Ό μΆλ ₯.
>
> μ‘°μ©μ°:
>
> \- λλ²μ§Έ κ³μ°κΈ°μ λν μ μ²΄μ μΈ CSS, layoutμμ
>
> \- API νΈμΆ κ° λ°μμ€κΈ°
>
> \- Input typeμ textλ‘ λ³κ²½ ν κΈμμλ₯Ό κ³μ°νμ¬ μΌμ  κΈμ μ μ΄μ μλ ₯μ μ½€λ§κ° μΆκ° λλλ‘ μμ νμ΅λλ€. μ΄ν μ€λ₯λ°μμΌλ‘ μ΅λ³ν νμλμ΄ μ¬μμ  νμ΅λλ€.
>
> \- typeμ textλ‘ λ³κ²½νμ¬λ textκ° μλ ₯λμ§ μλλ‘ μ‘°μΉνμ΅λλ€. μ΄ν μ€λ₯λ°μμΌλ‘ μ΅λ³ν νμλμ΄ μ¬μμ  νμ΅λλ€.

## βμκ° λ° νκΈ°

> μ΅λ³ν:
>
> pairλ₯Ό μ΄λ£¨μ΄ νλμ νλ‘μ νΈλ₯Ό μλ‘ μκ²¬μ κ³΅μ νλ©° νλ‘μ νΈλ₯Ό λ§λ  κ²½νμ΄ μ²μμλ λ€μ μ΄μνμλ€. λκ΅°κ° λ΄ μ½λλ₯Ό μμ±νλ κ²μ μ€μκ°μΌλ‘ λ³΄λ κ²μ΄ κ³Όμ° λ§μ λμμ΄ λ μ§ κ³ λ―Όνμλλ°, κ΅¬λ¬Έ μμμμ μ€μ λ° λ‘μ§μ κ°μ΄ μκ²¬μ λλ μ μμλ μ μ΄ νλ‘μ νΈμ μμ μλλ₯Ό λμΌ μ μμλ€. κΈ°λ₯ μμΌλ‘λ λ§μ κ²½νμ μμ μ μμλλ°, stateμμ κ΄λ¦¬νλ λ°°μ΄ κ°μ²΄μ νΉμ  μΌλΆ μμλ§μ λ€λ₯Έ μμλ‘ λ°κΎΈκΈ° μν΄ λ³΅μ¬λ³Έ κ°μ²΄λ₯Ό μλ‘ μμ±ν μ΄νμ μΈλ±μ€ κ°μΌλ‘ ν΄λΉ λ°°μ΄ κ°μ²΄μ νΉμ  μμλ₯Ό λ°κΎΈλ μ°μ°μ κ°λ¨νμ§λ§ ν₯ν νλ‘μ νΈμμ μ μλ―Ένκ² μ°μΌ μ μλ μ’μ κ²½νμ΄μλ€.
>
> μ‘°μμ΄:
>
> λ€λ₯Έ νμ λΆκ³Ό κ³Όμ λ₯Ό μ§ννλλ° λ΄κ° μ§μ  μ½λλ₯Ό μ§μ§ μκ³  λννλ©΄μ μ§ννλκ² μλ‘μ λ€. λκ°μ λ¬Έμ λ₯Ό κ°μ§κ³ λ λ€λ₯΄κ² μκ°νκ³  μ½λλ λ€λ₯Ό μ μλ€λ μ μ λ€μ ν λ² κΉ¨λ«κ² λλ€. νμλΆλ€κ³Ό μν΅νλ©΄μ λ§¨ μ²μμ μ΄κΈ° μΈνμ μ§ννμλλ° ν΄λ κ΅¬μ‘°λ₯Ό λ€ μ‘μλκ³  μ΄κΈ°μΈνμ λ§λ€κ³  μ§ννλκΉ ν¨μ¬ μμν΄μ μμΌλ‘ νΌμμ¬λ μ΄λ° λΆλΆλ€μ κΌΌκΌΌνκ² μ§κ³  λμ΄κ°μΌκ² λ€.
>
> μ μν:
>
> νλ‘μ νΈλ₯Ό μ§ννλ©΄μ νΌμμ κ³΅λΆν΄μλ μ μ μμμ μ§μλ€μ νμλ₯Ό νλ©΄μ λ°°μΈ μ μμλ κ² κ°λ€. λλΆμ μλ‘μ λΆμ‘±ν λΆλΆλ€μ μ±μ°κ³  λ°°μ°λ©° λ§μ κ²λ€μ μ»μ΄κ° νλ‘μ νΈλΌκ³  μκ°μ΄ λλ€.
>
> μ‘°μ©μ°:
>
> νμμ΄ μ²μμ΄λΌ μ²μμλ μ΅μνμ§ μμμ΅λλ€. νμ§λ§ μμμ μμνκ³  μλ‘ μμ΄λμ΄λ₯Ό κ³΅μ νκ³  μ΄μΌκΈ°νλ©΄μ μ κ° λͺ¨λ₯΄λ λΆλΆμ λν΄μλ λ λ§μ΄ μκ² λμκ³  νμμ μ€μμ±κ³Ό νμμ±μ λν΄ νμ€ν μκ² λμμ΅λλ€. λλ¬΄ μ’μ κ²½νμ΄μμ΅λλ€.

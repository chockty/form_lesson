# form_lesson
## 修正内容
### 1. ボックス内の背景色がモデルと異なっている。
 #### style.css
 - .input-box-design の background-color を #fbfbfb　へ変更。
----------
### 2. ボックスの外枠が消えている。
 #### style.css
 - .input-box-design の borderの色 を #d9d9d9　へ変更。
----------
### 3. 「アカウント作成」 ボタンへhoverした際にカーソルが変わっていない。
 #### style.css
 - .submit-btn:hover へプロパティ cursor: pointer;を追加
---------- 
### 4. input タグにname属性が未記入である。
 #### index.html
 - 以下該当項目の箇所にあるinputタグにname属性を追加。
 - 該当項目：
 - 名字: name="last-name"
 - 名前: name="first-name"
 - Eメール: name="email" 
 - 電話番号: name="tel" 
 - パスワード: name="password"
 - パスワード（確認用）: name="password-check"
 - 備考: name="opinion"
---------- 
### 5. 希望コースの項目が、html上で改行されていない。
 #### index.html
 - class: select-course の子要素 li を改行しました。
---------- 

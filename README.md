# app.js

非同期i/oのnode.jsを同期i/oに変更してみた
for文で0~500までを計算
出力はあ,い,う,え,お,

なぜしたか？

非同期でこれをするとあ、い、う、え、お、が同時進行してしまい結果がバラバラになってしまうので同期に変えて順番通りにしてみた

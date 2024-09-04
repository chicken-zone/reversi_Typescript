## TypeScript について

![alt text](image.png)

![alt text](image-1.png)

- コンパイルエラーとは

  - 下記の画像のように number と指定した変数に文字列を入れると起きるエラー
    ![alt text](image-2.png)

- 型推論とは

  - 下記の画像のように変数に 3 が代入されている状態で、Typescript が number 型だろうなと推論してくれること
    ![alt text](image-3.png)
  - 複数の型が入る可能性があるもの等は下記のように |　で定義する事が出来る
    ![alt text](image-4.png)

- 配列
  - never[]は number も string もどんな型も該当しない為、never の配列に number を追加する事が出来ない
    ![alt text](image-5.png)
  - 空の配列を用意してあとから変数を入れたい場合は下記のように number[]と記述してから配列で初期化すると変数を入れれる
    ![alt text](image-6.png)

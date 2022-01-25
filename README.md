VSCE - ConvertWidth for novel-writer README
=========================
この拡張機能は、[8amjp](https://github.com/8amjp)様の[ConvertWidth](https://marketplace.visualstudio.com/items?itemName=8amjp.convertwidth)からフォークし作成しております。  
半角文字と全角文字を相互に変換する、Visual Studio Codeの機能拡張です。

## Command

### `<A> 半角英字及び記号(&,.)を全角に変換`
半角英字(A-Z)、アンド(&)、カンマ(,)、ピリオド(.)を全角に変換します。

### `<1> 半角数字を全角に変換`
半角数字(0-9)を全角に変換します。

### `<?> 半角記号(!?)を全角に変換`
半角の感嘆符(!)、疑問符(?)を全角に変換します。

### `>A< 全角英字及び記号(&,.)を半角に変換`
全角英字(Ａ-Ｚ)、アンド(＆)、カンマ(，)、ピリオド(．)を半角に変換します。

### `>1< 全角数字を半角数字に変換`
全角数字(０-９)を半角に変換します。

### `>?< 全角記号(!?)を半角に変換`
全角の感嘆符(！)、疑問符(？)を半角に変換します。

コマンドは、コマンドパレットを開いて(<kbd><kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd></kbd>)入力する他に、
エディタ内で右クリックして表示されるコンテクストメニューから実行することもできます。  
また、コマンドが有効になるのは、言語モードがMarkdown形式、プレーンテキスト形式またはnovel形式の場合のみです。  
(novel形式は[novel-writer](https://marketplace.visualstudio.com/items?itemName=TaiyoFujii.novel-writer)からインストールされる言語機能です)

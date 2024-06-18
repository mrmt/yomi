# yomi

さまざまなスキルの相手に対し、パスワードなど文字列を一文字一文字正確に伝達したいとき、一文字ずつ日本語表記を添えて送ると効果があるときがある。
このスクリプトは、その日本語表記を生成する。

## Usage

./yomi [-h|--help] [-v|--verbose] some_text

## Examples

```
# ./yomi 'Hel!0, W0r1d'
エイチ イー エル びっくり ぜろ カンマ スペース ダブリュー ぜろ アール いち ディ
# ./yomi -v 'Hel!0, W0r1d'
大文字エイチ 小文字イー 小文字エル びっくり 数字ぜろ カンマ スペース 大文字ダブュー 数字ぜろ 小文字アール 数字いち 小文字ディー
```

## License

MIT


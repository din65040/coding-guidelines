# Coding Guidelines

ガイドラインは開発者が共通のルールのもと、設計や運用をおこなうための指標であり、以下のメリットがある。

- **開発時間の短縮**：運用すべきスタイルが明確になる。
- **効率的な構文エラーのチェック**：厳格なフォーマットを採用すれば、バリデータがエラーを見分けやすくなる。
- **可読性の向上**：人の目は秩序を好むため、一貫性のあるマークアップは開発者のストレスを軽減する。

## HTML

HTML 構文は、WHATWG の [HTML Living Standard](https://html.spec.whatwg.org/multipage/) に準拠する。

### 属性の記述順

属性値は class、id、data-*、その他の属性の順序で記述する。

### target="_blank" で開くリンクには rel="noopener" をつける

`target="_blank"` で開いたタブは、`window.opener` を使って親のタブを操作できるため **フィッシング詐欺攻撃の脆弱性** がある。

## CSS

## JavaScript

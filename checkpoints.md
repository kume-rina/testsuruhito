# checkpoins in tests

## checkpoints in WYSIWYG editor
### 文字と表示/characters and styles
- **太字/Bold**
- *斜体/Italic*
- <u>下線/Underline</u>
- ~~取り消し線/Strikethrough~~
- 左寄せ/text-align:left
- 中央寄せ/text-align:center
- 右寄せ/text-align:right
- リスト/List
    - 箇条書きリスト/Bulleted List
        * いち/one
        * に/two
        * さん/three
    - 番号付きリスト/Numbered List
        1. いち/one
        2. に/two
        3. さん/three
- フォントサイズ/font size
    - 8pt
    - 10pt
    - 12pt
    - 14pt
    - 18pt
    - 24pt
    - 36pt
- フォントカラー/font color
- フォント背景色/font background color
- リンク/Link
- インデント/Indent
- 上記の組み合わせ/a combination of the above

### HTMLソース用/HTML Source
```
<br />&lt;font color="red"&gt;あ&lt;/font&gt;&amp;"'&lt;hr&gt;&amp;nbsp;"' &lt;&gt;&amp;&lt;B&gt;!"#$%&amp;'()=~|--^\@['{;:]+*},./\&lt;&gt;?_&lt;/B&gt;￠ー－～―‐￣-髙﨑～~^^^&lt;?php echo("hello"); ?&gt;<br /><br />
<p><strong>太字</strong></p>
<p style="text-align: left;"><br />左寄せ</p>
<p style="text-align: center;">中央寄せ</p>
<p style="text-align: right;">右寄せ</p>
<p><span style="color: #00ccff;">リスト</span></p>
<ul>
<li>いち</li>
<li>に</li>
<li>さん</li>
</ul>
<ol>
<li>いち</li>
<li>に</li>
<li>さん</li>
</ol>
<p><br /><span style="color: #ff00ff;">フォントカラー<br /></span></p>
<hr />
<p style="padding-left: 30px;">インデント</p>
<p><a title="google" href="http://google.com/" target="_blank">リンク</a><br /><br /></p>
```

## checkpoints in Mail
- `touch[0x09]/tmp/foo` を差出人に指定する

## checkpoints in browser services
- Cookieの受け入れを拒否にしてテスト

## checkpoints in CSV
- エンコード
- `\` :円マークの確認
- `'` :シングルクォーテーションの確認
- `"` :ダブルクォーテーションの確認
- `=A1+A2` :計算式の確認
- <pre>	:タブの確認</pre>

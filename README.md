# gametech
Markdown: Syntax
================

*   [概述](#overview)
    *   [哲學](#philosophy)
    *   [行內 HTML](#html)
    *   [特殊字元自動轉換](#autoescape)
*   [區段元素](#span)
    *   [連結](#link)
    *   [強調](#em)
    *   [程式碼](#code)
    *   [圖片](#img)
*   [其它](#misc)
    *   [跳脫字元](#backslash)
    *   [自動連結](#autolink)
    *   [cardplay](docs/cardplay.md)
*   [感謝](#acknowledgement)

**注意：**這份文件是用 Markdown 寫的，你可以[看看它的原始檔][src] 。

  [src]: https://github.com/othree/markdown-syntax-zhtw/blob/master/syntax.md

* * *

<h2 id="overview">概述</h2>

<h3 id="philosophy">哲學</h3>

Markdown 的目標是實現「易讀易寫」。

不過最需要強調的便是它的可讀性。一份使用 Markdown 格式撰寫的文件應該可以直接以純文字發佈，並且看起來不會像是由許多標籤或是格式指令所構成。Markdown 語法受到一些既有 text-to-HTML 格式的影響，包括 [Setext] [1]、[atx] [2]、[Textile] [3]、[reStructuredText] [4]、[Grutatext] [5] 和 [EtText] [6]，然而最大靈感來源其實是純文字的電子郵件格式。



* * *

<h2 id="span">區段元素</h2>

<h3 id="link">連結</h3>

Markdown 支援兩種形式的連結語法： *行內*和*參考*兩種形式。

不管是哪一種，連結的文字都是用 [方括號] 來標記。

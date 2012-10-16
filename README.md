このファイルについて
-------------------
===================
日本語入力システムで使われることを想定した、現代日本語で使われる動詞・形容詞（イ形容詞）をできるだけ網羅的に集めたリストです。

形容動詞（ナ形容詞）は対象としていません。名詞+「する」の動詞は、漢字一文字のもののみ収録しています。

背景・特徴
----
====
ユーザの使用感を考えた日本語入力システムでは、辞書は一般的に人手を加えて保守されています。また、日本語のあり方を考えた入力システムでは、辞書の候補順は慎重に考慮されています。

そのような日本語入力システム・辞書を作るにあたって、特に難しいものが「用言」（動詞・形容詞）です。それらは活用を持つため、取り扱いに特別な処理が必要です。

一方で、用言は名詞などに比べると変化が少なく、ある程度安定しています。そこで、日本語入力システムのための用言のリストを作ることを考えました。

日本語の解析と入力では、それぞれ求められる辞書の性質が違います。 前者では、日本語の文書中に出てくるものをできるだけカバーすること(recall)が重要になるため、古語や変わった送り仮名・漢字などを含めることにはそれなりのメリットがありますが、人間が直接触る日本語入力においては、使い手が望まないものを含めない(precision)ということも、使用感にかかわってきます。そのため、このリストを作るにあたっては以下のような点を考慮しています。

* 現代の標準語話者の中に一定の使用者がいるものに限定して収録するよう努めています。「かしがましい」「いざとい」「くくめる」「とばしる」のような古語は除外しています。また、「tsudaる」のような使われなくなった流行語も除外しています。ただし、「退治る」「ナウい」のように、擬古文や死語としての位置づけで現代語で使われるものは収録しています。
* 複合動詞のうち、不特定の動詞につくことができる補助動詞との組み合わせは、原則として収録していません。たとえば、「治りかける」のようなものは、「治癒しかける」と同じ構成・意味であるため、収録していません。このようなものは、「〜合う」「〜飽きる」「〜返す」「〜比べる」「〜倒す」「〜疲れる」「〜直す」などがあります。ただし、「言い合う」「言い返す」「見比べる」のような常用されるものは収録しています。
* 複合動詞のうち、意味に変化のない単純な連続は、原則として収録していません。たとえば、「守り育む」などはその一例です。ただし、「泣き叫ぶ」のような常用されるものは収録しています。
* 変則的な送り仮名を持つもののうち、常用されないものは原則として収録していません。「定（さだま）る」「逆（さから）う」などはその例です。ただし、「癒す」と「癒やす」のようなものは両方とも収録しています。
* 変則的な仮名書きのうち、常用されないものは原則として収録していません。「打ちあげる」「うつり変わる」などはその例です。ただし、「ふさぎ込む」「貼りつける」のような常用されるものは収録しています。
* 複合動詞の漢字書きのうち、使用頻度の低いものを含む組み合わせをすべて列挙することはしていません。たとえば、「ミル」に対応する「視る」、「マワル」に対応する「廻る」はありますが、「ミマワル」には「視回る」、「見廻る」はありません。
* 当て字のうち、一般に使われないものは収録していません。「上手い」「美味い」はありますが、「甘味い」はありません。
* 「遊べる」「書ける」などの可能動詞や、「見れる」「食べれる」のようなら抜き形は、規則的に派生可能であるため収録していません。

また、一部の辞書には収録されないような単語も収録しています。
* 類推・派生による新しい動詞も収録しています。「盛り下がる」「巻き戻る」などはその例です。
* 俗語・卑語も収録しています。「ぶっこく」「シコる」はその例です。
* 方言に由来するものでも、標準語話者の間で流通しているものは収録しています。「しばき回す」はその一例です。
* 新語も収録するよう努めています。「拉致る」「過疎る」「びみょい」はその例です。
* ネット用語も収録するよう努めています。「ポチる」「disる・ディスる」はその例です。
* 使用分野の限られる用語も、2012年現在で、ある程度の頻度があるものは収録するよう努めています。「煮切る」（料理）、「コスむ」（囲碁）、「ハコる」（麻雀）、「ピチュる」（東方）、「闇る」（メイプルストーリー）などはその例です。
* 誤っているとされる表記の中で、一般に使われるものは収録しています。「悪どい」はその一例です。
* 動詞のテ形による複合動詞も、固有の意味があるものは収録しています。「とって返す」「打って出る」などはその例です。

リストの作成にあたっては、「現代日本語書き言葉均衡コーパス(BCCWJ)」を中心にさまざまな資料を参照していますが、上で挙げたような点を考慮していることもあり、機械的に流し込むことはしていません。ひとつひとつの項目について検討を加えています。

形式
----
====
以下のような形式です。

    仮名表記[TAB]活用形[TAB]語義番号[TAB]漢字表記[TAB]常用漢字表内フラグ
    ===================================================================
    アイアラソウ[TAB]五段・ワ行促音便[TAB][TAB]相争う[TAB]1
    アイイレル[TAB]一段[TAB][TAB]相容れる[TAB]0
    アイイレル[TAB]一段[TAB][TAB]相いれる[TAB]1
    アイイレル[TAB]一段[TAB][TAB]相入れる[TAB]1
    ...
    アウ[TAB]五段・ワ行促音便[TAB]1[TAB]合う[TAB]1
    アウ[TAB]五段・ワ行促音便[TAB]2[TAB]会う[TAB]1
    アウ[TAB]五段・ワ行促音便[TAB]2[TAB]逢う[TAB]0
    アウ[TAB]五段・ワ行促音便[TAB]2[TAB]遇う[TAB]0
    アウ[TAB]五段・ワ行促音便[TAB]3[TAB]遭う[TAB]1
    アウ[TAB]五段・ワ行促音便[TAB]3[TAB]あう[TAB]1

* 仮名表記は発音そのものではなく、仮名で書かれる場合の表記です。「多い」は「オーイ」ではなく、「オオイ」となります。ただし、「ぶーたれる」はこれがもっとも多い仮名表記なので、仮名表記も「ブータレル」としています。
* 「つまづく」「うなづく」「ひざまづく」のような許容表記は収録していません。
* 活用形は、IPA 品詞体系のものです。動詞か形容詞かは、活用形から一意に定まるため、記載していません。
* 「語義番号」は、同じ仮名表記と活用形を持つもので、漢字による安定した書き分けがあるものにつけています。
  * 日本語の語源にかかわらず分けています。たとえば「閉める」「締める」は同語源ですが、漢字の書き分けが成立しているため、別のものとしています。
  * 使い分けの安定していないものはひとつにまとめています。たとえば「探す」と「捜す」、「勧める」と「薦める」のようなものは、実態として明確に使い分けられていないため、別の語義とはしていません。
* ひとつの語義に対応する漢字表記は、一般的なものから順に並べてあります。BCCWJ での出現頻度を参考にしていますが、解析ミスなどもあるため、微調整を加えています。常用漢字表外のものであっても、頻度によっては第一候補にしていますが、その場合は表外字を仮名にしたものを第二候補以下に入れています。たとえば、「カイタタク」は第一候補が「買い叩く」ですが、第二候補を「買いたたく」としています。
* 現時点では、リストは文字コード順で、辞書順ではありません。「カ」から始まるものが終わった後に、「ガ」から始まるものが続きます。

ライセンス
----------
==========
ライセンスは CC0 とします。

このリストの作成にあたっては、[現代日本語書き言葉均衡コーパス](https://chunagon.ninjal.ac.jp/)・[UniDic](http://www.tokuteicorpus.jp/dist/)・[Webデータに基づく複合動詞用例データベース (開発版)](http://csd.ninjal.ac.jp/comp/index.php)などを参考にしていますが、それらのデータを利用する際にはすべて取捨選択を行っています。

ライセンスとは関係ないのですが、すでに日本語用言リストをお持ちの方がこのリストを補完的に使用される場合は、このリストの品質維持・向上に協力していただければ幸いです。

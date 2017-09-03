`# イントロダクション

micro:bitとは?
micro:bitは子供たちにコンピュータサイエンスを教えるために、2015年にイギリスのBBCによって開発されました。BBCは11歳から12歳の子供たちにmicro:bitを無料で配布しました。micro:bitは小さなコンピュータと考えてもいいでしょう。
http://microbit.org

![BBC micro:bit](/static/courses/csintro/algorithms/bbc-microbit.jpg)

## コンピュータとは？
多くのコンピュータは4つの主なパーツで成り立っています:

![Computer components](/static/courses/csintro/algorithms/cpu.png)

1. プロセッサ – コンピュータの内部にある小さなチップ。情報を処理したり変換したり出来ます。「CPU」という言葉を聞いたことがありますか？ CPUは「Central Processing Unit（中央情報処理装置）」の略です. プロセッサをコンピュータの脳に例えると、処理速度が速ければ速いほど、コンピュータもより早く考えることが出来るということになります。

2. メモリ – コンピュータはメモリを使って物事を記憶することが出来ます。メモリには大きく分けて二種類あります:
>* RAM (random access memory) - 短い間だけ覚えておくためのメモリ
>* ストレージ (「ハードドライブ」と呼ばれることもあります) - こちらは長い間、覚えておくためのメモリで、電源を入れていない状態でも情報を記憶しておくことが出来ます。

3. インプット Inputs （入力） – コンピュータが外界から情報を取り入れる仕組みのことです。人間の場合、耳や目などの五感を通してインプットが得られます。コンピュータの場合はどうでしょう？キーボード、マウス、タッチスクリーンに、カメラ、マイクロフォン、ゲームコントローラー、スキャナーなどいろいろあります。

4. アウトプット Outputs（出力） – コンピュータが情報を表示したり伝えたりする仕組みのことです。人間は話をするときには口を使うことが多いです。では、口を使う以外に他にどんな方法で話すことができるでしょうか？顔の表情や手話などがありますね。コンピュータのアウトプットにはどんなものがあるでしょう？モニター/スクリーン、ヘッドフォン/スピーカー、プリンタなどがあります。

それでは次に micro:bit を見て見ましょう：

![micro:bit hardware](/static/courses/csintro/algorithms/microbit-hardware.png)

* Use the diagram here as a visual aid: http://microbit.org/hardware/ 
* Can you find the Processor?
* How much memory does the micro:bit have? 16K, which is smaller than many files on your computer!
* Can you locate the following Inputs?  Buttons (on board), Pins (at base), Accelerometer / Compass.
>Note: Though not pictured, the Light Sensor is located on the LED lights
* Where are the Outputs?  LED lights, Pins

All computers need electricity to power them.  There are 3 ways to power your micro:bit:
* Through the USB port at the top
* By connecting a battery pack to the battery connector
* Through the 3V Pin at the bottom (not the recommended way to power your micro:bit)

On the top left corner you may notice that your micro:bit has a Bluetooth antenna.  This means your micro:bit can communicate and send information to other micro:bits.  We will learn more about this feature in the Radio Lesson.


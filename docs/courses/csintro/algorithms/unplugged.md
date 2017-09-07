# Unplugged: 関数とクレイジーな条件文

教材
* 鉛筆
* 紙 (またはインデックス・カード)

![入力 処理 出力](/static/courses/csintro/algorithms/inputs-process-outputs.png)

コンピュータ・プログラミングでは、アルゴリズムとはひとまとまりの命令語のことを指します。

アルゴリズムはコンピュータに対して、どのように入力情報を処理するかを指示し、さらに出力情報がある場合はどのような情報を出力するかを指示します。

アルゴリズムの例としては、算数のクラスで見たことがあるかもしれない「関数マシーン」というのがあります。

![入力 関数 出力](/static/courses/csintro/algorithms/input-function-output.png)

関数マシーンは入力情報を取り入れて、それを処理して、出力を生成します。

入力と出力の情報はｘを入力として、そしてｙを出力として表す「入出力表」に記録することが出来ます。例えば：

```
入力 (x)	出力 (y)
======================
    1           2
    2           4
    3           6
    4           8
```

算数のよくある問題のひとつに、それぞれの入力に対する出力結果からどのような処理かを判断する、というものがあります。上の例の場合、それぞれの入力値は2倍（２を掛ける）になっていることがわかります。

```
入力 (x)      処理 =>        出力 (y)
======================================
    1            * 2             2
    2            * 2             4
    3            * 2             6
    4            * 2             8
```

## Unplugged: あなたはどんな関数ですか？
このアクティビティでは生徒はプレイヤーAとプレイヤーBとして二人一組のペアで行います。ペアのひとりが関数マシーンとして、もう片方のパートナーからの入力を処理します。

生徒には、どのように結果を記録してほしいかを指示しましょう。
鉛筆と紙を使ってもいいですし、紙の代わりにインデックス・カードを使用しても構いません。
紙に書く場合は、入力と出力の値を表になるように記録していきます (上の例を参考にしましょう)。
インデックス・カードを使う場合は、プレイヤーAがインデックス・カードの表に入力の値をひとつ書いた後プレイヤーBに渡します。プレイヤーBはその裏に出力の値を書き込みます。

### 始め方:
* プレイヤーBは、プレイヤーAから渡される入力を処理するための、算数の関数もしくはちょっとした数の操作をひとつ決めます。
* プレイヤーBは決定した関数（もしくは数の操作）を別の紙に書いて、プレイヤーAからは見えない場所に置いておきます。
* プレイヤーAはプレイヤーBに数を伝えます。
* プレイヤーBはその数に処理を加え、結果を出力としてプレイヤーAに返します。
* Player A can then state what function or bit of processing she thinks Player B is using on the input to produce the given output. One try per round of input/output.
* If Player A states the correct function, Player B confirms that it is correct by showing the previously hidden function and the players switch roles and start the game over.
* If Player A does not guess correctly, Player A provides another input that Player B processes and provides an output for.
* The goal is for Player A to figure out what function or bit of processing Player B is using in the fewest number of rounds of input/output possible.
* After each student has had at least one chance to be the function machine, play more rounds as time permits.

### Notes: 
* The difficulty level of the possible functions should be determined by the teacher and shared with the students ahead of playing. Alternately, the teacher can provide function cards that are handed out at random to be used by the players, rather than the players creating their own.
* The player providing the input should not just guess what the function is. She should be able to explain why she thinks her input resulted in the given output.
* Examples of ‘easier’ functions: 
> * [ ] Add 8
> * [ ] Subtract 6
> * [ ] Multiply by 3
> * [ ] Divide by 2
* Examples of more difficult functions:
> * [ ] Multiply by 2 and then subtract 1
> * [ ] Square the input
> * [ ] Return 20% of the input

## Unplugged: Crazy Conditionals
This is a fun, interactive exercise to introduce conditionals and event handlers as computer processing.  Read through the entire activity and adjust as needed for your class and classroom.
 
### Preparation: 
* Print & cut into strips with one conditional on each strip
* Note that some of the same conditionals can be given to multiple students, while other conditionals are to be given to just one student.
* Except for the first ‘BEGIN’ conditional, hand out the conditionals PRINT SIDE DOWN. 
* Besides the ‘BEGIN’ and ‘STOP’ conditional, give at least two other conditionals to each student. A lesson from this is that it is challenging for a student to keep track of a lot of different conditionals, though not so for a computer! : )
 
### Notes: 
* Some of the same conditionals can be given to multiple students, while other conditionals are to be given to just one student.
* Technically these conditionals are all event handlers because the students are simply waiting for a specific event to trigger them into action.
* Unless instructed otherwise, students do not speak or make noise during this activity.

### Extensions/Variations: 
* Add AND, OR, AND/OR statements to the conditionals.
* Create nested IF’s
* Let students create the IF’s
* Relate this activity to a system and have the students create the conditionals that would end in a product of some kind or the completion of some task.
 
Give these 2 conditionals to all students. 
* These 2 conditionals will be triggered only once. 
* These conditionals start and stop this activity.
* Give the first ‘BEGIN’ conditional to the students PRINT SIDE UP.
 
**IF** the teacher writes the word ‘**BEGIN**’ on the whiteboard,<br/>
**THEN** flip over the conditionals in front of you and follow the directions.
 
**IF** you see the word ‘**STOP**’ on the whiteboard,<br/>
**THEN** sit back, cross your arms, and look at the teacher (smile!).

=================================================================

Give these 6 conditionals to multiple students.
* These 6 conditionals may be triggered more than once.
* Walk around the classroom during the activity to trigger some of these conditionals.

**IF** the teacher says the word ‘popcorn’,<br/>
**THEN** stand up and say ‘Pop!’ once and sit back down.
 
**IF** any student stands up for any reason,<br/>
**THEN** clap 3 times.
 
**IF** anyone writes on the whiteboard with a GREEN marker,<br/>
**THEN** get up and touch something GREEN in the room and sit back down.
 
**IF** anyone walks past you while you are seated,<br/>
**THEN** snap your fingers 3 times.
 
**IF** someone snaps their fingers **AND** you have the letter ‘e’ in your first name,<br/>
**THEN** select a book from the bookcase and sit back down.
 
**IF** anyone writes anything on the whiteboard,<br/>
**THEN** get up and turn around in place one full turn and sit back down.
 
=================================================================

Give one student each of the following 7 conditionals. 
* These 7 conditionals will be triggered only once and set in motion the spelling of STOP on the whiteboard.
 
**IF** the teacher picks up a book,<br/>
**THEN** get up and write the letter S on the whiteboard and sit back down.
 
**IF** someone writes the letter S on the whiteboard,<br/>
**THEN** go open and close the classroom door and sit back down.
 
**IF** someone opens and closes the classroom door,<br/>
**THEN** get up and write the letter T (after the letter S) on the whiteboard.
 
**IF** someone writes the letter T on the whiteboard,<br/>
**THEN** get up and turn the lights on and off and sit back down.
 
**IF** someone turns on and off the lights,<br/>
**THEN** get up and write the letter O (after the letter T) on the whiteboard.
 
**IF** someone writes the letter O on the whiteboard,<br/>
**THEN** get up and sharpen a pencil.
 
**IF** someone sharpens a pencil,<br/>
**THEN** get up and write the letter P (after the letter O) on the whiteboard.


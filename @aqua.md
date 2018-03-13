# Think Python Contents

```python
brief = [(0, 'Preface'),
         (1, 'The Way of the Program'),
         (2, 'Variables,Expressions and Statements'),
         (3, 'Functions'),
         (4, 'Case Study'),
         (5, 'Conditionals and Recursion'),
         (6, 'Fruitful Functions'),
         (7, 'Iteration'),
         (8, 'String'),
         (9, 'Case Study'),
         (10, 'Lists'),
         (11, 'Dictionaries
         (12, 'Tuples'),
         (13, 'Case Study'),
         (14, 'Files'),
         (15, 'Classes and Objects'),
         (16, 'Classes and Functions'),
         (17, 'Classes and Methods'),
         (18, 'Inheritance'),
         (19, 'The Goodies'),
         (20, 'Debugging'), 
         (21, 'Analysis of Algorithms'),
         (22, 'Index')]

#排版用的python代码[ i.split(':')[1] for i in brief]

brief_detials = {
'1.The Way of the Program':
                    [(1, 'What Is a Program'),
                     (2, 'Running Python'),
                     (3, 'The First Program'),
                     (4, 'Arithmetic Operators'),
                     (5, 'Values and Types'),
                     (6, 'Formal and Natural Languages'),
                     (7, 'Debugging'),
                     (8, 'Glossary'),
                     (9, 'Exercises')],
'2.Variable,Expressions and Statements':
                    [(1, 'Assignment Statements'),
                     (2, 'Variable Names'),
                     (3, 'Expressions and Statements'),
                     (4, 'Script Mode'),
                     (5, 'Order of Operations'),
                     (6, 'String Operations'),
                     (7, 'Comments'),
                     (8, 'Debugging'),
                     (9, 'GlossaryExercises')],
'3.Functions':
                    [(1, 'Function Calls'),
                     (2, 'Math Functions'),
                     (3, 'Composition'),
                     (4, 'Adding New Functions'),
                     (5, 'Definitions and Uses'),
                     (6, 'Flow of Execution'),
                     (7, 'Parameters and Arguments'),
                     (8, 'Variables and Parameters Are Local'),
                     (9, 'Stack Diagrams'),
                     (10, 'Fruitful Functions and Void Functions'),
                     (11, 'Why functions?'),
                     (12, 'Debugging'),
                     (13, 'Glossary'),
                     (14, 'Exercises')],
'4.Case Study:Interface Design':
                    [(1, 'The turtle Module'),
                     (2, 'Simple Repetition'),
                     (3, 'Exercises'),
                     (4, 'Encapsulation'),
                     (5, 'Generalization'),
                     (6, 'Interface Design'),
                     (7, 'Refactoring'),
                     (8, 'A Development Plan'),
                     (9, 'docstring'),
                     (10, 'DebuggingGlossaryExercises')],
'5.Conditionals and Recursion':
                    [(1, 'Floor Division and Modulus'),
                     (2, 'Boolean Expressions'),
                     (3, 'Logical Operators'),
                     (4, 'Conditional Execution'),
                     (5, 'Chained Conditionals'),
                     (6, 'Nested Conditionals'),
                     (7, 'Recursion'),
                     (8, 'Stack Diagrams for Recursive Functions'),
                     (9, 'Infinite Recursion'),
                     (10, 'Keyboard InputDebuggingGlossaryExercises')],
'6.Fruitful Functions':
                    [(1, 'Return Values'),
                     (2, 'Composition'),
                     (3, 'Boolean Functions'),
                     (4, 'More Recursion'),
                     (5, 'Leap of Faith'),
                     (6, 'One More Example'),
                     (7, 'Checking Type'),
                     (8, 'DebuggingGlossaryExercises')],
'7.Iteration':
                    [(1, 'Reassignment'),
                     (2, 'Updating Variables'),
                     (3, 'The while Statement'),
                     (4, 'break'),
                     (5, 'Square Roots'),
                     (6, 'Algorithms'),
                     (7, 'Debugging'),
                     (8, 'Glossary'),
                     (9, 'Exercises')],
'8.Strings':
                    [(1, 'A string is Sequence'),
                     (2, 'len'),
                     (3, 'Traversal with a for Loop'),
                     (4, 'Strings Are Immutable'),
                     (5, 'Searching'),
                     (6, 'Looping and CountingString Methods'),
                     (7, 'The in Operator'),
                     (8, 'String Comparison'),
                     (9, 'Debugging'),
                     (10, 'Glossary'),
                     (11, 'Exercises')]
'9.Case Study:Word Play':
                   [(1, 'Reading Word Lists'),
                    (2, 'Exercises'),
                    (3, 'Search'),
                    (4, 'Looping with Indices'),
                    (5, 'Debugging'),
                    (6, 'Glossary'),
                    (7, 'Exercises')], 
    
'10.Lists':
                   [(1, 'A List iS A Sequence'),
                    (2, 'Lists Are Mutable'),
                    (3, 'Traversing a List'),
                    (4, 'List Operations'),
                    (5, 'List Slices'),
                    (6, 'List Methods'),
                    (7, 'Map.Filter and Reduce')
                    (8, 'Deleting Elements'),
                    (9, 'Lists and Strings'),
                    (10, 'Objects and Values'),
                    (11, 'Aliasing'),
                    (12, 'List Arguments'),
                    (13, 'Debugging'),
                    (14, 'Glossary')
                    (15, 'Exercises')], 
'11.Dictionaries':
                   [(1, 'A Dictionary Is a Mapping'),
                    (2, 'Dictionary as a Collection of Counters'),
                    (3, 'Looping and Dictionaries of Counters'),
                    (4, 'Looping and Dictionaries'),
                    (5, 'Reverse Lookup'),
                    (6, 'Dictionaries and Lists'),
                    (7, 'Memos')
                    (8, 'Global Variables'),
                    (9, 'Debugging'),
                    (10, 'Glossary')
                    (11, 'Exercises')], 
'12.Tuples':
                   [(1, 'Tuples Are Immutable'),
                    (2, 'Tuple Assignment'),
                    (3, 'Tuples as Return Values'),
                    (4, 'Variable-Length Argument Tuple'),
                    (5, 'Lists and Tuples'),
                    (6, 'Sequences of Sequences'),], 
} 


       
```

## 1.The Way of the Program

```python
'1.The Way of the Program' = ['Program','Python','Arithmetic','Debug','Glossary']
```

**Program** /ˈproʊ.ɡræm/ 程序

1. 助记,
   Pro + gram

2. 词源,
   **OED Origin**

   US spelling of [programme](https://en.oxforddictionaries.com/definition/programme) (also widely used in computing contexts)
   **Etymology**

   1630s, "public notice," from Late Latin programma "proclamation, edict," from Greek programma "a written public notice," from stem of prographein "to write publicly," **from pro "forth" (see [pro-](https://www.etymonline.com/word/pro-?ref=etymonline_crossreference)) +graphein "to write" (see [-graphy](https://www.etymonline.com/word/-graphy?ref=etymonline_crossreference)).**

3. 释义,
   程序  to write a series of instructions that make a computer perform a particularoperation

4. 拓展

   英语单词program来自希腊语programma，由pro（往前）+gramma（写、画）构成，字面意思就是“书写出来的东西”，指的是书面公告。进入英语后原本指的也是“书面公告”。由于此类公告通常不是法律方面的，而是关于一些活动的预告、办事指南之类，因此program一词逐渐用来表示公告所涉及的内容本身，如活动、计划、程序、节目等。
   ​

**Python**/ˈpaɪ.θɑːn/ 巨蟒

1. 助记,
   Pytho

2. 词源,
   **OED Origin**

   Late 16th century (in the Greek sense): via Latin from Greek Puthōn, the name of a huge serpent killed by Apollo. The main current sense dates from the mid 19th century.
   **Etymology**

   1580s, fabled serpent, slain by Apollo near Delphi, from Latin Python, from Greek Python "serpent slain by Apollo," probably related to Pytho, the old name of Delphi, perhaps itself related to pythein "to rot," or from PIE *dhubh-(o)n-, from *dheub- "hollow, deep, bottom, depths," and used in reference to the monsters who inhabit them. Zoological application to large non-venomous snakes of the tropics is from 1836, originally in French.

3. 释义,
   巨蟒  a very large snake that kills animals for food by wrapping itself around them andcrushing them

4. 拓展

   在希腊神话中，当天后赫拉听说勒托（Leto）怀上了宙斯的孩子后，大为恼火，想方设法阻扰勒托的生产，并派出一条名叫“皮同“（Python）的巨蟒来袭击勒托。勒托被巨蟒追得无处栖身，后来逃到海中一个荒岛上才找到一个生产之地。勒托花了九天九夜才生下一对孪生子，即月亮女神阿尔忒弥斯和光明神阿波罗。阿波罗长大后，替母复仇，在德尔斐（Delphi）附近的海湾杀死了巨蟒皮同。人们在德尔斐修建了一座阿波罗神殿作为纪念。因为阿波罗拥有强大的预言能力，所以该神殿以其准确的“神谕”（Oracle）而闻名。
   英语单词python（巨蟒）就源自被阿波罗杀死的巨蟒的希腊语名字Python。在希腊语中，Python的来源可能与德尔菲的旧称Pytho有关。



**2018.03.07**

**Arithmetic** /əˈrɪθ.mə.tɪk/ 算术

1. 助记,
   Arith+m+etic

2. 词源,
   **OED Origin**

   Middle English: from Old French arismetique, based on Latin arithmetica, from Greek arithmētikē (tekhnē) ‘(art) of counting’, from arithmos ‘number’.

   **Etymology**

   "art of computation, the most elementary branch of mathematics," mid-13c., arsmetike, from Old French arsmetique (12c.), from Latin arithmetica, from Greek arithmetike (tekhne) "(the) counting (art)," fem. of arithmetikos "of or for reckoning, arithmetical," **from arithmos "number, counting, amount,"** from PIE *erei-dhmo-, suffixed variant form of root [*re-](https://www.etymonline.com/word/*re-?ref=etymonline_crossreference) "to reason, count."

3. 释义,
   算术 the part of mathematics that involves the adding and multiplying, etc. of numbers

4. 拓展

   arithmetic : arith-,计算，词源同read,reason-m,插入鼻音字母。希腊语里arithmos表示数字、总数，-etic后缀表pertaining to，arithmetic的字面意思是“(the) counting (art)”。这个单词与read、riddle谜语、rate比率；认为、ration配给；口粮和reason理由；推论等同源，但希腊人不习惯用字母r开头，所以......前边多了个a-。



Debug** /ˌdiːˈbʌɡ/  排除错误

1. 助记,
   De+bug

2. 词源,
   **OED Origin**

   **Etymology**

   1945, of machine systems, **from [de-](https://www.etymonline.com/word/de-?ref=etymonline_crossreference) + [bug](https://www.etymonline.com/word/bug?ref=etymonline_crossreference) (n.)** "glitch, defect in a machine." Meaning "to remove a concealed microphone" is from 1964. Related: Debugged; debugging.

3. 释义,
   排除错误 to remove bugs (= mistakes) from a computer program

4. 拓展

   debug : de-,不，非，使相反，bug,故障。(尤指计算机程序的)排错器，消除误差。



Glossary** /ˈɡlɑː.sɚ.i/ 术语表

1. 助记,
   Glossa+ary

2. 词源,
   **OED Origin**

   Late Middle English: from Latin glossarium, **from glossa (see gloss)**.

   **Etymology**

   "collected explanations of words (especially those not in ordinary use), a book of glosses," mid-14c., from Latin glossarium "collection of glosses," from Greek glossarion, diminutive of glossa "obsolete or foreign word" (see [gloss](https://www.etymonline.com/word/gloss?ref=etymonline_crossreference) (n.2)). Related: Glossarial.

3. 释义,
   术语表 an alphabetical list, with meanings, of the words or phrases in a text that aredifficult to understand

4. 拓展

   glossary : 来自拉丁语glossa,舌头，外来词，注释，-ary,集合名词后缀。 进而指“语言”、指“词汇”、指“词义解释”。Glossary就是“词义解释汇集”。

   ​

## 2.Variables,Expressions and Statements

```python
'2. Variables,Expressions and Statements' = ['Variable','Assignment','Script']
```

**Variable** /ˈver.i.ə.bəl/ 多变的

1. 助记,
   Vari+able

2. 词源,
   **OED Origin**

   Late Middle English: via Old French from Latin variabilis, from variare (see vary).

   **Etymology**

   late 14c., of persons, "apt to change, fickle," from Old French variable "various, changeable, fickle," from Late Latin variabilis "changeable," **from variare "to change" (see [vary](https://www.etymonline.com/word/vary?ref=etymonline_crossreference)).** Of weather, seasons, etc., attested from late 15c.; of stars, from 1788.

3. 释义,
   多变的 likely to change often

4. 拓展

   variable : 来自vary,改变，多变。通常与介词 from 连用，表示“不同于，有别于”，为正式用语，但也可以使用different to (或than)。



**Assignment** /əˈsaɪn.mənt/ 任务

1. 助记,
   Assign+ment

2. 词源,
   **OED Origin**

   Late Middle English: from Old French assignement, from medieval Latin assignamentum, from Latin assignare ‘allot’ (see assign).

   **Etymology**

   late 14c., "an order, request, directive," from Old French assignement "(legal) assignment (of dower, etc.)," from Late Latin assignamentum, noun of action **from Latin assignare/adsignare "to allot, assign, award" (see [assign](https://www.etymonline.com/word/assign?ref=etymonline_crossreference)).** Meaning "appointment to office" is mid-15c.; that of "a task assigned (to someone), commission" is by 1848.

3. 释义,
   任务 a piece of work given to someone, typically as part of their studies or job

4. 拓展

   略



**Script** /skrɪpt/ 手稿

1. 助记,
   Scri(be)+pt

2. 词源,
   **OED Origin**

   Late Middle English (in the sense ‘something written’): shortening of Old French escript, from Latin scriptum, neuter past participle (used as a noun) of scribere ‘write’.

   **Etymology**

   late 14c., "something written," earlier scrite (c. 1300), **from Old French escrit "piece of writing, written paper;** credit note, IOU; deed, bond" (Modern French écrit) from Latin scriptum "a writing, book; law; line, mark," noun use of neuter past participle of scribere "to write," from PIE root [*skribh-](https://www.etymonline.com/word/*skribh-?ref=etymonline_crossreference) "to cut, separate, sift." The original notion is of carving marks in stone, wood, etc.

3. 释义,
   手稿 the words of a film, play, broadcast, or speech:

4. 拓展

   script : 来自scribe,写，-pt,过去分词格。词性由形容词作名词使用，引申诸相关词义。古代，在墨水发明之前，人们都是用铭刻的方式来写字的，即用尖刻之物在竹简、木板、泥版、蜡板等书写材料上刻画。所以在英语单词中，表示“写”的单词scribe及由此衍生的词根scribe-还含有“刻”的含义。如inscribe，既表示“题写”，也表示“铭记”。英语单词scribe来自拉丁语scribere，本意是“刻”。与它同源的单词有：script（脚本）、prescribe（开处方）、describe（描述）、manuscript（手稿）等。而英语中表示“写”的更常用单词write来自古日耳曼语，本意是scratch（刮擦）。

   ​

## 3.Functions

```python
'3.Functions' =['Function','Composition','Execution','Parameter','Argument','Diagram','Fruitful']
```

**Function** /ˈfʌŋk.ʃən/ 功能

1. 助记,
   Funct+ion

2. 词源,
   **OED Origin**

   Mid 16th century: from French fonction, **from Latin functio(n-), from fungi ‘perform’.**

   **Etymology**

   1530s, "one's proper work or purpose; power of acting in a specific proper way," from Middle Frenchfonction (16c.) and directly from Latin functionem (nominative functio) "a performance, an execution," noun of action from funct-, past participle stem of fungi "perform, execute, discharge," from PIE *bhung- "be of use, be used" (source also of Sanskrit bhunjate "to benefit, make benefit, atone," Armenian bowcanem "to feed," Old Irish bongaid "to break, harvest"), which is perhaps related to root [*bhrug-](https://www.etymonline.com/word/*bhrug-?ref=etymonline_crossreference) "to enjoy." Meaning "official ceremony" is from 1630s, originally in church use. Use in mathematics probably was begun by Leibnitz (1692). In reference to computer operations, 1947.

3. 释义,
   功能 the natural purpose (of something) or the duty (of a person)

4. 拓展

   function : 来自拉丁语functio,履行，执行。

   ​

   **2018.03.07**

**Composition** /ˌkɑːm.pəˈzɪʃ.ən/  构成

1. 助记,
   Com+posit+ion

2. 词源,
   **OED Origin**

   Late Middle English: via Old French from Latin compositio(n-), **from componere ‘put together’**.

   **Etymology**

   late 14c., "a carrying out, a putting into effect; enforcement; performance (of a law, statute, etc.), the carrying out (of a plan, etc.)," from Anglo-French execucioun (late 13c.), Old French execucion "a carrying out" (of an order, etc.), from Latin executionem (nominative executio) "an accomplishing," noun of action from past participle stem of exequi/exsequi "to follow out" (see [execute](https://www.etymonline.com/word/execute?ref=etymonline_crossreference)).

3. 释义,
   构思、构成 the way that people or things are arranged in a painting or photograph

4. 拓展

   composition:com一起+posit+ion→放到一起→组合→构成，文章等。



**Execution** /ˌek.səˈkjuː.ʃən/ 执行

1. 助记,
   Ex+(s)ec+ution

2. 词源,
   **OED Origin**

   Late Middle English: from Old French executer, from medieval Latin executare, from Latin exsequi ‘follow up, punish’, **from ex- ‘out’ + sequi ‘follow’.**

   **Etymology**

   late 14c., "a carrying out, a putting into effect; enforcement; performance (of a law, statute, etc.), the carrying out (of a plan, etc.)," from Anglo-French execucioun (late 13c.), Old French execucion "a carrying out" (of an order, etc.), from Latin executionem (nominative executio) "an accomplishing," noun of action **from past participle stem of exequi/exsequi "to follow out" (see [execute](https://www.etymonline.com/word/execute?ref=etymonline_crossreference)).**

3. 释义,
   执行  the act of doing or performing something, especially in a planned way

4. 拓展

   execution : [ex-=out出；(s)ecut=to follow跟随；-e→“to follow out of the procedure跟着程序出来”→].词根sec-指“跟随”，字母s缺失，因为它和ex-读音融合了.



**Parameter** /pəˈræm.ə.t̬ɚ/ 参数

1. 助记,
   Para+meter

2. 词源,
   **OED Origin**

   Mid 17th century: modern Latin, **from Greek para- ‘beside’ + metron ‘measure’.**

   **Etymology**

   1650s in geometry, from Modern Latin parameter (1630s), **from Greek para- "beside, subsidiary" (see [para-](https://www.etymonline.com/word/para-?ref=etymonline_crossreference) (1)) + metron "measure" (from PIE root [*me-](https://www.etymonline.com/word/*me-?ref=etymonline_crossreference) (2) "to measure").**

3. 释义,
   参数 a set of facts or a fixed limit that establishes or limits how something can or musthappen or be done

4. 拓展

   parameter : para-,在旁，在周围，-meter,测量，规定，词源同meter,measure.引申词义参数，规范.【数学】参(变)数；参(变)量.



**Argument** /ˈɑːrɡ.jə.mənt/ 论证

1. 助记,
   Arg+ument

2. 词源,
   **OED Origin**

   Middle English (in the sense ‘process of reasoning’): via Old French from Latin argumentum, **from arguere ‘make clear, prove, accuse’.**

   **Etymology**

   early 14c., "statements and reasoning in support of a proposition or causing belief in a doubtful matter," from Old French arguement "reasoning, opinion; accusation, charge" (13c.), from Latinargumentum "a logical argument; evidence, ground, support, proof," **from arguere "make clear, make known, prove" (see [argue](https://www.etymonline.com/word/argue?ref=etymonline_crossreference)).** Sense passed through "subject of contention" (1590s) to "a quarrel" (by 1911), a sense formerly attached to [argumentation](https://www.etymonline.com/word/argumentation?ref=etymonline_crossreference).

3. 释义,
   论证 a reason or reasons why you support or oppose an idea or suggestion, or theprocess of explaining these reasons

4. 拓展

   阿尔戈斯的名字在希腊语中是Argos，含义是“明亮的、发亮的”。英语词根arg-（闪亮）和单词argus（警惕的人）都来自他的名字。英国海军二战前的一艘航空母舰、美国2012年推出的一款无人驾驶侦察机都叫做Argus。阿尔戈斯是希腊神话中的百眼巨人。他有100只眼睛，分布在全身，可以观察到各个方向发生的事情，即使睡觉时也有两只眼睛睁着。据说有一次宙斯下凡勾引凡间美女伊娥，为了遮人耳目就变出一团云雾笼罩在周围。天后赫拉心生怀疑，驱散云雾，宙斯赶紧将伊娥变出一头雪白的小母牛。赫拉看穿了宙斯的诡计，假意喜欢这头牛，要求宙斯把这头牛送给自己作宠物，然后派阿尔戈斯严密监视小母牛。宙斯派自己的儿子、神使赫尔墨斯前去解救伊娥。赫尔墨斯用笛子吹出动听的音乐，还给他讲潘神追求宁芙仙女不成最后发明潘神萧的故事，引诱阿尔戈斯闭上所有眼睛入睡。赫尔墨斯趁阿尔戈斯睡着后砍下了他的头，救出了伊娥。后来赫拉将阿尔戈斯的100只眼睛转移到她最宠爱的鸟——孔雀的尾羽上。从此以后，孔雀的尾羽上长满了眼睛一样的美丽花纹。

   引申：真理越辨越明。

5. 争论、论证的词源是ARG(明亮)。正如我们学习讨论的过程，每个人搜索论据来证明自己的观点，由于每个人有不同的出发点、立场、考虑问题的角度，最后不一定会得出一个所谓“正确”的结论，但是论证的过程，却可以让每个人思路更清晰、明亮，从中各取所需，这就是交流和讨论的乐趣吧。

   ​

**Diagram**/ˈdaɪ.ə.ɡræm/ 图解

1. 助记,
   Dia+gram

2. 词源,
   **OED Origin**

   Early 17th century: from Latin diagramma, from Greek, from diagraphein ‘mark out by lines’, **from dia ‘through’ + graphein ‘write’.**

   **Etymology**

   1610s, from French diagramme, from Latin diagramma, from Greek diagramma "geometric figure, that which is marked out by lines," from diagraphein "mark out by lines, delineate," **from dia- "across, out" (see [dia-](https://www.etymonline.com/word/dia-?ref=etymonline_crossreference)) + graphein "write, mark, draw" (see [-graphy](https://www.etymonline.com/word/-graphy?ref=etymonline_crossreference)). The verb is 1840, from the noun.**

3. 释义,
   图解 a simple plan that represents a machine, system, or idea, etc., often drawn toexplain how it works

4. 拓展

   diagram : [dia-=through, across穿过；gram=thing written, or figure书写的东西,图形→“figure made of lines going across it由穿行其间的线条构成的图形”→].词源同telegram.用来指图表，后引申为图解。



**Fruitful** /ˈfruːt.fəl/ 有成果的

1. 助记,
   Fruit+ful

2. 词源,
   **OED Origin**

   **Etymology**

   c. 1300, of trees, **from [fruit](https://www.etymonline.com/word/fruit?ref=etymonline_crossreference) + [-ful](https://www.etymonline.com/word/-ful?ref=etymonline_crossreference).** Related: Fruitfully; fruitfulness. Of animals or persons from early 16c.; of immaterial things from 1530s.

3. 释义,
   有成果的 producing good results

4. 拓展

   fruitful : 来自fruit, 硕果累累，有成效的。

   ​

## 4.Case Study:Interface Design

```python
'4.Case Study:Interface Design' = ['Interface','Encapsulate','Generalize']
```

**Interface** /ˈɪn.t̬ɚ.feɪs/ 界面

1. 助记,
   Inter+face

2. 词源,
   **OED Origin**

   **Etymology**

   1874, "a plane surface regarded as the common boundary of two bodies," **from [inter-](https://www.etymonline.com/word/inter-?ref=etymonline_crossreference) + [face](https://www.etymonline.com/word/face?ref=etymonline_crossreference) (n.).** Modern use is perhaps a c. 1960 re-coinage; McLuhan used it in the sense "place of interaction between two systems" (1962) and the computer sense "apparatus to connect two devices" is from 1964. As a verb from 1967. Related: Interfaced; interfacing.

3. 释义,
   接口、界面 a connection between two pieces of electronic equipment, or between a personand a computer

4. 拓展

   interface : inter-,在内，在中间，相互，face,脸。比喻用法【计算机】联系；接合。



**Encapsulate** /ɪnˈkæp.sjə.leɪt/ 装入胶囊（套入）

1. 助记,
   En+Capsul(e)+ate

2. 词源,
   **OED Origin**

   Late 19th century (also as incapsulate): **from en-, in- ‘into’ + Latin capsula (see capsule).**

   **Etymology**

   1842 (implied in encapsulated), "enclose in a capsule," **from [en-](https://www.etymonline.com/word/en-?ref=etymonline_crossreference) (1) "make, put in" + [capsule](https://www.etymonline.com/word/capsule?ref=etymonline_crossreference) + [-ate](https://www.etymonline.com/word/-ate?ref=etymonline_crossreference)(2). Figurative use by 1939. Related: Encapsulating.**

3. 释义,
   套入to express or show the most important facts about something

4. 拓展

   encapsulate : en-,进入，使，capsule,胶囊。 



**Generalize** /ˈdʒen.ər.əl.aɪz/ 通用化

1. 助记,
   General+ize

2. 词源,
   **OED Origin**

   Middle English (in the sense ‘reduce to a general statement’): **from general + -ize.**

   **Etymology**

   1751, probably a new formation **from [general](https://www.etymonline.com/word/general?ref=etymonline_crossreference) (adj.) + [-ize](https://www.etymonline.com/word/-ize?ref=etymonline_crossreference).** Middle English had generalisen (early 15c.). Related: Generalizable; generalized; generalizing.

3. 释义,
   通用化 to say or write that something is true all of the time, when it is only true some of the time

4. 拓展

   generalize : 来自general,通用的，概括的。从…概括出一般规律，从…引出一般性结论，归纳出，概括出，推断出。



**20180309**

## 5.Conditionals and Recursion

```
5:Conditionals and Recursion= ['Recursion','Alternative']
```

**Recursion** /rɪˈkɝː.ʒən/ 循环

1. 助记,
   Re+cur+sion

2. 词源,
   **OED Origin**

   1930s: from late Latin recursio(n-), **from recurrere ‘run back’ (see recur).**

   **Etymology**

   1610s, from Latin recursionem (nominative recursio) "a running backward, return," noun of action from past participle stem of recurrere "**run back" (see [recur](https://www.etymonline.com/word/recur?ref=etymonline_crossreference)).**

3. 释义,
   循环 the practice of putting a structure such as a phrase inside a structure of the same kind

4. 拓展

   recursion : re-,再，重新，-cur,跑，词源同course,current.引申诸相关词义。

**Alternative**  /ɑːlˈtɝː.nə.t̬ɪv/ 二择其一的

1. 助记,
   Alter+native

2. 词源,
   **OED Origin**

   Mid 16th century (in the sense ‘alternating, alternate’): from French alternatif, -ive or medieval Latin alternativus, **from Latin alternare ‘interchange’ (see alternate).**

   **Etymology**

   1580s, "offering one or the other of two," from Medieval Latin alternativus, from Latin alternatus, past participle of alternare "do one thing and then another, do by turns," from alternus "one after the other, alternate, in turns, reciprocal," **from alter "the other" (see [alter](https://www.etymonline.com/word/alter?ref=etymonline_crossreference))**. Meaning "purporting to be a superior choice to what is in general use" was current by 1970 (earliest reference is to the media); in popular music, by 1984 in reference to pirate radio. Alternative energy is from 1975. Related:Alternatively.

3. 释义,
   二择其一的 An alternative plan or method is one that you can use if you do not want to use another one.

4. 拓展

   alternative.Alter,改变的.两者(或两者以上)择一的，二择其一的，可从数个中任择其一的；(两种选择中)非此即彼的.


## 6.Conditionals and Recursion

```python
'6.Conditionals and Recursion'= ['Incremental','Example']
```

**Incremental** /ˌɪŋ.krəˈmen.t̬əl/ 增长的

1. 助记,
   In+cre+ment+al

2. 词源,
   **OED Origin**

   Early 18th century: **from increment + -al.**

   **Etymology**

   mid-15c., "act or process of increasing," from Latin incrementum "growth, increase; an addition," **from stem of increscere "to grow in or upon" (see [increase](https://www.etymonline.com/word/increase?ref=etymonline_crossreference) (v.)).** Meaning "amount of increase" first attested 1630s.

3. 释义,
   增长的  Changes at the [newspaper](https://dictionary.cambridge.org/zhs/%E8%AF%8D%E5%85%B8/%E8%8B%B1%E8%AF%AD/newspaper) are more incremental than [radical](https://dictionary.cambridge.org/zhs/%E8%AF%8D%E5%85%B8/%E8%8B%B1%E8%AF%AD/radical)

4. 拓展

   incremental ,in-=向内，或者等同于on，向上；cre-=增长，产生，如create；+al.increment可以表示“增长”。 

**Example** /ɪɡˈzæm.pəl/ 例子

1. 助记,
   In+cre+ment+al

2. 词源,
   **OED Origin**

   Late Middle English: from Old French, from Latin exemplum, **from eximere ‘take out’,** from ex- ‘out’ + emere ‘take’. **Compare with sample**.

   **Etymology**

   late 14c., "an instance typical of a class; a model, either good or bad, action or conduct as an object of imitation; an example to be avoided; punishment as a warning," partial re-Latinization of earlieressample, asaumple (mid-13c.), from Old French essemple "sample, model, example, precedent, cautionary tale," from Latin exemplum "a sample, specimen; image, portrait; pattern, model, precedent; a warning example, one that serves as a warning," literally "that which is taken out," fromeximere "remove, take out, take away; free, release, deliver, make an exception of," **from ex- "out" (see [ex-](https://www.etymonline.com/word/ex-?ref=etymonline_crossreference)) + emere "buy," originally "take,"** from PIE root [*em-](https://www.etymonline.com/word/*em-?ref=etymonline_crossreference) "to take, distribute." 

3. 释义,
   例子 a way of helping someone to understand something by showing them how it is used

4. 拓展

   example : ex-,向外，-em,拿出，带出，词源sample,exempt.

   【辨析】such as 和for example 这两个短语都可以作“例如”解。for example用来举例说明某一论点或情况，一般只举同类人或物中的“一个”为例，作插入语，可位于句首，句中或句末。 例如： Ball games, for example, have spread around the world. 球类运动就已经在世界各地传播开了。 What would you do if you met a wild animal？a lion, for example? 如果遇上野兽，例如狮子，你该怎么办？ such as用来列举事物时，一般列举同类人或事物中的几个例子。插在被列举的事物与前面的名词之间，as后面不可有逗号。 例如： Some of the rubbish, such as food, paper and iron, rots away over a long period of time. 有些废物，如剩饭、废纸和废铁，时间一久就烂掉了。 


## 7.Iteration

```python
'7.Conditionals and Recursion'= ['Iteration','Algorithm']
```

**Iteration**/ˌɪt̬.əˈreɪ.ʃən/ 迭代

1. 助记,
   Iter+ation

2. 词源,
   **OED Origin**

   Late Middle English: from Latin iteratio(n-), from the verb iterare (see iterate).

   **Etymology**

   late 15c., from Latin iterationem (nominative iteratio) "a repetition," noun of action **from past participle stem of iterare "do again, repeat**," from iterum "again," from PIE *i-tero-, from pronominal root *i- (see [yon](https://www.etymonline.com/word/yon?ref=etymonline_crossreference)). 

3. 释义,
   迭代   specialized mathematics, computing an amount that you get when you use a mathematical rule several times

4. 拓展

   iteration : 来自拉丁语iterare,重复，再次，词源同idem,item,-ter,比较级后缀。引申词义反复，反复声明。



 **Algorithm** /ˈæl.ɡə.rɪ.ðəm/ 算法

1. 助记,
   Algori+thm

2. 词源,
   **OED Origin**

   Late 17th century (denoting the Arabic or decimal notation of numbers): variant (influenced by Greek arithmos ‘number’) of Middle English algorism, via Old French from medieval Latin algorismus. The Arabic source, al-Ḵwārizmī ‘the man of Ḵwārizm’ (now Khiva), was a name given to the 9th-century mathematician Abū Ja‘far Muhammad ibn Mūsa, author of widely translated works on algebra and arithmetic.

   **Etymology**

   1690s, "Arabic system of computation," from French algorithme, refashioned (under mistaken connection with Greek arithmos "number") from Old French algorisme "the Arabic numeral system" (13c.), from Medieval Latin algorismus, a mangled transliteration of Arabic al-Khwarizmi "native of Khwarazm" (modern Khiva in Uzbekistan), surname of the mathematician whose works introduced sophisticated mathematics to the West (see [algebra](https://www.etymonline.com/word/algebra?ref=etymonline_crossreference)). The earlier form in Middle English was algorism (early 13c.), from Old French. Meaning broadened to any method of computation; from mid-20c. especially with reference to computing.

3. 释义,
   算法 a set of mathematical instructions or rules that, especially if given to a computer, will help to calculate an answer to a problem

4. 拓展

   algorithm : 来自阿拉伯数学家Khwarizmi的名字。algorithm是当时拉丁学者对该数学家名字的拙劣的翻译，或部分受arithmetic的影响.

   阿尔•花刺子模全名为穆罕默德•本•穆萨•阿尔•花剌子模（Muhammad ibn Msa al Khwarizmi），出生于波斯北部城市花剌子模，是阿拉伯阿拔斯王朝著名数学家、天文学家、地理学家，代数与算术的整理者，被誉为“代数之父”。公元830年，阿尔•花剌子模写了一本有关代数的书，英语单词Algebra（代数）就来源于这本书的书名中一个单词。
   阿尔•花剌子模还出版了一本数学著作，介绍了印度的十进制记数法和以此为基础的算术知识。13世纪，意大利数学家斐波那契（ Fibonacci）将这套十进制计数法和算术方法引介到欧洲，逐渐代替了欧洲原有的算板计算及罗马的记数系统。0~9等十个印度数字也因此被欧洲人误称为阿拉伯数字。意大利人将他的名字翻译成拉丁语Algorismus，并将他在这本著作中讲解的基于十进制计数法的算术方法也称为Algorismus。英语单词algorism（算术）一次就来自拉丁语Algorismus，后来被单词arithmetic（算术）逐渐替代，很少使用。而algorism的异体，英语单词algorithm却随着计算机科学技术的发展得以发扬光大，表示计算机领域的专业术语“算法”.


## 8.Strings

```python
'8.Strings'= ['Sequence','Immutable']
```

**Sequence**/ˈsiː.kwəns/ 序列

1. 助记,
   Sequ+ence

2. 词源,
   **OED Origin**

   Late Middle English (in sequence (sense 4 of the noun)): from late Latin sequentia, **from Latin sequent- ‘following’, from the verb sequi ‘follow’.**

   **Etymology**

   late 14c., "hymn sung after the Hallelujah and before the Gospel," from Old French sequence "answering verses" (13c.), from Medieval Latin sequentia "a following, a succession," **from Latin sequentem (nominative sequens), present participle of sequi "to follow" (from PIE root [*sekw-](https://www.etymonline.com/word/*sekw-?ref=etymonline_crossreference) (1) "to follow").** In Church use, a partial loan-translation of Greek akolouthia, from akolouthos "following." General sense of "succession," also "a sequence at cards," appeared 1570s.

3. 释义,
   序列 a series of related things or events, or the order in which they follow each other

4. 拓展

    sequence : 来自拉丁语sequi,追随，按顺序，词源同second,pursue.-ence,名词后缀。引申诸相关词义。



 **Immutable** /ɪˈmjuː.t̬ə.bəl/ 永恒的

1. 助记,
   Im+mutable

2. 词源,
   **OED Origin**

   Late Middle English: from Latin immutabilis, **from in- ‘not’ + mutabilis (see mutable).**

   **Etymology**

   early 15c., "unchanging, unalterable," from Old French immutable (Modern French immuable), and directly from Latin immutabilis "unchangeable, unalterable," from assimilated **form of in- "not, opposite of" (see [in-](https://www.etymonline.com/word/in-?ref=etymonline_crossreference) (1)) + mutabilis "changeable," from mutare "to change" (from PIE root [*mei-](https://www.etymonline.com/word/*mei-?ref=etymonline_crossreference) (1) "to change, go, move"). Related: Immutably.**

3. 释义,
   永恒的  not changing, or unable to be changed

4. 拓展

     immutable : im-,不，非，mutable,可改变的。




## 11.Dictionaries

```python
'11.Dictionaries'= ['Dictionary','Collection','Reverse']
```

**Dictionary** /ˈdɪk.ʃən.er.i/ 字典

1. 助记,
   Diction+ary

2. 词源,
   **OED Origin**

   Early 16th century: from medieval Latin dictionarium (manuale) or dictionarius (liber) ‘manual or book of words’, from Latin dictio (see diction).

   **Etymology**

   1520s, from Medieval Latin dictionarium "collection of words and phrases," from Latin dictionarius "of words," **from dictio "word," noun of action from past participle stem of dicere "speak, tell, say,"** from PIE root [*deik-](https://www.etymonline.com/word/*deik-?ref=etymonline_crossreference) "to show," also "pronounce solemnly." Probably first English use in title of a book was in Sir Thomas Elyot's "Latin Dictionary" (1538) though Latin Dictionarius was so used from early 13c. Grose's 1788 "Dictionary of the Vulgar Tongue" has "RICHARD SNARY. A dictionary."

3. 释义,
   字典 a book that contains a list of words in alphabetical order and that explainstheir meanings, or gives a word for them in another language; a similar productfor use on a computer

4. 拓展

   dictionary : [diction n. 措词；-ary n.=thing物→“book for diction措词用书”→。一本字典，就是人们对词汇的发音、拼法、含义等所作的解释的记载，即人们是怎么“说”的。它来自拉丁语动语dico，意思是“说”、“讲”。同出于dico之源的还有不少英语词，如，ditto，意思“同上”、“同前”，即和上面所“说”的一样；contradiction（矛盾），contra是“相反”、“反对”的意思，全词的意思是“说话自相矛盾”；verdict（陪审团的裁决），vere是“真实地”，全词即“正确地评说”，dictator（独裁者），意即“我一个人说了算”。都和“说”有关。



**Collection**/kəˈlek.ʃən/ 收藏

1. 助记,

   Collect+ion

2. 词源,
   **OED Origin**

   Late Middle English: via Old French from Latin collectio(n-), **from colligere ‘gather together’ (see collect).**

   **Etymology**

   late 14c., "action of collecting, practice of gathering together," from Old French collection (14c.), **from Latin collectionem (nominative collectio) "a gathering together**," noun of action from past-participle stem of colligere "gather together" (see [collect](https://www.etymonline.com/word/collect?ref=etymonline_crossreference)).

3. 释义,
   收藏 a group of objects of one type that have been collected by one person or in one place

4. 拓展

   collection : [collect v. 收集；-ion →“the result of collecting收集的结果”→]



**Reverse**/rɪˈvɝːs/ 反转

1. 助记,

   Re+verse

2. 词源,
   **OED Origin**

   Middle English: from Old French revers, reverse (nouns), reverser (verb), from Latin reversus ‘turned back’, past participle of revertere, **from re- ‘back’ + vertere ‘to turn’.**

   **Etymology**

   c. 1300, from Old French revers "reverse, cross, opposite" (13c.), **from Latin reversus, past participle of revertere "turn back, turn about, come back, return" (see [revert](https://www.etymonline.com/word/revert?ref=etymonline_crossreference))**. Reverse angle in film-making is from 1934. Reverse discrimination is attested from 1962, American English.

3. 释义,
   反转 to change the direction, order, position, result, etc. of something to itsopposite

4. 拓展

   reverse : 来自revert,回转，-s,过去分词格。引申诸相关词义，词性也由形容词兼做名词和动词使用。





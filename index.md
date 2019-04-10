<frontmatter>
  title: "Explore MarkBind"
  footer: footer.md
  header: header.md
  siteNav: site-nav.md
</frontmatter>

## Dynamic Programming

>The **O(V+E)** Dynamic Programming algorithm can solve special case of **SSSP problem**, i.e. when the input graph is a ++Directed Acyclic Graph(DAG)++ thus we can find at least one ~~tropicology~~ topological order of the DAG and process the ****edge relaxation**** according to this ****topological order****.
>
>>On the Modified Dijkstra's killer example shown above, DP(0) works fast as the graph is actually a DAG, albeit having negative weight edge. As the graph is a DAG, there will not be any negative weight cycle to worry about.
>>
>>>For more info: ++==https://visualgo.net/en/sssp?slide=10-1==++

https://visualgo.net/en/sssp?slide=10-1

### Testing image insertion
![](img/001.png)<br>
For more details, click [here](https://markbind.org).
****

### Testing List

* Item 1
  * Sub item 1.1
  * Sub item 1.2<br>
    Second line
    * Sub item 1.2.1
* Item 2
* Item 3

****
### Code Block Test
Consider the xml code `<bar type="name">goo</bar>`{.xml},
or the java code `public static void main(String[] args)`{.java}.

****
### Table Test
Animal | Trainable?| Price | Remarks
:----- | :-------: | ----: | ----
Ants   | no        | 5     |
Bees   | no        | 20    |
Cats|yes|100|

### Popover Test
<popover effect="fade" content="Lorem ipsum dolor sit amet" placement="top">
  <button class="btn btn-secondary">Popover on top</button>
</popover>
<popover effect="fade" content="Lorem ipsum dolor sit amet" placement="left">
  <button class="btn btn-secondary">Popover on left</button>
</popover>
<popover effect="fade" content="Lorem ipsum dolor sit amet" placement="right">
  <button class="btn btn-secondary">Popover on right</button>
</popover>
<popover effect="fade" content="Lorem ipsum dolor sit amet" placement="bottom">
  <button class="btn btn-secondary">Popover on bottom</button>
</popover>


****
### Question and Answer Test
<question>
  This question has no hint or answer.
  <div slot="hint"></div>
  <div slot="answer"></div>
</question>



# cs61a-homework-5--trees-linked-lists-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Homework 5- Trees, Linked Lists Solved](https://www.ankitcodinghub.com/product/cs61a-homework-5-trees-linked-lists-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119652&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Homework 5- Trees, Linked Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Instructions

Download hw05.zip. Inside the archive, you will find a file called hw05.py, along with a copy of the ok autograder.

Using Ok: If you have any questions about using Ok, please refer to this guide.

Readings: You might find the following references useful: Section 4.2

Grading: Homework is graded based on correctness. Each incorrect problem will decrease the total score by one point. There is a homework recovery policy as stated in the syllabus. This homework is out of 2 points.

Required Questions

Getting Started Videos

YouTube link

Mid-Semester Feedback

Q1: Mid-Semester Feedback

As part of this week’s homework, please fill out the Mid-Semester Feedback form.

Once you finish the survey, you will be presented with a passphrase (if you miss it, it should also be at the bottom of the confirmation email you receive). Put this passphrase, as a string, on the line that says passphrase = ‘*** PASSPHRASE HERE ***’ in the Python file for this assignment.

Use Ok to test your code:

python3 ok -q midsem_survey

Parsons Problems

Q2: Chain

For this question, we will define a chain as a path from the root of a tree t to any leaf such that all nodes on the path share the same label. Implement the function chain, which, given a tree t, returns True if there exists any chain in the tree, and False otherwise.

py def chain(t): “”” Returns whether there exists a path in t where all nodes share the same label. &gt;&gt;&gt; all_fives = Tree(5, [Tree(5), Tree(5, [Tree(5)])]) &gt;&gt;&gt; chain(all_fives) True &gt;&gt;&gt; t1 = Tree(1, [Tree(3, [Tree(4)]), Tree(1)]) &gt;&gt;&gt; chain(t1) True &gt;&gt;&gt; t2 = Tree(1, [Tree(3, [Tree(4)]), Tree(5)]) &gt;&gt;&gt; chain(t2) False

“”” “*** YOUR CODE HERE ***”

Q3: Flatten Link

Write a function flatten_link that takes in a linked list lnk and returns the sequence as a Python list. If lnk has nested linked lists, flatten_link should flatten lnk.

“`py def flatten_link(lnk): “””Takes a linked list and returns a flattened Python list with the same elements.

&gt;&gt;&gt; link = Link(1, Link(2, Link(3, Link(4))))

&gt;&gt;&gt; flatten_link(link)

[1, 2, 3, 4]

&gt;&gt;&gt; flatten_link(Link.empty)

[]

&gt;&gt;&gt; deep_link = Link(Link(1, Link(2, Link(3, Link(4)))), Link(Link(5), Link(6)))

&gt;&gt;&gt; flatten_link(deep_link)

[1, 2, 3, 4, 5, 6]

“””

“*** YOUR CODE HERE ***”

“`

Code Writing Questions

Q4: Has Path

This data structure is called a trie, and it has a lot of cool applications, such as autocomplete.

“`py def has_path(t, term): “””Return whether there is a path in a Tree where the entries along the path spell out a particular term.

&gt;&gt;&gt; greetings = Tree(‘h’, [Tree(‘i’),

… Tree(‘e’, [Tree(‘l’, [Tree(‘l’, [Tree(‘o’)])]),

… Tree(‘y’)])])

&gt;&gt;&gt; print(greetings) h i e l l o y

&gt;&gt;&gt; has_path(greetings, ‘h’)

True

&gt;&gt;&gt; has_path(greetings, ‘i’)

False

&gt;&gt;&gt; has_path(greetings, ‘hi’)

True

&gt;&gt;&gt; has_path(greetings, ‘hello’)

True

&gt;&gt;&gt; has_path(greetings, ‘hey’)

True

&gt;&gt;&gt; has_path(greetings, ‘bye’)

False

&gt;&gt;&gt; has_path(greetings, ‘hint’)

False “””

assert len(term) &gt; 0, ‘no path for empty term.’ “*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q has_path

Q5: Duplicate Link

Write a function duplicate_link that takes in a linked list lnk and a value. duplicate_link will mutate lnk such that if there is a linked list node that has a first equal to value, that node will be duplicated. Note that you should be mutating the original link list lnk; you will need to create new Links, but you should not be returning a new linked list.

Note: in order to insert a link into a linked list, you need to modify the .rest of certain links. We encourage you to draw out a doctest to visualize!

“py def duplicate_link(lnk, val): “””Mutateslnk` such that if there is a linked list node that has a first equal to value, that node will be duplicated. Note that you should be mutating the original link list.

&gt;&gt;&gt; x = Link(5, Link(4, Link(3)))

&gt;&gt;&gt; duplicate_link(x, 5)

&gt;&gt;&gt; x

Link(5, Link(5, Link(4, Link(3))))

&gt;&gt;&gt; y = Link(2, Link(4, Link(6, Link(8))))

&gt;&gt;&gt; duplicate_link(y, 10)

&gt;&gt;&gt; y

Link(2, Link(4, Link(6, Link(8))))

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q duplicate_link

Q6: Mutable Mapping

Implement deep_map_mut(fn, link), which applies a function fn onto all elements in the given linked list lnk. If an element is itself a linked list, apply fn to each of its elements, and so on.

Your implementation should mutate the original linked list. Do not create any new linked lists.

s = Link(1, Link(2, Link(3, Link(4)))) isinstance(s, Link) True isinstance(s, int) False “`

Construct Check: The last doctest of this question ensures that you do not create new linked lists. If you are failing this doctest, ensure that you are not creating link lists by calling the constructor, i.e.

s = Link(1)

“`py def deep_map_mut(fn, lnk): “””Mutates a deep link lnk by replacing each item found with the result of calling fn on the item. Does NOT create new Links (so no use of Link’s constructor).

Does not return the modified Link object.

&gt;&gt;&gt; link1 = Link(3, Link(Link(4), Link(5, Link(6))))

&gt;&gt;&gt; # Disallow the use of making new Links before calling deep_map_mut

&gt;&gt;&gt; Link.__init__, hold = lambda *args: print(“Do not create any new Links.”), Link.__init__ &gt;&gt;&gt; try:

… deep_map_mut(lambda x: x * x, link1) … finally:

… Link.__init__ = hold

&gt;&gt;&gt; print(link1)

&lt;9 &lt;16&gt; 25 36&gt;

“””

“*** YOUR CODE HERE ***”

“`

Use Ok to test your code:

python3 ok -q deep_map_mut

Submit

Make sure to submit this assignment by running:

python3 ok –submit

Optional Questions

Homework assignments will also contain prior exam-level questions for you to take a look at. These questions have no submission component; feel free to attempt them if you’d like a challenge!

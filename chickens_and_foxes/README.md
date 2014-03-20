Chickens and foxes!
==================

In this tutorial you'll gain the power of Wildcard.

A Wildcard is a symbol which tells BASH that you want to match *any* character in a filename or path.

Use Wildcards to target your BASH magic at multiple files which match a simple pattern.

Your mission
============

Oh dear! The foxes have got in with the chickens, and that's never good news.

With the help of your BASH powers, your mission is to separate the Foxes into the Fox Den and the chickens into the Chicken Pen.

But, wait, you can't do them one at a time with:

    mv chicken.1 chicken_pen/

No, no, that wont do! The foxes will nab the other chickens before you know what's happened.

You need a little BASH magic!

Enter the Wildcard. *

    mv chicken.* chicken_pen/

So, what does this do?

Well, the Wildcard character, or asterisk ( * ), will tell BASH that you don't care what number, or letter for that matter, follows the dot in the filenames of your chickens. That means you've instructed it to move chicken.1, chicken.2 and, if it exists, even chicken.pie!

Real world uses
===============

Like me, you've probably got a messy Home directory. It's about time to clean up, no?

Perhaps you should make a Python folder and move all your .py files there!

    cd ~
    mkdir python
    mv *.py python
    ls python

If you had any .py files, you should now see them all nestled inside the new python folder.

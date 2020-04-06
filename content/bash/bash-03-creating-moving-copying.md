+++
title = "Creating, moving, copying"
slug = "bash-03-creating-moving-copying"
weight = 3
+++

## Creating things

<!-- ~~~ {.bash} -->
<!-- $ mkdir thesis -->
<!-- $ ls -F -->
<!-- $ ls -F thesis -->
<!-- $ cd thesis -->
<!-- $ nano draft.txt   # let's spend few minutes learning how to use nano; can also use other editors -->
<!-- $ ls -->
<!-- $ more draft.txt   # displays a file one page at a time -->
<!-- $ cd .. -->
<!-- $ rm thesis   # getting an error - why? -->
<!-- $ rmdir thesis   # again getting an error - why? -->
<!-- $ rm thesis/draft.txt -->
<!-- $ rmdir thesis -->
<!-- ~~~ -->

<!-- Also could do 'rm -r thesis' in lieu of the last two commands. -->

03-creating.mkv

## Moving and copying things

<!-- ~~~ {.bash} -->
<!-- $ mkdir thesis -->
<!-- $ nano thesis/draft.txt -->
<!-- $ ls thesis -->
<!-- $ mv thesis/draft.txt thesis/quotes.txt -->
<!-- $ ls thesis -->
<!-- $ mv thesis/quotes.txt .   # . stands for current directory -->
<!-- $ ls thesis -->
<!-- $ ls -->
<!-- $ ls quotes.txt -->
<!-- ~~~ -->

<!-- ~~~ {.bash} -->
<!-- $ cp quotes.txt thesis/quotations.txt -->
<!-- $ ls quotes.txt thesis/quotations.txt -->
<!-- $ rm quotes.txt -->
<!-- $ ls quotes.txt thesis/quotations.txt -->
<!-- ~~~ -->

<!-- More than two arguments to mv/cp: -->
<!-- ~~~ {.bash} -->
<!-- $ touch  intro.txt  methods.txt  index.txt   # create three empty files -->
<!-- $ ls -->
<!-- $ mv  intro.txt  methods.txt  index.txt  thesis   # the last argument is the destination directory -->
<!-- $ ls -->
<!-- $ ls thesis -->
<!-- ~~~ -->

<!-- > **Quiz 5:** Suppose that you created a .txt file in your current directory to contain a list of the -->
<!-- > statistical tests you will need to do to analyze your data, and named it: statstics.txt. After creating -->
<!-- > and saving this file you realize you misspelled the filename! You want to correct the mistake, which of -->
<!-- > the following commands could you use to do so? -->

<!-- > **Quiz 6:** What is the output of the closing `ls` command in the sequence shown below? -->

03-moving.mkv
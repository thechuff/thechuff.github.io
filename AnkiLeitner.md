# TheChuff: How to Use Anki as a Leitner Box Game

*What is [Anki](https://en.wikipedia.org/wiki/Anki_(software))?* -- *What is a [Leitner Box](https://en.wikipedia.org/wiki/Leitner_system)?*

---

*In February 2016 I wrote this article explaining how to change Anki's settings to make it into the classic [Leitner system](http://en.wikipedia.org/wiki/Leitner_system), with revisions every set number of days (1, 2, 4, 8...).*

---

If you want to set up Anki software as a classic [Leitner system/box game](http://fluent-forever.com/wp-content/uploads/2014/05/LeitnerSchedule.pdf) (PDF), follow the steps below to modify the settings.

![image-20260203154056481](C:\Users\chris\AppData\Roaming\Typora\typora-user-images\image-20260203154056481.png)

## What's the Leitner System?

Here's a short video explaining it:

https://youtu.be/33DIo8iU7ws

The **Leitner Box Game** is a paper-and-pen spaced repetition system from the 1970’s that preceded Anki. I first learned about it from its promotion by [Gabriel Wyner](https://fluent-forever.com/appendix3/#.VrZAJ5MrLow).

Now you can use it with **Anki**!

## How to Change Anki's Settings into a Leitner System

1. Go to **Decks** list. 
2. Enter **Settings** >> **Deck Options**.
   * <u>Note</u>: *Changing Deck Options could affect **multiple decks** in your Anki system. If you want to just test this system out, you should **Add** a new deck option so you don’t lose your previous options.*

3. In the **New Cards** tab, input these options:

> **Steps (in minutes):** 1440 2880 5760 11520 23040 46080 92160

This gives you 1, 2, 4, 8, 16, 32, and 64 days of interval for each “Box” of the Leitner Game. (So after the first time you get it right, it will be 2 days (2880 minutes) until you see it again, and so on.)

> **Easy interval:** 64 days

The only option for us, although to play the Leitner game, we will **avoid the Easy button**! I will explain further below.

4. In the **Reviews** tab, input these options:

> **Easy bonus:** 100%
>
> **Interval modifier:** 100%

* This disables Hard and Easy from doing anything

> **Maximum interval:** 64 days

5. In the **Lapses** tab, input these options:

> **Steps (in minutes):** 1440

* This brings missed cards back to level 1 (instead of doing a 1-minute or 10-minute “refresher”)

> **New interval:** 0%

* This prevents the Leitner schedule at the round numbers of days (e.g. 4, 16)

>  **Minimum interval:** 1 day

You can customize the remaining options to however you want to learn.

## Playing the Leitner Box Game on Anki

> ⚠️ When you play with your Leitner Box — Anki style — you want to only use **Again** or **Good** buttons. 

In our system, clicking **Again** brings the card back to Level 1 (daily review) and clicking **Good** progresses it forward one level (to be reviewed after 2 days, or 4, 8, etc.) This option is defaulted at Enter/Return when you review your cards so this is very nice.

The options for the card are:

* 1d (**Again**) (For missed cards)
* 2d (**Good**) (For correct cards)
* ~~2.1mo (**Easy**)~~

> ⚠️ DO NOT click the **Easy** button unless you want to progress a card all the way forward to 64 days (~2.1 months). (The **Easy** button *serves no purpose* in a strict Leitner Box game, since you wouldn’t move a card from any box to the final box unless you were moving it forward from the penultimate box, in which case you would just click **Good** to do that)
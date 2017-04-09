.. Qwerty documentation master file, created by
   sphinx-quickstart on Sun Apr  9 01:02:27 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Qwerty's documentation!
==================================

.. toctree::
   :maxdepth: 1
   :caption: Contents:


Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum


.. code-block:: python

    import random

    guesses_made = 0

    name = raw_input('Hello! What is your name?\n')

    number = random.randint(1, 20)
    print 'Well, {0}, I am thinking of a number between 1 and 20.'.format(name)

    while guesses_made < 6:

        guess = int(raw_input('Take a guess: '))

        guesses_made += 1

        if guess < number:
            print 'Your guess is too low.'

        if guess > number:
            print 'Your guess is too high.'

        if guess == number:
            break

    if guess == number:
        print 'Good job, {0}! You guessed my number in {1} guesses!'.format(name, guesses_made)
    else:
        print 'Nope. The number I was thinking of was {0}'.format(number)

CategoryDocumentation



Text 1
======

line 1
------
War and Peace (pre-reform Russian: Война́ и миръ; post-reform Russian: Война́ и мир, translit. Voyná i mir [vɐjˈna i ˈmʲir]) is a novel by the Russian author Leo Tolstoy, which is regarded as a central work of world literature and one of Tolstoy's finest literary achievements.[1][2][3]

line 2
------
The novel chronicles the history of the French invasion of Russia and the impact of the Napoleonic era on Tsarist society through the stories of five Russian aristocratic families. Portions of an earlier version, titled The Year 1805,[4] were serialized in The Russian Messenger from 1865 to 1867. The novel was first published in its entirety in 1869.[5] Newsweek in 2009 ranked it first in its Top 100 Books.[6] In 2007, Time magazine ranked War and Peace third in its poll of the 10 greatest books of all time while Anna Karenina was ranked first.[7]

line 3
------
Tolstoy said War and Peace is "not a novel, even less is it a poem, and still less a historical chronicle". Large sections, especially the later chapters, are a philosophical discussion rather than narrative.[8] Tolstoy also said that the best Russian literature does not conform to standards and hence hesitated to call War and Peace a novel. Instead, he regarded Anna Karenina as his first true novel. According to the Encyclopædia Britannica, "no single English novel attains the universality of Leo Tolstoy's War and Peace.



Text 2
======
War and Peace is perhaps best known as one of the longest novels ever written.[citation needed]

Tolstoy began writing War and Peace in the year that he finally married and settled down at his country estate. The first half of the book was written under the name "1805". During the writing of the second half, he read widely and acknowledged Schopenhauer as one of his main inspirations. However, Tolstoy developed his own views of history and the role of the individual within it.[10]

The first draft of the novel was completed in 1863. In 1865, the periodical Russkiy Vestnik (The Russian Messenger) published the first part of this draft under the title 1805 and published more the following year. Tolstoy was dissatisfied with this version, although he allowed several parts of it to be published with a different ending in 1867. He heavily rewrote the entire novel between 1866 and 1869.[5][10] Tolstoy's wife, Sophia Tolstaya, copied as many as seven separate complete manuscripts before Tolstoy considered it again ready for publication.[10] The version that was published in Russkiy Vestnik had a very different ending from the version eventually published under the title War and Peace in 1869. Russians who had read the serialized version were anxious to buy the complete novel, and it sold out almost immediately. The novel was translated almost immediately after publication into many other languages.[citation needed]

It is unknown why Tolstoy changed the name to War and Peace. He may have borrowed the title from the 1861 work of Pierre-Joseph Proudhon: La Guerre et la Paix ("The War and the Peace" in French).[4] The title may also be another reference to Titus, described as being a master of "war and peace" in The Twelve Caesars, written by Suetonius in 119 CE. The completed novel was then called Voyna i mir (Война и мир in new-style orthography; in English War and Peace).[citation needed]

The 1805 manuscript was re-edited and annotated in Russia in 1983 and since has been translated into English, German, French, Spanish, Dutch, Swedish, Finnish, Albanian, Korean, and Czech. The existence of so many versions make this work one of the best insights into the mental processes of a great novelist.[citation needed]

Tolstoy was instrumental in bringing a new kind of consciousness to the novel. His narrative structure is noted for its "god-like" ability to hover over and within events, but also in the way it swiftly and seamlessly portrayed a particular character's point of view. His use of visual detail is often cinematic in scope, using the literary equivalents of panning, wide shots and close-ups. These devices, while not exclusive to Tolstoy, are part of the new style of the novel that arose in the mid-19th century and of which Tolstoy proved himself a master.[11]

The standard Russian text of War and Peace is divided into four books (comprising fifteen parts) and an epilogue in two parts. Roughly the first half is concerned strictly with the fictional characters, whereas the latter parts, as well as the second part of the epilogue, increasingly consist of essays about the nature of war, power, history, and historiography. Tolstoy interspersed these essays into the story in a way that defies previous fictional convention. Certain abridged versions remove these essays entirely, while others, published even during Tolstoy's life, simply moved these essays into an appendix.[citation needed]




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

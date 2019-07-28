.. _recursive:


To start preparing for the midterm exams, you begin to review
the lectures with friends. For the more abstract concepts, you
take turns in explaining the principles in your own words and
with analogies. The next concept you tackle is *dateset nesting*.

"What I like about this nesting so much is that it is so easy
to understand and apply, but the more you think about it works,
the more mesmerizing it becomes.", your friend starts. "Some of
the things DataLad lets you do with nested datasets are brilliantly
convenient and feel absolutely natural. I've been using :term:`Git`
for years and I never realized that some of the features DataLad
brings to datasets are really handy -- and now I'm missing them
whenever I only use Git."

"What exactly do you mean by that? Git can have other Git
repositories within a Git repository, can't it?" another friend
enquires. "What does DataLad do in nested datasets that Git doesn't?"

"Well, for example *recursion*! All of the recursive operations
DataLad lets you do on datasets are unique to DataLad. Have you
ever tried any of the DataLad commands with the ``-r``/``--recursive``
option? It's really fascinating to see, to be honest."

Thinking about this question, you remember the recursive option
for :command:`datalad install`. A recursive install would not only
install the superdataset, but also all of the subdatasets. You
didn't yet realize that other commands have a ``--recursive``
option as well. Intrigued you ask: "What other commands have this
option? And... how does it work? I think I understand it for
:command:`datalad install`, but I can't think of any example
with :command:`datalad add` for example."



make an analogy about recursion. Matroska?

Which commands: unlock, install, clean, drop, get
-> explain the principles behind this
Imp
===

Imps are processes that serve their Daemons, whether it be watching their memory or monitoring their status.

Inspiration
-----------

Process monitoring frameworks are very large for the most part, and I want to see if I can do it better. Imps in mythology were the servants of Demons and Wizards, making it a nice play on terminology. The irony is not lost on me that they tend to cause mischief and chaos wherever they go. We'll call those Beta and Alpha imps.

What do you want it to do?
--------------------------

I want a simple and robust framework for making sure daemonized processes stay in check, whether that be memory leaks or otherwise. As I've mentioned, most tools I've seen for this job are monolithic and rather cumbersome. I want to make something simple that does the job it needs to.

Concepts
--------

Every Daemon has multiple Imps serving it. Each imp is given one specific task, and only one. Imps can be grouped into clusters, and combined much in the same way my other application Mime can stack its files. Groups of imps can be assigned to a daemon just the same as a single imp, giving a lot of flexibility.

Consider an imp like a cleaner that watches after processes and makes sure they behave and are well fed so to speak.

Purpose
-------

I've noticed that I don't have a particular strength in deep sysinternals, something I need to remedy to grow in my Ops skills. The best way to grow is to build and create something that you're fully aware that you're weak in. In this case, low level Unix internals and some C code. 

Actually, let's forego the C and see what we can do with Common LISP on this one.


Glossary of Parsl Terms
=======================

This glossary defines terms based on their usage within Parsl. By defining our terminology, we hope to create understanding across our community and reduce confusion. When asking for or providing support to fellow Parsl users, please use these terms as defined.

Our glossary is organized alphabetically by the English alphabet. Feel free to contribute terms and definitions to this list that will benefit Parsl users.

.. glossary::

1. App
-------
In Parsl, an app is like a small, self-contained program that does a specific job. It's a piece of code, like a Python function or a Bash script, that you can run separately from your main program. Think of it as a mini-tool within your larger toolbox. [#app]_

.. [#app] "App" - A small, self-contained program in Parsl.

2. AppFuture
-------------
An AppFuture is like a placeholder for the result of an app that's running in the background. It's like a ticket you get when you order food at a restaurant – you get the ticket right away, but you have to wait for the food to be ready. Similarly, you get an AppFuture immediately when you start an app, but you have to wait for the app to finish before you can see the results. [#appfuture]_

.. [#appfuture] "AppFuture" - A placeholder for the result of an app running in the background.

3. Bash App
------------
A Bash app is a special kind of app in Parsl that lets you run commands from your computer's terminal (like the ones you type in the command prompt or shell). It's a way to use Parsl to automate tasks that you would normally do manually in the terminal. [#bashapp]_

.. [#bashapp] "Bash App" - An app in Parsl that runs terminal commands.

4. Block
---------
A block is like a group of computers loaned to you for doing work. Parsl will manage passing out work to each of them to do. This way, you can get your work done faster by using multiple computers at the same time. [#block]_

.. [#block] "Block" - A group of computers managed by Parsl.

5. Checkpointing
-----------------
Checkpointing is like saving your progress in a video game. If something goes wrong, you can restart from the last saved point instead of starting all over again. In Parsl, checkpointing lets you save the state of your work so that you can resume it later if there's an interruption. [#checkpointing]_

.. [#checkpointing] "Checkpointing" - Saving progress to resume work later.

6. Concurrency
---------------
Concurrency means doing multiple things at the same time. In Parsl, it means that your apps can run simultaneously, even if they're not on the same computer. This can make your programs run much faster. [#concurrency]_

.. [#concurrency] "Concurrency" - Running multiple tasks simultaneously.

7. Configuration
-----------------
Configuration is like setting up the rules for how Parsl should work. It's like adjusting the settings on your phone – you can choose how you want things to look and behave. In Parsl, you can configure things like how many computers to use, where to store data, and how to handle errors. [#configuration]_

.. [#configuration] "Configuration" - Setting up the rules for how Parsl should work.

8. DataFuture
--------------
A DataFuture is like a placeholder for a file that an app is creating. It's like a receipt for a package you're expecting – you get the receipt right away, but you have to wait for the package to arrive. Similarly, you get a DataFuture immediately when an app starts creating a file, but you have to wait for the file to be finished before you can use it. [#datafuture]_

.. [#datafuture] "DataFuture" - A placeholder for a file being created by an app.

9. DataFlowKernel (DFK)
------------------------
The DataFlowKernel is like the brain of Parsl. It's the part that controls how your apps run and how they share information. It's like the conductor of an orchestra, making sure that all the musicians play together in harmony. [#dfk]_

.. [#dfk] "DataFlowKernel (DFK)" - The brain of Parsl, controlling app execution.

10. Elasticity
---------------
Elasticity means being able to stretch or shrink. In Parsl, it means that you can easily add or remove blocks of computers as needed. This is useful if your workload changes – you can use more computers when you have a lot of work to do and fewer computers when you don't. [#elasticity]_

.. [#elasticity] "Elasticity" - Adjusting the number of computers used in Parsl.

11. Execution Provider
-----------------------
An execution provider is like a bridge between Parsl and the computers you want to use. It's the part that knows how to talk to different types of computers, like your laptop, a cluster, or a cloud service. [#executionprovider]_

.. [#executionprovider] "Execution Provider" - A bridge between Parsl and the computers.

12. Executor
-------------
An executor is like a manager for your apps. It's the part that decides which app should run on which computer and when. It's like a traffic controller, directing the flow of apps to make sure they all get where they need to go. [#executor]_

.. [#executor] "Executor" - Manages which app runs on which computer and when.

13. Future
-----------
A future is a placeholder for the result of a task that hasn't finished yet. Both AppFuture and DataFuture are types of Futures. You can use the `.result()` method to get the actual result when it's ready. [#future]_

.. [#future] "Future" - A placeholder for the result of a task that hasn't finished yet.

14. Launcher
--------------
A launcher is like a starter for your apps. It's the part that actually starts the apps running on the computers. It's like a coach telling the athletes when to start running. [#launcher]_

.. [#launcher] "Launcher" - Starts the apps running on the computers.

15. Memoization
-----------------
Memoization is like remembering something so you don't have to do it again. In Parsl, it means that if you run an app with the same inputs multiple times, Parsl will remember the result from the first time and give it to you again instead of running the app again. This can save a lot of time. [#memoization]_

.. [#memoization] "Memoization" - Remembering results to avoid rerunning apps.

16. MPI App
-------------
An MPI app is a special kind of app that uses a technology called Message Passing Interface (MPI) to communicate between different computers. It's like a walkie-talkie that lets different apps talk to each other. [#mpiapp]_

.. [#mpiapp] "MPI App" - An app that uses MPI to communicate between computers.

17. Parallelism
-----------------
Parallelism means doing multiple things at the same time. In Parsl, it means that your apps can run simultaneously on different computers. This can make your programs run much faster. [#parallelism]_

.. [#parallelism] "Parallelism" - Running apps simultaneously on different computers.

18. Parsl Script
------------------
A Parsl script is a file that contains the instructions for how to run your apps in parallel. It's like a recipe that tells you what ingredients to use and how to combine them. [#parslscript]_

.. [#parslscript] "Parsl Script" - A file containing instructions for running apps in parallel.

19. Plugin
------------
A plugin is like an add-on for Parsl. It's a piece of code that you can add to Parsl to give it new features or change how it works. It's like an extra tool that you can add to your toolbox. [#plugin]_

.. [#plugin] "Plugin" - An add-on for Parsl that adds features or changes functionality.

20. Python App
----------------
A Python app is a special kind of app in Parsl that's written in the Python programming language. It's a way to use Parsl to run your Python code in parallel. [#pythonapp]_

.. [#pythonapp] "Python App" - An app in Parsl written in Python.

21. Serialization
-------------------
Serialization is like packing your belongings into a suitcase so you can take them on a trip. In Parsl, it means converting your data into a format that can be sent over a network to another computer. [#serialization]_

.. [#serialization] "Serialization" - Converting data to a format for sending over a network.

22. Staging
--------------
Staging is like setting the stage for a play. In Parsl, it means preparing the data that your apps need before they start running. This can involve things like copying files to the right location or converting them into the right format. [#staging]_

.. [#staging] "Staging" - Preparing data for apps before they run.

23. Thread
------------
A thread is like a smaller part of a program that can run independently. It's like a worker in a factory who can do their job at the same time as other workers. [#thread]_

.. [#thread] "Thread" - A smaller part of a program that can run independently.

24. Workflow
--------------
A workflow is like a series of steps that you follow to complete a task. In Parsl, it's a way to describe how your apps should run and how they depend on each other. It's like a flowchart that shows you the order in which things need to happen. [#workflow]_

.. [#workflow] "Workflow" - A series of steps describing how apps should

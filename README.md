# os-project
Introducing our multi-tasking software project, where we've crafted fifteen different tasks ranging from a calculator to games like Tic Tac Toe. The unique aspect of our software is its ability to utilize different system calls to open each task in separate terminals on Ubuntu.

Efficient Resource Management:
Our software is designed to be resource-savvy. If there's enough RAM available, tasks run smoothly. However, if RAM is limited, we've implemented a waiting list. This means if a task can't run due to insufficient space, it patiently waits in line until RAM becomes available.

First In, First Out (FIFO) Approach:
To ensure fairness, we've adopted a "first come, first served" approach. The waiting list operates on a first in, first out (FIFO) basis. Tasks patiently queue up, and as soon as there's enough RAM, the oldest task in the waiting list gets the green light to execute.

Parallel Task Execution:
Our software promotes parallel task execution, allowing you to juggle multiple tasks simultaneously. Whether you're crunching numbers with the calculator, planning events with the calendar, or engaging in a game of Tic Tac Toe, our software optimizes system calls to keep things running smoothly.

User-Friendly Interface:
The interface is straightforward and user-friendly. Each task opens in its own terminal window, providing a seamless experience. If there's a delay due to limited RAM, you'll be informed, and the software will automatically prioritize tasks based on the FIFO principle.

In a nutshell, our software is your go-to solution for multitasking on Ubuntu. It intelligently manages resources, employs a fair waiting list system, and ensures a smooth parallel execution of tasks. Whether you're a tech enthusiast or a casual user, our project aims to provide a hassle-free and efficient multitasking experience.

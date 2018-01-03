# Personal
Fork/Join

用于多线程并发编程,需要注意的是,不可用 subtask.fork(),这样会把任务交给一个新线程,而当前线程会空闲, 需要用invokeAll(subtask1,subtask
2)来调用,这样会让当前线程也参与工作

---
title: "Learning Operating System"
description : "MIT 6.S081"
date: 2022-12-04T14:32:44+08:00
draft: true
---

# Operation System

## Lecture 1
---

### OS purposes:
- abstract hardware
- multiplex
- isolation
- sharing
- security
- performance
- range of uses

### OS ORG
```
+-----------------------------------------------+
|                                               |
|      +------+      +------+                   |
|      |  VI  |      |  SH  |                   |
|      +------+      +------+                   |
|                                     userspace |
+-----------------------------------------------+
|                PROCESS                        |
|      +------+  MEM ALLOC             kernel   |
|      |  FS  |  ACCESS CTL                     |
|      +------+                                 |
|                                               |
|                                               |
|                                               |
+-----------------------------------------------+

   CPU       MEMORY         DISK        NETWORK
```

### API kernel
- file
fd: file descriptor
```
fd = open("out", 1)
write(fd, "hello\n", 6)
```

- fork
```
pid = fork()
```

### why hard/interesting
- unforgiving
- tensions
    efficientt - abstract
    powerful - simple API
    flexible - secure

### syatem call VS function call
 



## Lecture 2
---

### Isolation

1.Unix interface: abstract the hareware resources
process <--> cpu
exec <--> memory
file <--> disk block

2.**OS should be deefensive**
- app cannot crash the OS 
- app cannot break out of isolation

=> Strong isolation between apps and OS
typically Hardware support:
{user/kernel mode}
{vitrual memory}

### kernel /user mode

kernel: privileged instructions
    set page table register/ disable clock interrupts/ 

user: unprivileged instructions
    add/sub/


### CPU provide virtual memory
page table: virtual address -> physical
process : hardware own page table
memory isolation


### enttering kernel
user use ecall (system_call_number) to make system calls

Kernel is trusted computing base(TCB)
- kernel must have no bug
- kernel must treat process as malicious

=>security

monolithic kernel design: whole OS run in kernel mode
micro kernel design: necessary part of OS run in kernel mode


## Lecture 3
---

## Lecture 4
---

## Lecture 5
---

## Lecture 6
---


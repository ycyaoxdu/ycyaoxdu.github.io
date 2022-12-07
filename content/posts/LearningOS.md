---
title: "Learning Operating System"
description = "MIT 6.S081"
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

## Lecture 3
---

## Lecture 4
---

## Lecture 5
---

## Lecture 6
---


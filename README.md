thread.c
========

一个线程创建的简单实例

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <sys/types.h>
#include <unistd.h>
#include <pthread.h>

typedef unsigned long u32;
pthread_t ntid; /*线程标识符*/


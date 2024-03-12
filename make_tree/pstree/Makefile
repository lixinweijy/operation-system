NAME := $(shell basename $(CURDIR))

print_name:
	@echo $(NAME)

export MODULE := M1

all: $(NAME)-64 $(NAME)-32

#生成 pstree-64   pstree-32
include ../Makefile

# $Id: Makefile 241205 2011-02-17 21:57:41Z $

CFG_MLONG64 ?= 1
CFG_LITTLE ?= 1
CFG_RELOC ?= 0
CFG_UNCACHED ?= 0
CFG_VAPI ?= 1
CFG_BOOTRAM ?= 0
CFG_PCI ?= 0

include ../pt1120/Makefile

VPATH += ../pt1120
CFLAGS += -I../pt1120

# disable most devices, console on Prom-ICE
CFLAGS += -D_PT1120_DIAG_CFG_ -DCFG_DRAM_ECC=0

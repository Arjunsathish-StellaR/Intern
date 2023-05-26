SIM ?= icarus
TOPLEVEL_LANG ?= verilog
VERILOG_SOURCES += $(PWD)/../HDL/dut.v
or:
    $(MAKE) sim MODULE=or_test TOPLEVEL=or_gate
include $(shell cocotb-config --makefile)/Makefile.sim

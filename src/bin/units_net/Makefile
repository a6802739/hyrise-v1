hyr-units-net := $(realpath $(dir $(lastword $(MAKEFILE_LIST))))

include $(hyr-units-net)/../../../rules.mk

include $(PROJECT_ROOT)/src/lib/net/Makefile
include $(PROJECT_ROOT)/third_party/gtest/Makefile

hyr-units-net.binname := units-net
hyr-units-net.deps := hyr-net gtest hyr-access
$(eval $(call test-binary,hyr-units-net))

thisdir = class/System.Data.Linq
SUBDIRS = 
include ../../build/rules.make

LIBRARY = System.Data.Linq.dll
LIB_REFS = System System.Core System.Data System.Transactions System.Xml
LIB_MCS_FLAGS =

NO_TEST = yes

ifeq (2.0, $(FRAMEWORK_VERSION))
# This is a .NET 3.5 only assembly, but built during the 2.0 build
LIB_MCS_FLAGS += -d:NET_3_5
endif

include ../../build/library.make

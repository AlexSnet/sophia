LIBSY_O = sy.o
LIBSY_OBJECTS = $(addprefix repository/, $(LIBSY_O))
OBJECTS = $(LIBSY_O)
ifndef buildworld
  include ../mk/sophia
  include ../mk/component
endif

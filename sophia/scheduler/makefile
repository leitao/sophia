LIBSC_O = sc_worker.o sc.o sc_step.o sc_ctl.o sc_backup.o sc_read.o sc_write.o
LIBSC_OBJECTS = $(addprefix scheduler/, $(LIBSC_O))
OBJECTS = $(LIBSC_O)
ifndef buildworld
  include ../mk/sophia
  include ../mk/component
endif

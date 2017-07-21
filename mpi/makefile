EXECS=mpi_hello_world
MPICC=/usr/local/bin/mpicc

all: ${EXECS}

mpi_hello_world: mpi_hello_world.c
	${MPICC} -o mpi_hello_world mpi_hello_world.c

clean:
	rm ${EXECS}

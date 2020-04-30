all: iterator.exe vec1.exe

.cpp.exe:
	bcc -D__MINMAX_DEFINED -IC:\bc45\stl $<

clean:
	del *.exe
	del *.obj

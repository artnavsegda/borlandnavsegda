all: size.exe max_size.exe push_bk.exe

.cpp.exe:
	bcc -D__MINMAX_DEFINED -IC:\bc4\stl $<

clean:
	del *.exe
	del *.obj

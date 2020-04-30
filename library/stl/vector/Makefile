all: size.exe push_bk.exe element.exe max_size.exe pop_back.exe insert.exe eras.exe

.cpp.exe:
	bcc -D__MINMAX_DEFINED -IC:\bc45\stl $<

clean:
	del *.exe
	del *.obj

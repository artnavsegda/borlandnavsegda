all: construc.exe empty.exe pop.exe push.exe size.exe top.exe

.cpp.exe:
	bcc -D__MINMAX_DEFINED -IC:\bc45\stl $<

clean:
	del *.exe
	del *.obj

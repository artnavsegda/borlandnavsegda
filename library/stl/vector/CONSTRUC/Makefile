all: empty.exe fill.exe copy.exe pointer.exe range.exe

.cpp.exe:
	bcc -D__MINMAX_DEFINED -IC:\bc4\stl $<

clean:
	del *.exe
	del *.obj

all: hello.exe

.cpp.exe:
	bcc -ml -Ic:\bc45\include\tvision -Lc:\bc45\lib $< tv.lib

clean:
	del *.exe
	del *.obj

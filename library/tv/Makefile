all: hello.exe

.cpp.exe:
	bcc -ml -Ic:\borlandc\tvision\include -Lc:\borlandc\tvision\lib $< tv.lib

clean:
	del *.exe
	del *.obj

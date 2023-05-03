| PATTERN | EXPLANATION/MATCHES | EXAMPLE |
| -------- | -------- | -------- |
| file.txt | All files with file.txt will be ignored | file.txt |
| DS_Store | This pattern will ignore the .DS_Store file that is created by macOS| '.DS_Store'|
| *.pyc |This pattern will ignore all compiled Python files, which have a .pyc extension| 'example.pyc' |
| *.txt | ignores all files that end with .txt extension or the specified extension |samp.txt, file1.txt, file2.txt, example.txt will all be ignored |
| .idea/ | This pattern will ignore the .idea directory that is used by IntelliJ IDEA.  |  '.idea/'|
| *.class | This pattern will ignore all compiled Java class files| 'Example.class' |
|*.pyo  | This pattern will ignore all optimized Python files, which have a .pyo extension | example.pyo |
| **| Matches directories and their sub-directories | to ignore files with '.tmp' extension in any directory, we will use **/*.tmp |
| *.log| This pattern will ignore all files with the .log extension  | debug.log and error.log will be ignored. 
| Lines starting with a # symbol| These lines are comments and will be ignored by git | # this is a gitignore file |
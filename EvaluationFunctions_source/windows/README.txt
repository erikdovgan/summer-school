# COMPILE - WINDOWS 

g++ -c EvaluationFunctions.cpp
g++ -shared -o EvaluationFunctions.dll EvaluationFunctions.o -Wl,--out-implib,libexample_dll.a
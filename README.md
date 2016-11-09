# vhdl-fuzzer
Generates random VHDL files for fuzzing VHDL compiler/parsers


## To use

Build GramTest  and create gramtest.jar using maven

    cd gramtest && mvn compile
    
Run fuzzer

    java -jar gramtest.jar -file vhdl.bnf
   

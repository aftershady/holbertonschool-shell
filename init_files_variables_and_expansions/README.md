this directory contain executable script :

0-alias : alias ls="rm *"
1-hello_you : echo "hello $USER"
2-path : PATH=$PATH:/action
3-paths : echo $PATH | tr -s ':' '\n' | wc -l
4-global_variables : printenv
5-local_variables : set
6-create_local_variable : BEST="School"
7-create_global_variable : export BEST="School"
8-true_knowledge : echo $((128+$TRUEKNOWLEDGE))
9-divide_and_rule : echo $((POWER/DIVIDE))
10-love_exponent_breath : echo $((BREATH ** LOVE))
11-binary_to_decimal : echo $((2#$BINARY))
12-combinations : echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"
13-print_float : echo $(printf "%.2f" "$NUM")
14-decimal_to_hexadecimal : printf '%X\n' $DECIMAL 

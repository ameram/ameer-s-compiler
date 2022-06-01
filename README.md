# super-duper-octo-enigma

I ran this using docker with ubuntu image, you also need to install flex, gcc, clang, and git to run this.

Run Steps:
* lex clac.l
* yacc -d calc.y
*  ```gcc lex.yy.c y.tab.c -o WANTED_APP_NAME```
crun:
	leg -o compiler.c ./compiler.leg
	gcc -o compiler compiler.c 

wrun:
	emcc compiler.c -o compiler.js -sEXPORTED_FUNCTIONS=_store,_get_result,_free -sEXPORTED_RUNTIME_METHODS=ccall,allocateUTF8 -sEXIT_RUNTIME=1
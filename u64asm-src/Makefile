all: u64asm

OBJS = about.h asm.h crc.h defines.h drjr.h err.h exp.h opcode.h pre.h symbols.h

u64asm: $(OBJS)
	$(CXX) -o u64asm n64.cpp

clean:
	rm -f u64asm

# Assembly Lab update log

## v2.2: Verified lessons, clearer help, time-travel debugging
- Self-test: every lesson solution was run through the simulator on all five architectures (143 of 143 pass), and no starter code passes by accident.
- Fixed a bug found by the self-test: on x86-64, byte reads and writes could corrupt text longer than seven characters. The Reading input and Shout capstone lessons now work correctly.
- Rewrote the explanations of the 13 early lessons (registers through factorial) in plainer language.
- Rewrote the last hint level for every lesson so it uses your real register names and no jargon.
- New Back button steps the program backwards one instruction at a time (up to 3000 steps). Alt+Left goes back and Alt+Right steps forward.
- New breakpoints box: type line numbers, and Run or Play pauses just before that line.
- New watch box: list registers or [addresses], and Run or Play pauses when one changes, telling you the old value, the new value and the line. Watched registers get a dashed outline.
- The "next" bar now shows the line number of the next instruction.

## v2.1: Reset buttons and detailed hints
- Restart project button in the sidebar. It changes to "You finished!" once every lesson on an architecture is done.
- Reset this architecture only, and Reset all progress (settings are kept). Both need two clicks.
- Hints now have three levels: what the lesson asks in plain words, a numbered plan with the instructions you will use, and a near-answer.

## v2.0: Offline file and real assembler
- Everything ships as one HTML file with no internet needed.
- New Assemble button produces real machine code for x86, x86-64, ARM, MIPS and PowerPC, with addresses, labels, endianness, Copy hex and Download .bin.
- 51 encodings were checked against known-correct machine code.

## v1.9: Progress and options
- Progress dashboard: rank, XP, streak, first-try count and a bar per architecture.
- Code autosave per lesson, Starter code button, export, import and backup.
- Play mode with speed setting, plain-English explanation of the next instruction, theme, text size and hex or decimal registers.
- New lesson: Capstone: count to five.

## v1.8: Input
- Console input box and the read system call.
- New lessons: Reading input, Capstone: shout.

## v1.7: System calls and debugging
- Console panel and the exit and write system calls with each architecture's real numbers.
- New lessons: System calls: exit, Hello world.
- New Debugging level with four bug hunts, plus the Trace button.

## v1.6: Bytes, strings and stack frames
- Byte-level memory with endianness (x86, x86-64 and ARM little-endian; MIPS and PowerPC big-endian).
- New lessons: Bytes and endianness, Strings, Nested calls, Recursion and stack frames.

## v1.5: Zero to one
- Basics level with reading lessons and a number converter.
- New lessons: Negative numbers, Even or odd, Fibonacci, Greatest common divisor, Playground.
- Instruction Reference and the road-to-pro lesson.

## v1.4: Compare and architecture lessons
- Compare syntaxes shows one solution in all five architectures.
- New lessons: ARM conditional execution, x86 scaled addressing.

## v1.3: Five architectures
- x86, x86-64, ARM, MIPS and PowerPC, each with its own syntax, registers and rules.

## v1.0: First release
- Four levels (Noob, Beginner, Intermediate, Pro), 11 lessons, an in-browser x86-style simulator, clean light and dark interface.

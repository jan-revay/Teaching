# ARM

https://en.wikipedia.org/wiki/ARM_architecture_family

## Online video courses

* [freecodecamp.org course on ARM assembly language programming](https://youtu.be/gfmRrPjnEw4?si=L-u9Ivvs4pxhOklY)
* [LaurieWired](https://youtube.com/playlist?list=PLn_It163He32Ujm-l_czgEBhbJjOUgFhg&si=f-D8VZnF9Az6Y4Xd)

## Online courses (no video)

* https://azeria-labs.com/writing-arm-assembly-part-1/


## Blogs

### Series by Raymond Chen
* https://devblogs.microsoft.com/oldnewthing/20210531-00/?p=105265
* https://devblogs.microsoft.com/oldnewthing/20210601-00/?p=105267
* https://devblogs.microsoft.com/oldnewthing/20210602-00/?p=105271
* https://devblogs.microsoft.com/oldnewthing/20210603-00/?p=105276
* https://devblogs.microsoft.com/oldnewthing/20210604-00/?p=105280
* https://devblogs.microsoft.com/oldnewthing/20210607-00/?p=105288
* https://devblogs.microsoft.com/oldnewthing/20210608-00/?p=105290
* https://devblogs.microsoft.com/oldnewthing/20210609-00/?p=105293
* https://devblogs.microsoft.com/oldnewthing/20210610-00/?p=105295
* https://devblogs.microsoft.com/oldnewthing/20210611-00/?p=105299
* https://devblogs.microsoft.com/oldnewthing/20210614-00/?p=105307
* https://devblogs.microsoft.com/oldnewthing/20210615-00/?p=105311
* https://devblogs.microsoft.com/oldnewthing/20210616-00/?p=105314
* https://devblogs.microsoft.com/oldnewthing/20210617-00/?p=105317
* https://devblogs.microsoft.com/oldnewthing/20210618-00/?p=105324
* https://devblogs.microsoft.com/oldnewthing/20210621-00/?p=105327
* https://devblogs.microsoft.com/oldnewthing/20210622-00/?p=105332
* https://devblogs.microsoft.com/oldnewthing/20210623-00/?p=105351
* https://devblogs.microsoft.com/oldnewthing/20210624-46/?p=105355
* https://devblogs.microsoft.com/oldnewthing/20210625-00/?p=105369

### Thumb2 vs. ARM encodings

* https://copyprogramming.com/howto/jump-between-thumb-and-arm?utm_content=cmp-true

### ISA specificity

* https://superuser.com/questions/1754983/is-the-arm-instruction-set-the-same-for-all-arm-processors

## VisUAL and VisUAL2 emulator

* https://scc416.github.io/Visual2-doc/
* https://github.com/tomcl/visual2.github.io
* https://salmanarif.bitbucket.io/visual/
* https://salmanarif.bitbucket.io/visual/supported_instructions.html
* https://developer.arm.com/documentation/dui0552/a/BABCAEDD
* https://developer.arm.com/documentation/dui0552/a/the-cortex-m3-instruction-set/instruction-set-summary?lang=en
* https://developer.arm.com/documentation/dui0552/a/BABEHFEF
* https://developer.arm.com/documentation/dui0552/a/CIHFDDHB#CIHEBCBI

## Lecture notes

* https://profile.iiita.ac.in/bibhas.ghoshal/COA_2021/lecture_slides/arm_inst.pdf

## Advanced

* https://youtu.be/3ixTKrE8lv8?si=qUobO-OzHEfpImvC
* [Paging in ARM](https://youtu.be/IJEiiByY0uI?si=1n00UlktJFSB4Abf)
* [Thumb state](https://youtu.be/XbVONAOYKTw?si=hK_g3tlFmGjL5NLI)
* [Engineering Funda](https://youtube.com/playlist?list=PLgwJf8NK-2e7nFEozQhZDZDSm09SwqbGP&si=F_y4U6JuxcikrJgl)
* [The ARM University Program, ARM Architecture Fundamentals](https://youtu.be/7LqPJGnBPMM?si=4NCrJMGu6fc9abjp)
* [Rosetta stone method for learning assembly](https://youtu.be/vhyettT7sdA?si=bMD7zLJc5ZTIX-q-)
* [Linux syscalls](https://man7.org/linux/man-pages/man2/syscalls.2.html)
* https://en.wikipedia.org/wiki/Relocation_(computing)

## Basics

* https://en.wikipedia.org/wiki/Endianness
* https://simple.m.wikipedia.org/wiki/File:ASCII-Table-wide.svg

## Object file

* https://en.wikipedia.org/wiki/Object_file
* https://en.wikipedia.org/wiki/Code_segment
* https://en.wikipedia.org/wiki/Data_segment
* https://en.wikipedia.org/wiki/.bss
* https://en.wikipedia.org/wiki/Loader_(computing)
* https://en.wikipedia.org/wiki/Dynamic_linker
* https://en.wikipedia.org/wiki/Linker_(computing)
* https://en.wikipedia.org/wiki/Stack-based_memory_allocation (advanced, optional reading)

## Compiler explorer

* https://godbolt.org/
* [example simple character search algorithm](https://godbolt.org/#g:!((g:!((g:!((h:codeEditor,i:(filename:'1',fontScale:14,fontUsePx:'0',j:1,lang:c%2B%2B,selection:(endColumn:2,endLineNumber:10,positionColumn:2,positionLineNumber:10,selectionStartColumn:2,selectionStartLineNumber:10,startColumn:2,startLineNumber:10),source:'//+Type+your+code+here,+or+load+an+example.%0Aint+find(int*+list,+int+len,+int+needle)+%7B%0A++++for(int+i+%3D+len+-+1%3B+i+%3E%3D+0%3B+i--)%0A++++%7B%0A++++++++if(list%5Bi%5D+%3D%3D+needle)%0A++++++++++++return+i%3B%0A++++%7D%0A%0A++++return+-1%3B%0A%7D'),l:'5',n:'0',o:'C%2B%2B+source+%231',t:'0')),k:50,l:'4',n:'0',o:'',s:0,t:'0'),(g:!((h:compiler,i:(compiler:armgtrunk,filters:(b:'0',binary:'1',binaryObject:'0',commentOnly:'0',debugCalls:'1',demangle:'0',directives:'0',execute:'1',intel:'0',libraryCode:'0',trim:'1'),flagsViewOpen:'1',fontScale:14,fontUsePx:'0',j:1,lang:c%2B%2B,libs:!(),options:'-O3',overrides:!(),selection:(endColumn:1,endLineNumber:1,positionColumn:1,positionLineNumber:1,selectionStartColumn:1,selectionStartLineNumber:1,startColumn:1,startLineNumber:1),source:1),l:'5',n:'0',o:'+ARM+GCC+trunk+(Editor+%231)',t:'0')),k:50,l:'4',n:'0',o:'',s:0,t:'0')),l:'2',n:'0',o:'',t:'0')),version:4)

## ARM datasheets

* <https://github.com/jan-revay/Teaching/tree/main/Assembler%20programming/Datasheets>

## Books

* [Modern Arm Assembly Language Programming: Covers Armv8-A 32-bit, 64-bit, and SIMD 1st ed. Edition by Daniel Kusswurm](https://www.amazon.com/Modern-Assembly-Language-Programming-Armv8/dp/1484262662)

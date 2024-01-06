# CPU architecture (beginner materials)

## Video courses

1. [Crash course on computing, videos #1 to #21](https://youtube.com/playlist?list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo&si=g7C1SamcjVqkt9vH)
2. [Ben Eater - Building an 8-bit breadboard computer! - videos](https://youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU&si=qTbTygQdp7m_kmk0)
3. [Ben Eater - Building an 8-bit breadboard computer! - web](https://eater.net/8bit)

## Emulators

1. [Johnny assembler](https://dev.inf-schule.de/content/12_rechner/4_johnny/johnny3/)
2. <https://www.inf-schule.de/rechner/johnny>
3. [www.inf-schule.de/ - How a computer works](https://www.inf-schule.de/rechner)

## Exercises

### Memory addressing

1. In writing and pictures explain to me, how reading from RAM and writing to RAM works (using the schematic we used
   on our lesson - TODO add here). Then explain how the same mechanism works in Johnny emulator and ARM.
2. What is a word size and address space of the Johnny computer/ARM32 cpu. Why?
3. Basic calculations with CPU freq. and memory access times. E.g. memory has a frequency 2000MHz and it takes 50 cycles
   to fetch a new byte from the memory. How long does it take in seconds? (yes some fellas have problem with such a simple stuff)
4. What does LSB and msb mean? What is little-Endianness, what is big-Endianness?
5. What is label in assembler, are labels necessary or they are just a syntactic sugar, why?
6. Why do we need cpu registers? Can't we just use ram to store everything?
7. What is the electrical structure of DRAM cell? How does it work? What is the electrical structure of SRAM cell? How does it work? Where is SRAM resp. DRAM used in moder computers?
8. What is a memory timing?
9. https://www.inf-schule.de/rechner/johnny/spruenge/uebungen
10. https://www.inf-schule.de/rechner/johnny/zusatzmaterial/exkurs_selbstmodifikation
11. https://www.inf-schule.de/rechner/johnny/zusatzmaterial/exkurs_eigene_makrobefehle
12. What is MAR and MBR in Johnny? What are MAR and MBR in ARM?

### Assmbler coding

1. sum() - write an accumulate of an array wrt. +
2. Write a algorithm that finds a given value in an array.
3. Write a bubble sort algorithm in ARM32 assembler.
4. Write a strcmp() algorithm in ARM32 assembler.
5. Write a memcpy()
6. Other [cstring](https://cplusplus.com/reference/cstring/) functions...
7. Write a simple string find algorithm in ARM32 assembler.
8. Write an array order reversal algorithm in ARM32 assembler.
9. String replace
10. strstr()
11. strtoi()
12. remove_if() for an array
13. is_sorted()
14. min()/max()

## Additional resources

* <https://www.reddit.com/r/beneater/comments/ii113p/helpful_tips_and_recommendations_for_ben_eaters/>
* <https://www.instructables.com/Making-an-8-Bit-Computer/>

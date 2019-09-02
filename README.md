# cyclicGen
cyclic pattern generator and offset calculator for buffer overflow exploits.

I had actually developed this before I knew that metasploit had the commonly used pattern_create.rb and pattern_offset.rb, but it ended up being a fun learning experience to develop my own version :).

## Usage
./cyclicGen 
Description: A cyclic pattern generator that will allow user to find offset of the return EIP address when performing a buffer overflow

usage: 
        cyclicGen gen [pattern_length]          Generate a pattern of a given length (default=200)
        cyclicGen off  address                  Give the offset of the EIP based on the segfault address

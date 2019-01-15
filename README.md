# my-gnuradio-decoders
gnuradio decoders made by me

## ASK decoder
+ file: ask.grc
+ usage: modify "Wav File Source" block (input), and "File Sink" block (output).
Output data is a binary file, use commands like
`hexdump foo.bin -e '/1 "%1d"' -v`
to get a string output.



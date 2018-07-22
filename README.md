# NEOGEO

To run 'Hello World' on a NEOGEO.
Use/download the Super Sidekicks rom set.
Download the assembler ASW aswcurr.zip and Flip_pad.zip

asw filename -L -quiet

p2bin filename -r $ $000000-$01FFFF

flip filename.bin 052-p1.p1

pad 052-p1.p1 524288 255

Replace the old 052-p1.p1 with then new one in the roms directory and run MAME

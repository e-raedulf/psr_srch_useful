# psr_srch_useful
Little useful progs relating to pulsar searching

                                  generate_header.c

Convert an ascii sigproc filterbank header into binary format. This can then be combined
with headerless filterbank format data. 

Compile: gcc -lm generate_header.c -o generate_header

Usage: ./generate_header ascii_header_filename 


# LaCReME
# Language: Python
# Input: TXT
# Output: TXT
# Tested with: PluMA 2.0, Python 3.6

PluMA plugin that runs LaCReME

Input is a TXT file of tab-delimited keyword-value pairs:
n: Cache size
infile: Cache accesses (one per line)
kind: Type of replacement

Possible values for kind:
 LaCReME_context1
 LaCReME_LFU_ARC
 LaCReME
 LaCReME_simple
 LaCReME_T1T2
 LaCReME_v3


Output is sent to TXT

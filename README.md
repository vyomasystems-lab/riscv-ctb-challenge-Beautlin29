# riscv_ctb_challenges

##Challenge_level1
###Challenge1_logical
--There are two bugs in the `test.S` and got rectified as follows.
test.S:15855: Error: illegal operands `and s7,ra,z4' --> 'here z4 is corrected to s4'
test.S:25584: Error: illegal operands `andi s5,t1,s0' --> 'here andi is changed to and'


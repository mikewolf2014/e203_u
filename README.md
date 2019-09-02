The Simulation Directory
================
we will use vcs to simulate and verify e203_u. os is linux, my os is redhat.

command as below

1. make compile
   
   // this command compile rtl files
2. make run_test TESTNAME=rv32ui-p-and
   
   // this command run test rv32ui-p-and, all tests in ./run/generated/
3. make debug TESTNAME=rv32ui-p-and
  
   //load design and waveform with verdi for test rv32ui-p-and, then you can debug test

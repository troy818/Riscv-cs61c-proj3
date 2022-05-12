# Riscv-cs61c-proj3

## Use logisim tool

1. link: (cs61c-2020summer)[https://inst.eecs.berkeley.edu/~cs61c/su20/projects/proj3/#part-a-getting-started]

1. cmd: java -jar logisim-evolution.jar

## Part_A

1. alu
```
 $ python3 test_runner.py part_a alu 

 Running tests for part_a/alu...
	 PASSED test: alu-add test
	 PASSED test: alu-comprehensive test
	 PASSED test: alu-div-rem test
	 PASSED test: alu-logic test
	 PASSED test: alu-mulh test
	 PASSED test: alu-mult test
	 PASSED test: alu-shift test
	 PASSED test: alu-slt-sub-bsel test
 Passed 8/8 tests
```

2. Register file
```
 $ python3 test_runner.py part_a regfile
 Running tests for part_a/regfile...
	 PASSED test: regfile-allregs test
	 PASSED test: regfile-insert test
	 PASSED test: regfile-x0 test
	 PASSED test: regfile-zero test
 Passed 4/4 tests
```

3. addi single
renamed `cpu_addi_single.circ` to `cpu.circ`
```
 $ python3 test_runner.py part_a addi_single 
 Running tests for part_a/addi_single...
	 PASSED test: cpu-addi-single test
 Passed 1/1 tests

```
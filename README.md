# colo-tests
A placeholder for colo tests

# Setup Environment
- Install fio
- Setup target directory where fio file will be setup and I/O will be done
  to these files

# Run Tests
bash run-tests.sh --iodepth 64 --size 72G --blocksize 4K --direct 0 --host 10.20.91.101 --storage 10.20.91.103 `pwd`/tmp fio-tests/seqread_libaio.fio

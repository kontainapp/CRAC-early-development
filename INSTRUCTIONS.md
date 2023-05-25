# Instructions to bring up CRAC stuff again

Will need ssh key for github repo `github.com:kontainapp`.

* 
ubuntu 20.04
    4  sudo apt install gcc
   20  sudo apt install g++
   29  sudo apt install make
   88  sudo apt install nvidia-cuda-dev
   99  sudo apt install nvidia-cuda-toolkit-gcc

16  git clone git@github.com:kontainapp/dmtcp.git


# Full History
    1  ls
    2  cc
    3  apt install gcc
    4  sudo apt install gcc
    5  sudo apt update
    6  sudo apt install gcc
    7  apt install git
    8  sudo apt install git
    9  ls .ssh
   10  ls -l ~/.ssh
   11  cd ~/.ssh
   12  ls
   13  chmod 400 id_rsa
   14  chmod 444 id_rsa.pub 
   15  cd
   16  git clone git@github.com:kontainapp/dmtcp.git
   17  cd dmtcp/
   18  ls
   19  ./configure 
   20  sudo apt install g++
   21  ./configure 
   22  vi config.log
   23  depfile
   24  depfiles
   25  sudo apt install depfiles
   26  man apt
   27  man dupfiles
   28  vi config.log
   29  sudo apt install make
   30  ./configure 
   31  make
   32  ls
   33  cd ..
   34  git pull git@github.com:kontainapp/CRAC-early-development.git
   35  git clone git@github.com:kontainapp/CRAC-early-development.git
   36  cd CRAC-early-development/
   37  ./configure
   38  make
   39  ls
   40  ls bin
   41  cd contrib/split-cuda/
   42  ls
   43  make
   44  sudo apt install python
   45  sudo apt install python3
   46  python
   47  make
   48  make clean
   49  make 
   50  make autogen
   51  make default 
   52  git branch -a
   53  make default 
   54  make clean
   55  vi Makefile
   56  git status
   57  cd ../..
   58  git status
   59  make clean
   60  git clean -f
   61  git checkout master
   62  git log
   63  git checkout -b fron-master
   64  git braanch -m fron-master from-master
   65  git branch -m fron-master from-master
   66  ./configuere
   67  ./configure
   68  make
   69  cd contrib/split-cuda/
   70  make
   71  python --version
   72  vi Makefile
   73  make
   74  git grep cuda_stub
   75  mkdir cuda_stub
   76  make
   77  ls
   78  ls cuda_stub*
   79  vi cuda_stub_lib/README.md 
   80  rmdir cuda_stub
   81  ls
   82  ls autogen/
   83  make
   84  vi Makefile 
   85  make clean
   86  make autogen
   87  apt list | grep cuda
   88  sudo apt install nvidia-cuda-dev
   89  make autogen
   90  make
   91  make clean
   92  make
   93  apt list | grep nvcc
   94  apt list | grep cuda
   95  apt list --available | grep cuda
   96  man apt
   97  apt list | grep cuda
   98  sudo apt install nvidia-cuda-gcc
   99  sudo apt install nvidia-cuda-toolkit-gcc
  100  make clean
  101  make
  102  history
  103  history | grep apt
  104  git status
  105  ls test/
  106  make -C test/ 
  107  type nvcc
  108  cat scripts/
  109  cat scripts/launch-matrix-example
  110  ls test/matrix/
  111  make -C test/matrix/ matrix_mul.dummy.exe 
  112  vi test/matrix/Makefile 
  113  cat scripts/launch-matrix-example
  114  cat scripts/launch-matrix-example-dummy 
  115  history > history.build

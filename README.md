# llvm-pacakge
- Pre-built LLVM Package
- Repository created for personal purposes.

## Environment variables
- Windows 11
   - `PATH` : `C:\llvm-package\bin`
   - `LLVM_HOME` : `C:\llvm-package`
   - `LLVM_DIR` : `C:\llvm-package\lib\cmake\llvm`
   - `Clang_DIR` : `C:\llvm-package\lib\cmake\clang`
- Linux
```
echo '
# LLVM 21 source-build
export LLVM_HOME=/home/jaytwo/workspace/llvm-package

export PATH="$LLVM_HOME/bin:$PATH"

export LD_LIBRARY_PATH="$LLVM_HOME/lib:$LD_LIBRARY_PATH"

export CMAKE_PREFIX_PATH="$LLVM_HOME:$CMAKE_PREFIX_PATH"

export LLVM_DIR="$LLVM_HOME/lib/cmake/llvm"

export Clang_DIR="$LLVM_HOME/lib/cmake/clang"
' >> ~/.bash_profile
```

## Version
- v21.1.6
   - https://github.com/JayTwoLab/llvm-pacakge/releases/tag/v21.1.6

 

# Tetris Game using PDCurses

Implement TETRIS GAME by using PDCurses lib.

### Environment

* Window 7, 10
* Visual Studio 2010
* PDCurses lib
* C++

### PDCurses Setup in Visual Studio

1. Right-click on the project file in the 'Solution Explorer'
2. Click `properties`
3. Navigate to the `C/C++` page and under the `General` tab add the following line in the box next to Additional Include Directories:

```sh
$(ProjectDir)include
```

4. Hit ‘Apply’
5. And navigate to the `Linker` page, click on the `Input` tab and in the box next to Additional Dependencies, add the following line:

```sh
$(ProjectDir)lib\pdcurses.lib
```
6. Enjoy Tetris!

### Issue

If you get the fatal error (fatal error LNK1112: module machine type 'x64' conflicts with target machine type 'X86'), refer to as follows..

http://stackoverflow.com/questions/3563756/fatal-error-lnk1112-module-machine-type-x64-conflicts-with-target-machine-typ

Configuration Manager > Active solution platform: x86

Configuration Manager > Project contexts > Platform : Win32


### License

* Author : Hyungjun Lee
* +1 (949) 309-1512
* +82 (010) 3007-1765
* hjlee1765@gmail.com
* https://github.com/LeeHyungJun


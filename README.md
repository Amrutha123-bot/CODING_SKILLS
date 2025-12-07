# CODING_SKILLS

# Sudoku Solver (Qt/C++)

## Windows Build (Tested with Visual Studio 2022)

1. Install Qt 6.10+ (msvc2022_64) from qt.io
2. Install Visual Studio 2022 with C++ Desktop Development
3. Clone: `git clone https://github.com/YOUR_USERNAME/SudokuSolver.git`
4. Open Developer Command Prompt for VS 2022
5. `cd SudokuSolver`
6. `cmake -B build -S . -DCMAKE_PREFIX_PATH="C:\Qt\6.10.1\msvc2022_64"`
7. `cmake --build build --config Release`
8. Run: `build\Release\SudokuSolver.exe`
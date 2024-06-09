# systax_analyzer
term project for class

You can add your test_case in test/...

# File Structure

```markdown
- team_42
  - bin
    - syntax_analyzer
  - result
    - outputs.txt
  - files
    - CFG.txt
    - Parsing_Table.csv
  - test
    - test_1.txt
  - main.cpp
  - output.txt

```
# Step

- Install g++ Ubuntu/Debian
```bash
sudo apt update
sudo apt install g++
```

- approach to directory
```bash
cd /mnt/c/Users/<YourUsername>/Desktop/something....
```

- Compile with command
```bash
g++ -o bin/syntax_analyzer main.cpp parser.cpp node.cpp
```

- Test with command
```bash
./bin/syntax_analyzer test/test_case_<number that you want>
```
you have to write your case by .txt

- Check output.txt
  there is explanation with whether it is valid or not

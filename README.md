
# For Updated Lists Use
## [Weak Pass](https://weakpass.com/)


# To use combine_wordlists.py

```
./wordlists.py *.txt -o masterlist.txt
```
OR
```
python3 wordlists.py *.txt -o masterlist.txt
```

### * is the wild card that will combine all wordlists together that end with .txt 
### -o is for output
### after the -o name the wordlist .txt you want it to be called with all combined files.

# Also Uses

You can also use it by naming the files that you want to combine by separating with a comma

```
./wordlists.py wordlist1.txt, wordlists2.txt, wordlist3.txt -o masterlists.txt
```

# Alternative Word List Compiling

## Using Sort

```
sort -T /path/to/temporary/folder/for/sorting -S 2G -u -o <combined-file-name>.txt *.txt
```
-T = creates temporary folder for sorting
-S 2G = limits RAM to only 2gbs
-u = unified/de-duplicate
-o = final product name
*.txt = wildcard for all .txt files in folder

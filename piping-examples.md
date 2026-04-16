# Piping Examples

## Basic piping

ls -la | grep ".txt"

## Show only usernames

cat /etc/passwd | cut -d ":" -f1

## Sort and remove duplicates

cat file.txt | sort | uniq

## Count lines

cat file.txt | wc -l

## Find specific word

cat file.txt | grep "hello"

## Show top 5 lines

cat file.txt | head -5

## Show last 5 lines

cat file.txt | tail -5

## Find files and filter

find . -name "*.txt" | wc -l

## Combine multiple filters

cat file.txt | grep "error" | sort | uniq

## Monitor logs

tail -f file.txt | grep "error"

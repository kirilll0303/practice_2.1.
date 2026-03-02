with open("text03.txt", 'w') as file:
    file.write("Hello World!\n")
    file.write("Hello Sanya!\n")
    file.write("My name is Kirill\n")
    file.write("What do you do?\n")
    file.write("Nothing\n")

with open("text03.txt", 'r') as file:
    lines = [line.rstrip('\n') for line in file.readlines()]

print(f"Кол-во строк в файле: {len(lines)}")

word_count = sum(len(line.split()) for line in lines)
print(f"Кол-во слов в файле: {word_count}")


longest_line = max(lines, key=len)
print(f"Самая длинная строка: {longest_line} (Длина: {len(longest_line)})")

file.close()

# Python-Program-to-Sort-and-Remove-Duplicates-from-a-Comma-Separated-Sequence-34-100
items = input("Input comma separated sequence of words: ")
words = [word.strip() for word in items.split(",")]
print(",".join(sorted(list(set(words)))))

Input comma separated sequence of words: apple,banana,apple,orange,banana
apple,banana,orange




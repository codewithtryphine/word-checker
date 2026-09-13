text = input("Enter your text: ")
word = input("Enter word to search: ")

text_lower = text.lower()
word_lower = word.lower()
exists = word_lower in text_lower
print("Word found?", exists)
if exists:
    position = text_lower.find(word_lower)
    print("First found at index:", position)python
censored = text.replace(word, "*" * len(word))
print("Censored text:", censored)
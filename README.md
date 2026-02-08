def count_vowels(text):
    vowels = "aeiou"
    return sum(1 for char in text.lower() if char in vowels)

if __name__ == "__main__":
    sentence = "Daily GitHub commits build consistency"
    print(f"Sentence: {sentence}")
    print(f"Vowel count: {count_vowels(sentence)}")

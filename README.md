def count_digits_in_string(tex):
    return sum(1 for char in text if char.isdigit())

if __name__ == "__main__":
    sample = "GitHub2026Commit115"
    print(f"Text: {sample}")
    print(f"Digit count: {count_digits_in_string(sample)}")

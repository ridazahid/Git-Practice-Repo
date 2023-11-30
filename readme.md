# Bioinformatics Learning Repository

Welcome to my Bioinformatics Learning Repository!

## About Me

I'm currently pursuing a Master's in Bioinformatics, passionate about exploring the intersection of biology and computational analysis. My academic journey involves diving into various bioinformatics tools, algorithms, and data analysis techniques.

## Repository Contents

This repository is a collection of resources and projects related to my bioinformatics studies:

- **Code Samples:** Python 
- **Datasets:** Publicly available biological datasets used for analysis and experiments.
- **Notes and References:** Summaries, notes, and references to articles, papers, or textbooks relevant to bioinformatics topics.
- **Projects:** Experimentation and exploration of various bioinformatics concepts and tools.
  ## Code samples
  def count_vowels_in_file(test_data):
        with open(test_data, 'r') as file:
            content = file.read().lower()
            vowels = set("aeiou")
            vowel_count = sum(1 for char in content if char in vowels)
            return(vowel_count)
print(count_vowels_in_file(test_data))
  

.






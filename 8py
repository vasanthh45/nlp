p1 = "the language learning platform helps users improve vocabulary."
p2 = "this system suggests synonyms to expand vocabulary"

set1 = set(p1.lower().split())
set2 = set(p2.lower().split())

score = len(set1 & set2) / len(set1 | set2)

if score >= 0.75:
    level = "High"
elif score >= 0.40:
    level = "Medium"
else:
    level = "Low"

print("Cosine Score:", score)
print("Similarity Level:", level)

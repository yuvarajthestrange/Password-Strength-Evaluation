
# Password List & Analysis

## Generated Passwords with Strength Levels

| Password          | Strength Level | Use Case Example       |
|-------------------|----------------|------------------------|
| `summer2023`      | Weak           | Personal social media  |
| `Summer2023`      | Moderate       | Work email            |
| `Summ3r2023!`     | Strong         | Online banking        |
| `7q$K2!pL9#W1`    | Very Strong    | Password manager master |

---

## Detailed Character Analysis

| Password       | Length | Uppercase | Lowercase | Numbers | Symbols | Entropy* |
|----------------|--------|-----------|-----------|---------|---------|----------|
| `summer2023`   | 9      | 0         | 6         | 4       | 0       | ~28 bits |
| `Summer2023`   | 9      | 1         | 5         | 4       | 0       | ~32 bits |
| `Summ3r2023!`  | 10     | 1         | 4         | 4       | 1       | ~56 bits |
| `7q$K2!pL9#W1` | 12     | 3         | 2         | 3       | 4       | ~80 bits |

> *Estimated entropy based on character variety ([Calculator](https://www.omnicalculator.com/other/password-entropy))

---

## Security Risk Assessment

1. **`summer2023`**  
   - ❌ Appears in [common password lists](https://github.com/danielmiessler/SecLists)
   - ❌ Crackable in <1 second with dictionary attacks

2. **`Summ3r2023!`**  
   - ✅ Withstands basic dictionary attacks
   - ⚠️ Could be vulnerable to targeted attacks (contains predictable substitutions)

3. **`7q$K2!pL9#W1`**  
   - ✅ No patterns or dictionary words
   - ✅ Estimated cracking time: >10,000 years (per [Hive Systems](https://www.hivesystems.io))

---

## How to Use This Data
1. Compare password strengths visually using the tables
2. Refer to entropy values when explaining cryptographic security
3. Use the risk assessments for awareness training

> **Pro Tip**: Generate stronger passwords with [Bitwarden Generator](https://bitwarden.com/password-generator/)

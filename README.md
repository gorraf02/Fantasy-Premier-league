[![Board Status](https://dev.azure.com/cancha/ed74100c-94d2-413b-8c02-fb2093f5b66a/4890dcd4-1977-48cc-8746-715d958fe5a0/_apis/work/boardbadge/8c421d1f-2f57-4bf3-a07c-3579cccf6338)](https://dev.azure.com/cancha/ed74100c-94d2-413b-8c02-fb2093f5b66a/_boards/board/t/4890dcd4-1977-48cc-8746-715d958fe5a0/Microsoft.RequirementCategory)
# 📊 FPL-Weekly-Standing-Python

**Developer**: Rafek Gorgay

Welcome to **FPL-Weekly-Standing-Python**! This Python script fetches all data for any league in Fantasy Premier League (FPL) and generates two comprehensive reports containing everything about the league and its players.

## 🚀 How to Use

1. **Open the league** from your browser. For example: [FPL League Example](https://fantasy.premierleague.com/leagues/xxxxxx/standings/c)
2. **Extract the league number** (the position of `xxxxxx` in the link).
3. **Update the script**: Change the league number variable on **line 11** of the script.
4. **Run the script**.
5. The reports will be generated under a new folder created in the directory.

## 📝 Example

```python
# Change this line in the script
league_number = 'xxxxxx'

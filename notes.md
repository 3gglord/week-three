# Week Three Notes

## REGEX
- [cheatsheet for regular expressions in Sublime](https://jdhao.github.io/2019/02/28/sublime_text_regex_cheat_sheet/)
- `|` means "or"
- when terms are separated by spaces, it defines it as a complete word
- `\<` or `\b` means the beginning of a word
- `\>` or `\b` for patterns at the end of the line
- can use parentheses to look for variations of a single word
- original search wasn't working
- played around with the critera individually and found that find: `\n[^~]+` replace: `\n` worked
- asked in discord and learned that `\n` meant that the remaining text would stay in its line rather than turning into one giant block of text

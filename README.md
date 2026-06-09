# UNSW Style Configs
So basically, I was reading the [UNSW Style Guide](https://cgi.cse.unsw.edu.au/~cs1511/26T1/resources/style_guide.html#code-structure), and realised there are so many rules :sob:

Then I realised that formatters and linters exist, so I (with help from GPT) decided to make config files for clang-format and clang-tidy. These configs will enforce some rules and warn you about others.

**Current C features:**
- Correct braces, indentation & spaces
- One executable statement per line
- Lines must be less than 80 characters
- Enforces snake case
- One variable declaration per line
- Blocks comma operator

**Current JS features:**
- Correct braces, indentation & spaces
- Automatic semicolon insertion
- Automatic arrow function parentheses
- Enforces camel case
- No `var` variable declarations
- No `==` or `!=` comparisons
- Use `const` when possible
- Avoid C-style loops when possible

**If you find improvements, please send over a PR, so everyone can enjoy beautiful and compliant code :D**

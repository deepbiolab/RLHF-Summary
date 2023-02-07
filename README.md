# RLHF-Summary
- [ ] single hard prompt, such as `</s>`
- [ ] multiple hard prompt, such as constant region, CDR region, paratope, epitope, disulfide
```
# Version 1:
source(x): antigen
context(prompt): constant region
target(y): cdr region

# Version 2:
source(x): antigen epitope
context(prompt): constant region
target(y): antibody paratope

# Version 3:
source(x): antigen epitope
context(prompt): constant region
target(y): antibody cdr region
```
- [ ] select prompt of antibody-antigen complex


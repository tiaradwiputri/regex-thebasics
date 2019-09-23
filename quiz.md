# RegEx: The basics
The following quiz set is created as an accompanying quiz for knowledge assessment purposes.


## Basic Pattern Knowledge

1. The following quantifier token is used to explicitly set how many pattern match you would like to have:  
    - [ ] `*`  
    - [ ] `+`  
    - [ ] `{n,m}`  
    - [ ] `?`  

2. By using a *grouping* token, we can create a group of possible matching token. Which grouping technique is the equivalent of **all upper case letters**:  
    - [ ] `[A-Z]`  
    - [ ] `[aZ]`  
    - [ ] `[\\W]`  
    - [ ] `[AZ]`  

3. The use of `^\D` token in regex will result in which pattern:  
    - [ ] Digit at the end of a string  
    - [ ] Non digit at the end of a string  
    - [ ] Digit at the start of a string  
    - [ ] Non digit at the start of a string  

4. The term: *wildcard* is used for a token that can match any character from a string. It is a powerful token, but need to be implemented carefuly. Which of the following is a wildcard token:  
    - [ ] `.`  
    - [ ] `*`  
    - [ ] `.*`  
    - [ ] `*.`  

5. If you came accross the following pattern: `(A|a)`, means it is trying to match with which pattern:  
    - [ ] Either a string `A` or `a`  
    - [ ] If both string present, match with `A` instead of `a`  
    - [ ] Match with both if both present in a string  
    - [ ] Replace `A` with the string `a`  

## Case Study: Implementing RegEx

6. The following regex pattern can be used to match correctly with an **indonesian phone number** within a registration form data:
    - [ ] `\+62{1}\D+(\b|$)`
    - [ ] `\+62.*`
    - [ ] `\+62+\d+`
    - [ ] `\+[62]+\d+`

7. The following regex pattern can be used to match with any upper case words in a system description, knowing that all upper case words is a specific keyword that needs to be extracted from the description:  
    - [ ] `[AZ]+\B`  
    - [ ] `[A-Z]+\b`  
    - [ ] `\W+\b`  
    - [ ] `[A-Za-z]*`

8. Say you have multiple format of providing street name between: Jl and Jl. (with no clear format on upper and lower case). Which of the following can be used to match with a one word street name:  
    - [ ] `([Jj][Ll])+(\.| )?\w+\b`  
    - [ ] `([JL]|[jl])+\.? \w+\b`  
    - [ ] `(Jl|jl\.) \w+\b`  
    - [ ] `([Jj]|[Ll]+.) \w+\b`  




# codingchallenges
Things that I got stuck with and learnt while solving python coding challenges on HackerRank



``` python
    #FINDING SUBSTRING FROM A STRING
    def count_substring(string, sub_string):
    index = 0
    countstring = 0
    for resultsearch in string:
        findresult = string.find(sub_string, index)
        if findresult > -1:
            countstring = countstring +1
            index = findresult+1
    return(countstring)```
    
    
  ``` python
  # any() Returns True if any item in an iterable object is true, all() Returns True if all items in an iterable object are true
    s = "qA2"
    print(any(c.isalnum() for c in s))
    print(any(c.isalpha() for c in s))
  ```
  
  

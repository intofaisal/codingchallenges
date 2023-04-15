# codingchallenges
Things that I got stuck with and learnt while solving coding challenges


**FINDING SUBSTRING FROM A STRING
**

  def count_substring(string, sub_string):
    index = 0
    countstring = 0
    for resultsearch in string:
        findresult = string.find(sub_string, index)
        if findresult > -1:
            countstring = countstring +1
            index = findresult+1
  return(countstring)

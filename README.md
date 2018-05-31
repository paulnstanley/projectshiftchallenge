# projectshiftchallenge

<b>Problem 1:</b>

def Durham():
  print "Durham is awesome!"
  
Durham()

Problem 2:

bandlist = ['Kiss', 'Aerosmith', 'ACDC', 'Led Zeppelin', 'Nickelback']

def bands():
  for band in bandlist:
    print "I love %s" % (band)

bands()

Problem 3:

bandlist = ['Kiss', 'Aerosmith', 'ACDC', 'Led Zeppelin', 'Nickelback']

def bands():
  for band in bandlist:
    if band != "Nickelback":
      print "I love %s" % (band)
    else:
      print "I DON'T love %s" % (band)

bands()

Problem 4:

array = [34, 203, 16, 46, 34, 432, 342, 124, 33, 188, 12]

def avgArray():
  for number in array:
    """I'd add all the numbers and divide the sum by the number of items in the list, but not sure how to add, divide, or count the list without googling.  Tried importing math but it had no average function and that's probably cheating anyway."""

avgArray()

Problem 5:

array = ['a', 'b', 'c', 'd', 'c', 'b', 'b', 'c', 'a', 'e', 'b', 'e']

def frequency():
  for letter in array:
    """count the number of occurrences of each letter"""
    """store those values in a variable for each letter"""
    """compare the values and assign to most or leastFrequent variables"
  print "The most frequent item is: " + mostFrequent
  print "The least frequent item is: " + leastFrequent

frequency()

"""I think this uses way too many variables but not sure how to do it cleaner."""

Problem 6:

arrayOne = ['a', 'b', 'c', 'a', 'a', 'b', 'd']
arrayTwo = ['a', 'b', 'b', 'a', 'e', 'c', 'c', 'g']

"""Not sure without research.  If I had solved problem 5, I'd probably try to use that counting logic to create a new list of the overlaps and then print that list."""

Problem 7:

"""I worked on this for way too long because I really felt like I could figure it out, but never got it quite right.  Totally googling this after submitting."""

cost = input("How much would you like to withdraw?")

def breakdown():

  hundreds = 0
  fifties = 0
  twenties = 0
  tens = 0
  fives = 0
  ones = 0

  while cost >= 100:
    cost - 100
    hundreds += 1
  elif cost >= 50:
    cost - 50
    fifties += 1
  elif cost >= 20:
    cost - 20
    twenties += 1
  elif cost >= 10:
    cost - 10
    tens += 1
  elif cost >= 5:
    cost - 5
    fives += 1
  else:
    cost - 1
    ones += 1
      
  print "100s: %s" % (hundreds)
  print "50s: %s" % (fifties)
  print "20s: %s" % (twenties)
  print "10s: %s" % (tens)
  print "5s: %s" % (fives)
  print "1s:%s " % (ones)

breakdown()

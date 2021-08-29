# calculator-challenge2
Another simple calculator made using React

Copied from a youtube video this version had a bug when a calculation 
went to double figures the app crashed.

Found this line of code:
    setText((text) => [...text, val + " "])
to be the problem.

Removed the space from the blank string to read like this:
    setText((text) => [...text, val + ""])


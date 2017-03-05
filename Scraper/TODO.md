Scrape all class thats currently offered at Berkeley, create .json file with useful information:
depart: string, the department this class is in. For example "Math"
name: string, name of the class. For example "Multivariable Calculus"
prereq: list of string, all the "immediate" pre-req of the class, in the format "department number". i.e. ["Math 1A", "Math 1B"]
number: string, number of the class "53"
isAC: boolean, true if it satisfy American Culture requirement
isRCA: boolean, true if it satisfy first half of reading and composition
isRCB: boolean, true if it satisfy first half of reading and composition

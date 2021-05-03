# sdlfile_name = raw_input("enter the name of file")
file = open(file_name,'r')
lines =0
words=0
characters =0
for line in file:
wordcount =line.split()
lines=lines +1
words = words + len(wordcount)
characters = characters +len(line)
print "lines in file =",lines
print "words in file =",words
print "characters in file:",characters
#output:
#enter teh name of fileass3.py
#lines in file = 8
#words in file = 23
#characters in file: 167

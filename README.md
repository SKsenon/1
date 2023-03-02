import re
file = "folder1/folder2/file.ext"
FileParts=file.split(".", 1)
print (FileParts[1])


import http.client
conn = http.client.HTTPSConnection("www.google.com")
conn.request("GET", "/")
r1 = conn.getresponse()
print(r1.status, r1.reason)


import calendar
if calendar.isleap(2027):
    print ("2027 год виcокосный!!!")
else: print ("2027 год невисокосный!!!")
day=calendar.weekday(1995, 6, 25)
print ("0 - понедельник, 6 - воскресенье")
print ("А 25 июня 1995 года было:")
print (day)
calendar.prcal(2023, w=0, l=0, c=6, m=3)

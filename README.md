# Pooja C
import mysql.connector 

mydb=mysql.connector.connect(host="localhost",user="root",passwd="",database="pooja")

mycursor =mydb.cursor()

mycursor.execute("select * from pooja")

for i in mycursor:
    print(i)

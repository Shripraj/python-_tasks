#######TASK1####
try:
    file1=open('sample.txt','r+')
    reading=file1.read()
    print(reading)
    file1.close
except:
    print("THE FILE 'sample.txt' not found")
finally:
    print("HAVE A GRATE DAY *_*")



#######TASK2#######
n=input("Enter text to write to the file:")
file2=open('output.txt','a')
writing=file2.write(n)
file2.close()
print("DATA SUCCESSFULLY WRITTEN TO output.txt")
m=input("Enter another text to append to the file:")
file2=open('output.txt','a')
appending=file2.write(m)
file2.close()
file2=open('output.txt','r')
reading=file2.read()
print("THE FINAL CONTENT OF output.txt is")
print(reading)
file2.close()

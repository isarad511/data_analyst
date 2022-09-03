Text = 'blah blah blah'
x = input("enter text here")
Def encrypt(txt):
      ''.join(chr((ord(txt[i])+i)%256)
For i in range(len(txt)))


encrypt(x)
Print("hello my name is Eugene")

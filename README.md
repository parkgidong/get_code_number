# get_code_number

ch = input("문자 1개를 입력하세요: ")

while len(ch)==0:
    ch = input("문자 1개를 입력하세요: ")

else:
    ch = ch[0]
    chv = ord(ch)
    print('문자: %s\t코드값: %d[%s]' %(ch, chv, hex(chv)))
    



# TIL
## for와 if문 사용하여 리스트 형태의 데이터를 딕셔너리 데이터로 바꾸기 (2021/02/03)
 for i in range(len(phone_split)):
    if(phone_split[i]!=''):
        phone_dict[phone_split[i].split()[0]]=phone_split[i].split()[1]
phone_dict

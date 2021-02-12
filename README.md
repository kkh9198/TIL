# TIL
## for와 if문 사용하여 리스트 형태의 데이터를 딕셔너리 데이터로 바꾸기 (2021/02/03)
 for i in range(len(phone_split)):
    if(phone_split[i]!=''):
        phone_dict[phone_split[i].split()[0]]=phone_split[i].split()[1]
phone_dict

## 판다스 내에 있는 plot만들기 (2021-02-04)
* plot()
* plot.bar()
* plot.barh() bar차트의 가로세로 바꿈


## 데이터 프레임으로 만들기 (2021-02-06)
* value_counts().to_frame() 도수를 데이터 프레임화
* sns.heatmap(data.corr(),annot=True) 히트맨 그래프,상관계수,annot=숫자 표시

## colab(google colaboratory)에서 판다스 실습하기 (2021-02-12)
* 출처:https://github.com/corazzon/cracking-the-pandas-cheat-sheet 

## 그래프에 평행선 긋기 
* plt.axhline(30, color='red',linestyle=":")

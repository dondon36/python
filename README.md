# # d={"key":"value"}
# d['apple']='사과'
# d['apple']='파인애플'
# del d['apple']
# print(d)
# a=True
# b=False
# print(type((a)))
# #값 o=참 값 x=거짓
# print(bool('Python'),bool(''))  #문자열
# print(bool([1,2,3]),bool([]))   #리스트
# print(bool((1,2,3)),bool(()))   #튜플
# print(bool({'a':1}),bool({}))   #딕셔너리
# print(bool(8),bool(0))          #정수 0만 거짓 나머지 참
# print(bool(None))               #None
# a= 4 #if a  != 3:=다름,if a == 3:=같다
# if a > 3:
#     print('a') #만약 ~라면
# elif a < 4:
#     print('b') #그렇지 않으면 elif=무한
# else:
#     print('c') #그밖에
#비교 연산자 (A 비교연산자 b)
# A > B =>A가 B보다 크다
# A < B =>A가 B보다 작다
# a != b=A와 B가 다름
# a == b A와 B가 같다
# A >= B =>A가 B보다 크거나 같다
# A <= B =>A가 B보다 작거나 같다
#논리 연산자 (and,or,not)
# a,b,c,d = [3,4,5,3]
# if not a:
#     print(True)
# else:
#     print(False)
# #in ~안에 있는
# l1 = ['a','b','c,d']
# var = 'a'
# if var in l1:
#     print(True)
# else:
#     print(False)
# i=int(input('숫자를 입력하세요'))
# # print(i + 10)
# if i % 2 == 0:
#    print('짝수')
# else:
#    print('홀수')
# print(13//2)
#20 더한 값이 255초과시 255출력
# i = i+20
# if i > 255:
#     print(255)
# else:
#     print(i)
# a=5
# a+=3 #a= a+3
# print(a)
# i = i-20
# if i < 0:
#     print(0)
# elif i > 255:
#     print(255)
# else:
#     print(i)
# time=input("시간을 입력하세요")
#
# if time[-2:] == '00':
#     print("정각입니다")     #서로같은 자료형끼리 연결해 비교해야한다
# else:
#     print("정각이 아닙니다")
fruit = {"봄" : "딸기", "여름" : "토마토", "가을" : "사과"}
# f = input("과일을 입력하세요:")
# if f in fruit:
#     print("정답입니다")
# else:
#     print("정답이 아닙니다")
s = input("과일을 입력하세요:")
if s in fruit.values():
     print("정답입니다.")
else:
     print("정답이 아닙니다")

# homework2
homework2_vimgolf5

# vim golf의 문제 리스트 5가지
## (1)  5f0f5fbe280fbf000c233304

* 최고점 : 8점
* **나의 최고점: 11점**


![vimgolf과제(1)](https://user-images.githubusercontent.com/94296757/144639918-2abcafa8-332c-47de-a311-89e63c9e4db9.gif)

* 첫번째 시도 (13점): G -> W -> " -> esc -> $ -> i-> end키 -> " -> esc -> :x 
* **두번째 시도 (11점):**
* **G -> W -> " -> esc -> A -> " -> esc -> :x**

* 설명 
>>처음에는 커서를 어떻게 맨뒤로 바로 옮길 수 있을까 생각하다가 $ -> i-> end키 를 생각했는데
이 세개의 키를 한번에 처리 할 수 있는 A 를 썼다.


## (2) 603ba26a01b4d00009c10a49

* 최고점 : 19점
* **나의 최고점: 27점**

![vimgolf과제(2)](https://user-images.githubusercontent.com/94296757/144640078-56d2b540-3d1a-4b50-9310-e7c1cc9265be.gif)


* 첫번째 시도 (37점): :%s/sublime/vim/g -> :%s/emacs/vim/g
* **두번째 시도 (27점):**
* **:%s/sublime\|emacs/vim/g -> :x**

* 설명 
>> sublime과 emacs를 따로따로 바꾸려다 보니 키를 더 많이 누르게 되었다.
>> sublime\|emacs을 이용해 둘을 한꺼번에 vim으로 치환하였다.

## (3)  5f1063aa8361810006e73210

* 최고점 : 20점
* **나의 최고점: 38점**

![vimgolf과제(3)](https://user-images.githubusercontent.com/94296757/144640127-e0e7f35f-5989-47f1-a4b3-12b9894dabff.gif)


* 첫번째 시도 (47점): :4 -> // Version TODO -> esc키 -> yy-> end키 한번 -> p -> :.s/Version/Debug/g -> :x
* **두번째 시도 (38점):**
* **:4 -> // Version TODO -> esc키 -> yy-> end키 한번 -> p -> w -> dw -> i -> Debug +띄어쓰기 -> esc키 -> :x**

* 설명 
>>처음 에는 **:.s/Version/Debug/g -> :x** 을 이용했으나  **w -> dw -> i -> Debug +띄어쓰기 -> esc키 -> :x** 을 이용하여
>>즉, 현재 커서가 있는 행의 Version을 찾아서 Debug을 주는 대신
>> dw을 이용한 Version단어 삭제하고 직접 Debug를 써주었음.

## (4) 9v0060da5177000000000209

* 최고점 : 34점
* **나의 최고점: 33점**

![vimgolf과제(4)](https://user-images.githubusercontent.com/94296757/144640170-b44183e3-92e7-4dfd-af70-eb0a25fb77d1.gif)


* **첫번째 시도(33점):**
* **:%s/y1/abs(y1)/g -> w5번 -> ctrl +a  3번 -> 위로 -> ctrl +a  2번 -> 위로 -> ctrl +a  1번**

* 설명 
>> y1을 abs(y1)로 바꾸는 것은 쉬웠으니까
>> 숫자를 차례대로 증가시키는 것을 최소의 횟수로 해내는 것이 어려웠다.
>> %s/y1/abs(y2)/g 처럼 일일이 바꾸는 것 보다 ctrl +a 이용 하여 숫자를 하나씩 증가시키는 방법으로 해보았다.


## (5)  6013804df3308e0009368f1c

* 최고점 : 19점
* **나의 최고점: 40점**

![vimgolf과제(5)](https://user-images.githubusercontent.com/94296757/144640243-ca157552-2522-4c55-890d-a82620f9dea3.gif)


* **첫번째 시도( 40점):**
* **:%s/""/"student_id,name,age,score"/g -> :x**

* 설명 
>> 5행으로 이동하여(:5) 단어를 복사(yw)하여 행 10으로 이동하여(:10) p붙여넣기를 하려고 했으나
>> 처음했던 시도 보다 복잡하여 처음 했던대로 시도했음.



 
 



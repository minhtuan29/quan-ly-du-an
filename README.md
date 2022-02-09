# quan-ly-du-an
Câu số 2:  
- thù lao mỗi người: 60Usd/tháng  
- bị phạt mỗi người: 50Usd/tháng nếu chưa hoàn thành trong 10 tháng  
- cho : A(6), B(5), C(2), D(4, AB), E(4) , F(5, AB)  
--> tìm các phương án khả thi ưu tiên mà tương ứng với số người tham gia ?  
Giải:  
Đầu tiên, từ ABCDEF ta tìm được Tmin(hay còn gọi là Te) = 11
ta có:  
```
Tổng Chi Phí = Tiền Công + Tiền Phạt  
       C     =   Ca      +   Cp
```
với T là thời gian hoàn thành dự án
```
Nếu  T >  10 : Tiền Phạt Cp = ( T - 10 ) * 50
Nếu  T <= 10 : Tiền Phạt Cp = 0
```
với n là số người tham gia
```
Tiền Công Ca = n * T * 60
```
Ta có :  
 ![1](https://user-images.githubusercontent.com/86332370/153129078-a389bde5-0d2f-44d3-8f0d-251eafad84a1.PNG)

Kết luận: Các phương án khả thi theo thứ tự ưu tiên là :
- phương án n = 2 : vì T2 >= Tmin và C2 min
- phương án n = 3 : vì T3 >= Tmin và C1 >= C3 >= C2 

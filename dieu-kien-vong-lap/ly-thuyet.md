## Hãy cho biết kết quả của Boolean Expression
Cho x, y, z = 3, 5, 7. Hãy cho biết kết quả của Boolean Expression:

(a) x == 3 

(b) x < y 

(c) x >= y 

(d) x <= y 

(e) x != y - 2 

(f) x < 10 

(g) x >= 0 and x < 10 

(h) x < 0 and x < 10 

(i) x >= 0 and x < 2 

(j) x < 0 or x < 10 

(k) x > 0 or x < 10 

(l) x < 0 or x > 10 

## Hãy cho biết kết quả xuất ra màn hình
Cho i, j, k là các con số và lệnh dưới đây:
```Python
if i < j:
  if j < k:
    i=j
  else:
    j = k
else:
  if j > k:
    j = i
  else:
    i = k
print("i =", i, " j =", j, " k =", k)
```
Hãy cho biết kết quả xuất ra màn hình nếu tuần tự 3 biến trên có các giá trị sau: 

(a) i = 3, j = 5, and k = 7 

(b) i = 3, j = 7, and k = 5 

(c) i = 5, j = 3, and k = 7 

(d) i = 5, j = 7, and k =3 

(e) i = 7, j = 3, and k = 5 

(f) i =7, j = 5, and k = 3 

## Cho biết bao nhiêu dấu * được in ra trên màn hình
```Python
a = 0
while a < 100:
  print('*', end='')
print()
```

## Cho biết bao nhiêu dấu * được in ra trên màn hình
```Python
a = 0
while a < 100:
  b = 0
  while b < 40:
    if (a + b) % 2 == 0:
      print('*', end='')
    b += 1
  print()
  a += 1
```
## Giải thích cách chạy của dòng lệnh range
(a) range(5) 

(b) range(5, 10) 

(c) range(5, 20, 3) 

(d) range(20, 5, -1) 

(e) range(20, 5, -3) 

(f) range(10, 5) 

(g) range(0) 

(h) range(10, 101, 10) 

(i) range(10, -1, -1) 

(j) range(-3, 4) 

(k) range(0, 10, 1)

## Cho biết bao nhiêu dấu * được in ra trên màn hình
```Python
for a in range(20, 100, 5):
  print('*', end='')
print()
```


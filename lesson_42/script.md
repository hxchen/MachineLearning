##控制语句：for while if语句
for循环
example-1
```octave
v=zeros(10,1);
for i=1:10,
    v(i)=2^i;
end;
```
example-2
```octave
indices=1:10;
for i = indices,
    disp(i);
end;
```
while循环
```octave
i=1;
while i <=5
    v(i)=100;
    i=i+1;
end;
```
while循环
```octave
i=1;
while true,
    v(i) = 999;
    i=i+1;
    if i == 6
        break;
    end;
end;
```     
if-else语句
```octave
v(1) == 2;
if v(1)==1,
    disp('The value is one');
elseif v(1)==2,
    disp('The value is two');
else 
    disp('The value is not one or two');
end;
```
函数定义




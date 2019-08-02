1.字符串长度计算函数：length

语法: length(string A)

```
select length('iteblog') 
```


#### 2.字符串反转函数：reverse

语法: reverse(string A)
返回值: string
说明：返回字符串A的反转结果

```
select reverse('iteblog')
```

#### 3.字符串连接函数：concat

语法: concat(string A, string B…)
返回值: string
说明：返回输入字符串连接后的结果，支持任意个输入字符串

```
 select concat('www','iteblog','com') 
```

使用||运算符实现字符串的拼接(快)

``` 
 select  'www' ||  'iteblog' || 'com'
```

#### 4.字符串截取函数：substr,substring

语法: substr(string A, int start),substring(string A, int start)
返回值: string
说明：返回字符串A从start位置到结尾的字符串

```
  select substr('iteblog',3) 
   
  select substr('iteblog',3,2) 

  select substr('iteblog',-3,2)  
  
  select substring('iteblog',3) 
   
  select substring('iteblog',3,2) 

  select substring('iteblog',-3,2)  
```

#### 5.replace(string, search) → varchar

删除字符串 string 中的所有子串 search 。


```
select replace('itebtlog', 't')
```

replace(string, search, replace) → varchar

将字符串 string 中所有子串 search 替换为 replace。

```
select replace('itebtlog', 't','k')

```

#### 6.strpos(string, substring) → bigint

返回字符串中子字符串的第一次出现的起始位置。位置以 1 开始 ，如果未找到则返回 0 。

```
select  strpos('titebtlog', 't')

select  strpos('itebtlog', 'p')

```


#### 7.regexp_replace:将原字符中的指定字符替换

```
select regexp_replace('aabb','b','c')

```

#### 

#### 






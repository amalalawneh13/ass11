# ass11
حل اسايمنت 

def sleep_in(weekday, vacation):
  return not weekday or vacation
def parrot_trouble(talking, hour):
 return talking and hour not in range(7,21)
def monkey_trouble(a_smile, b_smile):
 if((a_smile and b_smile) or ((not a_smile) and (not b_smile))):
   return True
 else:
  return False
def diff21(n):
   if n > 21:
    return abs(n-21) * 2
   return abs(n-21)
def not_string(str):
   return str if str[:3] == "not" else "not " + str
def front3(str):
  if len(str) < 3:
    return str * 3
  return str[:3] * 3



---------------------------------
def last2(str):
  s = 0
  for j in range(len(str)-2):
    if str[j:j+2] == str[-2:]:
      s += 1  
  return s
def array_front9(nums):
  for i in nums[:4]:
    if i == 9:
      return True
  return False
def string_bits(str):
  t = ''
  for i in range(0, len(str)):
    if i%2 == 0:
      t += str[i]
  return t
def string_match(a, b):
  m = min(len(a), len(b))
   
  s = 0 
  for i in range(m-1):
    if a[i:i+2] == b[i:i+2]:
      s += 1
  return s
def front_times(str, n):
  if len(str) < 3:
    return str * n
  return str[:3] * n


----------------------
def hello_name(name):
   return "Hello " + name + "!"
def extra_end(str):
  return str[-2:] * 3
def make_tags(tag, word):
  return "<" + tag + ">" + word + "</" + tag + ">"
def left2(str):
  return str[2:] + str[:2]
def without_end(str):
  return str[1:-1]
def first_two(str):
   t = ''
   if len(str) <= 2:
    t= str
   else:
      t=str[:2]
   return t


----------------------------------
def common_end(a, b):
  t=a[0] == b[0] or a[-1] == b[-1]
  return t
  
def make_pi():
  t=[3,1,4]
  return t
def rotate_left3(nums):
  t=[nums[1], nums[2], nums[0]]
  return t
def max_end3(nums):
   t = max(nums[0], nums[2])
   return [t, t, t]
def make_ends(nums):
  t=[nums[0], nums[-1]]
  return t
def sum2(nums):
   t=0
   if len(nums) == 0:
     t=0
   if len(nums) == 1:
     t= nums[0]
   if len(nums) >= 2:
     t=nums[0] + nums[1]
   return t


-----------------------------------
def love6(a, b):
  t= a == 6 or b == 6 or (a + b) == 6 or abs(a - b) == 6
  return t
def date_fashion(you, date):
    t=1
    if you <= 2 or date <= 2:
     t= 0
    elif you >= 8 or date >= 8:
     t= 2
    return t
def squirrel_play(temp, is_summer):
  t=False
  if is_summer:
    t= 60 <= temp <= 100
  else:
    t= 60 <= temp <= 90
  return t
def sorta_sum(a, b):
  t=0
  if 10 <= a + b < 20:
    t= 20
  else:
    t=a+b
  return t
def alarm_clock(day, vacation):
  if not vacation:
    if 1 <= day <= 5:
      return '7:00'
    return '10:00'
  
  if 1 <= day <= 5:
    return '10:00'
  return 'off'

--------------------------------------
def lone_sum(a, b, c):
   t=0
   if a == b == c:
    t= 0
   elif b == c:
    t= a
   elif a == c:
    t= b
   elif a == b:
    t= c  
   else:
    t=a + b + c
    
   return t
def make_bricks(small, big, goal):
  t=goal%5 >= 0 and goal%5 - small <= 0 and small + 5*big >= goal
  return t
def lucky_sum(a, b, c):
  t = 0
  list = [a,b,c,13]
  for i in list[:list.index(13)]:
    t += i
  return t
def close_far(a, b, c):
  x = abs(a-b) <= 1 and abs(b-c) >=2 and abs(a-c) >= 2
  y = abs(a-c) <= 1 and abs(a-b) >=2 and abs(c-b) >= 2
  return x or y


------------------------------------
def double_char(str):
  t = ''
  for x in str:
    t += x * 2
  return t
def count_hi(str):
  t = 0
  for i in range(len(str)-1):
    if str[i:i+2] == 'hi':
      t += 1
  return t
def count_code(str):
  t = 0
  for i in range(0, len(str)-3):
    if str[i:i+2] == 'co' and str[i+3] == 'e':
      t += 1
  return t

-----------------
def count_evens(nums):
  t = 0
  for i in nums:
    if i % 2 == 0:
      t = t+1
  return t
def has22(nums):
  for i in range(0, len(nums)-1):
    if nums[i] == 2 and nums[i+1] == 2:
      return True    
  return False
def centered_average(nums):
  t = 0
  for i in nums:
    t = t+i
  return (t - min(nums) - max(nums)) / (len(nums)-2)
--------------------

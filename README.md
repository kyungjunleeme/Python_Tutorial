# https://runestone.academy/ns/books/published/fopp/Functions/Returningavaluefromafunction.html

# operator
![image](https://user-images.githubusercontent.com/45473846/167428419-3c1e4212-40d7-4506-bc3c-9ad3f5d672b6.png)
https://devbruce.github.io/python/py-40-getattr,hasattr,setattr/

# Q

<img width="627" alt="image" src="https://user-images.githubusercontent.com/45473846/167167284-cd031bd5-3e73-4e62-8219-59c990745376.png">


# built in
https://docs.python.org/3/library/functions.html


# 인코딩/디코딩 # binary-sequence-types-bytes-bytearray-memoryview
https://docs.python.org/3/library/stdtypes.html?highlight=byte#binary-sequence-types-bytes-bytearray-memoryview

<img width="639" alt="image" src="https://user-images.githubusercontent.com/45473846/166103429-12d5e36d-03b2-476a-8a3f-112bd60ae06b.png">

# kib, gib
https://blankspace-dev.tistory.com/342

# python 3.0 의 
https://docs.python.org/release/3.0.1/whatsnew/3.0.html#text-vs-data-instead-of-unicode-vs-8-bit

https://docs.python.org/3/library/codecs.html?highlight=utf#encodings-and-unicode
https://docs.python.org/3/library/stdtypes.html#text-sequence-type-str
https://docs.python.org/3/reference/lexical_analysis.html#strings
https://peps.python.org/pep-0393/


https://www.youtube.com/watch?v=X4zlQkmjmfQ
https://www.youtube.com/watch?v=njx8EzusUSA



# django 오픈소스에서 배우는 from functools import partialmethod, total_ordering

https://github.com/django/django/blob/main/django/db/models/fields/__init__.py

# Runtime - 

https://docs.python.org/3/library/python.html


# Python_Tutorial

https://docs.python.org/3/library/collections.html#collections.OrderedDict

https://python-course.eu/oop/introduction-to-descriptors.php

https://docs.python.org/3/tutorial/index.html

https://docs.python.org/3/glossary.html

공식문서로 제대로 공부하자. 영어공부도 하고 일석이조구만

type
https://docs.python.org/3/library/collections.abc.html#collections-abstract-base-classes

context manager
https://docs.python.org/3/reference/datamodel.html#with-statement-context-managers

![image](https://user-images.githubusercontent.com/45473846/160242427-850592aa-fb92-4703-a238-b31e3f068618.png)

- statements
- clauses
- clause header
- suite : A suite is a group of statements controlled by a clause.
- block
- 


8. Compound statements¶
Compound statements contain (groups of) other statements; they affect or control the execution of those other statements in some way. In general, compound statements span multiple lines, although in simple incarnations a whole compound statement may be contained in one line.

The if, while and for statements implement traditional control flow constructs. try specifies exception handlers and/or cleanup code for a group of statements, while the with statement allows the execution of initialization and finalization code around a block of code. Function and class definitions are also syntactically compound statements.

A compound statement consists of one or more ‘clauses.’ A clause consists of a header and a ‘suite.’ 
The clause headers of a particular compound statement are all at the same indentation level. 
Each clause header begins with a uniquely identifying keyword and ends with a colon. 
A suite is a group of statements controlled by a clause. 
A suite can be one or more semicolon-separated simple statements on the same line as the header, following the header’s colon, or 
it can be one or more indented statements on subsequent lines. 
Only the latter form of a suite can contain nested compound statements; the following is illegal, 
mostly because it wouldn’t be clear to which if clause a following else clause would belong:

![image](https://user-images.githubusercontent.com/45473846/160265256-d4a1f208-b3ee-4ce7-bba8-e6c980023e05.png)


https://docs.python.org/3.10/library/itertools.html


<img width="613" alt="image" src="https://user-images.githubusercontent.com/45473846/160595536-502b4991-d3f3-4392-99be-4cdc34712661.png">

"klass" is a common convention in OOP code when referring to classes, because "class" and "Class" are often reserved already.
https://news.ycombinator.com/item?id=19690657



https://docs.python.org/3/howto/descriptor.html

migrations 파일 생성은 했으나, migrate 명령어를 수행하지 않은 단계에서도  
만약 models.py 내 소스 코드 변경 (e.g 기존에 없던 필드 생성의 경우)이 있었다면 
내부적으로 ORM이 동작하는 순간에 새롭게 생성된 필드가 없어서 에러가 발생할 수 있다. 
> (착각했던 부분은 migration이 반영되지 않았기 때문에 전혀 문제가 없을 것이라고 생각햇다. migration을 적용하지 않았기에 분리된 환경이라고 생각했다. 하지만 애초에 python manage.py runserver를 할 때 -> 새로운 필드도 읽어서 로딩하는 걸 디버깅에서 확인했다.) > (에러가 발생한 이유는 기본적으로 모델.objecsts.last()만 하더라도 -> 이 과정에서 ORM을 거쳐 -> SELECT 명령문 수행 시 포함되는 필드에 새롭게 생성된 필드가 models.py 내의 새로운 필드를 참조해서 실행되기 때문이다.)

https://docs.python.org/3/howto/descriptor.html#orm-example

# descriptor
<img width="1154" alt="image" src="https://user-images.githubusercontent.com/45473846/160647216-00380de8-cb1a-43b5-a82d-8d07fec760e2.png">


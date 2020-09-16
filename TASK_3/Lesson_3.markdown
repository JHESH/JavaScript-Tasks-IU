# ������ JSON - �����������

������ ������������� ����������� ��������� � ������ **JSON**

���������� ������

```
"use strict";

const boy = {name: "George"};
const girl = {name: "Ann"};

boy.pair = girl;
girl.pair = boy;

try {
    const jsonString = JSON.stringify(boy);
} catch (err) {
    console.error(err.message);
}
```

��������� ������ ���������

```
Converting circular structure to JSON
    --> starting at object with constructor 'Object'
    |     property 'pair' -> object with constructor 'Object'
    --- property 'pair' closes the circle
```

����� �������, ���� �� ��������� ������������� ������ � ������ **JSON**, ���� ������������� ��������� ������� � ������ ������� ����������� ��������









# �������� ����� � �������������

�������� ����� �� ������� ����� � ������ *my-js-project*

��������� **Visual Studio Code**

�������� **File**, ����� **Open Folder**

� ������� ���������� �������� ����� *my-js-project*

������ ����� *my-js-project* ����� ����������� �������

��������� ��������: �������� **Terminal**, ����� **New Terminal**

� �������� �������

```
npm init --yes
```

�������� ���� � ������ **package.json**

� ����� **package.json** ��������� ����������

```
{
  "name": "my-js-project",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

��������� ������ **fs** ��� ������ � �������� ��������

� �������� �������

```
npm install fs --save
```

����� ����� ��������� ����� **node_modules**

� ������ ����� �������� ������������� ������������ �����

� ����� **package.json** �������� ������, � ������� ����������� ������������� ���� ����������

```
"dependencies": {
    "fs": "0.0.1-security"
}
```

�� ������� **scripts** ������ ������ **test**, ��� ��� ���� �� �� ���������� ������ �����

������������� ������ **scripts** ��������� �������

```
"scripts": {
    "start": "node index.js"
}
```

������� ���� **index.js**

����� � ��� ���

```
"use strict";

console.log("Hello");
console.log("World");
```

������� � �������� 

```
npm start
```

����� ����� ����� ������� ���� **index.js**

��������� ������ ���������

```
Hello
World
```

������ ���������� ����� **package.json**

```
{
  "name": "my-js-project",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "dependencies": {
    "fs": "0.0.1-security"
  }
}
```

����� �������, �� ������� ���� � �������������, ���������� ���������� ��� ������ � �������, � ����� �������� ������ **start** ��� ������� ����� **index.js**


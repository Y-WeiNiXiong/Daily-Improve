
>����������Լ��Ĳ��ͣ���ԭ��ӡ��ʼ��м�¼һЩ�����������������Լ��Ĳ����У������Ժ�ϰ����
### 1.��װSQLAcodegen     

pip install sqlacodegen

### 2.ִ����������

**ģ�壺**

```
sqlacodegen mysql://root:123456@127.0.0.1:3306/test > models.py

������ĺ����ǰѵ�ǰ���õ�test���ݿ��µ����б�ṹ��������model,�������ɽ��д�뵱ǰĿ¼�����ɵ�models.py�ļ���
```

### 3.�����python3�����
�ᱨ��No module named 'MySQLdb'����ʱִ���������

```
pip install pymysql
```

�������⻷����Ӧ��Ŀ¼��F:\Git_Repository\Envs\project_name\Lib\site-packages\sqlacodegen���ҵ�__init__.py�ļ����������ֶ��������Ĵ��룺

```
import pymysql

pymysql.install_as_MySQLdb()
```
�ٴ�ִ�У�ִ�гɹ���
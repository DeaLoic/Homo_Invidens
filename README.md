# Homo Invidens
## ����������� ���������� � ����������, ����������� ��� ������� ���������:

1. [Python 3.* Toolkit](https://www.python.org/downloads/) - � ������ �������� ������ ������������� �����,   
������� ��� ������� ���������� .py, ����������� �������� ��� ��������� ���� � �������� ������� pip3.

2. ����������: (������������������ �������� ��� ������� ������������ ���� ����� �������� � ��������� ������������)
  1. scipy
  2. matplotlib 
  3. math
  4. pandas

## ������������������� �������� ��� ������� ������������ ����:

1. ��������� Python 3.* Toolkit - �� ������ ����.
2. ��������� ��������� � ������� pip3 � ������� Toolkit'�:
  * ��� Windows ������� cmd: C:\your\path\to\pip3.exe install <lib_name>
  * ��� Linux ������� bash: sudo C:\your\path\to\pip3.exe install <lib_name>
  * ������ ����: "C:\Python34\Tools\Scripts\pip3.exe install numpy"

  * � ������������ � ����� �� ��������� �������: pip3 install libs.txt

3. ��������� ���������� �� ���������� ������� ������.  
   ������� ������� ������:  
   V0 >= 0  
   m > 0  
   h > 0  
  ����� **Wind.csv** � **F.csv** ������ ������ � ����� ���������� � **main.py**, **integrate_method.py**, **digit_method.py**.
  ���� **Wind.csv** ������ ���������� �� ������ "Height (m),Wx (m/s),Wz (m/s)",
  � ���� **F.csv** - "V(m/s),F(N)"  
  ����������� � **.csv** ������ - ������� 
4. ����� ����, ��� ��� ���������� ���������, ��������� ���� **main.py** 
� ��������� ����������� � �������.

## ������ ���. ������

�.� ���������� ��������� ����� ���������� ������ ��������� ���������, ��� ��������� ����, ���� ��������� �� 0.  
���� ���. ������ ����� ����������� � ���� ������� ���������������� ���������.



## ������ ���������

� ��������� ����������� ��� ������ ���������� ��������� � �������� ���� � ����������� �� �������. 

� ������ **digit_method** �� ������������� ��������� ������� �������. � ������� ������� ������ ������� �� ���������, ��� ����, 
����������� �� ����, ���������, � ������������� ��������������� �������. ���� ����� ��������, �� �������, � ��� ����� ������������ 
�������� ������� �� �������� ������� �����.

� ������ **integrate_method** �� ������ ������� ���������������� ��������� � ������� ������� ����������. ���� ����� ������ �����������, 
�� ������������. ��� ��������� ������� ������ � ������-�� ������� �������� ���������� ��� ���������� �������� �������� ����������,
��-�� ������������ ����������

� �����: ��������� ������� ���������� ����� **integrate_method**; ���� �� �������� ���������, �� ��� ������� ��� ���������, ��� - 
��������� **digit_method** � ������� ��� ���������.
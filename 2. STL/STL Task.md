### STL
# ������������ ������ � 1
### ������� � ���������� ������������ ������.


����������� �������������� ����� (�������) `TokenCounter`, ����������� ����������� ���������� ���������������� ��������� �������� ��������� � ������ ������. ��� ������������������� ����������� ������� � ����, ��� ���� ������ ������ �� ����� ������� ����� � ��� ��������� ���������: ������ �`aaabb`� �������� ��������� �`aa`� ������ ���� ���.

����� `TokenCounter` ������ �����:

- �����������, ����������� ��������� ��� ������ ��� ��������:

```cpp
TokenCounter (const std::string& i_substr);
```

- �������, ������������ ���������� ��������� ���������:

```cpp
size_t GetTokenCount() const;
```
�������� ��������� �������� ��������� � ������ �������������� ����� �������� ��������������� ������� `TokenCounter`, ������������������� ����������, � �������� `for_each`, ������� ��������� ��������� �� ������ � ����� ������, � ������� ����� �������������� �����. �������������� ������, ������� ������ `for_each` ��� ������������ ��������, ������ ��������� ���������� � ���������� ��������� ���������.

�������� ���������� ����������, ������� ������������� ������ ��������������� ������� � ��������� � `for_each` ��� ������ ��������� ������ � ��������� ������. ��� ������������ ����� ������������ ������� `assert()` (������� `#include <cassert>`).

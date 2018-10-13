# DataTypes
($var).GetType() => To identify a datatype of variable

------
### System.Object
String
```PowerShell
('A').GetType()
```
------
### System.ValueType
Char
```PowerShell
([char]'A').GetType()
```
Int32
```PowerShell
(10).GetType()
```
Int64
```PowerShell
([long]10).GetType()
```
------
### System.Array
Object[]
```PowerShell
(10, 12).GetType()
('A', 'B').GetType()
@().GetType()
```
String[]
```PowerShell
([String[]]('A', 'B')).GetType()
'AB'.split('').GetType()
```
Int32[]
```PowerShell
([int[]](10, 12)).GetType()
```
Char[]
```PowerShell
([char[]]('A', 'B')).GetType()
```

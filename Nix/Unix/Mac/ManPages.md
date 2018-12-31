# ManPages
Manual Pages

------
As per system configuration they are displayed mostly by pager programs such as less (default on Mac) or more

Configuration of ManPages mostly are set using /private/etc/man.conf file
### Sections
ManPages are divided into sections which are searched in a particular order

And, additional sections can be added using config file

Default order mostly used is
```
MANSECT         1:1p:8:2:3:3p:4:5:6:7:9:0p:tcl:n:l:p:o
```
|Section|Description|
|:-----:|:---------:|
|1|General commands|
|2|System calls|
|3|C library functions|
|4|Kernel Interface|
|5|File formats and conventions|
|6|Games|
|7|Miscellaneous Information|
|8|BSD System Mangers|
|9|BSD Kernel developer/routines|
|n|Tcl keywords|

### Usage
```Shell
man [-options] <name>
```
name is command or program you want to read more on
```Shell
man man
```
A particular section can be specified too to read from
```Shell
man 2 printf
man 3 printf
```
Locate location most of ManPages
```Shell
man -w man
```


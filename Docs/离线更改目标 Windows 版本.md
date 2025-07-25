# 离线更改目标 Windows 版本

## Windows 8 (NT 6.2, build 9200), Windows 8.1 (NT 6.3, build 9600)

``` cmd
dism /Image:X:\xxx /Get-TargetEdition
dism /Image:X:\xxx /Set-Edition:ProfessionalWMC
```

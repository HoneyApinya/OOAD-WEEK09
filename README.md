# OOAD-WEEK09
Class Diagram

  ส่งงาน Class Diagram 5 รูป
   
* องค์ประกอบของประเทศ : 1

![](http://www.plantuml.com/plantuml/img/JOwn3eCm34JtV4L6El03J5ImTECNeX1Lbe9TsKub_XudYDBjzCvtlb4qi9OjkuaAAk-U-julJ5_0c7vmyCzr0mHH3Wg4tUFVKgEnOZ5-PLlH1BhVPF2IwHrQsensCTTEYEekSGwWJydjaxkbvPV4GlYQtPXmjTK7)
```
@startuml

Country o-- Province 
class Country {
Administration()
attravtions()
}

Province o-- City
class Province {
slogan()
}

City o-- District

District o-- Population
class Population {
PersonID
}


@enduml
```
* อาหาร : 2

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU9ApaaiBbPmoyzFKL2sj7HpStRc0dDiQdHr5VA0h9nK1IIHeina57v6OcvIQL5wQX7C9AWMe5dEpfQMK46mBcLd830pWmh1DIeekxbPMWB5kRWSKlDIW8u20000)

```
@startuml

class Food #99FFCC
Food <|-- noodle 
Food <|-- rice 
Food <|-- hamburger

class noodle #99CC99
class rice #CCCC66
class hamburger #FF9966


@enduml
```

* ร้านค้าในห้างและตลาด : 3

![](http://www.plantuml.com/plantuml/img/RP112i8m44NtESL0rWN9GWsug1QpS-4H9Z6j8KbRaYYqU7X3aL8Xi_ll3SFmwvWmf9TtX2Y7CS8DWzK9AET2D0tvnTEdgk2jKwSJIgU12h7BywSx3CweecfDV1Q5rvXMiNxW7D0hv_l3cInXMHto3GEKiUE5iGsVS1fAlBMgGBs50XtDF6E1ImpIt4VSI5Bh_f7x-W80)

```
@startuml

class Market #99FFCC
Market <|-- vetgetable #FF0000
Market <|-- garlic #FF0000
Market <|-- fish #FF0000
Market <|-- meat #FF0000

class Mall #E9967A
Mall <|-- oishi #228B22
Mall <|-- yayoi #228B22
Mall <|-- fkc #228B22
Mall <|-- mk  #228B22
Mall <|-- pizza #228B22
Mall <|-- barbiQpaza #228B22

@enduml
```


* การส่งลูกเข้าเรียน : 4

![](http://www.plantuml.com/plantuml/img/JP31RiCm28RlF0LIpr7VOEfQQRtijCkq8tM8RSM1p2QgedNlFYTTeqeS3DyF_FXGZB9DGm8eVPIHCWru8TVxh9EqJfDcV1MBtnEVCxFipvhQ9wrBLCfnQpYj3P-1oMudpT8blN8-fea1LYc-qH3JZBlCRJDpgXn4ZJ5nPwZTnZMJU0P42x5WZUuEhYI6fbX9uUKP62ywBwNYWce2bXQNaV2OrJIt5_od26CrIvuV-MwCqk_Vem-sdCRoeUtNwWj_wewxQMDoWVEM5vkgqfwu2r9FztCjBV4BSAW-wiV-0G00)

```

```



* การใช้เทคโนโลยี : 5

![](http://www.plantuml.com/plantuml/img/RP312i8m44Jl-nK37ZpLWqX1y20KSXRq1zAurj8q6veK5VNVJHL5fNlOovkP7NOTekvYtrgQOkjj7L6xA5Z0wue33Hlpyvp8M1q2TcoEJgnK5qoAGgay9tAwvU2rOKHTMewOABLS5iMLa6RsPLdTiWn975Bg4mA7v2j56gp-qBZvBNz9xZ_7sR8_YkDNCwKm5DXm5yG1oMkqjIefQIJtmrBa7pFI-ZvoDpj9rz2QtJvzwm40)

```

```

@startuml
' Split into 4 pages
page 2x2

class Technology #CCFF66

namespace tablet #FF99CC{
    .Technology <|-- message
      facebook <-- message
    
    .Technology <|-- facebook
    
}

namespace telephone #CCFFFF {
  Person  -- callFace
  .Technology <|-- callFace
}

Technology <|--computer.work
@enduml

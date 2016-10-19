# OOAD-WEEK09
Class Diagram

  ส่งงาน Class Diagram 5 รูป
   
* องค์ประกอบของประเทศ : 1

![](http://www.plantuml.com/plantuml/img/JOwn3eCm34JtV4L6El03J5ImTECNeX1Lbe9TsKub_XudYDBjzCvtlb4qi9OjkuaAAk-U-julJ5_0c7vmyCzr0mHH3Wg4tUFVKgEnOZ5-PLlH1BhVPF2IwHrQsensCTTEYEekSGwWJydjaxkbvPV4GlYQtPXmjTK7)

* อาหาร : 2

![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuNBBpqzHiAdHrLN80x9oKf44YZAJaRWPYRb9fKNfgKLS8E2GcfS2r0u0)

* ร้านค้าในห้างและตลาด : 3

![](http://www.plantuml.com/plantuml/img/ZP51JiCm44NNzIbyWTx0YagBw8e5Oe5OJf9fQddiiSPEgnHnTnoYAWOsxFv_u-y_bdSfW-JHarB9sH11mEkE82NzeJPxwDmWF8R-mCIYemrERHv4-Be0mRwSOkbH5l0QnORXA8ZXJzoO9-QcqMzdXFmZTf-qDABwh3P96GKvJn4FltTvHoA-Bat_2HYZIuakBO_M7mKcfPv176PjJDCKJNHNtvItMtt1F626bh2c0mZPhYOdcywrz_C3bojdosLiLpl1n9LrfqwlphjLHtkxmMfRQErBX89s6Fhvpxu0)

* การส่งลูกเข้าเรียน : 4

![](http://www.plantuml.com/plantuml/img/JP31RiCm28RlF0LIpr7VOEfQQRtijCkq8tM8RSM1p2QgedNlFYTTeqeS3DyF_FXGZB9DGm8eVPIHCWru8TVxh9EqJfDcV1MBtnEVCxFipvhQ9wrBLCfnQpYj3P-1oMudpT8blN8-fea1LYc-qH3JZBlCRJDpgXn4ZJ5nPwZTnZMJU0P42x5WZUuEhYI6fbX9uUKP62ywBwNYWce2bXQNaV2OrJIt5_od26CrIvuV-MwCqk_Vem-sdCRoeUtNwWj_wewxQMDoWVEM5vkgqfwu2r9FztCjBV4BSAW-wiV-0G00)


* การใช้เทคโนโลยี : 5

![](http://www.plantuml.com/plantuml/img/RP312i8m44Jl-nK37ZpLWqX1y20KSXRq1zAurj8q6veK5VNVJHL5fNlOovkP7NOTekvYtrgQOkjj7L6xA5Z0wue33Hlpyvp8M1q2TcoEJgnK5qoAGgay9tAwvU2rOKHTMewOABLS5iMLa6RsPLdTiWn975Bg4mA7v2j56gp-qBZvBNz9xZ_7sR8_YkDNCwKm5DXm5yG1oMkqjIefQIJtmrBa7pFI-ZvoDpj9rz2QtJvzwm40)


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

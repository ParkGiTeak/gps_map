# gps_map

* Flutter Sturdy
  - GoogleMapsFlutter
    - Android의 경우 Manifest에 위치권한 FineLocation, CoraseLocation을 추가해줘야한다.
    - metaData로 GoogleMaps API Key를 넣어줘야하는데 외부 유출 방지를 위해서 local.properties에 넣어서 사용하도록 커스텀.
  - Geolocator
    - geolocator Library를 사용하면 사용자의 현재 위치와 이전에 마지막에 연결된 위치, 변경되는 위치정보를 Stream 데이터로 받을 수 있게 해준다.

---
### 위에 정렬된 내용을 사용하여 수평 측정 기능을 제공하는 Android, iOS, Web Flutter App Study
- [참고 강의](https://www.inflearn.com/course/플러터-초입문-왕초보/dashboard)

# luadec patched
다양한 기기를 지원하는 luadec 패치 버전

## execute
```
./luadec ./luafile.lua
```

## 지원 기기
- tplink

## 업로드 현황

- [x] luadec 업로드 (25.09.21)
  - [x] openwrt 패치 적용 완료 (25.09.21)

- [ ] tplink
   - [x] tplink Datatype 9 int형으로 패치 (25.09.21)
     <details>
     <summary>패치 전후</summary>
     <div markdown="1">

     - 패치 전
     ```
     local l_0_24 = Unknown_Type_Error
     ```
     - 패치 후
     ```
     local l_0_24 = 4
     ```
     </div>
     </details>

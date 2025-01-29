---
aliases:
  - "깃 포스트 버퍼 오류 Git Error: RPC failed; HTTP 400 curl 22"
---
```
Git Error: RPC failed; HTTP 400 curl 22 The requested URL returned error: 400
```


**에러**
한번에 다량의, 큰 사이즈의 자산을 업로드 할 때 발생함.


**해결**
깃의 포스트 버퍼의 크기를 늘린다.

```
git config --global http.postBuffer 524288000        
```
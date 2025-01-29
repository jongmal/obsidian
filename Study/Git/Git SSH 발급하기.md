깃랩에서는 SSH 인증을 통하여 더욱 안전하게 계정/비밀번호를 사용할 수 있다.



SSH키 생성하기
    ```
    ssh-keygen -t rsa -b 4096 -C "zotnlnn@gmail.com"
    ```

깃랩에 등록할 키 출력하기
    ```
    cat ~/.ssh/id_rsa.pub
    ```


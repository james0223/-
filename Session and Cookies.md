# Session and Cookies



## Http의 특징

- Client가 server에 요청
- Server는 요청에 대한 처리를 한 후, Client에 응답
- 응답 후 연결은 해제! >> **Stateless**
  - 지속적인 연결로 인한 자원낭비를 줄이기 위해 연결이 해제됨
  - 그러나 Client와 Server간 연결 상태를 유지해야 하는 경우 문제가 발생 (로그인 정보 등)
  - 즉, Client 단위로 상태 정보(State)를 유지해야 하는 경우 Cookie와 Session이 활용된다





## Session % Cookie 특징

- ![image-20210216175624623](Session%20and%20Cookies.assets/image-20210216175624623.png)

- Session은 memory에 저장되기 때문에 object 형태로 저장될 수 있다!
- 하지만 Cookie는 file로 저장되기 때문에 object형태로 저장하는 것이 불가능하여 string 형태로 저장되는 것!
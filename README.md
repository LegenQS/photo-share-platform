# photo-sharing-platform

after cloning, under file:

photo-sharing-platform

`cd photo-sharing-platform`

run to install modules:

`npm install`

run to start:

`npm start`



## 1. pages router

1. /login
2. /signup
3. /main
4. /post
5. userInfo
6. /imgDetail

```react
<Routes>
    <Route path="/login" element={<Login />}></Route>
    <Route path="/signup" element={<Signup />}></Route>
    <Route path="/main" element={<Main />}></Route>
    <Route path="/post" element={<Post />}></Route>
    <Route path="/userInfo" element={<UserInfo />}></Route>
    <Route path="/imgDetail" element={<ImgDetail />}></Route>
    <Route path="/" element={<Navigate replace to="/login" />} />
</Routes>
```



## 2. Interfaces

### login

![image-20220427181312760](README.assets/image-20220427181312760.png)

### signup

![image-20220427181342656](README.assets/image-20220427181342656.png)

### main

![image-20220427181408800](README.assets/image-20220427181408800.png)

### imgDetail

![image-20220427181433190](README.assets/image-20220427181433190.png)

### userInfo

![image-20220427181457091](README.assets/image-20220427181457091.png)

### post

![image-20220427181524393](README.assets/image-20220427181524393.png)

![image-20220427181831774](README.assets/image-20220427181831774.png)
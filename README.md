# photo-sharing-platform

After cloning, you should firstly go to the frontend path by 

`cd photo-sharing-platform`

Then run the following code to install modules

`npm install`

Now you can start the web by running

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

![image-20220427181312760](img/image-20220427181312760.png)

### signup

![image-20220427181342656](img/image-20220427181342656.png)

### main

![image-20220427181408800](img/image-20220427181408800.png)

### imgDetail

![image-20220427181433190](img/image-20220427181433190.png)

### userInfo

![image-20220427181457091](img/image-20220427181457091.png)

### post

![image-20220427181524393](img/image-20220427181524393.png)

![image-20220427181831774](img/image-20220427181831774.png)

For more details about our project, please refer to [here](https://github.com/LegenQS/photo-share-platform/blob/main/Project%20Report.pdf).

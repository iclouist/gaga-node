1.Tạo tài khoản Gaga Node

https://dashboard.gaganode.com/register?referral_code=cgktbqvsdfzmbxv ``



![Image](https://user-images.githubusercontent.com/116245100/248438935-36cdfa45-bee9-46b1-aefa-0190bb56b8ac.png)


2.Sau khi có tài khoản vào mục install run để bắt đầu cài đặt


![Image](https://user-images.githubusercontent.com/116245100/248438971-af08005b-7e16-4fc1-b999-f25c81695a9b.png)


**Mở VPS lên bắt đầu đăng nhập**

`**ssh root@<Your_VPS_IP>**`
nhập mật khẩu
**update Ubuntu**
`sudo apt update && sudo apt upgrade -y`
3.**Cài đặt tmux**
`sudo apt install tmux`
4.**tạo session gaga bằng tmux**
`tmux new -s gaga`
**Bắt đầu cài đặt Gaga Node**


![Image](https://user-images.githubusercontent.com/116245100/248439147-e31848e4-bd5e-4ba5-8f3b-1240631c952a.png)

**Chạy lần lượt tất cả command** 

![Image](https://user-images.githubusercontent.com/116245100/248439208-d0e989b0-67c9-4118-900f-32951d2ee744.png)

**_Chú ý phần token , mỗi tài khoản sẽ có mỗi Token khác nhau_**



![Image](https://user-images.githubusercontent.com/116245100/248439245-5b42233d-f76e-437b-9dda-9c1747a132b6.png)

Sau đó kiểm tra tình trạng node đã chạy chưa , Rồi out khỏi session tmux bằng commmad
`tmux detach`
Để kiểm tra lại các session chạy command
`tmux ls`
Để vào lại session tmux đã tạo nhập command
`tmux a -t <tên session>`
ví dụ ở trên để đăng nhập lại node gaga nhập commnd
`tmux a -t gaga`

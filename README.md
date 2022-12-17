# MicroServiceByMsg
A framework of micro service with pub/sub messages instead of http request.
<a name="PqIsB"></a>
## Pain - Spring cloud
![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671154165304-d97290f5-b2b4-4132-8dd9-1d5030bcc328.jpeg)<br />What if many http last for 10 seconds?<br />Safety: Anyone who read src can call any api.
<a name="Hubrx"></a>
# MicroServiceByMsg
<a name="LUElA"></a>
## How - Stable
![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671154098591-ba329f7d-172e-4844-8dc6-73db7c87da48.jpeg)

<a name="dPKwl"></a>
## How - Safety

- Different account with different topic rights in single msg service

![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671235533405-0c5527e7-4bb2-4d61-a12e-0abadd49e3e8.jpeg)

- Different msg service

![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671153451840-b0f44f13-b64c-4572-ab8d-4e13a22210e6.jpeg)<br />A person who read src doesn't know the msg service connect information which got from Nacos.<br />The front end(vue, android, ios, h5) could also use msg instead of http to communicate with back service.
<a name="ADd4g"></a>
## How - Metrics
![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671153616257-3ad7eef9-2faf-49ae-8ec0-d8179e7eb718.jpeg)
<a name="WoHjJ"></a>
## How - No limit language
![](https://cdn.nlark.com/yuque/0/2022/jpeg/34701396/1671156252254-7e3c9ed4-dac1-4356-bfe2-51f5e4b042fa.jpeg)
<a name="v3sh1"></a>
## What is the msg

- The msg service could be pub/sub in redis service.
- Could be mqtt by EMQ server.
- Could be mqtt by mosquitto server.
<a name="Oh5Lb"></a>
## Please joint us

- If you like it. Please star me.
- If you practice it. Please pull request to write your story or demo code.

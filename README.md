# MOCC
Implementation for paper "Secure Data Group Sharing and Conditional Dissemination with Multi-Owner in Cloud Computing"
## Rate of Progress
已完成setup、UserKeyGen和AttrKeyGen三个部分。
## Instructions
### Setup
1. 将CMakeList.txt文件内容修改如下:

![SetUp](./images/SetUp.png "SetUp.png")

2. cd build
3. cmake ..
4. make
5. ./SetUp
### UserKeyGen
1. 将CMakeList.txt文件内容修改如下:

![UserKeyGen](./images/UserKeyGen.png "UserKeyGen.png")

2. cd build
3. cmake ..
4. make
5. ./UserKeyGen -o xxx_user_key pub_key msk_key 20181214006
### AttrKeyGen
1. 将CMakeList.txt文件内容修改如下:

![AttrKeyGen](./images/AttrKeyGen.png "AttrKeyGen.png")

2. cd build
3. cmake ..
4. make
5. ./AttrKeyGen -o xxx_attr_key pub_key msk_key sysadmin it_department 'office = 1431'

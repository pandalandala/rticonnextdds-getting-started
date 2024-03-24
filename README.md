# rticonnextdds-getting-started

## 1. Environment and Start
1. OS: Windows 10/11

2. IDE: Visual Studio 2017 (with `Windows 10 SDK 10.0.17134.0`)

3. Fill in the form at [Try Connext for Free](https://www.rti.com/free-trial). Download the `.exe` file.

4. Follow the instructions at [Installing an Evaluation or LM Version](https://community.rti.com/static/documentation/connext-dds/7.2.0/doc/manuals/connext_dds_professional/installation_guide/installation_guide/Installing.htm#1.2_Installing_an_Evaluation_or_LM_Version).

5. Follow the instructions at [2.2. Hands-On 1: Your First DataWriter and DataReader](https://community.rti.com/static/documentation/connext-dds/7.2.0/doc/manuals/connext_dds_professional/getting_started_guide/cpp11/intro_pubsub_cpp.html#hands-on-1-your-first-datawriter-and-datareader).

## 2. FastDDS & RTI Connext DDS

FastDDS 和 RTI Connext DDS 使用相同的`.idl`文件中的结构分别生成各自的代码，并且使用相同的topic；可以在一个DDS中开启`Publisher`，另一个DDS中开启`Subscriber`（注：只要两个厂家的DDS都符合OMG的通信规范就可以在DSCP模型下一同工作）。

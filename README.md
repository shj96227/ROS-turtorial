# ROS-turtorial
ROS turtorials for study
>**Note:**
>* ROS 사용에 익숙해 지기 위해 간단한 코드를 만들어 업로드하게되었습니다.
>* topic을 publisher와 subscriber를 생성하였습니다.
실행방법은 다음과 같다

## Overview

![Screenshot from 2024-08-22 22-58-04](https://github.com/user-attachments/assets/9f4f62d6-abbf-42b0-9820-39962fa36873)

## Getting Started
### 1. Clone

이 repository를 clone 한다.
([How to "git clone" including submodules?](https://stackoverflow.com/questions/3796927/how-to-git-clone-including-submodules))

```sh
cd .
mkdir ROS-turtorial
cd ROS-turtorial
git clone https://github.com/shj96227/ROS-turtorial.git
```

### 2. Run roscore

```sh
roscore
```

### 3. Run Publisher & Subscriber

행맨 파일을 실행한다.
```sh
rosrun ros_tutorials_topic topic_publisher
rosrun ros_tutorials_topic topic_subscriber
```


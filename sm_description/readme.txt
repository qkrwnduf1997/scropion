대충만든 매니퓰레이터 rviz시뮬레이션용 패키지

<Environment>

- Dependency는 package.xml에 있으니 확인바람
- Ubuntu 18.04 Bionic Beaver, ROS melodic

<How to use>

1. 워크스페이스 아무데나(catkin_ws도 ㄱㅊ)안의 src파일안에 패키지를 복사한다.
2. 커맨드창에서 (아마 catkin_make로 했을테니) /catkin_ws로 가서 catkin_make를 실행한다.
    만약 안되면 catkin build도 해보고 
    그래도 안되면 의존성 확인(urdf)
    그래도 그래도 안되면 문의바람
3. 빌드가 완료되면 커맨드창에 source /devel/setup.bash 실행
4. 이제 roslaunch mrm_description testbot.launch 실행


<TODO>

-urdf파일 보완
-모바일 베이스의 자유도도 포함
-좀 예쁘게 다듬기
-더 필요한 기능이라던가 불편한 점 피드백 요망. 노력해보겠슴

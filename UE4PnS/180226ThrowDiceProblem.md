# Unreal Engine 4 Problems and Solutions - 3D 주사위를 던지고 값 알아내기

## Problems

3D 정육면체를 던지고, 값을 알아내고 싶다. 여러 방법이 떠오르지만, 어떤 방법이 가장 효율적일까?


## 해결 과정

값을 정해놓고 던지는 애니메이션을 값에 맞추기, 각 면마다 보이지 않는 Collision을 만들어서 충돌 체크를 통해 값을 반환하기, LineTrace를 통해 값을 알아내기 등 여러 방법이 있었다.

위의 방법들은 내가 즉시 제작할 수는 있지만, '좀 더 깔끔하고 효율적인 방법은 없을까?'라고 고민하며 검색을 이어나갔다.

그러던 도중 http://ue4resources.com/3d-projects 에서 Dice Game 예제를 구할 수 있었다.

<iframe src="https://blueprintue.com/render/x3j8hvni" scrolling="no" height="600" width="600"></iframe>
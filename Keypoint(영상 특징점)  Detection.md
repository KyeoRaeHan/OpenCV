## Keypoint(영상 특징점)  Detection



영상 특징점이란?

영상에서 물체를 추적, 인식하거나 영상과 영상을 매칭할 때 사용하는 방법

주요 특징점(keypoint)을 뽑아서 매칭하는 것.



좋은 영상 특징점(keypoint)이 되기 위한 조건

물체의 형태, 크기, 위치가 변해도 쉽게 식별이 가능할 것

카메라의 시점, 조명이 변해도 영상에서 해당 지점을 쉽게 찾아낼 수 있을 것



영상에서 이러한 조건을 만족하는 가장 좋은 특징점은 바로 코너점(corner point)입니다. 그리고 대부분의 특징점(keypoint) 추출 알고리즘들은 이러한 코너점 검출을 바탕으로 하고 있습니다.
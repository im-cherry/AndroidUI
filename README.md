## 1. LinearLayout
- 부모 뷰(컨테이너 뷰)입니다.
- 자식 뷰의 배치(위치)를 가로 혹은 세로로 설정합니다.
- 실습 코드 : [linearlayout.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/linearlayout.xml)

## 2. RelativeLayout (권장 X)
- 부모 뷰(컨테이너 뷰)입니다.
- 기준점(부모 뷰, 자식 뷰)을 중심으로 뷰를 배치합니다.
- 실습 코드
  - 기준점이 부모 뷰일 경우 : [relativelayout1.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/relativelayout1.xml)
  - 기준점이 자식 뷰일 경우 : [relativelayout2.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/relativelayout2.xml)

## 3. Margin & Padding
- 마진 : 외부와 뷰 사이의 여백을 설정합니다.
- 패딩 : 뷰 안의 여백을 설정합니다.
- 실습 코드 : [margin_padding.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/margin_padding.xml)

## 4. ConstraintLayout
- 제약을 통해서 뷰를 배치하는 부모 뷰(컨테이너 뷰)입니다.
- 반대 방향으로 작용하는 두 개의 제약을 동시에 적용하면, 두 제약의 가운데에 배치됩니다.
- 해당 뱡향으로 여백을 두기 위해서는 반드시 그 쪽 방향에 제약이 있어야합니다.
- 실습 코드
  - 기본 : [constraintlayout1.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout1.xml)
  - 여백 : [constraintlayout2.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout2.xml)
  - Bias(0~1) : [constraintlayout3.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout3.xml)
  - 비율 : [constraintlayout4.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout4.xml)
  - 원형 배치 : [constraintlayout5.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout5.xml)
  - Chain : [constraintlayout6.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/constraintlayout6.xml)

## 5. FrameLayout
- 부모 뷰(컨테이너 뷰)입니다.
- 액자에 사진을 넣은 것처럼, 프레임에 뷰를 넣습니다.
- 중첩이 필요할 때 사용합니다.
- 먼저 적힌 자식 뷰가 맨 뒤로 깔리게 됩니다.
- 실습 코드 : [framelayout.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/framelayout.xml)

## 6. Gravity
- gravity 속성이 부여된 뷰는 설정된 값 방향으로 끌어 당겨집니다.
- gravity : 속성이 부여된 뷰와 그 안에 있는 뷰의 관계
- layout_gravity : 속성이 부여된 뷰와 그 외부에 있는 뷰의 관계
- | 키워드를 사용하여 두 가지이상의 속성을 부여할 수 있습니다.
- 실습 코드 : [gravity.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/gravity.xml)

## 7. ScrollView
- 위젯의 내용이 화면 영역을 벗어나면 스크롤 표시가 자동으로 보이는 컨테이너 뷰(부모 뷰)입니다.
- 자식 뷰는 오직 하나만 가질 수 있습니다.
- 자식 뷰의 높이를 match_parent 로 지정하면 적용되지 않습니다. 적용하기 위해서는 fillViewport 속성값을 true 로 설정해야합니다.
- 실습 코드 : [scrollview.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/scrollview.xml)

## 8. Resource
- 안드로이드에서 사용하는 xml, 이미지, 문자열, 아이콘 등을 리소스로 정의합니다.
- drawable : 실제 이미지 파일(jpg, png 등) 혹은 xml 로 된 이미지 파일
- layout : 화면을 구성하는 xml 파일
- mipmap : 앱 아이콘 이미지 파일
- values
  - colors.xml : 색을 정의하는 파일
  - strings.xml : 문자열을 정의하는 파일
  - themes.xml : 테마를 설정하는 파일
- 실습 코드(values) : [resource.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/resource.xml)

## 9. Drawable
- 이미지 리소스 파일이 위치하는 곳입니다.
  - jpg, png 파일 : 복잡한 이미지
  - xml 파일 : 도형과 같은 간단한 이미지, 이미지 파일로는 그릴 수 없는 이미지
- 실습 코드
  - 복잡한 이미지 : [drawable1.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/drawable1.xml)
  - 도형 이미지 : [drawable2.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/drawable2.xml)
  - 이미지 파일로는 그릴 수 없는 이미지 : [drawable3.xml](https://github.com/im-cherry/AndroidUI/blob/main/app/src/main/res/layout/drawable3.xml)

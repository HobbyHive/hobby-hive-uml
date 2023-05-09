# hobby-hive-uml

# Plant Uml

PlantUML은 텍스트 기반의 UML 다이어그램 생성 도구입니다. 다양한 UML 다이어그램을 생성할 수 있으며, 코드를 작성하여 다이어그램을 생성할 수 있습니다.

PlantUML을 사용하려면 다음 단계를 따르면 됩니다.

PlantUML 다운로드: PlantUML은 Java 기반으로 작동하므로 Java를 먼저 설치해야 합니다. 그리고 PlantUML 공식 사이트 < https://plantuml.com/ko/download >에서 다운로드할 수 있습니다.

PlantUML 코드 작성: PlantUML은 다양한 UML 다이어그램을 지원합니다. 예를 들어, 클래스 다이어그램을 생성하려면 다음과 같은 PlantUML 코드를 작성할 수 있습니다.

```
@startuml
class Car {
  - make: string
  - model: string
  - year: int
  + drive(): void
}
@enduml
```
다양한 문법 < https://plantuml.com/ko/ >

# Visual Studio Code에서 PlantUML을 실행하기 위해서는 다음과 같은 단계를 따르면 됩니다.

PlantUML 확장 설치: Visual Studio Code의 Marketplace에서 PlantUML 확장을 설치합니다.

PlantUML을 설치하려면 다음과 같은 단계를 따릅니다:

Java 설치하기
PlantUML은 Java로 작성되었으므로 Java가 먼저 설치되어 있어야 합니다. Java가 설치되어 있지 않은 경우, 다음 사이트에서 다운로드하고 설치합니다: https://www.java.com/ko/download/

Graphviz 설치하기 (선택사항)
PlantUML에서 다이어그램을 렌더링하기 위해 Graphviz를 사용할 수 있습니다. Graphviz는 다음 사이트에서 다운로드할 수 있습니다: https://graphviz.org/download/

Graphviz를 설치하지 않아도 PlantUML은 다이어그램을 렌더링할 수 있지만, 일부 다이어그램에서 보다 나은 결과를 얻을 수 있습니다.

PlantUML 다운로드하기
PlantUML은 공식 웹 사이트 https://plantuml.com/ko/download 에서 다운로드할 수 있습니다. 새로운 버전이 출시될 때마다 업데이트할 수 있으므로, 최신 버전을 다운로드하는 것이 좋습니다.

PlantUML 파일 생성: PlantUML 코드를 작성하는 파일을 생성합니다. 파일의 확장자는 .iuml로 지정합니다.

PlantUML 미리보기: 작성한 PlantUML 코드를 미리보기하려면, 작성 중인 PlantUML 파일을 열고, Ctrl + Shift + P를 누른 후, "PlantUML: Preview Current Diagram"을 선택합니다.

PlantUML 다이어그램 생성: 작성한 PlantUML 코드를 실행하여 다이어그램 이미지를 생성하려면, 작성 중인 PlantUML 파일을 열고, Ctrl + Shift + P를 누른 후, "PlantUML: Export Workspace Diagrams"를 선택합니다. 이후 생성할 이미지 형식을 선택하고, 이미지가 저장될 디렉토리를 지정합니다.

위와 같은 단계를 따르면, Visual Studio Code에서 PlantUML을 쉽게 실행할 수 있습니다. PlantUML 확장은 실시간 미리보기와 다양한 다이어그램 형식 지원 등 다양한 기능을 제공하므로, UML 다이어그램 작성에 편리하게 사용할 수 있습니다.

# hobby-hive-uml

# Plant Uml

PlantUML은 텍스트 기반의 UML 다이어그램 생성 도구입니다. 다양한 UML 다이어그램을 생성할 수 있으며, 코드를 작성하여 다이어그램을 생성할 수 있습니다.

PlantUML을 사용하려면 다음 단계를 따르면 됩니다.

PlantUML 다운로드: PlantUML은 Java 기반으로 작동하므로 Java를 먼저 설치해야 합니다. 그리고 PlantUML 공식 사이트 (https://plantuml.com/ko/download)에서 다운로드할 수 있습니다.

PlantUML 코드 작성: PlantUML은 다양한 UML 다이어그램을 지원합니다. 예를 들어, 클래스 다이어그램을 생성하려면 다음과 같은 PlantUML 코드를 작성할 수 있습니다.

'''
@startuml
class Car {
  - make: string
  - model: string
  - year: int
  + drive(): void
}
@enduml
'''


# Visual Studio Code에서 PlantUML을 실행하기 위해서는 다음과 같은 단계를 따르면 됩니다.

PlantUML 확장 설치: Visual Studio Code의 Marketplace에서 PlantUML 확장을 설치합니다.

PlantUML 설정: PlantUML 확장을 설치한 후에는, Visual Studio Code의 설정 파일에 PlantUML의 설정을 추가해야 합니다. settings.json 파일에서 다음과 같은 내용을 추가합니다.

PlantUML 파일 생성: PlantUML 코드를 작성하는 파일을 생성합니다. 파일의 확장자는 .iuml로 지정합니다.

PlantUML 미리보기: 작성한 PlantUML 코드를 미리보기하려면, 작성 중인 PlantUML 파일을 열고, Ctrl + Shift + P를 누른 후, "PlantUML: Preview Current Diagram"을 선택합니다.

PlantUML 다이어그램 생성: 작성한 PlantUML 코드를 실행하여 다이어그램 이미지를 생성하려면, 작성 중인 PlantUML 파일을 열고, Ctrl + Shift + P를 누른 후, "PlantUML: Export Workspace Diagrams"를 선택합니다. 이후 생성할 이미지 형식을 선택하고, 이미지가 저장될 디렉토리를 지정합니다.

위와 같은 단계를 따르면, Visual Studio Code에서 PlantUML을 쉽게 실행할 수 있습니다. PlantUML 확장은 실시간 미리보기와 다양한 다이어그램 형식 지원 등 다양한 기능을 제공하므로, UML 다이어그램 작성에 편리하게 사용할 수 있습니다.

# Calculator
개요
LV1.계산기에서는 두 개의 숫자와 사칙연산 기호를 입력받아 계산 결과를 반환하는 간단한 계산기 프로그램입니다. "exit"를 입력할 때까지 반복적으로 연산을 수행할 수 있습니다.

기능
1. 사칙연산: 두 숫자에 대해 더하기, 빼기, 곱하기, 나누기를 수행합니다.
2. 잘못된 입력 처리:
3. 0으로 나누기 방지: 나누기에서 두 번째 숫자가 0일 경우 오류 메시지를 출력합니다.
4. 유효하지 않은 연산 기호: 입력한 기호가 +,-,*,/ 이외의 경우 오류 메시지를 출력합니다.
5. 종료 옵션: "exit"입력 시 프로그램이 종료됩니다.

사용법
1. 프로그램 실행 후 첫 번째 숫자를 입력합니다.
2. 두 번째 숫자를 입력합니다.
3. 사칙연산 기호를 입력합니다.
4. 결과가 출력됩니다.
5. 계속 계산을 원하면 "exit"가 아닌 다른 문자를 입력하고, 프로그램을 종료하려면 "exit"를 입력합니다.


# Calculator2
개요
LV2.계산기에서는 LV1.계산기에서의 사칙연산 계산을 수행하고, 연산 결과를 저장할 수 있는 계산기 프로그램입니다. 이 프로그램은 계산된 결과 값을 기록하고, 가장 먼저 저장된 데이터를 삭제할 수 있는 기능을 포함하고 있습니다. LV1.계산기와 마찬가지로 "exit"를 입력할 때까지 반복적으로 연산을 수행할 수 있습니다.

기능
1. 사칙연산: 두 숫자에 대해 더하기, 빼기, 곱하기, 나누기를 수행하고, 나누기 에서 두번째 숫자가 0일 경우 오류 메시지를 출력하고, 0을 반환합니다
2. 연산 결과 저장: 연산 결과를 리스트에 저장하고 누적된 결과를 유지합니다.
3. 결과 조회: 현재까지 저장된 연산 결과 목록을 조회할 수 있습니다.
4. 가장 오래된 데이터 삭제: 연산 결과 리스트의 첫 번째 데이터를 삭제할 수 있습니다.

사용법
1. 프로그램 실행 후, 첫 번째 숫자와 두 번째 숫자를 입력합니다.
2. 사칙연산 기호를 입력합니다.
3. 결과가 출력되고, 현재까지의 연산 결과 목록이 표시됩니다.
4. "yes"를 입력하면 가장 먼저 저장된 데이터를 삭제할 수 있습니다.
5. "exit"를 입력하여 프로그램을 종료할 수 있습니다.


# Calculator3
*LV3.계산기에서는 LV2.계산기에서 정수 -> 실수로 연산값이 나오도록 변경한게 끝 입니다...

조건
양의 정수만 받았지만 이제부터는 실수도 받을수 있게 수정한다. (O)
결과가 저장되어 있는 컬렉션을 조회하는 기능을 만든다. (X)
그때 특정 값 보다 큰 결과 값을 출력 할 수 있도록. (X)

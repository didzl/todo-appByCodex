# Today’s Tasks

A simple to-do app for writing down daily tasks and checking them off when finished. It runs in a web browser such as Chrome or Edge. No account or separate app installation is required.

## Open the app

1. Open the folder where you saved this project.
2. Double-click `index.html`.
3. When the **오늘의 할 일** (Today’s Tasks) screen appears in your browser, the app is ready to use.

If the file opens in another program instead of a browser, right-click `index.html` and choose **Open with → Chrome or Microsoft Edge**. `README.md` is the guide you are reading; the app itself is `index.html`.

## Add your first task

1. Enter a task, such as `Buy milk`, in the **무엇을 해볼까요?** (What would you like to do?) field.
2. If the task has a due date, choose one under **마감일(선택)** (Due date, optional). You can leave it blank.
3. Click **추가** (Add) or press Enter.
4. When you finish a task, click its checkbox. Click it again to mark the task as in progress.

## Features

- **Search:** Type in **할 일 검색** (Search tasks) to show tasks containing that text. Clear the query to see the selected filter’s list again. If there are no results, try changing the query or filter.
- **Filter by status:** Choose **전체** (All), **진행 중** (In progress), or **완료** (Completed). You can combine a status filter with search.
- **Mark important tasks:** Click a task’s star (☆) to mark it as important. Click it again to remove the mark.
- **Manage due dates:** Change a task’s due date after adding it, or click **지우기** (Clear) beside the date to remove it. Unfinished tasks past their due date are marked **기한 지남** (Overdue).
- **Reorder tasks:** Drag the ⠿ handle on the left of a task. With a keyboard, press Tab until the handle is focused, then press ↑ or ↓.
- **Delete tasks:** Click **삭제** (Delete) on a task to remove it, or use **완료한 일 지우기** (Clear completed tasks) near the bottom to remove all completed tasks. Deletion cannot be undone.
- **Choose a theme:** Use the **다크 모드** (Dark mode) or **라이트 모드** (Light mode) button near the top to change the screen brightness.

## Where is my list stored?

Tasks, their order, and the theme are saved automatically in the browser you use. There is no separate save button. To see your list again, open the app in the same browser using the same file or address.

Your list does not automatically sync to other browsers or devices. Clearing your browser’s site data may also remove the saved list. Data in a private or incognito window may not persist after you close the window, so using a regular browser window is recommended.

If you see a message that the app could not save, check your browser’s storage settings. Changes may be lost when you close the window while saving is unavailable.

## Optional: Open the app with a local server

You can get started by opening the file as described above. If Python is already installed and you prefer to use the same address each time, you can use these steps instead:

1. Open a terminal or PowerShell in the project folder. On Windows, you can right-click an empty area in the folder and choose **Open in Terminal**.
2. Enter the following command and press Enter:

   ```powershell
   python -m http.server 8000
   ```

3. Leave the terminal open and visit `http://localhost:8000` in your browser.
4. When you are finished, press Ctrl+C in the terminal to stop the server.

If you see a message that the `python` command cannot be found, use the **Open the app** method above. Opening the file directly and using a local server use different storage locations, so your existing list will not move between them automatically.

## Project files

- `index.html`: Contains the app’s interface, design, and behavior
- `README.md`: App overview and usage instructions
- `AGENTS.md`: Contribution guide for code changes and commits

No package installation or build step is required.

---

# 오늘의 할 일

매일 해야 할 일을 적고, 끝낸 일을 체크하는 간단한 한국어 할 일 앱입니다. Chrome이나 Edge 같은 웹 브라우저에서 사용할 수 있으며, 회원가입이나 별도 앱 설치가 필요하지 않습니다.

## 앱 열기

1. 이 프로젝트를 저장한 폴더를 엽니다.
2. `index.html` 파일을 두 번 클릭합니다.
3. 브라우저에 **오늘의 할 일** 화면이 나타나면 바로 사용할 수 있습니다.

파일이 브라우저 대신 다른 프로그램에서 열리면, `index.html`을 마우스 오른쪽 버튼으로 클릭하고 **연결 프로그램 → Chrome 또는 Microsoft Edge**를 선택하세요. `README.md`는 지금 읽고 있는 설명서이고, 실제 앱은 `index.html`입니다.

## 첫 할 일 추가하기

1. **무엇을 해볼까요?** 입력칸에 `우유 사기`처럼 할 일을 적습니다.
2. 마감일이 있다면 **마감일(선택)**에서 날짜를 고릅니다. 비워 두어도 됩니다.
3. **추가** 버튼을 누르거나 Enter 키를 누릅니다.
4. 일을 마치면 항목 왼쪽의 체크박스를 누릅니다. 다시 누르면 진행 중 상태로 돌아갑니다.

## 이런 기능이 있어요

- **검색:** ‘할 일 검색’에 글자를 입력하면 해당 글자가 포함된 할 일만 표시됩니다. 검색어를 지우면 선택한 필터의 목록이 다시 나타납니다. 결과가 없으면 검색어나 필터를 바꿔 보세요.
- **상태별 보기:** ‘전체’, ‘진행 중’, ‘완료’를 눌러 원하는 항목만 볼 수 있습니다. 검색과 함께 사용할 수도 있습니다.
- **중요 표시:** 항목의 별(☆)을 누르면 중요한 일로 표시됩니다. 다시 누르면 해제됩니다.
- **마감일 관리:** 추가한 항목에서도 마감일을 바꾸거나 날짜 옆의 ‘지우기’로 없앨 수 있습니다. 마감일이 지난 미완료 항목에는 ‘기한 지남’이 표시됩니다.
- **순서 바꾸기:** 항목 왼쪽의 ⠿을 끌어 이동하세요. 키보드에서는 Tab 키로 ⠿에 초점을 맞춘 뒤 ↑ 또는 ↓ 키를 누르세요.
- **삭제:** 항목의 ‘삭제’로 한 개를 지우거나, 아래쪽의 ‘완료한 일 지우기’로 완료한 항목을 한꺼번에 지울 수 있습니다. 삭제를 되돌리는 기능은 없습니다.
- **화면 테마:** 위쪽의 ‘다크 모드’ 또는 ‘라이트 모드’ 버튼으로 화면 밝기를 바꿀 수 있습니다.

## 내 목록은 어디에 저장되나요?

할 일, 순서, 테마는 사용하는 브라우저에 자동으로 저장됩니다. 별도의 저장 버튼은 없습니다. 다음에도 같은 브라우저에서 같은 파일이나 주소로 앱을 열어 주세요.

다른 브라우저나 기기로 목록이 자동 동기화되지는 않습니다. 브라우저의 사이트 데이터를 지우면 저장된 목록도 사라질 수 있습니다. 시크릿 창의 데이터는 창을 닫으면 유지되지 않을 수 있으므로 평소 사용하는 일반 창에서 여는 것을 권장합니다.

저장할 수 없다는 안내가 나오면 브라우저의 저장 설정을 확인하세요. 저장에 실패한 상태에서는 창을 닫을 때 변경 내용이 사라질 수 있습니다.

## 선택 사항: 로컬 서버로 열기

위의 파일 열기 방법으로 바로 시작할 수 있습니다. Python이 이미 설치되어 있고 항상 같은 주소로 접속하고 싶다면 다음 방법도 사용할 수 있습니다.

1. 프로젝트 폴더에서 터미널이나 PowerShell을 엽니다. Windows에서는 폴더의 빈 곳을 마우스 오른쪽 버튼으로 클릭한 뒤 **터미널에서 열기**를 선택할 수 있습니다.
2. 아래 명령을 입력하고 Enter 키를 누릅니다.

   ```powershell
   python -m http.server 8000
   ```

3. 터미널을 열어 둔 채 브라우저 주소창에 `http://localhost:8000`을 입력합니다.
4. 사용을 마친 뒤 서버를 종료하려면 터미널에서 Ctrl+C를 누릅니다.

`python` 명령을 찾을 수 없다는 메시지가 나오면 앞의 **앱 열기** 방법을 사용하세요. 파일을 직접 여는 방식과 로컬 서버 방식은 저장 공간이 다르므로 기존 목록이 자동으로 옮겨지지는 않습니다.

## 프로젝트 구성

- `index.html`: 앱 화면, 디자인, 동작이 모두 들어 있는 파일
- `README.md`: 앱 소개와 사용 방법
- `AGENTS.md`: 코드 수정과 커밋을 위한 기여 가이드

별도의 패키지 설치나 빌드 과정은 없습니다.
